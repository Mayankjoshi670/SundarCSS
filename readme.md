# Documentation Website : [url](https://sundar-css-doc.vercel.app/)
https://sundar-css-doc.vercel.app/
# 🚀 SundarCSS — A Lightweight SCSS Utility Framework

A lightweight, customizable SCSS utility framework for rapidly building responsive and modern UIs.

---

## ✨ Features

- ⚡ Utility-first classes (margin, padding, display, etc.)
- 📱 Responsive 12-column grid system
- 🌙 Built-in dark mode support
- 🎯 Smooth animations and transitions
- 🎨 Typography and color utility classes
- 🧱 Modular, easy-to-extend SCSS architecture

---

## 📦 Installation

#### Using npm:

``` 
npm install sundarcss
```
#### Or using yarn:
 
 ```
yarn add sundarcss
```
🛠️ Usage
### Step 1: Convert SCSS to CSS
First, install sass as a dev dependency:
 ```
npm install sass --save-dev 
```
### Step 2: Update your package.json Scripts
 
```
"scripts": {
  "build": "sass node_modules/sundarcss/scss/main.scss dist/sundar.css"
}
```
##### 🔴🔴 If you are using react or other library inside package.json first comment the old build command other wise it will build the complete code 

### Step 3: Compile SCSS

 ```
npm run build
```
After running this, you’ll get your compiled CSS file at:

 ```
dist/sundar.css
```
## 🧪 Example Usage
 ```
<div class="container grid-3 gap-2 p-4 text-center bg-dark text-light">
  <div class="card">Card 1</div>
  <div class="card">Card 2</div>
  <div class="card">Card 3</div>
</div>
```
### 📄 License
This project is licensed under the [MIT License.]()

🧑‍💻 Made with  by Mayank & Team

 