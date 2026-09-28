# 🎓 Student Registration & Result Portal

A responsive and user-friendly **Student Registration & Result Portal** developed using **HTML5 and CSS3**.

This mini project demonstrates how HTML5 can be used to create structured forms, input fields, tables, navigation components, and student result sections, while CSS3 is used to create an attractive, responsive, and well-organized user interface.

---

## 📌 Project Overview

The **Student Registration & Result Portal** is a front-end mini project designed to provide a simple interface for entering student information and displaying academic results.

The portal allows students to:

* Enter personal information
* Enter roll number and contact details
* Select their course
* Select their academic year
* Enter examination marks
* View student information
* Display subject-wise marks
* View total marks and percentage
* View the overall result
* Use HTML5 built-in form validation
* Access the website on desktop, tablet, and mobile devices

The project focuses on the integration of **HTML5 and CSS3** to create a structured and visually appealing web application.

---

## 🎯 Project Objective

The main objective of this project is to develop a responsive Student Registration & Result Portal using HTML5 and CSS3.

The project aims to demonstrate:

1. Creation of student registration forms.
2. Use of different HTML5 form elements.
3. Implementation of native HTML5 form validation.
4. Creation of course selection fields.
5. Entry of examination marks.
6. Presentation of student information in a structured layout.
7. Display of results using HTML tables.
8. Styling forms, cards, buttons, tables, and navigation components.
9. Use of CSS Flexbox and Grid.
10. Implementation of responsive web design using media queries.

---

## ✨ Features

### 👤 Student Registration

The portal provides a registration form where students can enter:

* Full Name
* Roll Number
* Email Address
* Phone Number
* Date of Birth
* Gender
* Course
* Academic Year
* Address

---

### 🎓 Course Selection

Students can select their course from a dropdown menu.

Available courses include:

* Computer Science Engineering
* Artificial Intelligence & Machine Learning
* Electronics & Communication Engineering
* Electrical & Electronics Engineering

The dropdown makes the form simple and easy to use.

---

### 📝 Examination Marks

The portal provides fields for entering marks in different subjects.

Each mark field accepts values between:

```text
0 - 100
```

HTML5 `min` and `max` attributes are used to restrict incorrect values.

---

### ✅ HTML5 Form Validation

The project uses built-in HTML5 validation features.

Examples include:

```html
required
```

```html
type="email"
```

```html
type="number"
```

```html
min="0"
```

```html
max="100"
```

```html
pattern="[0-9]{10}"
```

These attributes help prevent invalid data from being submitted.

---

## 🎨 User Interface

The interface contains several major sections:

### 1. Navigation Bar

The navigation bar provides links to:

* Home
* Registration
* Results
* About

It remains visible while scrolling because CSS `position: sticky` is used.

---

### 2. Home Section

The home section introduces the project.

It contains:

* Project title
* Short project description
* Register Now button

The button takes the user to the registration form.

---

### 3. Registration Section

The registration section contains the main student form.

The form is divided into different fieldsets:

```text
Personal Details
       ↓
Course Details
       ↓
Examination Marks
       ↓
Additional Information
```

This makes the form easier to understand and use.

---

### 4. Result Section

The result section displays student academic information.

It contains:

* Student name
* Roll number
* Course
* Subject-wise marks
* Pass/Fail status
* Total marks
* Percentage
* Overall result

---

### 5. About Section

The About section explains the purpose of the project and the technologies used to develop it.

---

### 6. Footer

The footer contains project information and copyright details.

---

# 🛠️ Technologies Used

## HTML5

HTML5 is used to create the structure of the webpage.

HTML5 is used for:

* Headings
* Paragraphs
* Forms
* Input fields
* Dropdown lists
* Radio buttons
* Text areas
* Tables
* Navigation
* Sections
* Footer

Example:

```html
<form>
    <label for="name">Full Name</label>

    <input
        type="text"
        id="name"
        name="name"
        required>
</form>
```

---

## CSS3

CSS3 is used to design and style the webpage.

CSS3 is used for:

* Colors
* Fonts
* Spacing
* Borders
* Shadows
* Buttons
* Cards
* Tables
* Navigation
* Flexbox
* CSS Grid
* Responsive design
* Hover effects
* Media queries

Example:

```css
.form-card {
    background: white;
    padding: 35px;
    border-radius: 15px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.08);
}
```

---

# 📂 Project Structure

The project contains two main files:

```text
Student-Portal/
│
├── index.html
│
├── style.css
│
└── README.md
```

### `index.html`

Contains the complete structure of the website.

It includes:

* Navigation
* Home section
* Registration form
* Course selection
* Marks section
* Result section
* About section
* Footer

### `style.css`

Contains all the styling and responsive design rules.

---

# 🧩 HTML5 Form Elements Used

The project demonstrates different HTML5 input types.

### Text Input

```html
<input type="text">
```

Used for entering names and other text information.

### Email Input

```html
<input type="email">
```

Used for email addresses.

### Telephone Input

```html
<input type="tel">
```

Used for phone numbers.

### Date Input

```html
<input type="date">
```

Used for date of birth.

### Number Input

```html
<input type="number">
```

Used for examination marks.

### Radio Buttons

```html
<input type="radio">
```

Used for selecting gender.

### Dropdown

```html
<select>
    <option>CSE</option>
    <option>AIML</option>
</select>
```

Used for selecting courses and academic years.

### Textarea

```html
<textarea></textarea>
```

Used for entering the student's address.

---

# 📐 CSS Layout

The project uses modern CSS layout techniques.

## CSS Grid

CSS Grid is used to arrange form fields.

```css
.form-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
}
```

This creates two columns on larger screens.

---

## Flexbox

Flexbox is used for navigation and buttons.

```css
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

---

# 📱 Responsive Design

The project is designed to work on:

* Desktop
* Laptop
* Tablet
* Mobile phone

CSS media queries are used for responsive behavior.

Example:

```css
@media (max-width: 768px) {

    .form-grid {
        grid-template-columns: 1fr;
    }

    .result-summary {
        grid-template-columns: 1fr;
    }
}
```

On smaller screens, the two-column layout changes into a single-column layout.

---

# 🎨 Design Features

The website includes several CSS3 design features.

### Rounded Cards

```css
border-radius: 15px;
```

### Box Shadows

```css
box-shadow: 0 8px 25px rgba(0,0,0,0.08);
```

### Hover Effects

```css
.nav-links a:hover {
    color: #93c5fd;
}
```

### Gradient Background

```css
background: linear-gradient(
    135deg,
    #2563eb,
    #7c3aed
);
```

These features provide a clean and modern appearance.

---

# 🔐 Validation

HTML5 validation is
