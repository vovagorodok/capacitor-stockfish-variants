# Capacitor Stockfish Multi Variants plugin

[Multi Variant Stockfish](https://github.com/ddugovic/Stockfish) chess engine
interface for Ionic Capacitor.

## Example usage

- https://github.com/veloce/lichobile/blob/master/src/stockfish.ts
- https://github.com/veloce/lichobile/blob/master/src/ui/analyse/ceval/StockfishClient.ts

## API

<docgen-index>

* [`getMaxMemory()`](#getmaxmemory)
* [`start()`](#start)
* [`cmd(...)`](#cmd)
* [`exit()`](#exit)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### getMaxMemory()

```typescript
getMaxMemory() => Promise<{ value: number; }>
```

**Returns:** <code>Promise&lt;{ value: number; }&gt;</code>

--------------------


### start()

```typescript
start() => Promise<void>
```

--------------------


### cmd(...)

```typescript
cmd(options: { cmd: string; }) => Promise<void>
```

| Param         | Type                          |
| ------------- | ----------------------------- |
| **`options`** | <code>{ cmd: string; }</code> |

--------------------


### exit()

```typescript
exit() => Promise<void>
```

--------------------

</docgen-api>
