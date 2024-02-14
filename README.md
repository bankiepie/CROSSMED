# CROSSMED
 A Blockchain-based Access Control for Secure and Fine-grained Cross Medical Treatment Record Data Sharing 
--เปลี่ยนข้อมูล
ไฟล์ services/contractServices.js
contractAddress เป็น address ของ contract ที่ deploy ขึ้นมาใหม่
privateKey เอาจาก metamask ไปที่จุดสามจุดขวาบน เลือก account detail เลือก show privatekey
userAddress กอป address ของกระเป๋าตัวเองอันเดียวกับที่ใข้ privateKey

ไฟล์ routes/index.js
private_key ที่ใช้ในการเช้ารหัส เปลี่ยนหรือไม่เปลี่ยนก็ได้
ตอนนี้ user1 ใช้ private_key1 user2 ใช้ private_key2

เปลี่ยนข้อมูลทั้ง 2 โฟลเดอร user1 และ user2 ตามกระเป๋าที่สร้าง

ติดตั้งโปรเจค
1 ติดตั้ง node 17.0.0
2 เปิด cmd เข้า user1 
3 รัน npm i
4 รัน npm start

ติดตั้งเหมือนกันทั้ง user1 และ user2
