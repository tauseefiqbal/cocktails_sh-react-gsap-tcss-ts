# 🍹 Cocktails Landing Page

A modern, animated cocktails showcase website built with React, TypeScript, and GSAP animations featuring stunning visual effects and smooth scrolling experiences.

---

## 📑 Table of Contents

- [🍹 Cocktails Landing Page](#-cocktails-landing-page)
  - [📑 Table of Contents](#-table-of-contents)
  - [✨ Features](#-features)
  - [🛠️ Tech Stack](#️-tech-stack)
    - [Core Technologies](#core-technologies)
    - [Animations \& UI](#animations--ui)
    - [Development Tools](#development-tools)
  - [🚀 Deployment](#-deployment)
    - [Live Application](#live-application)
    - [Deployment Platform](#deployment-platform)
  - [🔐 Test and Admin Users Credentials](#-test-and-admin-users-credentials)
  - [👤 How to Use App for Regular User](#-how-to-use-app-for-regular-user)
    - [1. **Landing Page**](#1-landing-page)
    - [2. **Browse Cocktails**](#2-browse-cocktails)
    - [3. **Explore About Section**](#3-explore-about-section)
    - [4. **View Art Gallery**](#4-view-art-gallery)
    - [5. **Check Menu**](#5-check-menu)
    - [6. **Contact Us**](#6-contact-us)
    - [7. **Navigation**](#7-navigation)
  - [⚙️ How to Use App for Admin User](#️-how-to-use-app-for-admin-user)
  - [📦 Installation](#-installation)
    - [Prerequisites](#prerequisites)
    - [Setup Steps](#setup-steps)
  - [💻 Development](#-development)
    - [Available Scripts](#available-scripts)
    - [Project Structure](#project-structure)
  - [🎨 Customization](#-customization)
    - [Modifying Content](#modifying-content)
  - [🌐 Browser Support](#-browser-support)
  - [📄 License](#-license)
  - [🤝 Contributing](#-contributing)
  - [📧 Contact](#-contact)

---

## ✨ Features

✅ **Smooth GSAP Animations** - Professional scroll-triggered animations throughout the site

✅ **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices

✅ **Interactive Navigation** - Smooth scrolling navigation bar with active section highlighting

✅ **Hero Section** - Eye-catching hero with animated text and background video

✅ **Cocktails Showcase** - Display of most popular cocktails with prices and details

✅ **Mocktails Section** - Featured non-alcoholic beverages for all audiences

✅ **About Section** - Information about the cocktail bar and its unique offerings

✅ **Art Gallery** - Visual showcase of the bar's artistic ambiance

✅ **Menu Display** - Complete menu with animated elements and pricing

✅ **Contact Section** - Easy-to-use contact form with animations

✅ **Parallax Effects** - Engaging parallax scrolling on decorative elements

✅ **Split Text Animations** - Character and line-by-line text reveal animations

✅ **Performance Optimized** - Built with Vite for lightning-fast loading times

✅ **Type Safety** - Full TypeScript implementation for robust code

✅ **Modern CSS** - Tailwind CSS 4 for utility-first styling

---

## 🛠️ Tech Stack

### Core Technologies

- **React 19.1.0** - Latest React with concurrent features
- **TypeScript 7.0.2** - Type-safe development
- **Vite 6.3.5** - Next-generation frontend tooling

### Animations & UI

- **GSAP 3.13.0** - Professional-grade animation library
- **@gsap/react 2.1.2** - React hooks for GSAP
- **Tailwind CSS 4.1.7** - Utility-first CSS framework
- **React Responsive 10.0.1** - Media queries in React

### Development Tools

- **ESLint 9.25.0** - Code quality and consistency
- **TypeScript ESLint** - TypeScript-specific linting
- **Vite Plugin React** - Fast refresh and JSX support

---

## 🚀 Deployment

### Live Application

🌐 **Live URL:** [APP URL]

The application is deployed and accessible at the URL above. Visit the link to explore the interactive cocktails showcase with smooth animations and responsive design.

### Deployment Platform

- Hosted on modern web infrastructure
- Optimized build for production
- CDN-enabled for fast global access
- SSL/HTTPS secured

---

## 🔐 Test and Admin Users Credentials

> ⚠️ **Note:** There is no user management system in this App.

---

## 👤 How to Use App for Regular User

### 1. **Landing Page**
   - Visit the application URL
   - Enjoy the animated hero section with video background
   - Watch smooth text reveal animations

### 2. **Browse Cocktails**
   - Scroll down to view the cocktails section
   - Browse popular cocktails with their countries of origin
   - Check prices and ingredient details
   - Explore mocktail options

### 3. **Explore About Section**
   - Learn about the cocktail bar's story
   - Discover what makes the offerings unique
   - Experience parallax scroll effects

### 4. **View Art Gallery**
   - Browse the artistic ambiance showcase
   - Enjoy animated gallery elements
   - Get a feel for the bar's atmosphere

### 5. **Check Menu**
   - Access the complete menu section
   - View categorized drink offerings
   - Note prices and special items
   - Experience smooth scroll animations

### 6. **Contact Us**
   - Scroll to the contact section
   - Fill out the contact form with:
     - Your name
     - Email address
     - Message or inquiry
   - Submit your message
   - Receive confirmation

### 7. **Navigation**
   - Use the top navigation bar for quick access
   - Click any section link for smooth scrolling
   - Watch active section highlighting
   - Responsive menu on mobile devices

---

## ⚙️ How to Use App for Admin User

> ⚠️ **Note:** There is no user management system in this App.

---

## 📦 Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v18 or higher)
- **npm** (v9 or higher) or **yarn** or **pnpm**
- **Git** (for version control)

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd cocktails_sh
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open browser**
   - Navigate to `http://localhost:5173`
   - The app will automatically reload on code changes

---

## 💻 Development

### Available Scripts

- **`npm run dev`** - Start development server with hot reload
- **`npm run build`** - Build production-ready application
- **`npm run preview`** - Preview production build locally
- **`npm run lint`** - Run ESLint for code quality checks
- **`npm run type-check`** - Run TypeScript type checking

### Project Structure

```
cocktails_sh/
├── public/              # Static assets
│   ├── fonts/          # Custom fonts
│   ├── images/         # Images and graphics
│   ├── videos/         # Video assets
│   └── readme/         # README assets
├── src/
│   ├── components/     # React components
│   │   ├── Navbar.tsx
│   │   ├── Hero.tsx
│   │   ├── Cocktails.tsx
│   │   ├── About.tsx
│   │   ├── Art.tsx
│   │   ├── Menu.tsx
│   │   └── Contact.tsx
│   ├── App.tsx         # Main app component
│   ├── main.tsx        # Application entry point
│   └── index.css       # Global styles
├── constants/          # App constants and data
│   └── index.ts
├── index.html          # HTML template
├── package.json        # Dependencies and scripts
├── vite.config.ts      # Vite configuration
├── tsconfig.json       # TypeScript configuration
└── eslint.config.js    # ESLint configuration
```

---

## 🎨 Customization

### Modifying Content

1. **Update Cocktails/Mocktails Data**
   - Edit `constants/index.ts`
   - Add or modify cocktail/mocktail objects

2. **Change Animations**
   - Modify GSAP timelines in component files
   - Adjust `ScrollTrigger` settings for different effects

3. **Styling**
   - Update Tailwind classes in components
   - Modify `index.css` for global styles

4. **Images & Videos**
   - Replace files in `public/images/` and `public/videos/`
   - Update image references in components

---

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📧 Contact

For questions, suggestions, or support:

- **Email:** contact@cocktails.com
- **Website:** [APP URL]
- **GitHub Issues:** [Repository Issues Page]

---

<div align="center">
  Made with ❤️ and 🍹
  
  **Enjoy Responsibly!**
</div>
