# ใบงานการทดลอง HTML

## การทดลองที่ 5: การสร้างตารางและรายการ
### วัตถุประสงค์
- เรียนรู้การสร้างตารางข้อมูล
- เรียนรู้การสร้างรายการแบบต่างๆ

### ขั้นตอนการทดลอง
1. สร้างไฟล์ tablelist.html ดังตัวอย่าง:
```html
<table border="1">
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </tbody>
</table>
```

### คำอธิบายเพิ่มเติม
- `<table>` กำหนดขอบเขตของตาราง
- `<thead>` สำหรับส่วนหัวตาราง
- `<tbody>` สำหรับเนื้อหาตาราง
- `<tr>` แทนแถว
- `<th>` แทนเซลล์หัวตาราง
- `<td>` แทนเซลล์ข้อมูล

2. การสร้างรายการ โดยเพิ่มเติม Code ในไฟล์ tablelist.html :
```html
<ul>
    <li>Unordered item 1</li>
    <li>Unordered item 2</li>
</ul>

<ol>
    <li>Ordered item 1</li>
    <li>Ordered item 2</li>
</ol>

<dl>
    <dt>Term 1</dt>
    <dd>Definition 1</dd>
    <dt>Term 2</dt>
    <dd>Definition 2</dd>
</dl>
```

### คำอธิบายเพิ่มเติม
- `<ul>` สำหรับรายการแบบไม่เรียงลำดับ
- `<ol>` สำหรับรายการแบบเรียงลำดับ
- `<dl>` สำหรับรายการแบบคำจำกัดความ
- `<li>` แทนรายการแต่ละรายการ

### แบบฝึกหัด
1. สร้างตารางแสดงข้อมูลส่วนตัว
2. สร้างรายการเมนูอาหาร

[วางโค้ด HTML ที่นี่]
```html
<<table border="4">
    <h1>ตารางชีวิต</h1>
    <thead>
        <tr>
            <th>เวลาตื่น/นอน</th>
            <th>เวลาเรียน</th>
            <th>พักรับประทานข้าว</th>
            <th>เวลาเรียน</th>
            <th>กลับบ้านนอน</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>08:00-16:00</td>
            <td>08:00</td>
            <td>12:00</td>
            <td>16:00</td>
            <td>23.00</td>
        </tr>
        <tr>
            <td></td>
            <td>LAB T.Piya</td>
            <td>Enjoy Eating</td>
            <td>Software Design</td>
            <td>Freetime/sleep</td>
        </tr>
    </tbody>
</table>
<h1></h1>
<ul>
    <li>กระเพราไก่ 50 baht</li>
    <li>กระเพราหมูกรอบ 60 baht</li>
    <li>กระเพราทะเล 60 baht</li>
    <li>กระเพราหมูสับ 50 baht</li>
    <li>กระเพรากุ้ง 59 baht</li>
    <li>กระเพราปลาหมึก 50 baht</li>
    <li>เพิ่มไข่ดาว 10 baht</li>
</ul>

<ol>
    <li>กระเพรา 50 baht</li>
    <li>กระเพราหมูกรอบ 60 baht</li>
    <li>กระเพราทะเล 60 baht</li>
    <li>กระเพราหมูสับ 50 baht</li>
</ol>

<dl>
    <dt>ป้าจิ๋ม</dt>
    <dd>สั่งกระเพราหมูสับไข่ดาว</dd>
    <dt>น้าสาว</dt>
    <dd>สั่งกระเพราหมูกรอบไข่ดาว</dd>
</dl>


```
- ภาพผลลัพธ์:
[วางภาพ screenshot ที่นี่]
![image](https://github.com/user-attachments/assets/cc40ddf3-8fb6-4fe0-be2c-bd7e45558fb2)


