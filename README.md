### Lecture 9 Examples

#### Example 1
Build an AST for the following x program:

```
program {boolean j int i
  int factorial(int n) {
      if (n < 2) then 
         { return 1 }
      else 
         {return n*factorial(n-1) }
  }
  while (1==1) {
      i = write(factorial(read()))
  }
}
```

##### Answers
* [Image Representation](example-1/answer.png)
* [Text Representation](example-1/answer.md)

#### Example 2
Build an AST for the following x program:

```
program { int i
  int f( int j ) { int i return j + 5 }
  i = f( 7 )
}
```

##### Answers
* [Image Representation](example-2/answer.png)
* [Text Representation](example-2/answer.md)