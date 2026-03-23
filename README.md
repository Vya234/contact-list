# 📇 Advanced Contact List

**Live Demo:** https://contactlist-orcin.vercel.app/  
**Repository:** https://github.com/Vya234/contact-list  

A modern contact management web application built for the Tria Frontend Development Assignment.  
While the task required a basic contact list, this project extends it into a polished, production-quality application with strong UX and thoughtful engineering decisions.

---

## 🧾 Overview

This application focuses on:
- Clean and intuitive user experience
- Smooth interactions and animations
- Real-world data persistence
- Performance and scalability considerations

---

## ✨ Features

### Core Functionality
- Full CRUD support (Add, Edit, Delete contacts)
- Debounced search (300ms delay)
- Alphabetical grouping of contacts

### UI/UX Enhancements
- 🌗 Light/Dark mode with saved user preference
- 📱 Fully responsive design (mobile + desktop)
- Smooth animations using Framer Motion
- Skeleton loader for better perceived performance

### User Interactions
- 📋 Click-to-copy email and phone number
- 📞 One-click actions (Call, Message, Email)
- 🔔 Toast notifications for real-time feedback

### Forms and Validation
- Required field validation (Name, Email, Phone)
- 🌍 Country code selector for international numbers

### Modal System
- 👁️ View contact details
- ⚠️ Confirm delete actions
- 📖 App features overview modal

### Data Handling
- 💾 LocalStorage persistence
- API fetch only on first load

---

## 🛠️ Tech Stack

- React  
- Axios  
- Framer Motion  
- React Hot Toast  

---

## 🚀 Local Setup

```bash
# Clone the repository
git clone https://github.com/Vya234/contact-list

# Navigate into the project directory
cd contact-list

# Install dependencies
npm install

# Run the development server
npm run dev
