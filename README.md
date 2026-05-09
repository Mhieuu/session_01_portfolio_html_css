# Session 01 - Portfolio HTML/CSS

## 🎯 Mục tiêu
Xây dựng một trang portfolio cá nhân sử dụng HTML5 semantic elements, CSS Grid, Flexbox, và responsive design.

## 📁 Cấu trúc thư mục
```
session_01_portfolio_html_css/
├── index.html              ← Complete HTML file (header, hero, about, skills, portfolio, contact, footer)
├── README.md               ← This file
├── css/                    ← Modular CSS stylesheets
│   ├── variables.css       ← CSS custom properties (colors, fonts, spacing)
│   ├── base.css            ← Global reset and base styles
│   ├── header.css          ← Header and navigation styling
│   ├── hero.css            ← Hero section styling
│   ├── about.css           ← About section styling
│   ├── skills.css          ← Skills section with progress bars
│   ├── portfolio.css       ← Portfolio gallery and lightbox
│   ├── contact.css         ← Contact form styling
│   ├── footer.css          ← Footer styling
│   └── responsive.css      ← Media queries for responsive design
├── js/                     ← JavaScript files
│   └── main.js             ← Scroll animations with IntersectionObserver
└── images/                 ← Project images
    ├── anh the 2.jpg       ← Profile photo
    ├── e-commerce.jpg      ← Portfolio image 1
    ├── data-analytics.png  ← Portfolio image 2
    ├── SaaS.png            ← Portfolio image 3
    ├── food-app.png        ← Portfolio image 4
    ├── fitness-tracker.png ← Portfolio image 5
    └── brand-design.jpg    ← Portfolio image 6
```

## 📋 Cấu trúc bài

### Bài 1.1: Header + Hero Section
- Sticky header với navigation menu
- Hamburger menu cho mobile
- Hero section full viewport với CTA button

### Bài 1.2: About + Skills Section
- About section 2 cột (avatar + nội dung)
- Skills section với progress bar animation
- Scroll animation sử dụng IntersectionObserver

### Bài 1.3: Portfolio Gallery
- Portfolio grid responsive (3/2/1 columns)
- Hover effects với transform scale
- CSS-only lightbox sử dụng :target pseudo-class

### Bài 1.4: Contact + Footer
- Contact form với validation UI
- Responsive footer với social links
- Email, GitHub, LinkedIn links

## 🔧 Công nghệ sử dụng
- HTML5
- CSS3 (Grid, Flexbox, Variables, Media Queries)
- Vanilla JavaScript (IntersectionObserver API)

## 🏗️ Kiến trúc CSS Modular
Project sử dụng kiến trúc CSS modular để dễ bảo trì và mở rộng:
- **variables.css**: Định nghĩa CSS custom properties cho colors, fonts, spacing
- **base.css**: Reset global và base styles cho tất cả elements
- **component-specific files**: Mỗi component (header, hero, about, skills, portfolio, contact, footer) có file CSS riêng
- **responsive.css**: Tất cả media queries cho các breakpoint (desktop, tablet, mobile)

Cách tiếp cận này giúp:
- Dễ maintain và debug
- Tái sử dụng CSS variables across components
- Tách biệt logic styling theo component
- Dễ mở rộng khi thêm feature mới


## 📱 Responsive Design
- Desktop (1024px+): 3-column portfolio, 2-column contact
- Tablet (768px-1023px): 2-column portfolio, 1-column contact  
- Mobile (<768px): 1-column, hamburger menu

## 👤 Thông tin cá nhân
- Name: Hiếu
- Email: hvuminh998@gmail.com
- GitHub: https://github.com/Mhieuu
- LinkedIn: https://www.linkedin.com/in/hi%E1%BA%BFu-v%C5%A9-minh-bb0bb430a/

## 🌐 Live Demo
- **GitHub Pages:** https://mhieuu.github.io/session_01_portfolio_html_css/

## 🚀 Cách chạy project

### Cách 1: Mở trực tiếp file
```bash
# Chỉ cần mở index.html trong trình duyệt
# Không cần server hay build tools
```

### Cách 2: Dùng Live Server (VS Code)
```bash
1. Install Live Server extension
2. Right-click index.html → Open with Live Server
3. Trình duyệt tự động mở tại http://localhost:5500/
```

### Cách 3: Dùng Python simple server
```bash
python -m http.server 8000
# Sau đó mở http://localhost:8000/
```

## 📝 Commit History
Tổng cộng 14 commits:
- 12 commits ban đầu theo quy tắc [TYPE] Description
- 1 commit thêm ảnh và cập nhật đường dẫn
- 1 commit refactor với modular CSS architecture và folder organization
