# LUC Compiler

## Syntax and Sematics

### Variable Types
```
- num (int, float)
- txt (char, string)
```

### Functions
```
function <id> (<type> <id>, <type> <id>, ... , <type> <id>) <statement>
```

### Statements
```
- { <statememt> }
- <expression>;
- ;
- if (<expression>) <statement>
- if (<expression>) <statement> else <statement>

###
- for (<expression>; <expression>; <expression>) <statement>
- while (<expression>) <statement>

or

- loop (<expression>; <expression>; <expression>) <statement>
- loop (<expression>) <statement>
###
```

### Expressions
```
- <number literal>
- <text literal>
- <id>
- <expression>[<expression>] - indexing expression
- <expression>(<expression>, <expression>, ... , <expression>) - function call expression
- <expression><binary operator><expression>
- <unary operator><expression>
- <preincrement><expression>
- <predecrement><expression>
- <expression><postincrement>
- <epxression><postdecrement>
- <expression>? yes: <expression> no: <expression> - ternary expression
```

### Arrays
```
- <type> array(<size>) <id>;
- <type> array(<size>, <initializer>) <id>;

- <type> array(<size>) <id> = <expression>;
- <type> array(<size>, <initializer>) <id> = <expression>;
```

### Keywords
```
- null
- break
- continue
- return
- and
- or
- not
- equals
- true
- false
```

### Special Characters
```
- =
- <
- >
- <=
- >=
- +
- -
- *
- /
- %
- ^
- ++
- --
- +=
- -=
- ,
- ;
```
