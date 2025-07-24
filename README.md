
# ⚡ Flach Web

Welcome to **Flach Web**, a curated collection of modern web UI tools and libraries to enhance your development workflow.
Click any section title to explore examples and usage in detail.

---

## 1. [Tailwind CSS](tailwind/index.html)

A utility-first CSS framework for rapid UI development.

Use concise classes like:

```
p-4, text-center, bg-blue-500
```

to style your layout quickly and consistently.

```html
<script src="/tailwind/tailwind.js"></script>
```

---

## 2. [AOS (Animate On Scroll)](animations-scrolling/aos-js/index.html)

Add scroll-triggered animations using `data-aos` attributes.

Example:

```html
<div data-aos="fade-up">...</div>
```

Attributes:

* `data-aos-delay="300"`
* `data-aos-duration="1000"`
* `data-aos-offset="120"`

```html
<link href="animations-scrolling/aos-js/aos.css" rel="stylesheet" />
<script src="animations-scrolling/aos-js/aos.js"></script>
<script>
  AOS.init({
    duration: 1000,
    easing: 'ease-out-back',
    once: false,
    mirror: true,
    offset: 100,
  });
</script>
```

---

## 3. [Sal.js](animations-scrolling/sal-js/index.html)

Lightweight animation library using `IntersectionObserver`.

Example:

```html
<div data-sal="slide-left">...</div>
```

Attributes:

* `data-sal-delay`, `data-sal-duration`
* `data-sal-easing`

```html
<link rel="stylesheet" href="animations-scrolling/sal-js/sal.css" />
<script src="animations-scrolling/sal-js/sal.js"></script>
<script>
  sal({
    threshold: 1,
    once: false,
    easing: 'ease-out-cubic',
  });
</script>
```

---

## 4. [Animate.css + WOW.js](animations/index.html)

Combine Animate.css and WOW\.js to animate elements on scroll.

Example:

```html
<div class="wow bounceInUp">...</div>
```

Popular classes: `fadeIn`, `zoomIn`, `slideInLeft`

```html
<link rel="stylesheet" href="animations/animate.css" />
<script src="animations/wow.min.js"></script>
<script>
  new WOW().init();
</script>
```

---

## 5. [Font Awesome](font-awesome/index.html)

Scalable vector icons customizable with CSS.

Examples:

```html
<i class="fas fa-home"></i>       <!-- Solid home icon -->
<i class="fab fa-github"></i>     <!-- GitHub brand icon -->
```

Customize using:

* `fa-2x`
* Tailwind classes like `text-blue-500`

```html
<link rel="stylesheet" href="font-awesome/css/all.min.css" />
```

---

## 6. [Hint.css (Tooltips)](hint-css/index.html)

Simple tooltip library using `data` attributes.

Example:

```html
<button class="hint--top" aria-label="Tooltip text">Hover me</button>
```

Customize:

* Positions: `hint--top`, `hint--bottom`, etc.
* Styling:

```html
style="--hint-background: #8e44ad; --hint-color: #fff;"
```

```html
<link rel="stylesheet" href="hint-css/hint.min.css" />
```

---

## 7. [Fonts](fonts/index.html)

Includes a collection of Arabic and English fonts for web typography.
Easily integrate unique typefaces into your project.

```html
<link rel="stylesheet" href="fonts/fonts.css" />
```

---

## 8. [Bootstrap 5](bootstrap/index.html)

A powerful front-end framework for building responsive websites quickly using prebuilt components and utility classes.

Features:

* Grid system:

  ```html
  .container, .row, .col
  ```
* Buttons:

  ```html
  .btn, .btn-primary, .btn-outline-*
  ```
* Components:

  ```html
  .navbar, .card, .modal, .alert
  ```
* JS Plugins: Carousel, Collapse, Dropdowns, Tooltips

Example:

```html
<button class="btn btn-success">Click me</button>
<div class="alert alert-info">Bootstrap Alert</div>
```

Customize with:

```html
.bg-*, .text-*, .m-*, .p-*
```

```html
<link rel="stylesheet" href="bootstrap/css/bootstrap.min.css" />
<script src="bootstrap/js/bootstrap.bundle.min.js"></script>
```

---

## 🔧 Initialization Scripts

All libraries are initialized with default settings for quick use:

* **AOS**: `duration`, `offset`, `mirror`
* **SAL**: `easing`, `threshold`
* **WOW**: Basic setup on scroll

---

## 📌 Notes

* Use only **one animation library per element** to avoid conflicts.
* Add **extra vertical space** to see scroll animations clearly.
* Customize **animation offset** for earlier/later trigger points.

---

## 💚 Made with love by **Ammar Chacal**


