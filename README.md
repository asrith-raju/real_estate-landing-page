# 🏡 Real Estate Landing Page

A sleek, responsive landing page for a real estate business built using **React + Vite**, styled with **Tailwind CSS**, and enhanced with **Framer Motion animations**, **Formspree forms**, and **React Toastify notifications**.

---

## 🚀 Getting Started

### Prerequisites
- Node.js **v20+** recommended

### Installation
```bash
npm install
# or
yarn install
# or
pnpm install
```

### Scripts
| Command | Description |
| :-- | :-- |
| `npm run dev` | Start app in development mode |
| `npm run build` | Build app for production |
| `npm run lint` | Run ESLint checks |
| `npm run preview` | Preview production build |

---

## ⚙️ Tech Stack
- **Frontend:** React (^19.1.1)
- **Bundler:** Vite (^7.1.7)
- **Styling:** Tailwind CSS (^3.4.18), PostCSS, Autoprefixer
- **Animations:** Framer Motion (^12.23.24)
- **Forms:** Formspree React (^3.0.0)
- **Notifications:** React Toastify (^11.0.5)
- **Linting:** ESLint (React Hooks + Refresh plugins)

---

## 🌟 Features
✅ Fully responsive layout for all devices  
✅ Smooth scroll & animated transitions via Framer Motion  
✅ Contact form with **Formspree integration**  
✅ Toast notifications for form submission success/failure  
✅ Dynamic project carousel  
✅ Organized and reusable component structure  

---

## 📂 Project Structure
```
src/
 ├── assets/
 │   ├── assets.js          # Image & data exports
 │   ├── logo.svg, header_img.png, icons, etc.
 ├── components/
 │   ├── Navbar.jsx         # Responsive navigation with mobile toggle
 │   ├── Header.jsx         # Hero section with background and CTA
 │   ├── About.jsx          # Company information and stats
 │   ├── Projects.jsx       # Animated project carousel
 │   ├── Testimonials.jsx   # Client feedback with ratings
 │   ├── Contact.jsx        # Formspree + Toastify integration
 │   └── Footer.jsx         # Newsletter & copyright
 ├── App.jsx                # Root component with section imports
 ├── main.jsx               # Entry point
 ├── index.css              # Global styles
postcss.config.js           # Tailwind & Autoprefixer setup
tailwind.config.js          # Tailwind configuration
vite.config.js              # Vite setup
```

---

## 🖼️ Assets
- **Icons:** `logo.svg`, `menu_icon.svg`, `cross_icon.svg`, `star_icon.svg`, arrows  
- **Images:** `header_img.png`, `brand_img.png`, `project_img_1.jpg–project_img_6.jpg`  
- **Profiles:** `profile_img_1.png–profile_img_3.png`

---

## 💬 Data Samples
**Projects:** Skyline Haven, Vista Verde, Serenity Suites, Central Square  
**Testimonials:** Donald Jackman ⭐⭐⭐⭐⭐, Richard Nelson ⭐⭐⭐⭐, James Washington ⭐⭐⭐⭐⭐  

---

## 📧 Contact Form (Formspree)
The **Contact** component uses Formspree (`useForm("xanawoew")`) to handle submissions and shows:  
- ✅ Success toast → “Form Submitted Successfully”  
- ❌ Error toast → “Error in Sending Message”  

---

## 🎨 Animations
Each section (Header, About, Projects, Testimonials, Contact) uses **Framer Motion**:  
- Smooth fade-in and slide animations on scroll  
- One-time viewport triggers (`viewport={{ once: true }}`)

---

## 🧑‍💻 Contribution
Contributions are welcome!  

1. Fork the repository  
2. Create a new branch (`feature/your-feature`)  
3. Commit your changes  
4. Push and open a Pull Request 🚀  

---

## 🪪 License
This project is licensed under the **MIT License**.
