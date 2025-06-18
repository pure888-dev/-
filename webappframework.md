เว็บแอปพลิเคชั่นคือ ซอฟต์แวร์ที่ทำงานบนเบราเซอร์

องค์ประกอบ 
:แบ่งได้สองแบบ มีความสัมพันธ์กันหมด 1.ไคลแอนท์ คือฝั่งผู้ใช้ ร้องขอและแสดงผลลัพธ์จากทางฝั่ง Server 
เข้าข่าย Font-End 

เซิฟเวอร์ 
:ทำหน้าที่ประมวลผลคำสั่ง มีหน้าที่ติดต่อกับฐานข้อมูล เข้าข่าย Back-End

ฐานข้อมูล 
:เป็นระบบที่ใช้เก็บข้อมูลของผู้ใช้ 

การทำงาน User มีการร้องขอข้อมูล เซิฟเวอร์มีการติดต่อฐานข้อมูล ส่งกลับมาในรูปแบบของไฟล์ต่างๆ

สถาปัตยกรรม 
:Font-End มี UX/UI Components เน้นในเรื่องของหน้าตา ประสบการณ์ผู้ใช้, Client-Site-Logic หรือ ตรรกะฝั่งไคลแอนด์ๆๆ
Back-End เป็นเรื่องของ Server เช่น Apache ที่เป็น Web Server, Application Server, Database Server, API

Optional จะมี Catching System จะทำให้รู้สึกเร็วขึ้น Load Balancer ป้องกันการทำงานหนักเกินไปของเซิฟเวอร์ CDN, Authen
เป็นระบบยืนยันตัวตน

Client-Server Architecture เป็นรูปแบบกระจาย มีเซิฟเวอร์เป็นผู้ให้บริการ ไคลแอนต์ร้องขอ เซิฟเวอร์ส่งกลับ
![image](https://github.com/user-attachments/assets/a5c16cf5-062a-482d-8bf0-2a7314044181)
-----------------------------------
![image](https://github.com/user-attachments/assets/64ff85fe-042d-47d8-8d3e-544d289a597a)


เครื่องมือที่ใช้จะมีหลายส่วน 1.Font-End Framework and Lib
มี React, NextJS, Bootstrap, Tailwind CSS

2.Back-End เป็นส่วนติดต่อกับ Database เช่น express asp.net, flask, nodejs, spring, django, laravel

3.Devlopment Enviroments and Code Editors เช่น VSCode 

4.Version Control เช่น github

5.COntainerization สำหรับควบคุม เช่น Docker

6.Package Manager เช่น npm 

7.Web Server / Web Server Package ฮาร์ดแวร์ ซอฟต์แวร์ที่ทำงานร่วมกับ / ชุดรวมซอฟต์แวร์
เช่น Nginx, Apache / xampp คือ  Web Server Package

8.Databases มีแบบ SQL และ  NoSQL 

9.API เช่น POSTMAN ซึ่งเป็นเครื่องมือทดสอบ API

10.Cloud Platform ทำหน้าที่เป็นเซิฟเวอร์ของเรา
