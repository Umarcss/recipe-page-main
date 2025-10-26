# 🍳 Simple Omelette Recipe Page

A beautiful, responsive recipe page showcasing a classic omelette recipe. Built with modern web technologies and designed with a mobile-first approach for optimal viewing across all devices.

![Recipe Page Preview](./preview.jpg)

## 📋 Table of Contents

- [Overview](#overview)
  - [Features](#features)
  - [Screenshots](#screenshots)
  - [Live Demo](#live-demo)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Design System](#design-system)
- [Development Process](#development-process)
- [Key Features](#key-features)
- [Responsive Design](#responsive-design)
- [Performance Optimizations](#performance-optimizations)
- [Browser Support](#browser-support)
- [Getting Started](#getting-started)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🎯 Overview

This project is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). It features a clean, modern design that showcases a simple omelette recipe with detailed ingredients, step-by-step instructions, preparation time, and nutritional information.

### ✨ Features

- **📱 Mobile-First Responsive Design** - Optimized for all screen sizes
- **🎨 Modern Typography** - Custom fonts (Young Serif & Outfit) for enhanced readability
- **📊 Nutritional Information** - Detailed nutrition table with calories, carbs, protein, and fat
- **⏱️ Preparation Time** - Clear breakdown of total, preparation, and cooking time
- **📝 Step-by-Step Instructions** - Numbered instructions for easy following
- **🎯 Semantic HTML** - Properly structured content for accessibility
- **🎨 Custom Color Palette** - Carefully selected colors for optimal visual hierarchy
- **📐 CSS Grid & Flexbox** - Modern layout techniques for responsive design

### 📸 Screenshots

#### Desktop View
![Desktop Design](./design/desktop-design.jpg)

#### Mobile View
![Mobile Design](./design/mobile-design.jpg)

### 🔗 Live Demo

- **Live Site**: [View Live Demo](https://your-live-site-url.com)
- **Frontend Mentor Solution**: [View Solution](https://www.frontendmentor.io/solutions/your-solution-url)

## 🛠️ Tech Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with custom properties
- **Responsive Design** - Mobile-first approach
- **Custom Fonts** - Young Serif & Outfit from Google Fonts
- **CSS Grid & Flexbox** - Modern layout techniques
- **Media Queries** - Responsive breakpoints

## 📁 Project Structure

```
recipe-page-main/
├── assets/
│   ├── css/
│   │   └── style.css          # Main stylesheet
│   ├── fonts/
│   │   ├── outfit/           # Outfit font family
│   │   └── young-serif/      # Young Serif font
│   └── images/
│       ├── favicon-32x32.png
│       └── image-omelette.jpeg
├── design/
│   ├── desktop-design.jpg
│   └── mobile-design.jpg
├── index.html                # Main HTML file
├── style-guide.md           # Design system documentation
└── README.md               # Project documentation
```

## 🎨 Design System

### Color Palette

- **White**: `hsl(0, 0%, 100%)` - Main background
- **Stone 100**: `hsl(30, 54%, 90%)` - Desktop background
- **Stone 600**: `hsl(30, 10%, 34%)` - Body text
- **Stone 900**: `hsl(24, 5%, 18%)` - Main headings
- **Brown 800**: `hsl(14, 45%, 36%)` - Section headings
- **Rose 800**: `hsl(332, 51%, 32%)` - Preparation time heading
- **Rose 50**: `hsl(330, 100%, 98%)` - Preparation time background

### Typography

- **Headings**: Young Serif (400 weight)
- **Body Text**: Outfit (400, 600, 700 weights)
- **Font Sizes**: Responsive scaling from 14px to 2.5rem

### Layout Breakpoints

- **Mobile**: 375px and below
- **Tablet**: 376px - 768px
- **Desktop**: 769px and above

## 🚀 Development Process

### 1. Planning & Analysis
- Analyzed the design requirements and created a component breakdown
- Identified key responsive breakpoints and layout considerations
- Planned the semantic HTML structure

### 2. HTML Structure
- Created semantic HTML5 markup with proper heading hierarchy
- Implemented accessible form elements and navigation
- Added proper alt text and ARIA labels

### 3. CSS Implementation
- Implemented mobile-first responsive design
- Created reusable CSS custom properties for colors and spacing
- Used modern CSS techniques (Grid, Flexbox, custom properties)

### 4. Responsive Design
- Tested across multiple device sizes
- Optimized typography and spacing for different screen sizes
- Ensured touch-friendly interface elements

## 🔧 Key Features

### Responsive Layout
```css
/* Mobile-first approach */
.main {
    width: 100%;
    margin: 0;
    padding: 0;
}

/* Desktop styles */
@media (min-width: 769px) {
    .main {
        width: 50%;
        margin: 50px auto;
        border-radius: 1.2rem;
        padding: 50px;
    }
}
```

### Custom Typography
```css
h1, h2 {
    font-family: "Young Serif";
    color: hsl(24, 5%, 18%);
}

p, li, span {
    font-family: "Outfit";
    color: hsl(30, 10%, 34%);
}
```

### Nutrition Table
```css
.nutrition-table {
    width: 100%;
    border-collapse: collapse;
}

.nutrition-table tr {
    border-bottom: 1px solid hsl(30, 10%, 34%);
}
```

## 📱 Responsive Design

The page is built with a mobile-first approach, ensuring optimal viewing experience across all devices:

- **Mobile (≤375px)**: Full-width layout with minimal padding
- **Tablet (376px-768px)**: Centered layout with moderate padding
- **Desktop (≥769px)**: Centered card layout with maximum padding

### Key Responsive Features:
- Fluid typography scaling
- Adaptive image sizing
- Flexible spacing and padding
- Touch-friendly interface elements

## ⚡ Performance Optimizations

- **Optimized Images**: Compressed and properly sized images
- **Font Loading**: Efficient Google Fonts loading with preconnect
- **CSS Optimization**: Minimal and efficient CSS
- **Semantic HTML**: Clean, accessible markup structure

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML and CSS

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Umarcss/recipe-page-main.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd recipe-page-main
   ```

3. **Open the project**
   - Open `index.html` in your web browser
   - Or use a local development server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

4. **View the project**
   - Open `http://localhost:8000` in your browser

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://Umarcss.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on every push
3. Get a custom domain and SSL certificate

### Vercel
1. Import your GitHub repository to Vercel
2. Deploy with zero configuration
3. Get automatic deployments and previews

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Frontend Mentor** - For providing the design challenge
- **Google Fonts** - For the beautiful Young Serif and Outfit fonts
- **Design Inspiration** - Based on the Frontend Mentor recipe page challenge

---

**Built with ❤️ by [Umar Abubakar](https://github.com/Umarcss)**

*This project is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).*