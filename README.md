# tensura

Tensura Neo Otherworld — คู่มือฉบับแจกจ่าย (static site, พร้อม deploy บน Vercel)

## โครงสร้าง

- `index.html` หน้าแรก + เริ่มด่วน
- `skills.html` สกิลทั้งหมด + เงื่อนไขครอบครอง
- `mobs.html` ม็อบ / เรทเกิด / ถิ่น
- `ores.html` แร่ / สูตรผสมโลหะ
- `bosses.html` บอส / วิธีเสก / มิติ
- `systems.html` ระบบสำคัญ / คำสั่ง + วิธี deploy
- `quests.html` เควสหลัก / เควสห้ามข้าม
- `items.html` ไอเทม / ของอีโวรายเผ่า
- `assets/` รูปไอเทม/สกิลจากม็อด
- `vercel.json` cleanUrls

## รันโลคอล

```bash
npx serve .
```

## Deploy

```bash
npx vercel --prod
```

หรือ import repo นี้ใน Vercel Dashboard (static, ไม่ต้อง build)
