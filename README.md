# SongFeng Tea Website

A bilingual (Traditional Chinese/English) e-commerce website for the SongFeng (嵩豐) tea brand.

## Current Features
- 🌏 Bilingual interface (Traditional Chinese & English)
- 🏷️ Product showcase with images, details, and gallery
- 🔘 Buy Now button adds item to cart and redirects to Cart page
- 📌 Sticky navbar: fixed position and appears on scroll up
- 🎨 Proportional image scaling for product grid and Teas page
- 🖼️ Structured asset naming for easy expansion (see below)
- 📱 Responsive, modern UI powered by Tailwind CSS
- 🌐 Smooth scroll to brewing guide steps when using dropdown navigation
- 📄 Enhanced About page layout with distinct Brand Promise and Core Values sections
- ✉️ Footer now includes contact email for quick inquiries
- 🌐 Deployed on Vercel: [https://tea-website-rho.vercel.app/](https://tea-website-rho.vercel.app/)

## Planned Features
- 🛒 Order page with form and Firebase integration
- 🔐 User authentication and account management
- 💳 Payment processing integration
- 📊 Admin dashboard for order management
- 🔍 Advanced product search and filtering
- 📱 Progressive Web App (PWA) capabilities
- 🌐 RESTful API with Express.js and MongoDB backend
- ✅ Comprehensive testing with Jest, React Testing Library, and Cypress

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Run the development server:**
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure
- `src/pages/` — Main pages (Home, About, Products, Guide, Order, Contact)
- `src/components/` — Reusable UI components (Navbar, Hero, ProductCard, Footer...)
- `src/assets/` — Product images and brand assets

## Asset Naming Convention
Product images are named as:
```
product-id-category-sequence.ext
# Example: alisan-oolong-150g-x2-main-1.jpg (main product image)
# Example: alisan-oolong-150g-x2-gallery-1.jpg (gallery/product image)
```
This keeps assets organized and scalable as new products are added.

- For the Alishan Gift Box product, use:
  - Main image: `alisan-oolong-giftbox-150g-x2-main-1.jpg`
  - Gallery image: `alisan-oolong-giftbox-150g-x2-gallery-1.jpg`

## Live Demo
[https://tea-website-rho.vercel.app/](https://tea-website-rho.vercel.app/)

## Bilingual Support
All user-facing text is available in both Traditional Chinese and English. Use the language toggle in the navbar to switch languages.

## Current Tech Stack
- **Frontend**: React, React Router, Context API
- **Styling**: Tailwind CSS
- **State Management**: React Context, React Hooks
- **Deployment**: Vercel with CI/CD

## Planned Tech Stack Additions
- **Backend**: Firebase Firestore (orders & auth), Express.js + MongoDB REST API
- **Testing**: Jest, React Testing Library, Cypress
- **Performance**: Code splitting, lazy loading, image optimization
- **Analytics**: Google Analytics integration



## License
MIT

---

> This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
