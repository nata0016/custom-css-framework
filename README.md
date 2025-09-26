# 🎨 Custom CSS Framework

A lightweight and customizable CSS framework built with **Sass**.  
It provides:
- A consistent theme for standard HTML elements (typography, lists, tables, forms).  
- Utility classes (spacing, colors, display, borders, typography).  
- Ready-to-use components (buttons, forms, tables).  

---

## 🚀 Installation

Clone the repository:
```bash
git clone https://github.com/<username>/custom-css-framework.git
cd custom-css-framework

## Install dependencies:
npm install
## Run the watcher for development (auto-recompile on save):
npm run watch
## Build the framework for production:
npm run build

# 📂 Project Structure
src/
  core/         # Variables, mixins, functions, reset
  utilities/    # Utility classes (spacing, colors, display, etc.)
  theme/        # Global HTML styles (typography, elements)
  components/   # UI components (buttons, forms, tables)
dist/           # Compiled CSS (framework.css & framework.min.css)
examples/       # Demo HTML files showing usage

## Include the compiled CSS file in your project:
<link rel="stylesheet" href="dist/framework.css">

## Example button
<button class="btn btn--primary">Primary Button</button>
<button class="btn btn--secondary">Secondary Button</button>

## Example form
<form>
  <label for="email">Email</label>
  <input type="email" id="email" placeholder="Enter your email">
  <button class="btn btn--primary">Submit</button>
</form>

## 🎨 Customization
$color-primary: #4CAF50; // change primary color
$font-sans: "Helvetica Neue", Arial, sans-serif; // change default font
$radius-md: 1rem; // change border radius

# Rebuild after changes:
npm run build

## 📌 Roadmap / Features
 Core setup (variables, mixins, reset, functions)
 Buttons component
 Utilities (spacing, colors, display, borders, typography)
 Theme (typography, elements)
 Forms component
 Tables component
 Documentation complete

 