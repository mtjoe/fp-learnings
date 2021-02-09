# Companion Objects

```
class Person {
  def greet() {
  
  }
}

object Person {
  def apply(name: String) = new Person()
  
  def unapply() = {
  
  }
  
  def anotherFunction() = {
  
  }
}
```

- Companion objects are objects that are defined
- Objects inside companion objects are abstract objects
- Companion objects and its class can access each other's private objects

## Usages

### 1. Additional constructors

### 2. Abstract functions

### 3. `apply` function

### 4. `unapply` function


## Resources

- https://docs.scala-lang.org/overviews/scala-book/companion-objects.html
