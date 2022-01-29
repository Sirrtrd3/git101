# Functions and Program Structure


## 1.Function Definitions

- รูปแบบของการนิยามฟังก์ชัน
    ```
    return-value-type function-name (parameter-list)

    {
       declarations

       statement
       statement
       :
    }
    ```

### 1-2.Function Prototypes

- รูปแบบของฟังก์ชัน prototype
    ```
    return-value-type function-name (parameter-list);
    ```
- มีลักษณะเหมือน function header ของ function definition


## 2.Standard Library Functions and Math Library Functions

- ฟังก์ชัน printf, scanf และ getchar เป็นตัวอย่างของฟังก์ชันที่อยู่ใน standard library functions
- ฟังก์ชัน sqrt, exp และ log เป็นตัวอย่างของฟังก์ชันที่อยู่ใน math library functions

## 3.Return Values
- ฟังก์ชันจะต้องส่งค่ากลับ หรือไม่ก็ส่งกลับในรูปของ void
- เราใช้ void เพื่อบอกคอมไพเลอร์ว่าฟังก์ชันนี้ไม่มีการส่งค่าใดๆ กลับไปยังผู้เรียก


## 4.Using Functions as Parameters to Functions-
- ค่าที่ได้จากการเรียกใช้ฟังก์ชันสามารถส่งผ่านไปเป็นพารามิเตอร์ของอีกฟังก์ชันได้


## 5.Recursion
- ฟังก์ชันสามารถเรียกใช้ตนเองได้เรียกว่า recursion


## 6.Scope Rules
- ในบางบริเวณของโปรแกรม ตัวแปรที่ถูกกำหนดขึ้นอาจถูกเข้าถึงได้ และเมื่อออกนอกบริเวณดังกล่าว ตัวแปรนั้นอาจไม่สามารถถูกเข้าถึงได้

### 6-1.Local Variables
- ตัวแปรที่ถูกประกาศไว้อยู่ภายในตัวฟังก์ชัน รวมถึงตัวแปรพารามิเตอร์ของฟังก์ชัน จะเป็นตัวแปร local ซึ่งสามารถถูกใช้งานได้เพียงภายในฟังก์ชันที่ถูกประกาศไว้

### 6-2.Global Variables
- ตัวแปรที่ถูกประกาศไว้นอกฟังก์ชันเป็นตัวแปร global ซึ่งสามารถถูกเข้าถึงได้จากฟังก์ชันต่างๆ รวมถึงฟังก์ชัน main ได้
- หากใน local มีตัวแปรชื่อซ้ำกับตัวแปรใน global การแก้ไขค่าใน local จะไม่กระทบกับตัวแปร global

### 6-3.Storage Classes
![storage classes](https://cdn.discordapp.com/attachments/691726300880044103/935846381602611250/unknown.png)
[Source](https://www.guru99.com/c-storage-classes.html#:~:text=A%20storage%20class%20in%20C%20is%20used%20to%20represent%20additional,classes%20in%20a%20C%20program.)

