
# 📦 **MyStore – Modern E-Commerce Frontend**

MyStore is a clean, responsive, modern e-commerce front-end website built using **HTML, CSS, and JavaScript** (no backend required).
It was developed as part of an internship submission and demonstrates UI design, product catalog rendering, cart management, search, filters, and checkout simulation.

---

## 🚀 **Features**

### 🏠 **Home Page**

* Modern hero section
* Clean UI with responsive design
* Feature cards (shipping, payment, support)
* Latest products preview

### 🛒 **Products Page**

* Dynamic product listing
* Category filtering
* Price range filtering
* Search functionality
* “Add to Cart” button
* “View Product” detailed page

### 🔍 **Search Page**

* Query-based search (`?q=term`)
* Shows filtered matching products

### 📘 **Product View Page**

* Large product image
* Product details & price
* Add to cart
* Related products

### 👜 **Cart Page**

* Shows items added to cart
* Increase / decrease quantity
* Auto-updates total price
* Remove items when qty → 0
* Fully powered by `localStorage`

### 💳 **Checkout Page**

* Shipping details form
* Order summary
* Total amount calculation
* Generate unique order number

### ✅ **Order Confirmation Page**

* Displays:

  * Order number
  * Total amount
  * Status (Processing)

### 🧭 **Navigation**

* Sticky header
* Mobile menu button
* Cart count auto-updates

---

## 🗂 **Project Structure**

```
ecommerce_site/
│── index.html
│── products.html
│── product-view.html
│── cart.html
│── category.html
│── checkout.html
│── order-confirmation.html
│── about.html
│── contact.html
│── search.html
│── README.md
│── .gitignore
│
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── app.js
    ├── data/
    │   └── products.json
    └── images/
        ├── logo.svg
        ├── hero.svg
        ├── product-1.svg
        ├── product-2.svg
        └── product-3.svg
```

---

## 🏗 **Tech Stack**

* **HTML5**
* **CSS3** (Minified)
* **JavaScript (ES6+)**
* **localStorage** for cart persistence
* **JSON** as product data source
* **SVG assets**

No frameworks, no backend — just clean frontend code.

---

## 🔧 **How to Run**

1. Download or clone the repository
2. Open the folder
3. Double-click **index.html**
4. Browse through the site (no server required)

---

## ☁️ **Deploy on GitHub Pages**

1. Commit + push your project to a GitHub repository
2. Go to:
   **Settings → Pages → Deploy from branch**
3. Select:

   * Branch: `main`
   * Folder: `/root`
4. The site will be live at:

```
https://yourusername.github.io/your-repository-name/
```

---

## 🧰 **Git Commands (Optional)**

```bash
git init
git add .
git commit -m "Initial commit – MyStore"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin main
```

---

## ✨ **Author**

**Ananta Aditya Chavali**


This project is free to use for learning and academic purposes.

