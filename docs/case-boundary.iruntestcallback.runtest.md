<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@contract-case/case-boundary](./case-boundary.md) &gt; [IRunTestCallback](./case-boundary.iruntestcallback.md) &gt; [runTest](./case-boundary.iruntestcallback.runtest.md)

## IRunTestCallback.runTest() method

Called once for each test in a Verification run. In an implementation, you should tell your test runner that it is running a test, and what the name of the test is.

**Signature:**

```typescript
runTest(testName: string, invoker: IInvokeCoreTest): Promise<BoundaryResult>;
```

## Parameters

| Parameter | Type                                                  | Description                                                                          |
| --------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------ |
| testName  | string                                                | The name of this test                                                                |
| invoker   | [IInvokeCoreTest](./case-boundary.iinvokecoretest.md) | an IInvokeCoreTest to tell the ContractCase core that you'd like it to run the test. |

**Returns:**

Promise&lt;[BoundaryResult](./case-boundary.boundaryresult.md)<!-- -->&gt;

a promise that indicates the result of calling the invoker (BoundaryResult)
