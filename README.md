# 🖥️ Multi-Code IDE

A cloud-based code editor to write and run code in multiple languages — right from your browser.

🔗 **Live Demo:** [multi-code-ide-gray.vercel.app](https://multi-code-ide-gray.vercel.app)

---

## ✨ Features

- 🔐 Secure authentication via Clerk
- 📁 Create, edit, rename & delete projects
- 💻 Monaco Editor (VS Code-like experience)
- ▶️ Run code instantly in 6 languages
- 🎨 Multiple themes — VS Dark, Dracula & more
- 💾 Save with `Ctrl/Cmd + S`

---

## 🌐 Supported Languages

`Python` `JavaScript` `C` `C++` `Java` `Bash`

---

## 🛠️ Tech Stack

| Frontend | Backend |
|----------|---------|
| React + Vite | Node.js + Express |
| Monaco Editor | MongoDB Atlas |
| Tailwind CSS | Clerk Auth |
| Framer Motion | Glot.io API |

---

## 📸 Screenshots

> **Home Page**

<img width="1900" height="872" alt="Screenshot 2026-02-02 204037" src="https://github.com/user-attachments/assets/69cc9755-121d-46f9-9acd-0e640795e483" />


> **Editor Page**

<img width="1870" height="874" alt="Screenshot 2026-03-22 225510" src="https://github.com/user-attachments/assets/8e97c52c-ad47-4ee5-89c5-5894d32ad274" />


---

## 🚀 Clone & Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/Bhumika-Sahu-bit/Multi-code-IDE.git
cd Multi-code-IDE

# 2. Setup Backend
cd backend
npm install
# Create .env file with your keys (see below)
npm start

# 3. Setup Frontend
cd ../frontend
npm install
npm run dev
```

### Backend `.env`
```env
MONGODB_URI=your_mongodb_uri
CLERK_PUBLISHABLE_KEY=pk_test_xxx
CLERK_SECRET_KEY=sk_test_xxx
GLOT_TOKEN=your_glot_token
```

### Frontend `.env`
```env
VITE_BACKEND_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=pk_test_xxx
```

---

## 👩‍💻 Author

**Bhumika Sahu** — [@Bhumika-Sahu-bit](https://github.com/Bhumika-Sahu-bit)
