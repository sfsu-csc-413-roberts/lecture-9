```
1:  Program
2:    Block
5:      Decl
3:        BoolType
4:        Id: j
8:      Decl
6:        IntType
7:        Id: i
11:     FunctionDecl
9:        IntType
10:       Id: factorial
12:       Formals
15:         Decl
13:           IntType
14:           Id: n
16:       Block
17:         If
19:           RelOp: <
18:             Id: n
20:             Int: 2
21:           Block
22:             Return
23:               Int: 1
24:           Block
25:             Return
27:               MultOp: *
26:                 Id: n
29:                 Call
28:                   Id: factorial
31:                   AddOp: -
30:                     Id: n
32:                     Int: 1
33:     While
35:       RelOp: ==
34:         Int: 1
36:         Int: 1
37:       Block
39:         Assign
38:           Id: i
41:           Call
40:             Id: write
43:             Call
42:               Id: factorial
45:               Call
44:                 Id: read
```