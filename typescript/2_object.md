### Object creation in typescript vs javascript.

## Javascript

```javascript
const carjs = {
  type: "Toyota",
  model: "Corolla",
  year: 2009,
};

console.log("car in js");
console.log(carjs);
```

## Typescript

```typescript
const carts: { type: string; model: string; year: number } = {
  type: "Toyota",
  model: "Corolla",
  year: 2009,
};
console.log("car in ts");
console.log(carts);
```

## Difference

Following code after the variable name <code>cardts </code>

```typescript
: { type: string; model: string; year: number }
```
