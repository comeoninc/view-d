# วิว-ดี : เผยแพร่หน้าเว็บ .html เป็นเว็บแอพได้ง่ายๆ
#เฟรมเวิคปรับปรุงคุณสมบัติไฟล์.html

แอพฯโครงสร้างฐานรากอย่างง่าย เพื่อสร้างรูปแบบของหน้าที่ต้องการเผยแพร่เป็น " เว็บแอพ " 
รุ่นรองรับอุปกรณ์ " ระบบปฎิบัติการแอนดรอยด์ " 
ระบบปฏิบัติการหรือแพลตฟอร์มอื่นๆไม่รองรับชุดคำสั่งนี้ ทำให้ไม่สามารถแสดงผลเนื้อหาบางส่วนของแอพฯได้

หลักการทำงาน 
เลือกใช้ CustomElement มาทำหน้าที่เป็นตัวกรอง และปรับปรุงเนื้อหา html อยู่ที่รากของโดเมน การร้องขอ.html จะถูกเรียกผ่าน Element ทุกไฟล์
เพื่อปรับปรุงรูปแบบ.html ให้สามารถเผยแพร่ได้ตามรูปแบบที่ต้องการ.
