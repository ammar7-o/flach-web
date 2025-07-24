
# ⚡ Flach Web

**Welcome to Flach Web**, a curated collection of modern web UI tools and libraries to enhance your development workflow.
Click any section title to explore examples and usage in detail.

---

## 1. Tailwind CSS

A utility-first CSS framework for rapid UI development.

Use concise classes like:

```html
p-4, text-center, bg-blue-500
```

to style your layout quickly and consistently.

---

## 2. AOS (Animate On Scroll)

Add scroll-triggered animations using `data-aos` attributes.

Example:

```html
<div data-aos="fade-up">...</div>
```

Other attributes:

```html
data-aos-delay="300"
data-aos-duration="1000"
data-aos-offset="120"
```

---

## 3. Sal.js

Lightweight animation library using `IntersectionObserver`.

Example:

```html
<div data-sal="slide-left">...</div>
```

Attributes:

```html
data-sal-delay
data-sal-duration
data-sal-easing
```

---

## 4. Animate.css + WOW\.js

Combine Animate.css and WOW\.js to animate elements on scroll.

Example:

```html
<div class="wow bounceInUp">...</div>
```

Popular animation classes:

```
fadeIn, zoomIn, slideInLeft
```

---

## 5. Font Awesome

Scalable vector icons customizable with CSS.

Examples:

```html
<i class="fas fa-home"></i>       <!-- Solid home icon -->
<i class="fab fa-github"></i>     <!-- GitHub brand icon -->
```

Customize with:

```
fa-2x, text-blue-500 (Tailwind)
```

---

## 6. Hint.css (Tooltips)

Simple tooltip library using `data` attributes.

Example:

```html
<button class="hint--top" aria-label="Tooltip text">Hover me</button>
```

Customize position with:

```
hint--top, hint--bottom, etc.
```

Style with inline CSS variables:

```html
style="--hint-background: #8e44ad; --hint-color: #fff;"
```

---

## 7. Fonts

Includes a collection of **Arabic and English fonts** for web typography.

Easily integrate unique typefaces into your project using CSS.

---

## 8. Bootstrap 5

A powerful front-end framework for building responsive websites quickly.

Features:

* **Responsive grid system**:

  ```html
  .container, .row, .col
  ```
* **Button styles**:

  ```html
  .btn, .btn-primary, .btn-outline-*
  ```
* **Reusable components**:

  ```html
  .navbar, .card, .modal, .alert
  ```
* **JavaScript plugins**:
  Carousel, Collapse, Dropdowns, Tooltips

Example:

```html
<button class="btn btn-success">Click me</button>
<div class="alert alert-info">Bootstrap Alert</div>
```

Customize with:

```html
.bg-*, .text-*, .m-*, .p-* 
```

---

## 🔧 Initialization Scripts

All libraries are initialized with default settings for quick use:

* **AOS**: `duration`, `offset`, `mirror`
* **SAL**: `easing`, `threshold`
* **WOW**: Basic setup on scroll

---

## 📌 Notes

* ✅ Use **only one animation library per element** to avoid conflicts.
* ✅ Add extra **vertical space** to see scroll animations clearly.
* ✅ Customize animation **offset** for earlier/later trigger points.

---

### 💚 Made with love by **Ammar Chacal**

---

