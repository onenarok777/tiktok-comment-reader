# 🎵 TikTok Live Reader

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Flet](https://img.shields.io/badge/GUI-Flet-purple.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

โปรแกรมสำหรับอ่านคอมเมนต์ TikTok Live แบบ Real-time พร้อมระบบอ่านออกเสียง (Text-to-Speech) และหน้าจอ GUI ที่สวยงามใช้งานง่าย

## ✨ ฟีเจอร์หลัก (Features)

- 💬 **Real-time Comments**: ดึงคอมเมนต์จาก TikTok Live ได้ทันที
- 🗣️ **Text-to-Speech (TTS)**: อ่านออกเสียงคอมเมนต์ภาษาไทยให้ฟังอัตโนมัติ
- 🖥️ **Modern GUI**: หน้าจอสวยงาม ทันสมัย ใช้งานง่ายด้วย Flet
- 🎛️ **Control Panel**: เปิด/ปิดเสียงได้ตามต้องการ
- 🚀 **Easy to Use**: แค่กรอกชื่อช่องก็เริ่มใช้งานได้เลย

## 🛠️ การติดตั้ง (Installation)

1. **Clone Repository**

   ```bash
   git clone https://github.com/onenarok777/tiktok-comment-reader.git
   cd tiktok-comment-reader
   ```

2. **Run Application**
   เรามีสคริปต์สำเร็จรูปให้ใช้งาน ง่ายๆ แค่คำสั่งเดียว:
   ```bash
   ./run.sh
   ```
   _ระบบจะทำการสร้าง Virtual Environment และติดตั้ง Library ที่จำเป็นให้เองโดยอัตโนมัติในครั้งแรก_

## 📖 วิธีการใช้งาน (Usage)

1. รันโปรแกรมด้วยคำสั่ง `./run.sh`
2. หน้าต่างโปรแกรมจะเด้งขึ้นมา
3. กรอก **ชื่อผู้ใช้ TikTok** ที่กำลัง Live อยู่ (ไม่ต้องใส่ @)
   - ตัวอย่าง: `charlieputh`, `blackpink`
4. กดปุ่ม **"เริ่มเชื่อมต่อ"**
5. คอมเมนต์จะไหลขึ้นมาบนหน้าจอพร้อมเสียงอ่านทันที! 🎧

## 📦 Requirements

- Python 3.x
- Internet Connection
- macOS (for `afplay` audio support) / Windows/Linux (may need adaptation for audio)

## 🤝 Contributing

ยินดีต้อนรับทุกการแก้ไขและพัฒนา! สามารถ Fork และส่ง Pull Request มาได้เลยครับ

---

Developed with ❤️ by [magiccode.dev](https://magiccode.dev)
