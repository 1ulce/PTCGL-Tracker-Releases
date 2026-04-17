[English](README.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Bahasa Indonesia](README.id.md) | [Italiano](README.it.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Español](README.es.md) | [ภาษาไทย](README.th.md)

# PTCGL Tracker

เครื่องมือที่บันทึกบันทึกการต่อสู้ที่แสดงหลังการแข่งขันใน Pokémon Trading Card Game Live (PTCGL) โดยอัตโนมัติ

## ดาวน์โหลด

[ดาวน์โหลดเวอร์ชันล่าสุด](https://github.com/1ulce/PTCGL-Tracker-Releases/releases/latest)

| OS | ไฟล์ |
|---|---|
| Windows | `PTCGL Tracker.exe` |
| macOS | `PTCGL Tracker.app.zip` |

## วิธีการติดตั้ง

### Windows

1. ดาวน์โหลด `PTCGL Tracker.exe`
2. วางในโฟลเดอร์ใดก็ได้และเรียกใช้
3. การติดตั้งเสร็จสมบูรณ์เมื่อไอคอนปรากฏในถาดระบบ

### macOS

1. ดาวน์โหลด `PTCGL Tracker.app.zip`
2. แตกไฟล์และย้าย `PTCGL Tracker.app` ไปยังโฟลเดอร์ Applications
3. เมื่อเปิดครั้งแรก ให้คลิกขวา → "Open" เพื่อเรียกใช้

## ⚠️ การตั้งค่า PTCGL (สำคัญ)

เพื่อให้การวิเคราะห์รีเพลย์ทำงานได้อย่างถูกต้อง กรุณากำหนดค่าต่อไปนี้ใน PTCGL

![การตั้งค่า PTCGL](ptcgl-settings.png)

### 1. เปิดใช้งานโหมดหน้าต่าง
`VIDEO OPTIONS` → **เลือก "WINDOWED"**

จำเป็นสำหรับให้ tracker เข้าถึงไฟล์บันทึกได้

### 2. ตั้งค่าภาษาเป็นภาษาอังกฤษ
`LANGUAGE` → **เลือก "ENGLISH"**

ปัจจุบันรองรับเฉพาะบันทึกภาษาอังกฤษสำหรับการวิเคราะห์รีเพลย์

### 3. แสดง ID การ์ด
`BATTLE LOG SETTINGS` → **ยกเลิกการเลือก "HIDE CARD IDS FROM EXPORT"**

หากไม่มี ID การ์ด รูปภาพการ์ดจะไม่แสดงในบันทึก

## วิธีการใช้งาน

1. เปิด PTCGL Tracker (ทำงานในถาดระบบ)
2. จบการต่อสู้ใน PTCGL
3. ปุ่ม "BATTLE LOG" บนหน้าจอผลลัพธ์จะถูกคลิกโดยอัตโนมัติ
4. บันทึกการต่อสู้จะถูกบันทึกอัตโนมัติใน `~/PTCGLLogs/`

## อัปโหลดไปยังคลาวด์
สร้างบัญชีที่ PTCGTools และเข้าสู่ระบบเพื่อจัดการบันทึกการต่อสู้และเด็คของคุณบน[เว็บไซต์ PTCGL Replayer](https://replay.ptcgtools.com)

## อัปเดตอัตโนมัติ

เมื่อมีการเผยแพร่เวอร์ชันใหม่ การแจ้งเตือนจะปรากฏขึ้นเมื่อเปิดแอป
คุณสามารถอัปเดตได้อย่างง่ายดายจากเมนูถาดระบบ

## ภาษาที่รองรับ

🇯🇵 日本語 | 🇺🇸 English | 🇨🇳 简体中文 | 🇫🇷 Français | 🇩🇪 Deutsch | 🇮🇩 Bahasa Indonesia | 🇮🇹 Italiano | 🇰🇷 한국어 | 🇧🇷 Português | 🇪🇸 Español | 🇹🇭 ภาษาไทย

## ความต้องการของระบบ

- Windows 10/11
- macOS 12+

## ลิขสิทธิ์

MIT License

## รายงานปัญหา

โปรดรายงานจุดบกพร่องและคำขอผ่าน [Issues](https://github.com/1ulce/PTCGL-Tracker-Releases/issues)
