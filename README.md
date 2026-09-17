# Personal Password Manager System (ระบบจัดการบัญชีและรหัสผ่านส่วนบุคคล)

## สมาชิกในทีม
1. นายกิตติคุณ (008) - Project Manager
2. นายกิตติพงษ์ (009) - Business Analyst 
3. นายจักรกฤษณ์ (011) - Software Developer
4. นายพงษ์พิสุทธิ์ (019) - UI/UX Designer

## รายละเอียดโปรเจกต์
ระบบบันทึกและจัดการรหัสผ่านส่วนบุคคล รองรับการยืนยันตัวตนด้วย Master Password, การเข้ารหัสรหัสผ่าน, ค้นหาตามหมวดหมู่ และ คัดลอกไปยัง Clipboard

## โครงสร้างโปรเจกต์
- `src/models/` : คลาสโครงสร้างข้อมูล User, Account, Category
- `src/services/` : ระบบจัดการเข้ารหัส PasswordManager และ Database
- `src/ui/` : โค้ดเชื่อมต่อส่วนแสดงผลผู้ใช้

## วิธีการติดตั้งและรันใช้งาน
1. Clone Repository นี้ลงเครื่อง
2. เปิดไฟล์ `index.html` ผ่านเว็บเบราว์เซอร์