# สารบัญโปรเจคทั้งหมด

_อัปเดต: 2026-09-08_

## คุมจริงจัง (มี subagent + STATUS.md) — ดู CLAUDE.md

| โปรเจค | Path | คืออะไร | subagent |
|---|---|---|---|
| **BTK** | `btk` | ใบเสนอราคา/ใบแจ้งหนี้ บ. บีทีเค (single-file HTML + Supabase) | `btk-agent` |
| **The Bright** | `thebright-main` | ระบบจัดการโรงเรียนกวดวิชา (Next.js + Supabase + Vercel) · repo `thionwatthanakit-afk/TheBright` · Supabase `qmydasezcwegkuxygzpe` | `bright-agent` |
| **Prism Lab** | `prism-lab` (โค้ดที่ `prism-lab/app`) | ทดลองทำ The Bright เป็น SaaS หลายโรงเรียน — ระยะ research + fork แล้ว | `prism-agent` |

## ทำเล่นๆ / ทดลอง — ยังไม่คุมจริงจัง (ไม่มี subagent, ไม่ต้องตามงาน)

| โปรเจค | Path | คืออะไร | หมายเหตุ |
|---|---|---|---|
| **arena-pos** | `arena-pos` | POS + บัญชี สนามฟุตบอล — ขาย/รายจ่าย/สต็อก/ขายเชื่อ/ปิดงวด 26–25 แบ่งกำไร + PDF · Next.js + Supabase + Vercel · ยกจาก Google Sheets | repo `plaipk/ARENA-POS` · ทำเล่นๆ |
| **NKT-Rescue-Refer** | `NKT-Rescue-Refer` | ระบบ EMS / รับส่งต่อผู้ป่วย รพ. · Next.js + Supabase | repo `nutunrees-bot/NKT` · ทำเล่นๆ |
| **quotesaas** | `quotesaas` | ทำเอกสารใบเสนอราคาหลายรูปแบบ (หลายบริษัท/หลายเทมเพลต) — คนละอันกับ Prism · ตอนนี้เป็น demo localStorage ไฟล์เดียว ไว้โชว์ลูกค้า Fastwork · schema.sql ร่างไว้ ยังไม่ต่อ backend จริง | repo `plaipk/EZDoc` · ทำเล่นๆ |
| **Bork** | `Bork` | product "money app" — landing html + mockup + Expo app (`bork-money-app`) + Next.js (`bork-money-bot`) + prompt รูป | ระยะเริ่ม · ทำเล่นๆ |
| **gridbot** | `gridbot` | สคริปต์ Python backtest คริปโต (grid / DCA / rebalance strategies) | งานวิจัยส่วนตัว |
| **camera-playground** | `camera-playground` | เว็บเล่นกล้อง — detect หน้า/มือ/การเคลื่อนไหว + เมนูท่ามือไซเบอร์พังก์ (browser ล้วน) | toy |
| **fast work** | `fast work` | โฟลเดอร์ screenshot + รูป reference งาน Fastwork | ไม่ใช่โค้ด |
| **สุ่มเมนูอาหารไทย** | `สุ่มเมนูอาหารไทย.html` | หน้าเว็บสุ่มเมนูอาหารไทย + สูตร | toy ไฟล์เดียว |

> ถ้าผู้ใช้จะ "โฟกัส" ตัวไหนในกลุ่มนี้ → ตอนนั้นค่อยสร้าง subagent + `<โปรเจค>/STATUS.md` แล้วย้ายขึ้นกลุ่มบน + อัปเดต `CLAUDE.md`
