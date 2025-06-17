![Tests failed](https://img.shields.io/badge/tests-1%20passed%2C%204%20failed%2C%201%20skipped-critical)
|Report|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[fixtures/jest-junit.xml](#user-content-r0)|1 ✅|4 ❌|1 ⚪|1s|
## ❌ <a id="user-content-r0" href="#user-content-r0">fixtures/jest-junit.xml</a>
**6** tests were completed in **1s** with **1** passed, **4** failed and **1** skipped.
|Test suite|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[__tests__\main.test.js](#user-content-r0s0)|1 ✅|3 ❌||486ms|
|[__tests__\second.test.js](#user-content-r0s1)||1 ❌|1 ⚪|82ms|
### ❌ <a id="user-content-r0s0" href="#user-content-r0s0">__tests__\main.test.js</a>
```
Test 1
  ✅ Passing test
Test 1 › Test 1.1
  ❌ Failing test
	Error: expect(received).toBeTruthy()
	
	Received: false
	    at Object.<anonymous> (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\__tests__\main.test.js:10:21)
	    at Object.asyncJestTest (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmineAsyncInstall.js:106:37)
	    at C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:45:12
	    at new Promise (<anonymous>)
	    at mapper (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:28:19)
	    at C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:75:41
	    at processTicksAndRejections (internal/process/task_queues.js:97:5)
  ❌ Exception in target unit
	Error: Some error
	    at Object.throwError (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\lib\main.js:2:9)
	    at Object.<anonymous> (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\__tests__\main.test.js:14:11)
	    at Object.asyncJestTest (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmineAsyncInstall.js:106:37)
	    at C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:45:12
	    at new Promise (<anonymous>)
	    at mapper (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:28:19)
	    at C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:75:41
	    at processTicksAndRejections (internal/process/task_queues.js:97:5)
Test 2
  ❌ Exception in test
	Error: Some error
	    at Object.<anonymous> (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\__tests__\main.test.js:21:11)
	    at Object.asyncJestTest (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmineAsyncInstall.js:106:37)
	    at C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:45:12
	    at new Promise (<anonymous>)
	    at mapper (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:28:19)
	    at C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\queueRunner.js:75:41
	    at processTicksAndRejections (internal/process/task_queues.js:97:5)
```
### ❌ <a id="user-content-r0s1" href="#user-content-r0s1">__tests__\second.test.js</a>
```
❌ Timeout test
	: Timeout - Async callback was not invoked within the 1 ms timeout specified by jest.setTimeout.Timeout - Async callback was not invoked within the 1 ms timeout specified by jest.setTimeout.Error: 
	    at new Spec (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmine\Spec.js:116:22)
	    at new Spec (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\setup_jest_globals.js:78:9)
	    at specFactory (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmine\Env.js:523:24)
	    at Env.it (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmine\Env.js:592:24)
	    at Env.it (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmineAsyncInstall.js:134:23)
	    at it (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\jasmine\jasmineLight.js:100:21)
	    at Object.<anonymous> (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\__tests__\second.test.js:1:34)
	    at Runtime._execModule (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-runtime\build\index.js:1245:24)
	    at Runtime._loadModule (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-runtime\build\index.js:844:12)
	    at Runtime.requireModule (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-runtime\build\index.js:694:10)
	    at jasmine2 (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-jasmine2\build\index.js:230:13)
	    at runTestInternal (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-runner\build\runTest.js:380:22)
	    at runTest (C:\Users\Michal\Workspace\dorny\test-check\reports\jest\node_modules\jest-runner\build\runTest.js:472:34)
⚪ Skipped test
```