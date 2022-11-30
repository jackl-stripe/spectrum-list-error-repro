# `@react-spectrum/list` error repro

1. `yarn`
2. `yarn tsc --project tsconfig.json`
3. Should see the following error:

```
node_modules/@react-spectrum/list/dist/types.d.ts:3:34 - error TS2307: Cannot find module '@react-spectrum/dnd' or its corresponding type declarations.

3 import { DragAndDropHooks } from "@react-spectrum/dnd";
```