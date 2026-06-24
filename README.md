# 🚀 Deploy Project

### 🌐 ทดลองใช้งานโปรเจ๊ค

[Open Project](https://test-ypgs.onrender.com/)

---

## 1️⃣ ติดตั้ง Git (ทำครั้งเดียว)

ดาวน์โหลดและติดตั้ง Git จาก:

https://git-scm.com

หลังติดตั้งเสร็จ ตรวจสอบว่าใช้งานได้หรือไม่:

```bash
git --version
```

หากแสดงเวอร์ชัน เช่น `git version 2.x.x` แสดงว่าติดตั้งสำเร็จ

---

## 2️⃣ ตั้งค่า Git (ทำครั้งเดียว)

กำหนดชื่อและอีเมลที่ใช้กับ GitHub

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

ตัวอย่าง

```bash
git config --global user.name "Bunkham Yolai"
git config --global user.email "bun@gmail.com"
```

---

## 3️⃣ อัปโหลดโปรเจกต์ขึ้น GitHub

เปิด Terminal ภายในโฟลเดอร์โปรเจกต์ แล้วรันคำสั่งตามลำดับ

```bash
git init
git add .
git commit -m "first commit" ตั้งชื่ออื่นได้
git branch -M main
git remote add origin https://github.com/bisket77/test2.git
git push -u origin main
```

---

## 🔄 กรณีเคยใช้ Git อยู่แล้ว

หากโปรเจกต์มี Git อยู่แล้ว และต้องการเชื่อมกับ Repository ใหม่ ให้ใช้คำสั่ง:

```bash
git remote add origin https://github.com/bisket77/test2.git
git branch -M main
git push -u origin main
```

---

✅ เมื่อ Push สำเร็จ โค้ดจะถูกอัปโหลดขึ้น GitHub Repository เรียบร้อย
