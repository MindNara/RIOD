
1. เปิด xampp

2. กด Start ที่ apache

3. กด Start ที่ mySQL ( ไม่ต้อง Edit )

4. เปิด PHPmyAdmin
	วิธีเข้า
	- พิมพ์ใน URL -> localhost
	- เลือกปุ่มบนขวาของจอ "phpMyAdmin"

5. สร้าง db ทางซ้าย ชื่อว่า "register_db"
	- กด new
	- ใส่ชื่อว่า "register_db"
	- เลือก unicode เป็น "utf8_general_ci"
	- กด create

5.1. กด Import ไฟล์ชื่อ "register_db.sql" ข้างใน db ที่ชื่อ "register_db"
	- ไม่ต้อง set อะไรเลย
	- กด import

6. สร้าง db ทางซ้าย ชื่อว่า "tbwm"
	- กด new
	- ใส่ชื่อว่า "tbwm"
	- เลือก unicode เป็น "utf8_general_ci"
	- กด create

6.1. กด Import ไฟล์ชื่อ "tbwm.sql" ข้างใน db ที่ชื่อ "tbwm"
	- ไม่ต้อง set อะไรเลย
	- กด import

7. พิมพ์ localhost/RIOD-main/ ในช่อง url 

8. เปิด RIOD
