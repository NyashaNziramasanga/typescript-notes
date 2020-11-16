# Access Modifiers

Keyword applied to a field, property or method of a class to control its access from the outside, by default all members are public.

The three access modifiers are:

1. protected
2. private
3. public

```typescript
class Point{
  private x: number;
  protected y: number;
}
```

## Constructor Parameters

If contractor parameters are prefixed with private or public, the tsc creates the fields with the same name and initialise the field with the value of the argument

```typescript
class Point {
  constructor(public x: number, protected y?: number){}
}
```

## Resources

- [Angular 4: Beginner to Pro (paid)](https://codewithmosh.com/courses/206545/lectures/3196193)
