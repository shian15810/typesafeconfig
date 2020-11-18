# TypeSafeConfig

TypeScript base configuration (tsconfig.json) to extend from with emphasis on **type safety**.

## Installation

```shell
npm install --save-dev typesafeconfig
```

## Usage

In your `tsconfig.json`:

```jsonc
{
  "extends": "typesafeconfig/tsconfig.json",
  "compilerOptions": {
    "incremental": true,
    "outDir": "dist"
  }
}
```

## Minimum TypeScript Version

Since `noUncheckedIndexedAccess` is being enabled, you should have at least **TypeScript 4.1** installed.
