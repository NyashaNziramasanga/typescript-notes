# Constructors

Method that is called when an instance of a class is created

```typescript
class FullName {
  firstName: string;
  lastName: string;

// firstName is required and lastName is optional marked by `?`
  constructor(firstName: string, lastName?: string) {
    this.firstName = firstName; // initialised the fields
    this.lastName = lastName;
  }

  fullName() {
    console.log(
      'First Name: ' + this.firstName + ' Last Name: ' + this.lastName,
    );
  }
}

// instance of FullName is created with supplied values
let fName = new FullName('nyasha', 'nziboi');
fName.fullName();

// First Name: nyasha Last Name: nziboi
```

## Resources

- [Angular 4: Beginner to Pro (paid)](https://codewithmosh.com/courses/206545/lectures/3196189)