# 💆‍♀️ Carolina Spa – Responsive Spa Website

Carolina Spa is a *study project* developed as part of a front-end course. It is a modern, elegant, and fully responsive website designed for a spa business. The project is built using HTML5, SCSS, JavaScript, and Gulp, following best practices for maintainability, automation, and design. The site includes interactive elements such as image sliders and uses BEM methodology for clean CSS structure.

> ⚠️ Note: This is a front-end prototype for educational purposes and does not include backend functionality.

## 🔗 Live Preview

[👉 View the Demo on Netlify](https://nucleus-juligeraldev.netlify.app/)
## ✨ Features

- Responsive Design using SCSS media queries to ensure smooth display across all screen sizes  
- Modular SCSS Architecture with base styles, mixins, and component-specific files  
- Swiper Integration for a modern image slider experience  
- BEM Methodology to maintain consistent and readable CSS  
- Gulp Automation for compiling SCSS, optimizing images, and generating WebP/AVIF formats  
- Accessibility-Friendly navigation and semantic HTML structure

## 📁 Project Structure

carolina_spa/  
├── build/              # Compiled CSS and optimized images  
├── src/                # Source files  
│   ├── scss/  
│   │   ├── base/       # Variables, mixins, global styles  
│   │   ├── ui/         # UI components (header, footer, etc.)  
│   │   └── app.scss    # SCSS entry point  
│   ├── js/             # JavaScript files (Swiper, interactions)  
│   └── img/            # Source images  
├── index.html          # Main landing page  
├── gulpfile.js         # Gulp configuration  
├── package.json        # Project dependencies and scripts  
└── .gitignore          # Git ignore file

## 🛠️ Technologies Used

- HTML5 – Semantic structure for accessibility and clarity  
- SCSS – Modular and scalable styling using variables and mixins  
- JavaScript – For interactive features like the image slider  
- Gulp – Automates compilation, optimization, and development workflows  
- Swiper.js – Enables modern responsive carousels and sliders  

## ⚙️ Installation

To set up the project locally:

1. Clone the repository  
   git clone https://github.com/your-repo/carolina_spa.git  
   cd carolina_spa

2. Install the dependencies  
   npm install

3. Start the development server  
   npm run dev

This will:  
- ✅ Compile SCSS into minified CSS  
- ✅ Optimize images and generate WebP/AVIF formats  
- ✅ Watch for changes in SCSS, JS, and image files and recompile automatically

## 🎨 SCSS Structure

base/  
- _variables.scss – Font families, colors, spacing  
- _mixins.scss – Media queries and reusable snippets  
- _globales.scss – Reset and base styles

ui/  
- Component styles for layout sections, header, footer, and page content

## 🔁 Gulp Tasks

- CSS Compilation – Converts SCSS to CSS and autoprefixes  
- Image Optimization – Compresses and converts images to modern formats  
- File Watching – Rebuilds on every change for a smooth workflow

## 👩‍💻 Author

Juliana García Corredor  
GitHub: @JuliGeralDev

## 📝 Notes

- Make sure Node.js and npm are installed on your system  
- The `/build` folder is auto-generated and ignored in Git
