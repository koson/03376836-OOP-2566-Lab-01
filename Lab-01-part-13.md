# Lab-01 การตั้งชื่อตัวแปรและชนิดข้อมูลในภาษา C\#


 ให้นักศึกษาพิจารณาชื่อตัวแปรตามตารางต่อไปนี้ ว่าสามารถใช้ได้หรือไม่ พร้อมบอกเหตุผล

| ชื่อตัวแปร | ใช้ได้/ไม่ได้ | เหตุผล|
|--|--|--|
| `xxx`     | ใช้ได้ | ไม่มีตัวอักษรที่ละเมิดกฎการตั้งชื่อ |
| `null` | ใช้ไม่ได้|มีคำสั่งที่ซ้อนกับnull|
| `_value` |ใช้ได้|ถูกตามหลักสร้างตัวแปร|
| `First-name`|ใช้ไม่ได้|มีเครื่องหมายทางคณิตศาสตร์|
| `Hello!` |ใช้ไม่ได้|มีเครื่องหมายตกใจ|
| `w*h` |ใช้ไม่ได้|มีเครื่องหมายทางคณิตศาสตร์|
| `time` |ใช้ได้|ถูกตามหลักสร้างตัวแปร|
| `do` |ใช้ไม่ได้	|มีคำสั่งที่ซ้อนกับdo|
| `Do` |ใช้ได้	|ถูกตามหลักสร้างตัวแปร|
| `21November`|ใช้ไม่ได้	|ตัวเลขนำหน้าไม่ได้|
| `ladkrabang`|ใช้ได้|ถูกตามหลักสร้างตัวแปร|
| `Student ID`|ใช้ไม่ได้|มีการเว้นว่าง|


---ผลการทดลอง
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/732352fe-1ae8-4169-943c-aec241f7850c)

## ชนิดข้อมูลภายในภาษา C\#

Property ของชนิดข้อมูล ในภาษา C# มีชนิดข้อมูลต่างๆ ได้แก่ `byte`, `char`, `bool`, `sbyte`, `short`, `ushort`, `int` , `uint`, `float`, `double`, `decimal`, `long`, `ulong` โดยแต่ละชนิด มีคุณสมบัติที่สำคัญได้แก่ ขนาด (เป็นไบต์) ค่าต่ำสุด ค่าสูงสุด ที่เก็บในตัวแปรชนิดนั้นๆ ได้ ซึ่งมีฟังก์ชันในภาษา C# ที่ช่วยให้เราทราบคุณสมบัติเหล่านั้น ได้แก่คำสั่ง `sizeof()`, `MinValue()` และ `MaxValue()` การแสดงค่าคุณสมบัติต่างๆ ของตัวแปร สามารถทำได้โดยใช้ฟังก์ชั่นเหล่านั้น ดังตัวอย่าง

## 13. โปรแกรมแสดงคุณสมบัติ size, MinValue และ MaxValue ของชนิดข้อมูล

```csharp
Console.WriteLine("Data type : int");
Console.WriteLine("Size :" + sizeof(int));
Console.WriteLine("Minimum Value :" + int.MinValue);
Console.WriteLine("Maximum Value :" + int.MaxValue);
```

### ผลที่ได้จากโปรแกรม

```text
Data type : int
Size :4
Minimum Value :-2147483648
Maximum Value :2147483647
```

👉 คำสั่งสำหรับการทดลอง  

ให้นักศึกษา เขียนโปรแกรมคล้ายกับตัวอย่างในข้อ 13 โดยมีชนิดข้อมูลเป็น `byte`, `char`, `bool`, `sbyte`, `short`, `ushort`, `uint`, `float`, `double`, `decimal`, `long` `และ ulong`  

### หมายเหตุ

ชนิดข้อมูล bool เก็บข้อมูลได้เฉพาะ true และ false ไม่ต้องหา MinValue และ MaxValue

ชนิดข้อมูล char จะต้องมีการ cast ค่า MinValue และ MaxValue ไปยัง int ก่อน ดังนี้

