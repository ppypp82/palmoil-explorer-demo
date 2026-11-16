PalmOil Explorer v4

วิธีเปิด:
1. แตกไฟล์ ZIP
2. เปิดโฟลเดอร์ PalmOil_Explorer_v4
3. ดับเบิลคลิก index.html

เมนู:
1. Overview
2. Data Explorer — ข้อมูลครบ 9 CSV tables พร้อมค้นหาและดาวน์โหลด CSV
3. Graph Explorer — ภาพกราฟ Neo4j ต้นฉบับที่แนบมา
4. Semantic Search — แสดงผลทดสอบที่บันทึกไว้สำหรับคำค้น “ข้อมูลเกี่ยวกับน้ำเสียจากโรงงานสกัดน้ำมันปาล์ม” พร้อม score และค้นหาคำอื่นใน CSV แบบ keyword demo
5. Functional Queries — ทดลอง FR-01 ถึง FR-06

ข้อจำกัดสำคัญ:
- เป็นเว็บ static ใช้ข้อมูลสำเนาจาก CSV ไม่ได้เชื่อม MySQL/Neo4j สด
- FR-01 เป็นการ INSERT จำลองใน session ของหน้าเว็บเท่านั้น ไม่ได้บันทึกกลับฐานข้อมูล
- FR-02 ถึง FR-06 ประมวลผลจากข้อมูล CSV ที่แนบมากับเว็บ
- Graph Explorer แสดงภาพนิ่งจาก Neo4j
