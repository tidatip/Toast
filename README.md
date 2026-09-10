# Toast v1.2

## ไฟล์
index.html · sw.js · manifest.json · icons/ · firestore.rules

## ติดตั้ง
1. อัปโหลดทั้งโฟลเดอร์ขึ้น repo `tidatip.github.io/Toast`
2. เปิดใช้ได้ทันทีในโหมดทดลอง (localStorage, เห็นแค่เครื่องเดียว)
3. เพื่อใช้ร่วมกับเพื่อน: สร้าง Firebase project ใหม่ → Firestore (production mode) →
   วาง `firestore.rules` → คัดลอก config มาใส่ `FIREBASE_CONFIG` ใน index.html

## เวอร์ชัน
ต้องเปลี่ยน 3 ที่: `VERSION` ใน index.html · `CACHE` ใน sw.js · ชื่อไฟล์ zip

## URL
- `?t=ID`      หน้าผู้รับฝาก (ต้องมี PIN ในเครื่องนั้น)
- `?t=ID&r=1`  หน้าผู้ฝาก (ลิงค์ที่ส่งเข้ากลุ่ม)
