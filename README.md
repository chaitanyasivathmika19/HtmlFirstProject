# HtmlFirstProject
A simple static Student Information System built with HTML &amp; CSS, featuring Public and Student areas. Includes Home, Registration, Login, Contact Us, and ERP links. After login, users can view their dashboard, profile, and logout. Ideal for beginners to practice front-end web design.

# Student Information System (MSWD)

A simple web-based **Student Information System** built using **HTML** and **CSS**.  
Users can browse public pages (**Home**, **Registration**, **Login**, **Contact Us**, **ERP**).  
After a successful login, the site switches to a student area with **Home**, **Profile**, and **Logout** navigation.


---

## ✨ Features

### Public Navigation (Before Login)
- **Home** – `index.html`
- **Registration** – `registration.html`
- **Login** – `login.html`
- **Contact Us** – `contact.html`
- **ERP** – External link to ERP portal

### Student Navigation (After Login)
- **Home** – `studenthome.html`
- **Profile** – `profile.html`
- **Logout** – `login.html` (returns user to login page)

### Pages Overview
- **Home (Public):** Landing page with navigation menu  
- **Registration:** Static student registration form  
- **Login:** Static login page leading to student section  
- **Student Home:** Post-login dashboard  
- **Profile:** Displays student information (ID, name, course, contact, location, image)  
- **Contact Us:** Static contact form layout  
- **ERP:** Opens the ERP portal in a new tab

---

## 🛠️ Tech Stack
- **HTML** – Page structure  
- **CSS** – Styling and layout (`style.css`)

---

## 🚀 How It Works
1. Open `index.html` or visit the **Live Demo** link.  
2. Use the public navigation menu to explore **Home**, **Registration**, **Login**, **Contact Us**, and **ERP**.  
3. Logging in will switch navigation to **Home**, **Profile**, and **Logout**.  
4. Logout redirects back to the login page.

> This is a **static frontend** project. Forms are not connected to any backend.

---

## 📂 Project Structure
```
/ (root)
├── index.html          # Home (public)
├── registration.html   # Registration form
├── login.html          # Login page / Logout redirect
├── contact.html        # Contact Us page
├── studenthome.html    # Home page after login
├── profile.html        # Profile page after login
├── style.css           # CSS styling
└── assets/             # Optional images/screenshots
```

---

## 📜 License
This project is for educational purposes and can be modified freely.
