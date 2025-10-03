Custom CSS Framework
A lightweight, customizable CSS framework built with Sass.
It provides a consistent theme for standard HTML elements, reusable components, and a full set of utility classes for rapid prototyping.

Features
Built with Sass partials for modularity.
Customizable variables (colors, typography, spacing, borders, shadows).
Base styles for HTML elements (headings, paragraphs, lists, blockquotes, code).
Reusable components: buttons, forms, tables.
Utility classes: spacing, display, colors, typography, borders, shadows.
Compiled CSS ready to use (dist/framework.css & dist/framework.min.css).

Project Structure
custom-css-framework/
├── dist/                  # Compiled CSS (final output)
│   ├── framework.css
│   └── framework.min.css
├── src/                   # Source Sass files
│   ├── core/              # Variables, mixins, functions, reset
│   ├── utilities/         # Utility classes
│   ├── components/        # Reusable UI components
│   ├── theme/             # Theme styles (typography, elements)
│   └── framework.scss     # Main entry file
├── examples/              # Demo HTML files
│   └── index.html
└── README.md              # Project documentation

Installation
Clone the repo:
git clone https://github.com/<nata0016>/custom-css-framework.git
cd custom-css-framework

Install dependencies:
npm install

Usage
Link the compiled CSS in HTML:
<link rel="stylesheet" href="dist/framework.css">

Customization
Open src/core/_variables.scss to override defaults:
$color-primary: #265DAB;
$color-secondary: #E27D35;
$font-sans: 'Inter', sans-serif;
$radius-md: 8px;

Recompile:
npm run build

Documentation
Utilities
Examples:
<div class="p-3 bg-primary text-white">Padding + Background</div>
<p class="fw-700 fs-lg">Bold and large text</p>
<div class="d-flex gap-4">
  <div class="border rounded shadow-sm">Box with border + rounded corners</div>
</div>

Available utility categories:
Spacing: .p-3, .m-2, .gap-4
Colors: .bg-primary, .text-secondary, .bg-gray-200
Display: .d-flex, .d-grid, .d-none
Typography: .fw-700, .fs-lg
Borders & Shadows: .border, .rounded, .shadow-sm

Theme
Headings (h1–h6) styled with consistent scale.
Lists (ul, ol) with spacing.
Blockquote with left border in primary color.
Code with inline styles for readability.
Components

Buttons
<button class="btn btn--primary">Primary</button>
<button class="btn btn--secondary">Secondary</button>
Forms
<form>
  <label for="email">Email</label>
  <input type="email" id="email" placeholder="you@example.com">
  <button class="btn btn--primary">Submit</button>
</form>

Tables
<table>
  <thead><tr><th>Name</th><th>Role</th></tr></thead>
  <tbody>
    <tr><td>Ada</td><td>Lead</td></tr>
    <tr><td>Lin</td><td>Dev</td></tr>
  </tbody>
</table>

Team
Lead: Ghita Natami
Utilities: Giovani Sariel Efombagne Emok
Theme: Elsie Akuzwe
Components: Kinsy Awassume

