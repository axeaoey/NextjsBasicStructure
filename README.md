# Next.js + Tailwind CSS Basic Project

โครงสร้างพื้นฐานสำหรับการเริ่มต้นพัฒนาเว็บด้วย Next.js และ Tailwind CSS

---

## 🚀 วิธีติดตั้งและเริ่มต้น

### 1. ติดตั้ง dependencies
```bash
npm install
# หรือใช้ yarn:
# yarn install
```

### 2. รันเซิร์ฟเวอร์ dev
```bash
npm run dev
# หรือใช้ yarn:
# yarn dev
```

### 3. เปิดเว็บ
เข้า browser ที่ http://localhost:3000

---

## 🛠️ เทคโนโลยีที่ใช้

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- TypeScript

---

## 🌱 คำสั่ง Git สำหรับจัดการ Branch

### 🔍 ตรวจสอบ branch ที่มี
```bash
git branch
```

### 🌿 สร้าง branch ใหม่ และสลับไปใช้งาน
```bash
git checkout -b feature/ชื่อฟีเจอร์
```

### 💡 สลับกลับไป branch อื่น
```bash
git checkout main
```

### 📤 push branch ใหม่ไปที่ remote
```bash
git push -u origin feature/ชื่อฟีเจอร์
```

### 🔄 รวม branch (merge) เข้ากับ main
```bash
# ไปที่ main ก่อน
git checkout main

# ดึงอัปเดตล่าสุด
git pull origin main

# รวม branch
git merge feature/ชื่อฟีเจอร์
```

### 🧼 ลบ branch ที่ merge แล้ว
```bash
# ลบ local
git branch -d feature/ชื่อฟีเจอร์

# ลบ remote
git push origin --delete feature/ชื่อฟีเจอร์
```

---

## 🧪 การใช้งาน Tailwind CSS

ใน `index.tsx` มีตัวอย่างการใช้คลาสของ Tailwind เช่น:

```jsx
<div className="min-h-screen bg-gray-100 text-center">
  <h1 className="text-4xl font-bold">Welcome to Next.js + Tailwind CSS</h1>
</div>
```

---

## 📁 โฟลเดอร์สำคัญ

- `src/pages/` — หน้าเว็บแต่ละหน้า
- `src/components/` — คอมโพเนนต์แยกย่อย
- `src/styles/globals.css` — ไฟล์ CSS หลักรวม Tailwind

---

## 📦 Build production
```bash
npm run build
```

## 🧼 Clean install (ในกรณีที่มีปัญหา)
```bash
rm -rf node_modules
rm package-lock.json
npm install
```

---

## 🧑‍💻 ผู้สร้าง
https://portfolio-axeaoeys-projects.vercel.app/
