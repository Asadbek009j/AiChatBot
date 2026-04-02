# AI Chat & Telegram Bot with WebApp

Bu loyiha foydalanuvchilarga **Telegram bot** va **WebApp** orqali AI bilan muloqot qilish imkonini beradi. Shuningdek, foydalanuvchilar rasm generatsiya qilish va rasm tahlil qilish imkoniyatiga ega.

---

## 🔹 Asosiy xususiyatlar

- Telegram bot orqali foydalanuvchi ro‘yxatdan o‘tadi.
- Inline tugmalar orqali WebAppni ochish.
- AI chat (Groq API) bilan real-time muloqot.
- Har bir foydalanuvchining chat sessiyalarini saqlash (`ChatSession`, `ChatMessage`).
- Rasm generatsiyasi HuggingFace modeli orqali.
- Rasmni tahlil qilish Groq Vision modeli orqali.
- Frontend WebApp: chat interfeysi va rasm ko‘rsatish.
- DB: GORM orqali SQLite/PostgreSQL qo‘llab-quvvatlanadi.

---

## 🔹 Texnologiyalar

- **Backend**: Go (Golang)
- **Web Framework**: Gin
- **Telegram API**: telebot.v4
- **AI API**: Groq API, HuggingFace API
- **DB ORM**: GORM
- **Frontend**: HTML, CSS, JS (Static files)

---


