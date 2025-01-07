### Function in Typescript

```typescript
// the `: number` here specifies that this function returns a number
function getTime(): number {
  return new Date().getTime();
}
```

## void return

```typescript
function printHello(): void {
  console.log("Hello!");
}
```

## Parameters

```typescript
function multiply(a: number, b: number) {
  return a * b;
}
```

## Optional Parameters

```typescript
// the `?` operator here marks parameter `c` as optional
function add(a: number, b: number, c?: number) {
  return a + b + (c || 0);
}
```

## Default Parameters

```typescript
function pow(value: number, exponent: number = 10) {
  return value ** exponent;
}
```

## Named Parameters

```typescript
function divide({ dividend, divisor }: { dividend: number; divisor: number }) {
  return dividend / divisor;
}
```

## With Interface or Type

```typescript

```

## Rest Parameters

```typescript
function add(a: number, b: number, ...rest: number[]) {
  return a + b + rest.reduce((p, c) => p + c, 0);
}
```

## Type Alias

```typescript
type Negate = (value: number) => number;

// in this function, the parameter `value` automatically gets assigned the type `number` from the type `Negate`
const negateFunction: Negate = (value) => value * -1;
```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```

##

```typescript

```
