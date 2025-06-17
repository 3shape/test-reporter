![Tests failed](https://img.shields.io/badge/tests-3%20passed%2C%205%20failed%2C%201%20skipped-critical)
|Report|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[fixtures/dotnet-nunit.xml](#user-content-r0)|3 ✅|5 ❌|1 ⚪|230ms|
## ❌ <a id="user-content-r0" href="#user-content-r0">fixtures/dotnet-nunit.xml</a>
**9** tests were completed in **230ms** with **3** passed, **5** failed and **1** skipped.
|Test suite|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[DotnetTests.NUnitV3Tests.dll.DotnetTests.XUnitTests](#user-content-r0s0)|3 ✅|5 ❌|1 ⚪|69ms|
### ❌ <a id="user-content-r0s0" href="#user-content-r0s0">DotnetTests.NUnitV3Tests.dll.DotnetTests.XUnitTests</a>
```
CalculatorTests
  ✅ Is_Even_Number(2)
  ❌ Is_Even_Number(3)
	   at DotnetTests.XUnitTests.CalculatorTests.Is_Even_Number(Int32 i) in C:\Users\Michal\Workspace\dorny\test-reporter\reports\dotnet\DotnetTests.NUnitV3Tests\CalculatorTests.cs:line 61
	
  ❌ Exception_In_TargetTest
	   at DotnetTests.Unit.Calculator.Div(Int32 a, Int32 b) in C:\Users\Michal\Workspace\dorny\test-reporter\reports\dotnet\DotnetTests.Unit\Calculator.cs:line 9
	   at DotnetTests.XUnitTests.CalculatorTests.Exception_In_TargetTest() in C:\Users\Michal\Workspace\dorny\test-reporter\reports\dotnet\DotnetTests.NUnitV3Tests\CalculatorTests.cs:line 33
  ❌ Exception_In_Test
	   at DotnetTests.XUnitTests.CalculatorTests.Exception_In_Test() in C:\Users\Michal\Workspace\dorny\test-reporter\reports\dotnet\DotnetTests.NUnitV3Tests\CalculatorTests.cs:line 39
  ❌ Failing_Test
	   at DotnetTests.XUnitTests.CalculatorTests.Failing_Test() in C:\Users\Michal\Workspace\dorny\test-reporter\reports\dotnet\DotnetTests.NUnitV3Tests\CalculatorTests.cs:line 27
	
  ✅ Passing_Test
  ✅ Passing_Test_With_Description
  ⚪ Skipped_Test
  ❌ Timeout_Test
	
```