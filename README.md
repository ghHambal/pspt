# PDF Statement Parser (TH)

Local-first parser สำหรับสเตทเม้นท์ธนาคารภาษาไทย: **Tailwind + pdf.js + Chart.js + SheetJS**  
รองรับ: อ่านเฉพาะตาราง, จำแนกประเภทจาก Code, กรองแบบ **Unique Dropdown**, สรุปยอด + Audit, ส่งออก **CSV/XLSX/XLSX ตามหมวด**

**เดโม (รันไฟล์เดียว):** เปิด `index.html`

## ฟีเจอร์
- อ่าน PDF ด้วย pdf.js (ทำงานในเครื่อง 100%)
- Unique dropdown filters ทุกคอลัมน์ (ไม่ต้องพิมพ์เอง)
- แผนภูมิรายเดือน / สัดส่วนค่าใช้จ่าย / สุทธิสะสม (Chart.js)
- ตรวจยอดรวมจากหน้าสุดท้าย (Audit)
- ส่งออก CSV, XLSX, และ XLSX แยกชีต/ไฟล์ตามหมวด (มีโหมดสำรอง .xls)

## เทคโนโลยี
Tailwind, pdf.js, Chart.js, SheetJS

## การใช้งาน
1. เปิด `index.html`
2. เลือกไฟล์ PDF (ใส่รหัสผ่านถ้ามี)
3. ปรับรูปแบบวันที่และตั้งค่า Code ได้ใน “ตั้งค่า Parser”
4. กรองข้อมูลผ่าน dropdown แล้วดาวน์โหลดผลลัพธ์

## ใบอนุญาต
MIT
