# Java-Master-Class

### Compiling and Running via Terminal


````
cd src
javac com/amigoscode/Main.java
java com/amigoscode/Main

java com.amigoscode/Main
````

### Java Reserved keyword
[w3schools](https://www.w3schools.com/java/java_ref_keywords.asp)


### Primitives

Primitive types are used to store simple values. For example, whole numbers, decimal values and characters. Here are the available data types for primitives in Java:

- [x] boolean
- [x] byte
- [x] short
- [x] char
- [x] int
- [x] long
- [x] float
- [x] double

| Type    | Size(bits) | Minimum                | Maximum               | Example                         |
|---------|------------|------------------------|-----------------------|---------------------------------|
| byte    | **8**      | *-128*                 | *127*                 | byte   b = 100;                 |
| short   | **16**     | *-32,768*              | *32,767*              | short  s = 300_000;             |
| int     | **32**     | *-2147483648*          | *214748347*           | int    i = 100_000_000;         |
| long    | **64**     | *-9223372036854775808* | *9223372036854775807* | long   l = 100_000_000_000_000; |
| float   | **32**     | *-2-149*               | *(2-2-23).2127*       | float  f = 1.456f;              |
| double  | **64**     | *-2-1074*              | *(2-2-52).21023*      | double d = 1.456789012345678;   |
| char    | **16**     | *0*                    | *216-1*               | char   c = 'c';                 |
| boolean | **1**      |                        |                       | boolean b = true;               |

### BODMAS
- B-Brackets
- O-Orders (powers/indices or roots)
- D-Division
- M-Multiplication
- A-Addition
- S-Subtraction

### String (Java SE 17 &amp; JDK 17)
[Docs](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/String.html)


### Memory stack
Stack Memory in Java is used for static memory allocation and the execution of a thread LIFO - Last in First Out

### Frame
A stack frame contains all the data for one function \
The stack frame only exists during the execution time of a function including any references

### Heap
- Space is used to store objects and JRE classes at runtime.
- New Objects are always created in heap space.
- References to these objects are stored in Stack Memory