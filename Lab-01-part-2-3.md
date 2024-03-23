# Lab-01 Part 2~3 คำสั่ง Console.Write() และ Console.WriteLine()

## 2. การใช้เมดธอด Console.Write()

### 2.1 การใช้เมดธอด Console.Write()
👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้

```csharp
Console.Write("Hello");
Console.Write("Hello");
```

➢ รันโปรแกรมและบันทึกผล


❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
<img width="959" alt="ภาพถ่ายหน้าจอ 2567-03-23 เวลา 20 23 01" src="https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/892ea837-2345-4084-a5c8-a9b8279f258e">

### 2.2 การใช้เมดธอด Console.Write() ร่วมกับ  `Environment.NewLine`

`Environment.NewLine` เป็นค่าคงที่ที่ถูกนิยามในภาษา C# เพื่อใช้สำหรับการส่งอักขระขึ้นบรรทัดใหม่ไปยัง console

👉 แก้ไขโปรแกรม ให้เป็นดังด้านล่างนี้

```csharp
Console.Write("Hello" + Environment.NewLine);
Console.Write("Hello" + Environment.NewLine);
```

➢ รันโปรแกรมและบันทึกผล


❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย
<img width="958" alt="ภาพถ่ายหน้าจอ 2567-03-23 เวลา 20 24 31" src="https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/2a999c9f-1cbf-419f-a75d-aea16c872259">


## 3. เมดธอด Console.WriteLine()

`Console.WriteLine()` เป็นคำสั่งที่เทียบเท่ากับการใช้  `Console.Write` ร่วมกับ  `Environment.NewLine` ทำให้ประหยัดเวลาในการเขียนโปรแกรม
👉 แก้โปรแกรมในเมดธอด Main() ให้เป็นดังต่อไปนี้

```csharp
Console.WriteLine("Hello");
```

➢ รันโปรแกรมและบันทึกผล
<img width="959" alt="ภาพถ่ายหน้าจอ 2567-03-23 เวลา 20 24 48" src="https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/fbf2cabb-3061-470c-8391-6caf4c6f3391">


👉 แก้ไขโปรแกรม ให้เป็นดังรูปด้านล่างนี้

```csharp
Console.Write("Hello, ");
Console.WriteLine("World!");
```

➢ รันโปรแกรมและบันทึกผล
<img width="951" alt="ภาพถ่ายหน้าจอ 2567-03-23 เวลา 20 25 02" src="https://github.com/kanoksiriboonkam/03376836-OOP-2566-Lab-01/assets/144196048/e9029d72-8339-46fe-8c47-8b2ace756c47">

❔ ผลที่ได้จากการทดลอง เป็นอย่างที่นักศึกษาคิดหรือไม่ อย่างไร จงอธิบาย คำสั่งHello และ world จะอยู่ในบรรทัดเดียวกัน

❔ จงอธิบายความแตกต่างระหว่างคำสั่ง Console.Write() และ Console.WriteLine() 
Console.Write()จะแสดงคำให้อยู่ในบรรทัดเดียวกัน แต่ Console.WriteLine()จะเว้นบรรทัด
## [4. จำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()](./Lab-01-part-4.md)
