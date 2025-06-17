![Tests failed](https://img.shields.io/badge/tests-1%20passed%2C%201%20failed%2C%201%20skipped-critical)
|Report|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[fixtures/rspec-json.json](#user-content-r0)|1 ✅|1 ❌|1 ⚪|0ms|
## ❌ <a id="user-content-r0" href="#user-content-r0">fixtures/rspec-json.json</a>
**3** tests were completed in **0ms** with **1** passed, **1** failed and **1** skipped.
|Test suite|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[./spec/config/check_env_vars_spec.rb](#user-content-r0s0)|1 ✅|1 ❌|1 ⚪|0ms|
### ❌ <a id="user-content-r0s0" href="#user-content-r0s0">./spec/config/check_env_vars_spec.rb</a>
```
CheckEnvVars#call when all env vars are defined behaves like success load
  ❌ CheckEnvVars#call when all env vars are defined behaves like success load fails in assertion
	/usr/local/bundle/ruby/3.3.0/gems/net-http-0.4.1/lib/net/http.rb:1603:in `initialize'
	./config/check_env_vars.rb:11:in `call'
	./spec/config/check_env_vars_spec.rb:7:in `block (3 levels) in <top (required)>'
	./spec/config/check_env_vars_spec.rb:19:in `block (4 levels) in <top (required)>'
  ✅ CheckEnvVars#call when all env vars are defined behaves like success load logs success message
  ⚪ CheckEnvVars#call when all env vars are defined behaves like success load skips the test
```