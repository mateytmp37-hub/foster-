# Foster Engineering Website

เว็บไซต์ Foster Engineering (Industrial Automation Thailand) — static site ไม่ต้อง build

## โครงสร้างไฟล์

```
├── index.html          # โครงหน้าเว็บ (HTML)
├── css/
│   └── style.css       # สไตล์ทั้งหมด
├── js/
│   └── main.js         # สคริปต์ + ข้อมูลเนื้อหา (บริการ / โปรเจกต์ / ลูกค้า / แปลภาษา)
└── assets/
    ├── images/
    │   ├── logo.png, hero-bg.jpg
    │   ├── services/   # รูปประกอบบริการ
    │   ├── projects/   # รูปโปรเจกต์
    │   ├── solutions/  # รูปโซลูชัน
    │   ├── clients/    # โลโก้ลูกค้า (webp)
    │   ├── clients-alt/# โลโก้ลูกค้าที่ไม่มีไฟล์ webp (jpg)
    │   └── photos/     # รูปถ่ายหน้างาน
    └── video/          # วิดีโอพื้นหลัง (.webm / .mp4)
```

## เปิดดูในเครื่อง

ดับเบิลคลิก `index.html` ได้เลย หรือรันเซิร์ฟเวอร์:

```bash
python3 -m http.server 8000
# แล้วเปิด http://localhost:8000
```

## Deploy ด้วย GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)`
