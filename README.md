# Bootstrap
# 📘 Bootstrap Complete Documentation

> A well-structured, beginner-to-advanced guide to **Bootstrap 5**, suitable for sharing on **GitHub**. This documentation covers all major Bootstrap topics with clear explanations, examples, and best practices.

---

## 📌 Table of Contents

1. Introduction to Bootstrap
2. Why Use Bootstrap
3. Bootstrap Versions
4. Bootstrap Setup

   * CDN
   * Local Installation
5. Bootstrap File Structure
6. Bootstrap Grid System
7. Layout Utilities
8. Typography
9. Colors & Backgrounds
10. Images
11. Tables
12. Forms
13. Buttons
14. Alerts
15. Badges
16. Cards
17. List Groups
18. Navs & Navbar
19. Dropdowns
20. Pagination
21. Progress Bars
22. Spinners
23. Modals
24. Tooltips
25. Popovers
26. Toasts
27. Accordion
28. Carousel
29. Offcanvas
30. Collapse
31. Scrollspy
32. Utilities

* Spacing
* Display
* Flexbox
* Position
* Sizing
* Overflow
* Shadows
* Visibility

32. Icons (Bootstrap Icons)
33. Customization
34. Accessibility
35. Best Practices
36. Resources & References

---

## 1️⃣ Introduction to Bootstrap

Bootstrap is a **free, open-source front-end framework** for building responsive, mobile-first websites quickly using **HTML, CSS, and JavaScript**.

Developed by **Twitter**, Bootstrap provides ready-made UI components and a powerful grid system.

---

## 2️⃣ Why Use Bootstrap

* 📱 Mobile-first design
* ⚡ Fast development
* 🎨 Predefined components
* 🌍 Cross-browser compatibility
* 🧩 Easy customization

---

## 3️⃣ Bootstrap Versions

* **Bootstrap 3** – Legacy (not recommended)
* **Bootstrap 4** – Flexbox-based
* **Bootstrap 5 (Latest)** – No jQuery, better utilities

👉 This documentation focuses on **Bootstrap 5**.

---

## 4️⃣ Bootstrap Setup

### 🔹 Using CDN (Recommended)

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
```

### 🔹 Local Installation

1. Download from [https://getbootstrap.com](https://getbootstrap.com)
2. Include `bootstrap.min.css` and `bootstrap.bundle.min.js`

---

## 5️⃣ Bootstrap File Structure

```
bootstrap/
├── css/
│   └── bootstrap.min.css
├── js/
│   └── bootstrap.bundle.min.js
```

---

## 6️⃣ Bootstrap Grid System

Bootstrap uses a **12-column grid system**.

### Breakpoints

| Breakpoint  | Class Prefix | Width   |
| ----------- | ------------ | ------- |
| Extra Small | .col-        | <576px  |
| Small       | .col-sm-     | ≥576px  |
| Medium      | .col-md-     | ≥768px  |
| Large       | .col-lg-     | ≥992px  |
| Extra Large | .col-xl-     | ≥1200px |

### Example

```html
<div class="row">
  <div class="col-md-6">Column 1</div>
  <div class="col-md-6">Column 2</div>
</div>
```

---

## 7️⃣ Layout Utilities

* `.container`
* `.container-fluid`
* `.row`
* `.col`

---

## 8️⃣ Typography

* Headings (`h1`–`h6`)
* `.lead`
* `.text-center`, `.text-muted`
* `.fw-bold`, `.fst-italic`

---

## 9️⃣ Colors & Backgrounds

### Text Colors

* `.text-primary`
* `.text-success`
* `.text-danger`

### Background Colors

* `.bg-primary`
* `.bg-dark`
* `.bg-light`

---

## 🔟 Images

* `.img-fluid`
* `.rounded`
* `.rounded-circle`
* `.img-thumbnail`

---

## 1️⃣1️⃣ Tables

```html
<table class="table table-striped table-bordered">
```

Table classes:

* `.table-hover`
* `.table-dark`

---

## 1️⃣2️⃣ Forms

* `.form-control`
* `.form-label`
* `.form-check`
* `.input-group`

---

## 1️⃣3️⃣ Buttons

```html
<button class="btn btn-primary">Primary</button>
```

Variants:

* `.btn-success`
* `.btn-danger`
* `.btn-outline-*`

---

## 1️⃣4️⃣ Alerts

```html
<div class="alert alert-warning">Warning</div>
```

---

## 1️⃣5️⃣ Badges

```html
<span class="badge bg-success">New</span>
```

---

## 1️⃣6️⃣ Cards

Cards are flexible content containers.

---

## 1️⃣7️⃣ List Groups

* `.list-group`
* `.list-group-item`

---

## 1️⃣8️⃣ Navs & Navbar

* `.nav`
* `.navbar`
* `.navbar-expand-lg`

---

## 1️⃣9️⃣ Dropdowns

```html
<div class="dropdown"></div>
```

---

## 2️⃣0️⃣ Pagination

* `.pagination`
* `.page-item`

---

## 2️⃣1️⃣ Progress Bars

```html
<div class="progress">
```

---

## 2️⃣2️⃣ Spinners

* `.spinner-border`
* `.spinner-grow`

---

## 2️⃣3️⃣ Modals

Used for dialogs and popups.

---

## 2️⃣4️⃣ Tooltips

Requires JavaScript initialization.

---

## 2️⃣5️⃣ Popovers

Used for rich content overlays.

---

## 2️⃣6️⃣ Toasts

Lightweight notifications.

---

## 2️⃣7️⃣ Accordion

Used to toggle content panels.

---

## 2️⃣8️⃣ Carousel

Used for slideshows.

---

## 2️⃣9️⃣ Offcanvas

Sidebar components.

---

## 3️⃣0️⃣ Collapse

Show/hide content.

---

## 3️⃣1️⃣ Scrollspy

Auto-update navigation.

---

## 3️⃣2️⃣ Utilities

### Spacing

* `.m-3`, `.p-2`

### Display

* `.d-none`, `.d-flex`

### Flexbox

* `.justify-content-center`

### Position

* `.position-relative`

### Sizing

* `.w-50`, `.h-100`

---

## 3️⃣3️⃣ Bootstrap Icons

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css">
```

---

## 3️⃣4️⃣ Customization

* Customize via SCSS
* Override CSS variables

---

## 3️⃣5️⃣ Accessibility

* ARIA attributes
* Keyboard navigation
* Screen reader support

---

## 3️⃣6️⃣ Best Practices

* Use utility classes wisely
* Avoid excessive nesting
* Keep layout responsive

---

## 📚 Resources & References

* Official Docs: [https://getbootstrap.com](https://getbootstrap.com)
* Bootstrap Icons: [https://icons.getbootstrap.com](https://icons.getbootstrap.com)

---

## ⭐ Conclusion

Bootstrap is a powerful framework that helps developers build responsive, modern, and professional web applications efficiently.

> 💡 Feel free to fork, modify, and improve this documentation.

---

### 👨‍💻 Author

**Sagar Kumar**

Happy Coding! 🚀
