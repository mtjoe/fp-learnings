# The Apply Function

- In Scala, functions are treated as objects
- `apply()` function will run the function against the arguments given
- Syntactical sugar: We do not need to call the function object with the `.apply()`
  
    object SomeFunction {
      def apply(arg: String) = ???
    }
    
    SomeFunction.apply("foo")
    SomeFunction("foo") // Would also work
    
