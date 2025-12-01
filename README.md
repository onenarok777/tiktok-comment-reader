# TikTok Live Comment Reader

โปรแกรม Python สำหรับอ่านคอมเมนต์จาก TikTok Live โดยใช้ library `TikTokLive`

## การติดตั้ง (Installation)

1.  สร้าง Virtual Environment:
    ```bash
    python3 -m venv venv
    ```
2.  ติดตั้ง library:
    ```bash
    ./venv/bin/pip install -r requirements.txt
    ```

## การใช้งาน (Usage)

1.  เปิดไฟล์ `main.py`
2.  แก้ไขตัวแปร `tiktok_username` เป็นชื่อผู้ใช้ TikTok ที่กำลัง Live อยู่ (ไม่ต้องมี @)
    ```python
    tiktok_username = "ชื่อผู้ใช้ที่ต้องการ"
    ```
3.  รันโปรแกรม:
    ```bash
    ./venv/bin/python main.py
    ```

## หมายเหตุ

- โปรแกรมนี้จะทำงานได้ก็ต่อเมื่อผู้ใช้ที่ระบุกำลัง Live อยู่เท่านั้น
- กด `Ctrl+C` เพื่อหยุดการทำงาน
# tiktok-comment-reader
