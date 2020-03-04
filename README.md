### Lecture 9 

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

#### Answers

[Image Representation](answer.png)

[Text Representation](answer.md)