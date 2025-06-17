![Tests failed](https://img.shields.io/badge/tests-1%20failed%2C%201%20skipped-critical)
|Report|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[fixtures/external/java/TEST-org.apache.pulsar.AddMissingPatchVersionTest.xml](#user-content-r0)||1 ❌|1 ⚪|116ms|
## ❌ <a id="user-content-r0" href="#user-content-r0">fixtures/external/java/TEST-org.apache.pulsar.AddMissingPatchVersionTest.xml</a>
**2** tests were completed in **116ms** with **0** passed, **1** failed and **1** skipped.
|Test suite|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[org.apache.pulsar.AddMissingPatchVersionTest](#user-content-r0s0)||1 ❌|1 ⚪|116ms|
### ❌ <a id="user-content-r0s0" href="#user-content-r0s0">org.apache.pulsar.AddMissingPatchVersionTest</a>
```
⚪ testVersionStrings
❌ testVersionStrings
	
	      java.lang.AssertionError: expected [1.2.1] but found [1.2.0]
	at org.testng.Assert.fail(Assert.java:99)
	at org.testng.Assert.failNotEquals(Assert.java:1037)
	at org.testng.Assert.assertEqualsImpl(Assert.java:140)
	at org.testng.Assert.assertEquals(Assert.java:122)
	at org.testng.Assert.assertEquals(Assert.java:629)
	at org.testng.Assert.assertEquals(Assert.java:639)
	at org.apache.pulsar.AddMissingPatchVersionTest.testVersionStrings(AddMissingPatchVersionTest.java:29)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.testng.internal.MethodInvocationHelper.invokeMethod(MethodInvocationHelper.java:132)
	at org.testng.internal.InvokeMethodRunnable.runOne(InvokeMethodRunnable.java:45)
	at org.testng.internal.InvokeMethodRunnable.call(InvokeMethodRunnable.java:73)
	at org.testng.internal.InvokeMethodRunnable.call(InvokeMethodRunnable.java:11)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:748)
	
	    
```