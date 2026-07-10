# Ai-based-learning-journey
i started my coding journey on january 30th 2026.


# 🎯 AI Ta'lim Yordamchisi — O'rganish va Qurish Roadmap'i

> Python va JavaScript asosida qurilgan, portfolio va shaxsiy foydalanish uchun mo'ljallangan dastur: **vaqt hisobi**, **AI file manager**, **AI file checking**.

Bu hujjat sizga nol skilldan tayyor, ishlaydigan mahsulotgacha borishga yordam beradi. O'rganish va qurish **parallel** ketadi — har bir bosqichda yangi mavzuni o'rganasiz va uni darhol loyihangizga tatbiq qilasiz.

**Qanday foydalanish kerak:** har bir bosqichni tugatgach, pastdagi checkbox'larni belgilang (`- [ ]` → `- [x]`) va GitHub'ga commit qiling. Shunda progressni ham ko'rasiz, ham portfolio tarixi shakllanadi.

---

## 📋 Loyiha haqida qisqacha

| Qobiliyat            | Nima qiladi                                                                           |
| -------------------- | ------------------------------------------------------------------------------------- |
| **Time Tracker**     | Vazifalarga sarflangan vaqtni Start/Stop orqali hisoblaydi, statistikasini ko'rsatadi |
| **AI File Manager**  | Fayl va papkalarni ko'rish, ko'chirish, nusxalash, o'chirish, qidirish                |
| **AI File Checking** | Faylni o'qib, mazmuni haqida AI yordamida xulosa/kategoriya chiqaradi                 |

---

## 🏗️ Tavsiya etilgan arxitektura (Tech Stack)

- **Backend: Python (Flask yoki FastAPI)** — barcha "og'ir" ish shu yerda: fayllar bilan ishlash (`os`, `pathlib`, `shutil`), SQLite orqali vaqt yozuvlarini saqlash, AI API'ga so'rov yuborish.
- **Frontend: HTML + CSS + JavaScript** — foydalanuvchi ko'radigan qism; `fetch()` orqali backend bilan gaplashadi.
- **(Ixtiyoriy, keyinroq) pywebview yoki Electron** — tayyor ilovani haqiqiy desktop dasturga aylantiradi.

**Nega aynan shu yo'l?** Ikkala tilni ham mazmunli tarzda mashq qilasiz — biri "miya" (backend), ikkinchisi "yuz" (interfeys). Electron kabi murakkab vositalarni boshida o'rganish shart emas; ilova to'liq ishlagach, uni desktop ko'rinishiga o'rab qo'yasiz.

---

## 🗓️ Umumiy vaqt jadvali

| # | Bosqich | Davomiyligi |
|---|---|---|
| 0 | Git, GitHub, muhitni sozlash | 1 hafta |
| 1 | Python mustahkamlash + fayllar bilan ishlash | 2–3 hafta |
| 2 | JavaScript mustahkamlash (DOM, async, fetch) | 2 hafta |
| 3 | SQLite — ma'lumotlar bazasi | 1 hafta |
| 4 | Backend: Flask/FastAPI bilan REST API | 2 hafta |
| 5 | Loyiha #1 — Time Tracker | 2 hafta |
| 6 | Loyiha #2 — AI File Manager | 3 hafta |
| 7 | Loyiha #3 — AI File Checking | 3–4 hafta |
| 8 | Integratsiya + UI/UX | 2 hafta |
| 9 | *(Ixtiyoriy)* Desktop dastur qilib qadoqlash | 1–2 hafta |
| 10 | Portfolio uchun tayyorlash | 1 hafta |

**Jami: ~20–22 hafta (taxminan 5 oy)**, haftasiga 10–15 soat hisobida. Bu — moslashuvchan taxmin; o'z sur'atingizga qarab tezlashtiring yoki sekinlashtiring.

Legenda: 🎥 = video (inglizcha) · 📄 = maqola/hujjat (til muhim emas)

---

## 🚀 Bosqichma-bosqich Roadmap

### 0-bosqich — Poydevor: Git, GitHub, muhit (1 hafta)

**Mavzular:** Git asoslari (`init`, `add`, `commit`, `push`, `branch`), GitHub'da repository yaratish, VS Code sozlash.

- [ ] 🎥 Git and GitHub Tutorial for Beginners — https://www.youtube.com/watch?v=tRZGeaHPoaw
- [ ] 🎥 Git & GitHub | Beginners Tutorial (2026) — https://www.youtube.com/watch?v=h2a3Kw-I_Ec

