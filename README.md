# WST Audit CRM

CRM คอนแทคลูกค้างานสอบบัญชีสำหรับ WST — เว็บแอปไฟล์เดียว (index.html)

- ข้อมูลเก็บใน localStorage และ sync ผ่าน repo ส่วนตัว `tpnaudit/wst-audit-data` (ไฟล์ `crm.enc.json`)
- เชื่อมกับ WST Audit Tracker (อ่าน `data.enc.json` มาแสดงงานจริง) — token/PIN เดียวกัน
- `keygen.html` = เครื่องมือเข้ารหัส PAT เป็น `sync-token.enc.js` (ทำงานในเครื่อง ไม่ส่ง token ออกไปไหน)
