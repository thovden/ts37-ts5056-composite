# ts37-ts5056-composite

Minimal repo for reproduction of `ts5056` in Typescript 3.7.2 using
composite projects and `resolveJsonModule`.

```bash
npm run works
> tsc
# Project compiles file
npm run fails
> tsc -p tsconfig.composite.json
error TS5056: Cannot write file '.../ts37-ts5056-composite/dist/test.d.ts' because it would be overwritten by multiple input files.
```
