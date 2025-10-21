# 🌟 HNG Stage 1 Frontend Task – Multi-Page Profile App

## 👩‍💻 Developer
**Name:** Moyinoluwa Popoola  
**Track:** Frontend Development  

---

## 🚀 Project Overview
This project is part of the **HNG Internship Stage 1 Frontend Task**.  
It builds on the Stage 0 "Profile Card" project and introduces two additional pages — **Contact Us** and **About Me** — to create a simple, multi-page web application.

Each page follows **semantic HTML**, **accessibility**, and **responsiveness** standards, and includes the required `data-testid` attributes for automated testing.

---

## 🧱 Pages

### 🏠 **Home Page (`index.html`)**
Displays a profile card featuring:
- Avatar upload feature  
- Bio and hobbies/dislikes  
- Social media links  
- Current time display  
- Navigation links to the About and Contact pages  

**Key data-testids:**
`test-profile-card`, `test-avatar-image`, `test-user-name`, `test-user-bio`, `test-user-time`, `test-user-social-links`, `test-user-hobbies`, `test-user-dislikes`

---

### 💬 **Contact Us Page (`contact.html`)**
A functional contact form with real-time validation and accessibility support.

**Fields:**
- Full Name — `test-contact-name`  
- Email — `test-contact-email`  
- Subject — `test-contact-subject`  
- Message — `test-contact-message`  
- Submit Button — `test-contact-submit`

**Validation Rules:**
- All fields are required  
- Email must be in a valid format (`name@example.com`)  
- Message must be at least 10 characters long  
- Displays success message (`test-contact-success`) on valid submission  
- Displays error messages (`test-contact-error-<field>`) with `aria-describedby` for accessibility  

---

### 👩‍🎓 **About Me Page (`about.html`)**
A reflective page sharing insights, goals, and thoughts.

**Sections:**
- Bio — `test-about-bio`  
- Goals in this program — `test-about-goals`  
- Areas of low confidence — `test-about-confidence`  
- Note to future self — `test-about-future-note`  
- Extra thoughts — `test-about-extra`

Semantic structure uses `<main>` and `<section>` with clear headings and lists.

---

## ♿ Accessibility Features
- Every input field is linked with a `<label>` using `for`  
- Error messages connected to inputs via `aria-describedby`  
- Keyboard navigable form and links  
- Colour contrast and focus states maintained for readability  

---

## 💅 Responsiveness
- Fully responsive across **mobile**, **tablet**, and **desktop**  
- Uses media queries for smooth scaling  
- Maintains spacing, alignment, and readability on all screen sizes  

---

## 🧠 Technologies Used
- **HTML5**
- **CSS3 (Flexbox + Media Queries)**
- **JavaScript (Form Validation & Interactivity)**

---

## 🧩 Folder Structure