**✅ Amaliy natija:** GitHub'da `ai-talim-yordamchisi` nomli repository oching, README.md qo'shing, birinchi commit qiling. Bundan keyingi har bir bosqichda shu repo'ga commit qilib boring.

---

### 1-bosqich — Python mustahkamlash (2–3 hafta)

**Mavzular:** o'zgaruvchilar, funksiyalar, OOP (class/object), try/except, modullar, fayllar bilan ishlash (`os`, `pathlib`, `shutil`).

- [ ] 🎥 The Complete Python Course 2026 for Beginners (4 loyiha bilan) — https://www.youtube.com/watch?v=R_DarTl4a0g
- [ ] 🎥 CodeWithHarry — Complete 2026 Python Bootcamp — https://www.codewithharry.com/courses/complete-python-bootcamp-learn-python-from-scratch
- [ ] 📄 Real Python — pathlib bo'yicha to'liq qo'llanma — https://realpython.com/python-pathlib/
- [ ] 📄 Python rasmiy hujjatlari — pathlib — https://docs.python.org/3/library/pathlib.html
- [ ] 📄 Python rasmiy hujjatlari — shutil — https://docs.python.org/3/library/shutil.html
- [ ] 📄 GeeksforGeeks — Python Tutorial (OOP, Exception & File Handling qismlari) — https://www.geeksforgeeks.org/python/python-programming-language-tutorial/

**✅ Amaliy natija:** Kichik skript yozing — belgilangan papkadagi fayllarni turi (kengaytmasi) bo'yicha alohida papkalarga ko'chiradigan "fayl tartibga soluvchi". Bu — File Manager loyihangizning kichik prototipi.

---

### 2-bosqich — JavaScript mustahkamlash (2 hafta)

**Mavzular:** o'zgaruvchilar, funksiyalar, DOM, hodisalar (events), Promise, async/await, Fetch API.

- [ ] 🎥 freeCodeCamp — Learn JavaScript with Clear Explanations — https://www.freecodecamp.org/news/learn-javascript-with-clear-explanations/
- [ ] 🎥 freeCodeCamp — Full JavaScript Course for Beginners (Scrimba) — https://www.freecodecamp.org/news/full-javascript-course-for-beginners/
- [ ] 📄 MDN — Fetch API'dan foydalanish — https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch
- [ ] 📄 MDN — async/await — https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await

**✅ Amaliy natija:** Oddiy HTML sahifa yarating: tugma bosilganda ochiq API'dan (masalan, `https://official-joke-api.appspot.com/random_joke`) `fetch()` orqali ma'lumot olib, sahifada ko'rsating. Bu keyingi bosqichlarda backend bilan "gaplashish" mexanizmining asosi bo'ladi.

---

### 3-bosqich — SQLite: ma'lumotlar bazasi (1 hafta)

**Mavzular:** jadval yaratish, ma'lumot qo'shish/o'qish/yangilash/o'chirish (CRUD).

- [ ] 📄 SQLiteTutorial.net — Python bilan SQLite — https://www.sqlitetutorial.net/sqlite-python/
- [ ] 📄 Python rasmiy hujjatlari — sqlite3 moduli — https://docs.python.org/3/library/sqlite3.html

**✅ Amaliy natija:** `time_entries` jadvalini yarating (`id`, `task_name`, `start_time`, `end_time` ustunlari bilan), Python orqali 2–3 ta yozuv qo'shib, o'qib ko'ring.

---

### 4-bosqich — Backend: Flask yoki FastAPI (2 hafta)

**Mavzular:** REST API nima, endpoint yaratish, JSON qaytarish, GET/POST so'rovlarini qabul qilish.

