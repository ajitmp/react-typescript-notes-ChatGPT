### Use of Type vs Interface

## Type

```typescript
type CarType = {
  type: string;
  model: string;
  year: number;
};

const car_with_type: CarType = {
  type: "Toyota",
  model: "Corolla",
  year: 2009,
};

console.log(car_with_type);
```

## Interface

```typescript
interface CarInterface {
  type: string;
  model: string;
  year: number;
}

const car_with_interface: CarInterface = {
  type: "Toyota",
  model: "Corolla",
  year: 2009,
};

console.log(car_with_interface);
```

Notice the syntax difference !! i.e. = while using type defination and with it in interface.
