# Classes

Groups variable/properties and functions/methods tha are highly related using the
concept of cohesion in Object Oriented programing.

## Simple class

```typescript
class Point {
  // Two properties/fields for storing data
  x: number;
  y: number;

  // Two methods
  draw(){
    console.log('X: ' + this.x); //this field in the class
  }

  getDistance(){
    // implementation
  }
};

// Explicitly allocate memory to new object
let point = new Point();
point.x = 1;
point.draw(); // 'X: 1'
```

## Resources

- [Angular 4: Beginner to Pro (paid)](https://codewithmosh.com/courses/206545/lectures/3196203)