```csharp
Console.WriteLine("Minimum Value :" + (int) char.MinValue);
Console.WriteLine("Maximum Value :" + (int) char.MaxValue);
```
---ผลการทดลอง `char`
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/f9a53e2f-2b61-4f53-a06b-84c253e0fa51)
---ผลการทดลอง `byte`
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/c5479c63-1e83-4714-aaee-0911e2582565)
---ผลการทดลอง `short`
 ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/008ec0a6-cba3-4916-927b-97d217d1ac94)
---ผลการทดลอง `ushort`
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/391b2e1a-3b44-48bd-9bc2-e554043d4cb0)
---ผลการทดลอง `uint`
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/6c2d2235-b94c-45c7-8b61-371fcc2416e3)
---ผลการทดลอง `float`
 ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/6d5616c0-5c67-4bc5-bb10-cdc2c5cee77a)
---ผลการทดลอง `double`
 ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/4a04b01c-914a-4e56-9705-d076e847f8d9)
---ผลการทดลอง `decimal`
 ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/1707e8e5-5149-437f-8686-42bca549176f)
---ผลการทดลอง `long`
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/050f8dd4-9849-4f44-aec0-f2722d7bf6c0)
---ผลการทดลอง `ulong`
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/5cd3bfc3-43be-4cf0-86d5-5db2a3fa22d7)
---ผลการทดลอง `bool`

---ผลการทดลอง `sbyte`
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/4fde456e-9778-4f0f-a771-71e491fc9418)

## การใช้งานข้อมูลชนิดต่างๆ

ข้อมูลชนิดตรรกะ The Boolean Type
ข้อมูลชนิดตรรกะ (boolean) มีค่าที่เป็นไปได้เพียง 2 ค่าเท่านั้นคือ true และ false ในภาษา C# จะไม่สามารถกำหนดค่าตัวเลขลงไปในตัวแปร boolean ได้ ส่วนใหญ่ตัวแปร boolean มักใช้เพื่อการตัดสินใจและมีที่มาจากการประเมินค่าสมการต่างๆ ตัวอย่างต่อไปนี้เป็นการใช้ตัวแปร boolean กับการเปรียบเทียบด้วยตัวดำเนินการ “>”
ตัวอย่าง

```csharp
bool a = 4 > 5;
Console.WriteLine("4 > 5 is {0}", a);
```

## สนุกกับการสร้างตัวเลขสุ่ม

ในภาษา C# มีวิธีการสร้างตัวเลขสุ่ม (random number) โดยใช้คลาส Random มาสร้างเป็นตัวแปรโดยมีรูปแบบดังนี้

```csharp
Random random = new Random();
```

เมื่อสร้างแล้ว เราสามารถนำมาหาค่าตัวเลขสุ่มจากตัวแปรดังกล่าว ซึ่งมักจะกำหนดค่าสูงสุดและต่ำสุดในการสุ่มลงไปด้วย ดังนี้

```csharp
int randomNumber = random.Next(0, 100);
```

โปรแกรมด้านล่างนี้เป็นตัวอย่างการสุ่มเลข 0 – 100

```csharp
Random random = new Random();
int randomNumber = random.Next(0, 100);
Console.WriteLine(randomNumber);
```
 
ให้รัน 10 ครั้งแล้วบันทึกค่าที่ได้จากการรัน
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/016d4f7a-6457-4a11-86eb-67a8b5351ff9)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/4fda24f2-5f8d-4ec4-b1cc-b191018769c6)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/5e8e5426-ab67-4d0d-bc4c-1858a50ae3e1)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/d1f62a21-8206-4689-94a2-83a02fb0b773)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/a862f9d1-47e6-4324-b0b0-5611112ba653)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/1232c2b1-2734-4a4d-8e60-53c422efda72)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/02e96b98-ea9e-428a-adf6-e05b3952a07c)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/d14294ec-7988-498c-a5dc-7774b00d5306)
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/27418875-b320-4e3e-a23c-c254997ba2b5)
## [การเขียนโปรแกรมด้วยตัวดำเนินการทางตรรกะ](./Lab-01-part-14.md)
