# Lab-01  Part 8  การกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์

👉 แก้โปรแกรมตามรูปด้านล่างนี้
```csharp
const double i = 123.456789d;
Console.WriteLine("{0:F1}", i);
Console.WriteLine("{0:F2}", i);
Console.WriteLine("{0:F3}", i);
Console.WriteLine("{0:F4}", i);
Console.WriteLine("{0:F5}", i);
```
➢ รันโปรแกรมและบันทึกผล
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/58f1adcd-ca83-4a88-b90e-e0f7577e2d86)

## ❔ แบบฝึกหัด จงรันโปรแกรมและบันทึกภาพ output ของบรรทัดคำสั่งต่อไปนี้

``` csharp
1. string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/f3464a2a-66b3-44fb-8570-c60e77b42d2a)
``` csharp
2. Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/11b9e0a9-a079-4ac0-ad83-ee2d57ea48c4)
``` csharp
3. Console.WriteLine("Hello " + "World");
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/4a4dd2ad-926b-41ef-8492-848033ab7905)
``` csharp
4. Console.WriteLine("Here comes a slash \\");
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/23d6bb92-92ec-4ad3-b1dd-ab9258f70542)
``` csharp
5. Console.WriteLine("|{0, 10}|", 999);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/6b34dece-cad5-4411-ac0c-a24e94f6a57d)
``` csharp
6. Console.WriteLine("|{0,-10}|", 000);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/f6bd5b82-43fa-4011-ab30-8b54a4d1ed8e)
``` csharp
7. Console.WriteLine("The value: {0}.", 500);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/c0aae91f-8530-40b0-9f7f-e8848e653731)
``` csharp
8. Console.WriteLine("The value: {0:C}.", 500);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/8c3ffe03-087b-46d4-aeb5-eb21054ae612)
``` csharp
9. Console.WriteLine("{0,-10:F4}", 12.3456789);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/6067373b-9336-4e15-a2fe-f0344b4e0b5e)
``` csharp
10. Console.WriteLine("{0,-10:C}", 12.3456789);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/d3a45c12-4fdd-4036-b507-d3702ec81828)
``` csharp
11. Console.WriteLine("{0,-10:E3}", 12.3456789);
``
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/32ac56e9-9a3c-43c8-a591-9810486173b9)
``` csharp
12. Console.WriteLine("{0,-10:x}", 65535);  // (x = lower case)
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/997a1ece-6f43-486a-8e84-9f04b5728b9d)
``` csharp
13. Console.WriteLine("{0,-10:X}", 65535);  // (X = upper case)
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/ab77a433-283d-4a39-aa09-964c72c3d9dc)
``` csharp
14. int i;
    Console.WriteLine("Value\tSquared\tCubed");
    for(i = 1; i < 10; i++)
        Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/93532668-d770-4f9b-8b18-94d823ba69d2)
``` csharp
15. Console.WriteLine("{0:#.###}.", 1234.56789);
```
![image](https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/5ee093b4-5ba2-45e0-9ae5-4991da20129c)

## [การใช้งานคำสั่ง Console.Read() และ Console.ReadLine()](./Lab-01-part-9-12.md)
