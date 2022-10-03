# วิธีการอัพเดต db.json

1. แก้ไขไฟล์ `src/data/raw_database.json` เพิ่ม ตำบล/อำเภอ
2. ไปที่ https://earthchie.github.io/jquery.Thailand.js/jquery.Thailand.js/database/tools/ และอัพโหลดไฟล์ `raw_database.json` เพื่อทำการบีบอัดไฟล์ให้เป็น `db.json`
3. นำไฟล์ที่ได้จากข้อ 2 มา replace `src/data/db.json`
4. เปิด pull request ไปที่ https://github.com/gluons/vue-thailand-address master
