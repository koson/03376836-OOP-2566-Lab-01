# Lab-01 การเขียนโปรแกรมด้วยตัวดำเนินการทางตรรกะ

ตัวแปรชนิด boolean มักจะถูกใช้เป็นที่เก็บผลที่เกิดจากการดำเนินการทางตรรกะ เช่น AND, OR, NOT เป็นต้น ซึ่งการดำเนินการทางตรรกะจะมีตารางความจริง เป็นตัวบอกผลในการดำเนินการของตัวดำเนินการต่างๆ ดังตัวย่าง

### ตัวดำเนินการ AND

Y = A AND B

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

### ตัวดำเนินการ OR

Y = A OR B

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

### ตัวดำเนินการ NOT

Y = NOT A

| A | Y |
|--|--|
| 0 | 1 |
| 1 | 0 |

ตัวดำเนินการในภาษา C#
ใช้เครื่องหมายต่างๆ ดังต่อไปนี้

| การดำเนินการ | เครื่องหมาย |
|------------|-----------|
| Logical AND | & |
| Logical XOR | ^ |
| Logical OR | \| |

## 14. การเขียนโปรแกรมด้วยตัวดำเนินการทางตรรกะ

ตัวอย่างภาษา C# ต่อไปนี้เป็นการพิมพ์ตารางความจริงออกทางหน้าจอ
👉 ให้เขียนโปรแกรมต่อไปนี้

```csharp
bool A, B,Y;
Console.WriteLine("      Y = A AND B");
Console.WriteLine("-----------------------");
Console.WriteLine("   A      B\t|  Y");
Console.WriteLine("-----------------------");
A = false; B = false; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A,B,Y);
A = false; B = true; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A, B, Y);
A = true; B = false; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A, B, Y);
A = true; B = true; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A, B, Y);
Console.WriteLine("-----------------------");
```

➢ รันโปรแกรมและบันทึกผล

 
👷 จากจ้อ 14 ให้เขียนโปรแกรมเพื่อสร้างตารางความจริงของลอจิกดังต่อไปนี้

1. `AND` ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/7d46c424-9d5d-4f10-ab26-5e14bb855e12)
2. `OR` ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/e25cf33e-cefe-467d-bde8-9b2e940a40d5)
3. `NOT` ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/cf3cf8ed-24da-454f-b7cd-0c38f48921dd)
4. `NAND` ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/2df6a0d8-036d-4b36-b47c-2d04606bfdfb)
5. `NOR`  ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/4bd10315-1ceb-4a1c-8f6a-6eb1b631a86f)
6. `Exclusive OR` ![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/9c93dff3-4acb-4377-a409-61080e1c3a1f)


## [ชนิดข้อมูลตัวเลขจำนวนเต็ม (Integer Types)](./Lab-01-part-15.md)
