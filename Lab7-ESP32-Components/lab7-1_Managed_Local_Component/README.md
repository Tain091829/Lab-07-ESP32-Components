# Lab 7-1: Local Component Demo
    ```bash
    # เข้าไปยังโฟลเดอร์โปรเจค Lab 7-1
    cd lab7-1_Managed_Local_Component

    # Export environment สำหรับ ESP-IDF
    . $IDF_PATH/export.sh

    # กำหนด target เป็น ESP32
    idf.py set-target esp32

    # สั่ง Build Project
    idf.py build

    # (ถ้ามีบอร์ดจริง) Flash และ Monitor
    idf.py -p <PORT> flash monitor

## สรุปคำสั่งที่ใช้ และผลลัพธ์ที่ได้
