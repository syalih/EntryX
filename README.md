# AuthFlow – Tailwind Login Page

A clean and modern **login page template** built with [Tailwind CSS](https://tailwindcss.com/). Includes dark mode, multiple authentication flows, password strength indicator, and responsive UI components. Perfect for use as a starter project for SaaS apps, portfolios, or authentication demos.

---

## ✨ Features
- 🎨 **Tailwind CSS** design (responsive & mobile-first)
- 🌗 **Dark mode toggle** (persisted with localStorage)
- 🔑 **Two authentication flows**:
  - Email & Password
  - Magic Link (passwordless)
- 👁 **Password show/hide toggle**
- 📊 **Password strength meter** (live feedback)
- ✅ **Form validation** with inline error messages
- ⏳ **Loading spinner** on submit (mock API call)
- 🔒 **Remember me** + Forgot password link
- 🌐 **Language dropdown** (English, Arabic, Russian – extendable)
- 🔗 **Social login buttons** (Google, Facebook, Apple)
- 📜 **Terms, Privacy, and footer** with auto-updating year
- ♿ **Accessible** with ARIA roles & status live region

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/authflow.git
cd authflow
```

### 2. Open in Browser
Simply open the `index.html` file in your browser:
```bash
open index.html   # macOS
# or
start index.html  # Windows
```

Alternatively, serve with a local dev server:
```bash
npx serve .
```

### 3. Edit & Customize
- Update brand name in the header (`YourBrand`).
- Replace demo social login buttons with real OAuth providers.
- Connect to your authentication backend (Firebase, Supabase, NextAuth, custom API, etc.).

---

## 🛠 Tech Stack
- **Tailwind CSS** – utility-first CSS framework
- **Vanilla JS** – for toggles, validation, and interactivity
- **HTML5** – semantic structure

---

## 📂 Project Structure
```
AuthFlow/
├── index.html   # Main login page
└── README.md    # Project documentation
```

---

## 🔮 Roadmap / Possible Additions
- [ ] OTP / Two-Factor Authentication (2FA)
- [ ] Real API integration (Firebase, Supabase, Auth0)
- [ ] reCAPTCHA integration
- [ ] Session persistence / JWT support
- [ ] Registration & Reset Password flows

---

## 📜 License
MIT License © 2025 [Your Name]

---

### 📸 Preview
![AuthFlow Preview](https://dummyimage.com/800x600/0077ff/ffffff&text=AuthFlow+Login+Page)

---

🔑 Built with ❤️ using Tailwind CSS. Ready to plug into your next project!
