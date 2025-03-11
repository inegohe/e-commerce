# Next.js Full-Stack E-Commerce Project

![ecommerce-banner](https://via.placeholder.com/1200x400.png?text=Next.js+E-Commerce+Project)

## 🚀 Overview
This is a full-stack eCommerce application built with **Next.js**, featuring **Sanity.io** as the headless CMS and **Stripe** for payment processing. The project allows users to browse and purchase electronic products seamlessly.

## 🛠️ Tech Stack
- **Frontend:** Next.js (React, Tailwind CSS)
- **Backend:** API Routes in Next.js
- **Database:** Sanity.io (Headless CMS)
- **Payments:** Stripe
- **State Management:** React Context API

## 🎯 Features
- 📌 **Modern UI/UX** with Tailwind CSS
- 📌 **Product Management** using Sanity.io CMS
- 📌 **Cart & Checkout** functionality
- 📌 **Secure Stripe Payment Integration**
- 📌 **Dynamic Routing for Product Pages**
- 📌 **Optimized SEO & Performance** with Next.js

## 📂 Project Structure
```
📦 nextjs-ecommerce
├── 📁 pages
│   ├── 📄 index.js          # Homepage
│   ├── 📄 product/[slug].js # Dynamic Product Page
│   ├── 📄 checkout.js       # Checkout Page
│   ├── 📄 api
│   │   ├── 📄 stripe.js     # Stripe Payment API
│   │   ├── 📄 sanity.js     # Sanity CMS API
├── 📁 components
│   ├── 📄 Navbar.js         # Navigation Bar
│   ├── 📄 ProductCard.js    # Product Display
│   ├── 📄 Cart.js           # Shopping Cart
├── 📁 lib
│   ├── 📄 sanity.js         # Sanity Client Config
│   ├── 📄 stripe.js         # Stripe SDK Setup
├── 📁 sanity                # Sanity Studio CMS Setup
├── 📄 .env.local            # Environment Variables
└── 📄 README.md             # Project Documentation
```

## 🔧 Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/inegohe/e-commerce.git
   cd e-commerce
   ```

2. **Install dependencies:**
   ```sh
   npm install  # or yarn install
   ```

3. **Set up environment variables:**
   Create a `.env.local` file in the root directory and add:
   ```env
   NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
   NEXT_PUBLIC_SANITY_DATASET=production
   STRIPE_SECRET_KEY=your_stripe_secret_key
   STRIPE_PUBLIC_KEY=your_stripe_public_key
   ```

4. **Run Sanity Studio (CMS):**
   ```sh
   cd sanity_ecommerce && sanity start
   ```

5. **Run the development server:**
   ```sh
   npm run dev  # or yarn dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🚀 Deployment
You can deploy this project on **Vercel** (recommended) or any hosting provider that supports Next.js. For Sanity Studio, deploy it using **Sanity Hosting**.

## 📸 Screenshots
| Home Page | Product Page | Checkout |
|-----------|-------------|----------|
| ![Home](https://private-user-images.githubusercontent.com/161653709/421234496-7b2335cb-41d3-487d-9fad-60f38598df8c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE2Nzc0MjEsIm5iZiI6MTc0MTY3NzEyMSwicGF0aCI6Ii8xNjE2NTM3MDkvNDIxMjM0NDk2LTdiMjMzNWNiLTQxZDMtNDg3ZC05ZmFkLTYwZjM4NTk4ZGY4Yy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzExJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMxMVQwNzEyMDFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03ZGZjYjg5YzMwOGUxMmQ0Y2NjNTE0OTcyMDRhZDBmMzIwODQ2ZGZhMDNhY2QwNmI0MWZmMDhhMDA3ZDkzZGI3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.OlP98V-AQRr9zwFqtjBwdbIab4D1FNE7e-9uExxoPhI) | ![Product](https://private-user-images.githubusercontent.com/161653709/421234495-7e0fcfa2-0f53-45f1-a9e3-591fb3135e78.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE2Nzc0MjEsIm5iZiI6MTc0MTY3NzEyMSwicGF0aCI6Ii8xNjE2NTM3MDkvNDIxMjM0NDk1LTdlMGZjZmEyLTBmNTMtNDVmMS1hOWUzLTU5MWZiMzEzNWU3OC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzExJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMxMVQwNzEyMDFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hNzQ2MWNmZDY5NGQ0YzllMWQ4NDU2ZjBhYmFiZDJmY2M5NGEyM2YwZmYxOGUyNzE1MjBhMTBhYjEwY2M1OTFiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.OB3xdr3YbwsKlbb9SQLyMf7oXChWZzbV18sAO2uN57A) | ![Checkout](https://private-user-images.githubusercontent.com/161653709/421234497-9cb7ca1f-f1fa-4f45-95d5-854b5013f1c1.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE2Nzc0MjEsIm5iZiI6MTc0MTY3NzEyMSwicGF0aCI6Ii8xNjE2NTM3MDkvNDIxMjM0NDk3LTljYjdjYTFmLWYxZmEtNGY0NS05NWQ1LTg1NGI1MDEzZjFjMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzExJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMxMVQwNzEyMDFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jOTQ3OWRhZjY4YmM0YjcyNmQyYTk0YzhlYmI1YTg5NzRhNmUxNGY5ZjI2ODA3MmQ0MzgzZTA4MzU1MDk3NTE1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.1QXPVBx6Hlr4l9PnMSFdUxOSODsOTtWXdKYAS-85dg4) |

## 💡 Future Improvements
- 🔹 User authentication & order history
- 🔹 Wishlist feature
- 🔹 Admin dashboard for managing products
- 🔹 Advanced filtering & search functionality

## 🤝 Contributing
Feel free to fork this repository, submit issues, or create pull requests to enhance the project.

## 📜 License
This project is licensed under the **MIT License**.

---
⭐ If you like this project, give it a **star** on GitHub!

