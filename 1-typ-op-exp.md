# Types, Operators, and Expressions


## 1.Variable Names

- การตั้งชื่อตัวแปรต้องคำนึงถึง readability เป็นหลัก
    - snake_case
    - camelCase


## 2.Data Types and Sizes

![c data types](https://cdn.discordapp.com/attachments/691726300880044103/935830912355172352/unknown.png)
[Source](https://www.javatpoint.com/data-types-in-c).


## 3.Constants

- integer constants, (เลขจำนวนเต็ม)
- long constants, (เลขจำนวนเต็ม)
- unsigned constants, (เลขจำนวนเต็มตามด้วย u)
- unsigned long constants, (เลขจำนวนเต็มตามด้วย ul)
- floating-point constants, (เลขจำนวนจริง, เลขจำนวนเต็มตามด้วย f)
- double constants, (ลงท้ายด้วย l)
- Binary, (0b นำหน้าเลขจำนวนเต็ม)
- Ocatal, (0 นำหน้าเลขจำนวนเต็ม)
- Hexadecimal, (0x นำหน้าเลขจำนวนเต็ม)
- Character constants, ('')


## 4.Declarations

- ในภาษา C ต้องประกาศตัวแปรก่อนใช้งาน
    - ต้องระบุประเภทข้อมูลก่อนประกาศตัวแปร

### 4-1.printf(), puts()

- %d     (print as decimal integer )
- %5d    (print as decimal integer, at least 5 character wide)
- %05d   (print as decimal integer, at least 5 character wide with 0 padding)
- %f     (print as floating point )
- %5f    (print as floating point, at least 5 character wide )
- %.2f   (print as floating point, 2 characters after decimal point )
- %5.2f  (print as floating point, at least 5 wide and 2 after decimal point )
    
- printf() also recognizes.
    - %o  (for octal)
    - %x  (for hexadecimal)
    - %c  (for character)
    - %s  (for character string)
    - %%  (for itself)

### 4-2.Character Input and Output

- getchar() ใช้รับอักขระ 1 ตัวจาก stdin เข้ามาในโปรแกรม
- putchar() ใช้ส่งอักขระ 1 ตัวออกไปยัง stdout


## 5.Arithmetic Operators

- +, -, *, /, %
- % ไม่สามารถใช้กับตัวแปรประเภท float และ double ได้


## 6.Relational Operators and Logical Operators

- Relational Operators
    - \>, >=, <, <=
    - ==, !=
- Logical Operators
    - && (and), || (or), ! (not)


## 7.Increment and Decrement Operators

- n++ (เหมือนกับ n += n)
- (i+j)++ ใช้ไม่ได้ อย่าหาทำ


## 8.Bitwise Operators
- & (AND)
- | (OR)
- ^ (XOR)
- <<(left shift)
- \>> (right shift)
- ~ (one's complement)


## 9.Array

- ตัวแปรอาเรย์สามารถเก็บข้อมูลมากกว่า 1 จำนวนที่เป็นประเภทเดียวกันไว้ด้วยกัน
- a[i] อ้างอิงขึ้นข้อมูลตัวที่ i ในอาเรย์ a โดยข้อมูลตัวแรกในอาเรย์คือ a[0]

```
int a[10]; //index มี10ตัว นับจาก0-9
```

