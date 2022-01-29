# Types, Operators, and Expressions


## Variable Names

- เป็นการตั้งชื่อตัวเเปรที่คำนึงถึง Readability
    - snake_case
    - camelCase


## Data Types and Sizes

![c data types](https://cdn.discordapp.com/attachments/691726300880044103/935830912355172352/unknown.png)
[Source](https://www.javatpoint.com/data-types-in-c).


## Constants

- integer constants  
- long constants                
- unsigned constants
- unsigned long constants
- floating-point constants
- double constants
- Binary
- Ocatal
- Hexadecimal
- Character


## Declarations

- ในภาษา C ต้องประกาศตัวแปรก่อนใช้งาน


###  printf(), puts()

- %d     (print as decimal integer )
- %xd    (print as decimal integer, at least x character wide)
- %0xd   (print as decimal integer, at least x character wide with 0 padding)
- %f     (print as floating point )
- %xf    (print as floating point, at least x character wide )
- %.xf   (print as floating point, x characters after decimal point )
- %y.xf  (print as floating point, at least y wide and x after decimal point )
    
- printf() also recognizes.
    - %o  (for octal)
    - %x  (for hexadecimal)
    - %c  (for character)
    - %s  (for character string)
    - %%  (for itself)

### Character Input and Output

- getchar() ใช้รับอักขระ 1 ตัวจาก stdin เข้ามาในโปรแกรม
- putchar() ใช้ส่งอักขระ 1 ตัวออกไปยัง stdout


## Arithmetic Operators

- +, -, *, /, %
- % ใช้กับ float กับ Double ไม่ได้


## Relational Operators and Logical Operators

- Relational Operators
    - \>, >=, <, <=
    - ==, !=
- Logical Operators
    - && (and), || (or), ! (not)


## Increment and Decrement Operators

- n++ (เหมือนกับ n += n)
- (i+j)++ ใช้ไม่ได้ อย่าหาทำ


## Bitwise Operators
- & (AND)
- | (OR)
- ^ (XOR)
- <<(left shift)
- \>> (right shift)
- ~ (one's complement)


## Array

- ตัวแปรอาเรย์สามารถเก็บข้อมูลมากกว่า 1 จำนวนที่เป็นประเภทเดียวกันไว้ด้วยกัน
- a[i] อ้างอิงขึ้นข้อมูลตัวที่ i ในอาเรย์ a โดยข้อมูลตัวแรกในอาเรย์คือ a[0]


