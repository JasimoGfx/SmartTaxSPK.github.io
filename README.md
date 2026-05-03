# JasimoGfx.github.io

SmartTax SPK — เว็บไซต์คำนวณภาษีเงินได้บุคคลธรรมดา สำหรับประเทศไทย ปี 2569

## ฟีเจอร์
- คำนวณภาษีแบบ real-time
- เลือกช่วงเวลา (ต่อปี, เดือน, วัน, ชั่วโมง)
- ปรับค่าลดหย่อนต่างๆ
- แสดงกราฟและสถิติ

## วิธีใช้งาน
เปิดไฟล์ `smarttax-spk.html` ในเบราว์เซอร์

หรือรันเซิร์ฟเวอร์โลคอล:
```bash
python3 -m http.server 8000
```
แล้วเปิด http://localhost:8000/

หรือหากต้องการหน้าเริ่มต้นโดยตรง ให้ใช้ `index.html` ซึ่งจะเปลี่ยนเส้นทางไปยัง `smarttax-spk.html`

## การ Deploy บน GitHub Pages
1. Push โค้ดไปยัง repository `JasimoGfx.github.io` บน GitHub
2. ไปที่ Settings > Pages
3. เลือก Source เป็น "Deploy from a branch" และ Branch เป็น `main`
4. เว็บไซต์จะพร้อมใช้งานที่ `https://jasimogfx.github.io/`

## ข้อมูลอ้างอิง
คำนวณตามกฎหมายภาษีของกรมสรรพากรไทย (rd.go.th)

## ข้อมูลอ้างอิง
คำนวณตามกฎหมายภาษีของกรมสรรพากรไทย