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
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/a7a34faf-c571-4ffb-9f67-f784d4c17f9a)


## ❔ แบบฝึกหัด จงรันโปรแกรมและบันทึกภาพ output ของบรรทัดคำสั่งต่อไปนี้

``` csharp
1. string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/4585df3f-d702-4385-a45f-67abcac1b2f0)

``` csharp
2. Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/d81f52e2-98be-425c-a23f-0ada109c41fa)

``` csharp
3. Console.WriteLine("Hello " + "World");
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/98ab856a-7d7d-4ce8-a0d4-f852dd67bc1f)

``` csharp
4. Console.WriteLine("Here comes a slash \\");
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/700afa33-dd10-47ec-ae95-ffa1b392b252)

``` csharp
5. Console.WriteLine("|{0, 10}|", 999);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/11065d77-6b16-49ba-ac09-ec3ebf712aa0)

``` csharp
6. Console.WriteLine("|{0,-10}|", 000);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/32d61f75-08ff-416b-a0d8-931acf8f6dda)

``` csharp
7. Console.WriteLine("The value: {0}.", 500);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/87fbb4ff-0ca2-4dcb-b033-75c6fafacbf7)

``` csharp
8. Console.WriteLine("The value: {0:C}.", 500);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/b4cc942d-7aa4-4c90-9018-e569c1452b40)

``` csharp
9. Console.WriteLine("{0,-10:F4}", 12.3456789);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/e67f3c59-bf7d-4b65-9f5d-8572bcb6634d)

``` csharp
10. Console.WriteLine("{0,-10:C}", 12.3456789);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/b49c2e20-38c1-44d8-b0b8-b7e24f7772ee)

``` csharp
11. Console.WriteLine("{0,-10:E3}", 12.3456789);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/2c5a5323-0e2b-4692-b1b6-244db8e827fe)

``` csharp
12. Console.WriteLine("{0,-10:x}", 65535);  // (x = lower case)
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/bb982930-828e-44fe-9faa-ab2df2551e09)

``` csharp
13. Console.WriteLine("{0,-10:X}", 65535);  // (X = upper case)
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/62381fd7-0f81-4693-806d-904faa0d12fa)

``` csharp
14. int i;
    Console.WriteLine("Value\tSquared\tCubed");
    for(i = 1; i < 10; i++)
        Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/7ce621ed-7de5-4af7-b02f-f8959b304fc8)

``` csharp
15. Console.WriteLine("{0:#.###}.", 1234.56789);
```
![image](https://github.com/ThanchiraCharakhon099/03376836-OOP-2566-Lab-01/assets/144195708/12354ba9-b717-4672-879c-68e6f8627ead)




## [การใช้งานคำสั่ง Console.Read() และ Console.ReadLine()](./Lab-01-part-9-12.md)
