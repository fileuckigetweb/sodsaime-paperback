# สดใสเมะ — Paperback 0.8 Repository v0.1.0

โครงสร้างอ้างอิงจากไฟล์ `source (3).js` (GoManga) ที่ผู้ใช้อัปโหลด ซึ่ง Build ด้วย toolchain/types 0.8.7

## ไฟล์
- `versioning.json` รายการ Source
- `SodsaiMe/source.js` JavaScript bundle (ผ่าน `node --check`)
- `SodsaiMe/icon.png` ไอคอน
- `index.html` หน้า Repository

## เผยแพร่
1. สร้าง GitHub Repository ใหม่ เช่น `sodsaime-paperback`.
2. อัปโหลด **เนื้อหาภายในโฟลเดอร์นี้** ไปที่ root ของ Repository.
3. เปิด Settings → Pages → Deploy from a branch → main / (root).
4. รอให้ Pages เผยแพร่ จากนั้นเพิ่ม URL `https://USERNAME.github.io/sodsaime-paperback/` ใน Paperback 0.8

## จุดทดสอบบน iPhone
- Search คำว่า `one punch man`
- เปิดรายละเอียดเรื่องและตอน
- เปิดหน้าอ่าน
- Latest หน้า 1 → หน้า 2 (URL `/manga/?page=2&order=update`)

**ข้อจำกัด:** ตรวจไวยากรณ์ JS แล้ว แต่ยังไม่ได้ทดสอบกับ Paperback บน iPhone หรือยืนยัน HTML สดของเว็บไซต์ จึงเป็นรุ่นทดลอง ไม่รับประกันการแสดงรายการหรือหน้าอ่านครบทุกเรื่อง. ใช้กับเนื้อหาที่ได้รับอนุญาตเท่านั้น.
