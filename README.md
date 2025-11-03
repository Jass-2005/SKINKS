# Skinks — Hyperlocal Skill Marketplace 🌍

Skinks is a 6-page prototype website designed to bridge the **hyperlocal gap** between skilled individuals and nearby opportunities.  
Built with **HTML, Tailwind CSS, and Firebase Firestore**, Skinks helps users **connect, collaborate, and earn** within a 5km radius.

---

## 🚀 Features

### 🏠 Homepage (index.html)
- Highlights Skinks' mission: “Connect. Collaborate. Earn.”
- Simple navigation to post or find local tasks.
- Clean, responsive design with scroll animations.

### 🔍 Find Talent (find_talent.html)
- Real-time task discovery from Firestore.
- Search placeholder for local skills (e.g., “Electrician,” “Tutor”).
- Interactive map placeholder for 5km radius view.

### 📝 Post Task (post_task.html)
- Submit local tasks via structured form.
- Firebase `addDoc()` saves new tasks securely to Firestore.
- Visual feedback (spinner + confirmation message).

### ⚙️ How It Works (how_it_works.html)
- Step-by-step guide for both **Hirers** and **Talent**.
- Visually rich layout with icons and transitions.

### 👥 About Us (about_us.html)
- Mission & vision of Skinks.
- Introduces founding members: **Jaspreet Singh (TL)**, **Aryan (Frontend/Integration)**, **Vanshaj Sharma (Backend)**.

### ❓ Help Center (help.html)
- FAQ section with JavaScript-driven accordions.
- “Contact Support” modal saves support tickets privately in Firestore.

---

## 🧩 Tech Stack

- **Frontend:** HTML5, Tailwind CSS  
- **Backend:** Google Firebase Firestore  
- **Scripts:** Vanilla JavaScript (for dynamic Firestore integration)

---

## 🔥 Firestore Collections
- `/artifacts/{appId}/public/data/tasks` — Public tasks data.  
- `/artifacts/{appId}/users/{userId}/support_tickets` — Private user support tickets.

---

## 💡 Purpose
Skinks is built as a **proof-of-concept prototype** for a community-driven skill-sharing platform.  
It demonstrates how hyperlocal digital ecosystems can strengthen trust and collaboration within small communities.

---

## 🖥️ Preview
*(Add screenshot or live demo link here once deployed)*

---

## 👨‍💻 Developed by
**Team Skinks Innovators**
- Jaspreet Singh — Team Lead
- Jaspreet Singh — Frontend and core idea
- Aryan — Frontend & Firebase Integration  
- Vanshaj Sharma — Backend Developer

---

## 📄 License
This project is open-sourced under the [MIT License](LICENSE).
