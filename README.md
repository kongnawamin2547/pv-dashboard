# PV Energy Analytics Dashboard

## เปิดแบบเร็วที่สุด (ไม่ต้องติดตั้งอะไร)
ดับเบิลคลิกไฟล์ `pv_energy_dashboard.html` เปิดในเบราว์เซอร์ได้เลย (ต้องต่ออินเทอร์เน็ตเพื่อโหลดไลบรารีจาก CDN)

## เปิดใน VS Code (สำหรับแก้ไขโค้ด/ต่อข้อมูลจริง)
1. เปิดโฟลเดอร์ `pv-dashboard` ใน VS Code
2. เปิด Terminal ใน VS Code แล้วรัน:
   ```bash
   npm install
   npm run dev
   ```
3. เปิดลิงก์ที่ขึ้นมา (ปกติ `http://localhost:5173`)

ไฟล์หลักที่ใช้แก้ไขคือ `src/App.jsx` — ฟังก์ชัน `makeDayData()` และ `makeHourlyData()` คือจุดที่ควรแทนที่ข้อมูลจำลองด้วยข้อมูลจริงจาก inverter
