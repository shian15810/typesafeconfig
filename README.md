# typesafeconfig

TypeScript base configuration (tsconfig) to extend from with emphasis on type safety.

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
    // ...
  }
}
```

Or:

```jsonc
{
  "extends": "typesafeconfig/tsconfig.strict.json",
  "compilerOptions": {
    // ...
  }
}
```

## See Also

- [`type-expand`](https://github.com/shian15810/type-expand)
