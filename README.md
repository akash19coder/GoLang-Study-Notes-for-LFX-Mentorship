# GoLang-Study-Notes-for-LFX-Mentorship

# ✅ Day 1
## ✔️Go Variables
  - ### Normal Variable Declaration, Definition and Assignments  
    A variable can be defined using `var variable_name type = value`. It is normal variable definition. In Go programming language, it is not necessary to explictly define the data type because the Go compiler automatically infers the data type based on the value provided to it. Hence the declaration would look like var variable_name = value. However if we are separately declaring and assigning value, we must implicitly provide the type. The normal variable declaraton works both inside and outside the function.

  - ### Shorthand assignment operator variable Definition( := )
    A variable can also be defined using the syntax `var variable_name := value`. It is using shorthand operator. Using a shorthand operator enables us to not use `var` keyword and also type is automatically inferred. We cannot use the shorthand variable declaration outside the function in Go programming language.

  ## ✔️Variable Naming Convention
- A variable name can contain character,digits and a special character called underscore(_).
- However, a variable cannot start with digits, it can only start with character or underscore.
- A developer can choose it to be more descriptive as per the need.
- In Go, programming lanuguage variable names are case-sensitive which means name,Name,nAme and naMe are not the same
- In case of multiwords variable name, we can use cases like snakecase,pascalcase,camelcase,etc
- We don't include spaces and variable name must not be a keyword.

## ✔️Const variables
- We define constants using `const variable_name = value`. `const` is a key word in Go. The constant variable once assigned a value cannot be changed in any way both in compile time or runtime. Constant variable naming uses the same naming conventions as the normal naming convention except for it is written in all UPPERCASE. It can be used outside or inside the function. *We cannot use shorthand assignment operator in const variable assignment.*

## ✔️Go Output
 - ## Print()
      We use Print() to simply print an output.
 - ## Println()
      We use Println() to add white spaces between arguments and also adds a new line automatically
 - ## Printf()
      We use it to format the the arguments based on formatting verbs

## ✔️Go Data types
| data type | bool | integer | float |
|---------- |------|---------|-------|
| keywords | true false | int int8 int16 int32 int64 uint uint8 iunt16 uint32 uint64 | float32 float64 |

# Day 2 ✅Pointers

- ## Declaring a pointer variable
    ``var pointer_variable_name *type = &variable``  
    *type - defines what type variable's memory location address will be pointed. If we don't mention it explictly, go compiler will automatically infer it.   
    & = address operator, it precedes the normal variable and it used to store memory address of the variable  
    \* = indirection operator, it precedes the pointer variable and it stores the value present in the memory address i.e dereferencing
