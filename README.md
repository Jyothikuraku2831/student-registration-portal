# 🎓 Student Registration & Result Portal

A responsive **mini project** built using **HTML5** and **CSS3** that demonstrates how these two 
technologies work together to create an interactive, form-driven web application. This project 
walks a user through registering student details, selecting a course, entering subject-wise marks, 
and instantly viewing a styled, auto-generated result card.

---

## 📌 Project Objective

Build a responsive Student Registration & Result Portal where a user can:
1. Enter personal details (name, roll number, DOB, email, phone)
2. Select a course/branch and semester
3. Enter marks for subjects specific to the chosen course
4. View the entered details and computed result in a clean, structured, styled layout
5. Get guided by HTML5's built-in validation while filling the form
6. Experience a fully responsive design across desktop, tablet, and mobile

---

## ✨ Features

- **3-step guided form** — Personal Details → Course Selection → Marks Entry, navigated with a tabbed stepper
- **HTML5 native validation** — `required`, `pattern`, `type="email"`, `type="tel"`, `type="date"`, `min`/`max` on number fields, with inline error messages
- **Dynamic subject loading** — subject list changes automatically based on the course selected (AIML, CSE, ECE, Mechanical)
- **Auto-calculated result**:
  - Total marks & percentage
  - Grade (O / A+ / A / B+ / B / C / F) based on percentage
  - Per-subject Pass/Fail status (pass mark = 35)
  - Overall Pass/Fail status
- **Styled result card** — student info strip, marks table, grade pill, summary row
- **Responsive design** — CSS Flexbox & Grid layouts, mobile-friendly via media queries
- **Edit option** — go back and re-edit details after viewing the result
- **No frameworks/libraries** — pure HTML, CSS, and vanilla JavaScript (JS used only for step-navigation and dynamic rendering logic)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure, semantic elements, form fields, native validation attributes |
| **CSS3** | Styling, responsive layout (Flexbox & Grid), cards, tables, buttons, media queries |
| **JavaScript (Vanilla)** | Step navigation, dynamic subject rows, marks calculation & result rendering |

---

## 📚 Learning Outcomes

- HTML forms and form elements
- HTML5 native form validation (`required`, `pattern`, `type`, `min`/`max`)
- CSS3 selectors, the box model, and layout fundamentals
- CSS Flexbox and Grid for responsive layouts
- Styling buttons, cards, tables, and alert/status boxes with CSS
- Responsive web design using media queries
- Structuring and displaying dynamic data (student details & results) in styled HTML
- Basic integration of HTML, CSS, and JavaScript

---

## 🚀 How to Run

No installation or build step required.

1. Clone or download this repository
```bash
   git clone https://github.com/<your-username>/student-result-portal.git
```
2. Open `student-result-portal.html` directly in any web browser
3. Fill in the details step by step and click **Generate result** to see the output

---

## 📂 Project Structure
