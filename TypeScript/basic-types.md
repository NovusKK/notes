# Basic types

## Type assertions

> Use when the type of some entity can be more specific than its current type.

```ts
let someValue: any = "this is a string";dsaf

let strLength: number = (<string>someValue).length;
```

