# 🚀 NEON DASH 3D

เกม 3D บังคับจรวดหลบสิ่งกีดขวาง สร้างด้วย Three.js (ไฟล์เดียว ไม่ต้อง build)

## ▶ วิธีเล่น
- ⬅️➡️ หรือ A/D = บังคับจรวด
- 📱 มือถือ: ลากนิ้วซ้าย-ขวา
- เก็บ ⬤ ออร์บสีเหลือง = +50 คะแนน
- ความเร็วเพิ่มขึ้นเรื่อยๆ ยิ่งนานยิ่งยาก!

## 🌐 Deploy ขึ้น GitHub Pages (ฟรี)
1. สร้าง repo ใหม่ชื่ออะไรก็ได้ เช่น `neon-dash`
2. อัปโหลด `index.html` ไฟล์นี้เข้า repo (root)
3. ไปที่ Settings → Pages → Source: Deploy from branch → Branch: main / (root) → Save
4. รอ 1 นาที เกมจะออนไลน์ที่ `https://<username>.github.io/neon-dash/`

## 🔧 แก้เกมต่อ
- `speed += dt*.55` — อัตราเร่งความยาก
- ตัวแปร `spawnObstacle` — ปรับความถี่/ขนาดอุปสรรค
- เปลี่ยนสี neon ได้ที่ `emissive` ของวัสดุแต่ละชิ้น

### [กดที่นี่เพื่อเปิด](https://aomsinjaroensuk15-stack.github.io/NEO-DASH-3D/)
