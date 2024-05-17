# Data Types

**Built-in**
- Boolean
- Characters: char
- Intergers: int (4 bytes), short int (2 bytes), long int (8 bytes)
- Floating Point: float, double
- Valueless: void
- Wide Character: wchar_t

**Type Modifiers**
The above types can be modified using the following type modifiers: signed,
unsigned short and long

**User Defined**
- Structures: struct
- Classes: class

C++ allow an array of chars to define strings. Using a library, we can use
string for type

**Typedefs**
Typedefs allow for creating new names (aliases) for existing types.
```
typedef int counter;
counter tick_c = 100; // tick_c is a valid int varible now
```

**Enumerated Types**
To create an enumeration requires the use of the keyword enum.
```
enum enum_name { list of names } var_list;
```
Above, the enum_name is the enumerations's type name, The list of names is comma
seperated. 
For example, the following code defines an enumeration of colors calles colors
and the variable a_color of type color. Finally, a_color is assigned the value
'green'.
```
enum color {red, green, blue} a_color, another_color;
a_color = green; // a_color will be assigned value of '1'
```

**Defining Variables**
For numbers, we will usually use the type int, which is an interger in the size
of a 'word' the default number size of the machine which your program is
compiled on. On most computers, it is a 32-bit number, which mean the number can
range from -2M to 2M (same as long).
To define the variables foo and bar, we use the following syntax:
```
int foo;
int bar = 1;
```
The variable foo can be used, but since we did not initailize it, we don't know
what's in it. The variable bar contains the number 1.

Now, we can do some math. Assuming a, b, c, d, and e are variables, we can
simple use math operators to assign a new value to a:
```
int a = 0, b = 1, c = 2, d = 3, e = 4;
a = b - c + d * e;
cout << a << endl; // will print 11 (1-2+3*4)
```

