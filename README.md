# 🔊 PC to PC Audio

ส่งเสียงจากคอมพิวเตอร์ไปยังอีกเครื่องผ่านเครือข่าย NDI

Send audio from one computer to another via NDI network

![PC2PC](https://img.shields.io/badge/Version-1.0-blue)
![Python](https://img.shields.io/badge/Python-3.8+-green)
![NDI](https://img.shields.io/badge/NDI-6.0-orange)

---

## 📥 Download

**[⬇️ ดาวน์โหลด PC2PC v1.0](https://github.com/JamornzMedia/PC2PC/releases/latest)**

---

## 🚀 วิธีติดตั้งและใช้งาน

### ฝั่งส่ง (Sender) - ติดตั้ง 2 อย่าง
1. [Python 3.8+](https://www.python.org/downloads/)
2. [NDI Runtime](https://downloads.ndi.tv/SDK/NDI_SDK/NDI%206%20Runtime.exe)

### ฝั่งรับ (Receiver) - ติดตั้ง 4 อย่าง
1. [Python 3.8+](https://www.python.org/downloads/)
2. [NDI Runtime](https://downloads.ndi.tv/SDK/NDI_SDK/NDI%206%20Runtime.exe)
3. [VB-Cable](https://vb-audio.com/Cable/) - สำหรับส่งเสียงไมค์
4. [Hi-Fi Cable](https://vb-audio.com/Cable/#DownloadASIOBridge) - สำหรับส่งเสียง Desktop

> 💡 รีสตาร์ทคอมพิวเตอร์หลังติดตั้งเสร็จ

---

## 📖 วิธีใช้งาน

1. ดาวน์โหลดและแตกไฟล์ ZIP
2. รันไฟล์ `Run.bat`
3. Browser จะเปิดอัตโนมัติ
4. เลือกโหมด **Sender** (ฝั่งส่ง) หรือ **Receiver** (ฝั่งรับ)

### Sender Mode
- เลือก Microphone และ Desktop Audio
- กด **Start Sending**

### Receiver Mode
- กด **Find NDI Sources**
- เลือก source และ output device:
  - 🎤 Mic → CABLE Input → ใช้ CABLE Output เป็นไมค์ใน Discord/Zoom
  - 🔊 Desktop → Hi-Fi Cable Input → ใช้ Hi-Fi Cable Output ใน OBS/TikTok

---

## 🌐 Features
- ✅ ส่งเสียงไมค์และ Desktop Audio แยกกัน
- ✅ รองรับภาษาไทย/English
- ✅ ปรับ Volume ได้
- ✅ Auto-detect devices

---

## 💖 สนับสนุนผู้พัฒนา

[https://ezdn.app/Jamornz](https://ezdn.app/Jamornz)

---

**Developer:** [JamonrzMedia](https://sites.google.com/view/jamornzmedia)
