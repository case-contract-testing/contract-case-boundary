<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@contract-case/case-boundary](./case-boundary.md) &gt; [BoundaryStateHandler](./case-boundary.boundarystatehandler.md) &gt; [teardown](./case-boundary.boundarystatehandler.teardown.md)

## BoundaryStateHandler.teardown() method

Call the user's state teardown function

If the user provided no teardown function, this should be a function that does nothing and returns a `BoundarySuccess`

**Signature:**

```typescript
teardown(): Promise<BoundaryResult>;
```

**Returns:**

Promise&lt;[BoundaryResult](./case-boundary.boundaryresult.md)<!-- -->&gt;

Either a `BoundaryFailure` with `kind=BoundaryFailureKindConstants.CASE_CONFIGURATION_ERROR` or a `BoundarySuccess`
