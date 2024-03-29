<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@contract-case/case-boundary](./case-boundary.md) &gt; [BoundaryContractDefiner](./case-boundary.boundarycontractdefiner.md) &gt; [(constructor)](./case-boundary.boundarycontractdefiner._constructor_.md)

## BoundaryContractDefiner.(constructor)

Construct a BoundaryContractDefiner to allow defining contracts.

**Signature:**

```typescript
constructor(config: ContractCaseBoundaryConfig, logPrinter: ILogPrinter, resultPrinter: IResultPrinter, parentVersions: string[]);
```

## Parameters

| Parameter      | Type                                                                        | Description                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| config         | [ContractCaseBoundaryConfig](./case-boundary.contractcaseboundaryconfig.md) | A ContractCaseBoundaryConfig object for the configuration                                                                                                                                       |
| logPrinter     | [ILogPrinter](./case-boundary.ilogprinter.md)                               | An ILogPrinter to enable printing logs                                                                                                                                                          |
| resultPrinter  | [IResultPrinter](./case-boundary.iresultprinter.md)                         | An IResultPrinter to enable printing results                                                                                                                                                    |
| parentVersions | string\[\]                                                                  | The names version(s) of the package(s) calling this, where each entry in the array contains a name and version, with the first entry in the array being the furthest package up the call stack. |
