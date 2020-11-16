# Types

Defining types of the values

```typescript
// Number type (1,2,3 ...)
let a: number;

// Boolean type (true/false)
let a: boolean;

// String type ('a','B')
let a: string;

//
let a: any;

// array types
let a: number[] = [1,2,3];
let a: string[] = ['a','b','c'];
let a: boolean[] = [true,false];

// Related constants
enum Color {Red = 0, Green = 1, Blue = 3};
let bgColor = Color.Red;
```

## Type Assertions

Explicitly asserting the type

```typescript
//Asserting string onto message object
let message = 'abc';

// Method 1: 
let endsWithC = (<string>message).endsWith('c');

// Method 2:
let endsWithC = (message as string).endsWith('c');
```

## Resources

- [Angular 4: Beginner to Pro (paid)](https://codewithmosh.com/courses/206545/lectures/3196200)