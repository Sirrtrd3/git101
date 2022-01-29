# Control Flow


## 1.Statements and Blocks

- expression กลายเป็น statement เมื่อถูกปิดท้ายด้วยเครื่องหมาย semi-colon ;
- เครื่องหมายปีกกา {} ใช้รวมส่วนของ declarations และ statements เข้าด้วยกันเป็น block


## 2.If-Else

```
if (expression)
   statement1
else 
   statement2
```


## 3.Else-If

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

## 4.Switch

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


## 5.While Loop and For Loop

```
while (expression) 
   statement
```

```
for (expr1; expr2; expr3)
   statement
```


## 6.Break and Continue

- break ทำให้โปรแกรมหลุดออกจากloop
- continue บังคับให้เกิดการวนซ้ำของloopขึ้นมาใหม่