- [ ] 🎥 Corey Schafer — Python Flask Tutorials (to'liq playlist) — https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH
- [ ] 📄 FastAPI rasmiy qo'llanmasi — https://fastapi.tiangolo.com/tutorial/
- [ ] 🎥 FastAPI Tutorial for Beginners – Full Course — https://www.youtube.com/watch?v=VirndPTeRaw
- [ ] 🎥 Python FastAPI Tutorial: Full Course for Beginners — https://www.youtube.com/watch?v=iukOehU5aF4

> **Flask yoki FastAPI?** Flask — soddaroq, Corey Schafer darslari juda batafsil, shuning uchun boshlang'ich uchun tavsiya etaman. FastAPI — zamonaviyroq, avtomatik dokumentatsiya bilan keladi. Ikkisi ham to'g'ri tanlov.

**✅ Amaliy natija:** `/api/ping` nomli endpoint yarating — chaqirilganda `{"status": "ok"}` qaytarsin. Uni 2-bosqichdagi `fetch()` bilan chaqirib ko'ring — backend va frontend birinchi marta "gaplashadi".

---

### 5-bosqich — Loyiha #1: Time Tracker (2 hafta)

**Nima qurasiz:** Start/Stop tugmali sekundomer; bosilganda backend'ga so'rov ketadi, backend SQLite'ga yozadi; kunlik/haftalik statistika ko'rsatiladi.

- [ ] 📄 "How I Built a Python Tool That Automatically Tracks My Coding Time" (os, datetime, sqlite3) — https://python.plainenglish.io/how-i-built-a-python-tool-that-automatically-tracks-my-coding-time-across-projects-259281a9277e
- [ ] 📄 "Build a PC Usage Time Tracker in Python" — https://medium.com/@mate-technologies/build-a-pc-usage-time-tracker-in-python-%EF%B8%8F-%EF%B8%8F-478adc2fe602

**✅ Amaliy natija:** To'liq ishlaydigan Time Tracker — vazifa nomi kiritiladi, Start/Stop bosiladi, sessiyalar ro'yxati va jami vaqt ko'rsatiladi.

---

### 6-bosqich — Loyiha #2: AI File Manager (3 hafta)

**Mavzular:** papka/fayl ro'yxatini olish, nusxalash/ko'chirish/o'chirish/qayta nomlash, qidiruv.

- [ ] 📄 GeeksforGeeks — File Explorer in Python using Tkinter — https://www.geeksforgeeks.org/python/file-explorer-in-python-using-tkinter/
- [ ] 📄 TechVidvan — Python Project: Create a File Manager — https://techvidvan.com/tutorials/python-project-file-manager/
- [ ] 📄 "Build a Simple File Explorer in Python with Tkinter – FileMate Explorer" (copy/paste/rename/drag-drop) — https://dev.to/matetechnologie/build-a-simple-file-explorer-in-python-with-tkinter-filemate-explorer-2ld8

> **Eslatma:** Bu darslar Tkinter uchun yozilgan, lekin asosiy mantiq (`os.listdir`, `shutil.copy`, `shutil.move`, `os.remove`, `os.rename`) bir xil qoladi. Siz shu funksiyalarni Tkinter oynalari o'rniga Flask/FastAPI endpoint'lariga joylashtirib, natijani JSON qilib qaytarasiz.

**✅ Amaliy natija:** `/api/files?path=...` endpoint — papkadagi fayllar ro'yxatini qaytaradi; frontend'da papka daraxti va fayl ustida ochish/o'chirish/ko'chirish mumkin bo'lgan interfeys.

---

### 7-bosqich — Loyiha #3: AI File Checking (3–4 hafta)

**Mavzular:** fayldan matn ajratish (PDF, DOCX, TXT), AI API'ga so'rov yuborib faylni tahlil qilish.

**Fayldan matn ajratish:**
- [ ] 📄 pypdf rasmiy hujjatlari — PDF'dan matn olish — https://pypdf.readthedocs.io/en/stable/user/extract-text.html
- [ ] 📄 GeeksforGeeks — Extract text from PDF File using Python — https://www.geeksforgeeks.org/python/extract-text-from-pdf-file-using-python/
- [ ] 📄 "Working with PDF and Word Documents in Python" (python-docx bilan) — https://www.spsanderson.com/steveondata/posts/2025-09-24/

**AI API bilan ishlash — 2 variant (birini tanlang yoki ikkalasini sinab ko'ring):**
- [ ] 📄 OpenAI API rasmiy quickstart — https://platform.openai.com/docs/quickstart?context=python
- [ ] 📄 OpenAI quickstart repo (GitHub) — https://github.com/openai/openai-quickstart-python
- [ ] 📄 Anthropic Claude API hujjatlari — https://platform.claude.com/docs/en/home
- [ ] 📄 Anthropic Python SDK (rasmiy GitHub) — https://github.com/anthropics/anthropic-sdk-python
- [ ] 📄 Claude quickstart loyihalari (GitHub) — https://github.com/anthropics/claude-quickstarts

> **Byudjet haqida:** Ikkala API ham pullik (so'rov hajmiga qarab). Joriy narxlarni har doim rasmiy saytdan tekshiring. O'rganish bosqichida xarajatni kamaytirish uchun kichik fayllar/qisqa matnlar bilan test qiling. Agar umuman xarajatsiz sinamoqchi bo'lsangiz, Ollama kabi vositalar orqali lokal (bepul) modellardan foydalanish ham muqobil variant.

**✅ Amaliy natija:** File Manager'da faylni tanlab "AI bilan tahlil qilish" tugmasi bosilsa — backend fayldan matn ajratadi, AI API'ga yuboradi, qisqacha xulosa/kategoriya/kalit so'zlarni ko'rsatadi.

---

### 8-bosqich — Integratsiya va UI/UX (2 hafta)

Uchala funksiyani (Time Tracker, File Manager, File Checking) bitta ilovaga, yagona navigatsiya bilan birlashtiring. Rang sxemasi va shriftlarni birxillashtiring.

**✅ Amaliy natija:** Bitta yaxlit ilova — uch funksiya orasida menyudan almashish mumkin.

---

### 9-bosqich — *(Ixtiyoriy)* Desktop dastur qilib qadoqlash (1–2 hafta)

Ilova to'liq ishlagach, uni haqiqiy desktop dasturga aylantirish uchun 2 variant:

**A) pywebview (soddaroq, tavsiya etiladi)** — Flask ilovangizni o'zgartirmasdan native oyna ichiga o'raydi.
- [ ] 📄 pywebview rasmiy GitHub — https://github.com/r0x0r/pywebview/
- [ ] 📄 pywebview + Flask qo'llanmasi — https://medium.com/@nohkachi/how-to-build-a-python-desktop-app-with-pywebview-and-flask-73025115e061
- [ ] 🎥 Complete Python PyWebView Tutorial — https://www.youtube.com/watch?v=g2_wXP8c9dI
- [ ] 📄 Tayyor misol-repo (aynan shu yondashuv) — https://github.com/codingforentrepreneurs/python-desktop-app

**B) Electron (murakkabroq, sanoat standarti)** — agar Node.js/JavaScript tomonini chuqurroq mashq qilishni istasangiz.
- [ ] 📄 Electron rasmiy tutorial — https://www.electronjs.org/docs/latest/tutorial/tutorial-first-app
- [ ] 🎥 Node.js Crash Course (Electron uchun Node.js zarur) — https://www.youtube.com/playlist?list=PL4cUxeGkcC9jsz4LDYc6kv3ymONOKxwBU

**✅ Amaliy natija:** Ilovangiz brauzerda emas, alohida oyna sifatida ochiladi.

---

### 10-bosqich — Portfolio uchun tayyorlash (1 hafta)

**Mavzular:** yaxshi README yozish, kodni tozalash, GitHub'ga to'liq yuklash.

- [ ] 📄 freeCodeCamp — How to Write a Good README File — https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/
- [ ] 📄 Write a Great README.md: Beginner GitHub Guide — https://unwiredlearning.com/blog/readme-github-guide

**✅ Amaliy natija:** README.md'da: loyiha nima qilishi, skrinshot/GIF, o'rnatish yo'riqnomasi, ishlatilgan texnologiyalar va "bu loyihada nimalarni o'rgandim" bo'limi (ish beruvchilar buni yoqtiradi).

---

## 🔗 Qo'shimcha umumiy resurslar

Quyidagilar — vizual, interaktiv roadmap'lar; har bir mavzuga bosilganda qo'shimcha tushuntirish va manbalar chiqadi. Shu hujjat bilan parallel foydalaning:

- 📄 roadmap.sh — Python Developer Roadmap — https://roadmap.sh/python
- 📄 roadmap.sh — JavaScript Developer Roadmap — https://roadmap.sh/javascript
- 📄 roadmap.sh — Backend Developer Roadmap — https://roadmap.sh/backend
- 📄 roadmap.sh — Full Stack Developer Roadmap — https://roadmap.sh/full-stack

---

## 💡 Muhim maslahatlar

- **Har kuni ozgina bo'lsa ham kod yozing.** Haftada 2 marta 5 soatdan ko'ra, har kuni 1 soat samaraliroq.
- **1-bosqichdanoq Git'dan foydalaning** — har bir kichik o'zgarishdan keyin commit qiling.
- **O'rganish va qurish parallel ketsin** — video ko'rib bo'lguncha kutmang; yangi tushunchani darhol loyihaga tatbiq qiling.
- **Xatolardan qo'rqmang** — Stack Overflow, GitHub Issues va rasmiy hujjatlarni o'qishni o'rganish ham dasturchilik skillining bir qismi.
- **Bosqichlar tartibi qat'iy emas** — agar biror mavzuni allaqachon bilsangiz, o'tkazib yuboring va vaqtni tejang.
