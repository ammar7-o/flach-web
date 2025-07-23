# Flach Web

\<img style="width: 100px; display: inline; margin: 5px;" src="logo.png" alt=""\>

Welcome to **Flach Web**, a curated collection of modern web UI tools and libraries to enhance your development workflow. Click any section title to explore examples and usage in detail.

-----

## 1\. Tailwind CSS

A utility-first CSS framework for rapid UI development. Use concise classes like: `p-4`, `text-center`, `bg-blue-500`, and more to style your layout quickly and consistently.

-----

## 2\. AOS (Animate On Scroll)

Add scroll-triggered animations using `data-aos` attributes. Example: `<div data-aos="fade-up">...</div>`

  * `data-aos-delay="300"`
  * `data-aos-duration="1000"`
  * `data-aos-offset="120"`

-----

## 3\. Sal.js

Lightweight animation library using IntersectionObserver. Example: `<div data-sal="slide-left">...</div>`

  * `data-sal-delay`, `data-sal-duration`
  * `data-sal-easing`

-----

## 4\. Animate.css + WOW.js

Combine Animate.css and WOW.js to animate elements on scroll. Example: `<div class="wow bounceInUp">...</div>`

Popular classes: `fadeIn`, `zoomIn`, `slideInLeft`.

-----

## 5\. Font Awesome

Scalable vector icons customizable with CSS. Example usage:

  * `<i class="fas fa-home"></i>` – Solid home icon
  * `<i class="fab fa-github"></i>` – GitHub brand icon

Customize using classes like `fa-2x`, or Tailwind classes like `text-blue-500`.

-----

## 6\. Hint.css (Tooltips)

Simple tooltip library using data attributes. Example: `<button class="hint--top" aria-label="Tooltip text">Hover me</button>`

  * Position using classes like `hint--top`, `hint--bottom`, etc.
  * Customize with inline CSS variables: `style="--hint-background: #8e44ad; --hint-color: #fff;"`

-----

## 7\. Fonts

Includes a collection of Arabic and English fonts for web typography. Easily integrate unique typefaces into your project.

-----

## 🔧 Initialization Scripts

All libraries are initialized with default settings for quick use:

  * **AOS:** Duration, offset, mirror
  * **SAL:** Easing, threshold
  * **WOW:** Basic setup on scroll

-----

## 📌 Notes

  * Use only one animation library per element to avoid conflicts.
  * Add extra vertical space to see scroll animations clearly.
  * Customize animation offset for earlier or later trigger points.

-----

## 💚 Made with love by Ammar Chacal
