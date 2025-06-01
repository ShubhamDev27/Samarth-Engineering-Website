
# Samarth Engineering Website

Welcome to the official website repository for **Samarth Engineering Works**.

This is a simple, lightweight single-page static website built using **HTML, CSS, and JavaScript**. It showcases company information, product catalog, and provides options to contact or chat via WhatsApp.

---

## 🌐 Live Features

- Company overview and product highlights
- WhatsApp contact integration
- Downloadable PDF product catalog (with local caching)
- Smooth scrolling and modern animations
- Responsive design using CSS and Swiper.js

---

## 📁 Folder Structure

```
samarth-engineering-website/
│
├── index.html                # Main HTML page
├── assets/
│   ├── css/                  # Stylesheets
│   │   └── style.css
│   ├── js/                   # JavaScript files
│   │   └── script.js
│   ├── docs/
│   │   └── SAMARTH LASER CATLOG.pdf  # PDF Catalog
│   └── images/               # Image assets
│       └── slider/
│           └── s_2.png
│
├── README.md                 # Project overview (this file)
└── LICENSE                   # Optional: Add if open-sourcing
```

---

## ⚙️ Features & Functionality

### ✅ Catalog Download with Local Caching
- First click downloads the PDF file using `fetch` and converts it to a Data URL.
- Cached using `localStorage`, so future downloads are instant without server calls.

```html
<a href="#" class="theme-btn download-catalog-btn">Download Catalog</a>
```

```js
// JavaScript uses .download-catalog-btn class
```

### ✅ WhatsApp Chat Button
```html
<a href="https://wa.me/9184216037355" target="_blank">
    💬 Chat with us on WhatsApp
</a>
```

---

## 🚀 How to Use / Deploy

### Locally
1. Clone the repo or copy the files to a local folder.
2. Open `index.html` directly in your browser.

### Upload to Web Hosting
- You can upload it to any static web host (like Netlify, GitHub Pages, Vercel, or your own server).
- Make sure the `assets/docs/` folder is also uploaded so the PDF file is accessible.

---

## 🛠 Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **Swiper.js** (for slider effects)
- **localStorage** (for caching)

---

## 📞 Contact

**Samarth Engineering Works**  
📧 Email: [shubhamchopdar27@gmail.com]  
📱 WhatsApp: [+91 7020200548 ]

---

## 📝 License

This project is private. All content belongs to **Samarth Engineering Works**. Contact the owner for reuse or distribution.
