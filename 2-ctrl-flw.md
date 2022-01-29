# Control Flow


## Statements and Blocks

- expression กลายเป็น statement เมื่อถูกปิดท้ายด้วยเครื่องหมาย ; (semi colon)
- เครื่องหมายปีกกา {} ใช้รวมส่วนของ declarations และ statements เข้าด้วยกันเป็น block


## If-Else

```
if (expression1)

      statement1

   else if (expression2)

      statement2

   else if (expression3)

      statement3

   else if (expression4)

      statement4

   else

      statement5
```


## Else-If

```
if (expression1)
   statement1
else if (expression2)
   statement2
else if (expression3)
   statement3
else if (expression4)
   statement4
else
   statement5
```

## Switch

- ใช้ตรวจสอบเงื่อนไขในลักษณะที่ดูว่าค่าของ expression นั้น match เข้ากับค่าคงที่ใดหลังจากนั้นโปรแกรมจะมาทำงานใน statement ภายใต้ค่าคงที่นั้นลงมาเรื่อยๆ จนกว่าจะเจอ break แล้วจึงหลุดออกจาก switch
    
    ```
       switch (expression) {

      case const-expr: 

         statements

      case const-expr:

         statements

      default: 

         statements

    }
    ```


## While Loop and For Loop

```
while (expression) 
   statement
```

```
for (expr1; expr2; expr3)
   statement
```


## Break and Continue

- break ทำให้โปรแกรมหลุดออกจากloop
- continue บังคับให้เกิดการวนซ้ำของloopขึ้นมาใหม่

