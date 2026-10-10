# KritRod 3D Showroom

โชว์รูมรถ 3 มิติในหน้าเดียว (three.js r128) — Honda Civic e:HEV, Toyota Corolla Altis, Lamborghini Aventador LP720-4 และ Ferrari Roma
มีโหมด Showroom, Blueprint, Engine (แยกชิ้น) และ Chassis (โครงสร้างตัวถัง ช่วงล่าง ระบบไฟ ของเหลว)

เว็บนี้ทำขึ้นเพื่อการศึกษา ไม่ใช้เชิงพาณิชย์ และไม่เกี่ยวข้องกับ Honda, Toyota, Lamborghini หรือ Ferrari

## ไฟล์

| ไฟล์ | เนื้อหา |
|---|---|
| `index.html` | หน้าเว็บทั้งหมด (HTML + CSS + JS) |
| `civic.json`, `altis.json`, `lambo.json`, `roma.json` | โมเดล glTF ที่ฝัง buffer เป็น base64 |

เป็น static ล้วน ไม่มีขั้นตอน build เปิดดูในเครื่องได้ด้วย

```bash
python -m http.server 8000
```

## เครดิตโมเดล 3 มิติ

| โมเดล | ผู้สร้าง | สัญญาอนุญาต | การดัดแปลง |
|---|---|---|---|
| [2025 Honda Civic RS e:HEV](https://sketchfab.com/3d-models/0dc6454d74a241e5a08fac82ce2826b2) | [Palma123 JAAT](https://sketchfab.com/palma123.jaat) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | ย่อขนาดให้ยาวเท่าสเปก |
| [Toyota Corolla Altis](https://sketchfab.com/3d-models/006c00b97d174d03bec347adf52d0bbd) | [niev](https://sketchfab.com/niev) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | ย่อขนาด ตัดชิ้นส่วนที่ไม่เกี่ยวข้อง |
| [Lamborghini Aventador LP720-4 50th Anniversary](https://sketchfab.com/3d-models/lamborghini-aventador-lp720-4-50th-anniversary-7c210c26a24c4b2d883cee882921cf0c) | [Ddiaz Design](https://sketchfab.com/ddiaz-design) | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) | บีบอัดพื้นผิว เปิดให้เปลี่ยนสีตัวถัง |
| [2020 Ferrari Roma](https://sketchfab.com/3d-models/2020-ferrari-roma-cbc0c13c0fb54fc8bbfa79a9ff99e3aa) | [Ddiaz Design](https://sketchfab.com/ddiaz-design) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | รวมชิ้นส่วน บีบอัดพื้นผิว เปิดให้เปลี่ยนสีตัวถัง |

`lambo.json` เป็นงานดัดแปลงจากโมเดล CC BY-NC-SA 4.0 จึงเผยแพร่ต่อภายใต้สัญญาอนุญาตเดียวกัน และห้ามใช้เชิงพาณิชย์
