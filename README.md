# 🤖 Bale ID & Tehran Time Bot

<p align="center">

![Bale](https://img.shields.io/badge/Bale-Bot-blue?style=for-the-badge)
![Cloudflare](https://img.shields.io/badge/Cloudflare-Workers-orange?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

<p align="center">
ربات پیام‌رسان <b>بله</b> برای نمایش ساعت تهران، تاریخ شمسی و آیدی کاربر<br>
اجرا شده روی ☁️ Cloudflare Workers
</p>

---

## ✨ Features

✅ نمایش تاریخ شمسی
✅ نمایش تاریخ میلادی
✅ نمایش ساعت تهران
✅ نمایش آیدی کاربر
✅ دکمه‌های تعاملی (Inline Keyboard)
✅ اجرا روی Cloudflare Workers
✅ بدون نیاز به سرور

---

## 📷 Preview

```text
✨ سلام فرهاد عزیز! ✨

👋 خوش آمدید به IDTime

──────────────
📅 تاریخ شمسی: 1405/04/01
📅 تاریخ میلادی: 2026/06/22
🕒 ساعت تهران: 14:30
──────────────
🆔 آیدی شما: 123456789
```

---

# 🛠 Installation

### 1️⃣ ساخت ربات در بله

ابتدا از BotFather بله یک ربات بسازید و توکن دریافت کنید.

---

### 2️⃣ قرار دادن توکن

در فایل Worker مقدار زیر را پیدا کنید:

```javascript
const TOKEN = "PUT_YOUR_BALE_TOKEN_HERE";
```

توکن ربات خود را جایگزین کنید.

---

### 3️⃣ Deploy روی Cloudflare Workers

فایل جاوااسکریپت را در Cloudflare Workers قرار دهید و Deploy کنید.

---

### 4️⃣ تنظیم Webhook

آدرس زیر را اجرا کنید:

```text
https://tapi.bale.ai/botTOKEN/setWebhook?url=https://YOUR_WORKER_URL
```

🔹 TOKEN = توکن ربات

🔹 YOUR_WORKER_URL = آدرس Worker

---

# 📋 Commands

| Command      | Description        |
| ------------ | ------------------ |
| `/start`     | شروع ربات          |
| ⌚ زمان تهران | نمایش ساعت و تاریخ |
| 🆔 آیدی      | نمایش آیدی کاربر   |

---

# 📂 Project Structure

```bash
.
├── index.js
├── README.md
└── LICENSE
```

---

# ⚡ How It Works

1. کاربر `/start` را ارسال می‌کند.
2. ربات تاریخ شمسی و میلادی را محاسبه می‌کند.
3. ساعت تهران نمایش داده می‌شود.
4. آیدی کاربر نمایش داده می‌شود.
5. کاربر می‌تواند با دکمه‌ها اطلاعات را دوباره دریافت کند.

---

# 🌟 Screenshots

شما می‌توانید اسکرین‌شات ربات را در این قسمت قرار دهید:

```text
images/preview.jpg
```

و سپس این کد را اضافه کنید:

```html
<p align="center">
  <img src="images/preview.jpg" width="350">
</p>
```

---

# 🤝 Contributing

Pull Request ها و پیشنهادات شما همیشه خوش آمد است.

اگر ایده‌ای برای بهبود ربات دارید، Issue ثبت کنید یا Pull Request ارسال نمایید.

---

# ⭐ Support

اگر این پروژه برای شما مفید بود:

🌟 به مخزن ستاره بدهید
🍴 پروژه را Fork کنید
💙 آن را با دوستان خود به اشتراک بگذارید

---

# 📄 License

This project is licensed under the **MIT License**.

---

<p align="center">

Made with ❤️ by **Farhad**

</p>
