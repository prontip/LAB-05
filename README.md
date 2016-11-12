
พรทิพย์  เกิดรัตน์  57030199

#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ตอบ เมื่อรันโปรแกรมแล้วจะปรากฎหน้าต่างสีดำcommandline และภายในปรากฎ this is text 1.ในบรรทัดที่1 this is text 2.ในบรรทัดที่2 this is text 3.ในบรรทัดที่3
  
  ![](https://github.com/prontip/LAB-05/blob/master/img/1.png?raw=true)
<hr>
<hr>
<hr>
<hr>
<hr>
 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้
 
 ในcommandline ปรากฎข้อความ 3 and 6
 
 ![](https://github.com/prontip/LAB-05/blob/master/img/2.png?raw=true)





###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร


{} เหมือนเป็นตัวเก็บเลขตำแหน่งตัวข้างหลัง Console.WriteLine(" {0} and {1} ",3,6);
 
 ![](https://github.com/prontip/LAB-05/blob/master/img/3.png?raw=true)
 
 3 สามอยู่ตำแหน่งที่ 0 ,6 สามอยู่ตำแหน่งที่ 1

<hr>
<hr>
<hr>
<hr>
<hr>
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย


ตอบ ใช้เลขข้ามได้แต่เลขที่ใช้จะต้องมีข้อมูลณตำแหน่งนั้น 
Console.WriteLine(" {1} and {0} and {2} ",3,6,1);ใช้ได้มีข้อมูลตำแหน่ง 2 คือเลข 1
Console.WriteLine(" {1} and {0} and {2} ",3,6,);ใช้ไม่ได้เพราะไม่มีข้อมูลตำแหน่ง 2


<hr>
<hr>
<hr>
<hr>
<hr>
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้
 
 ตอบ ตอบ ในcommandline ปรากฎข้อความ 6, 3 and 6
 
 ![](https://github.com/prontip/LAB-05/blob/master/img/4.png?raw=true)
<hr>
<hr>
<hr>
<hr>
<hr>

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ตอบ ปรากฎข้อความในcommandline ดังรูป
  
  ![](https://github.com/prontip/LAB-05/blob/master/img/5.png?raw=true)
<hr>
<hr>
<hr>
<hr>
<hr>

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร

ตอบ {x,y} 
Y คือ ค่าความกว้างของอาร์กกิวเมนต์
x คือ ข้อมูลที่จะให้ปรากฎในบิตสุดท้ายต่อจากความกว้างของอาร์กิวเมนต์ที่กำหนดไว้


<hr>
<hr>
<hr>
<hr>
<hr>


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ในcommandline ปรากฎข้อความดังรูป
  
  ![](https://github.com/prontip/LAB-05/blob/master/img/6.png?raw=true)
<hr>
<hr>
<hr>
<hr>
<hr>

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  
  ในcommandline ปรากฎข้อความดังรูป
  
  ![](https://github.com/prontip/LAB-05/blob/master/img/7.png?raw=true)

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้

ในcommandline ปรากฎข้อความดังรูป


![](https://github.com/prontip/LAB-05/blob/master/img/8.png?raw=true)

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```
![](https://github.com/prontip/LAB-05/blob/master/img/9.png?raw=true)
