# UTAMarket

**AI-powered E-Commerce Website for UTA Students**

---

## 🚀 What is UTAMarket?

UTAMarket is a modern, AI-powered e-commerce platform designed for the University of Texas at Arlington (UTA) community. It enables students, faculty, and alumni to buy, sell, and discover official UTA merchandise, apparel, accessories, school supplies, and more. The platform leverages advanced recommendation systems and a robust, scalable architecture to deliver a seamless campus marketplace experience.

---

## 🏷️ Tags

`e-commerce` `nextjs` `react` `ai` `recommendation-system` `prisma` `mysql` `tailwindcss` `uta` `student-marketplace` `aws` `serverless` `express` `socketio`

---

## 🛠️ Tech Stack

- **Frontend:** Next.js 15, React 18, Tailwind CSS 4, Radix UI, Shadcn UI
- **Backend:** Node.js, Express, RESTful APIs, Socket.IO (real-time features)
- **Database:** MySQL (Amazon RDS), Prisma ORM
- **Authentication:** JWT, bcrypt
- **AI/ML:** Personalized product recommendations
- **Dev Tools:** TypeScript, ESLint, Prettier, PostCSS
- **Deployment:** AWS Amplify (Next.js), AWS Lambda (API), Amazon RDS (MySQL)
- **Other:** dotenv, CORS, Lucide Icons, Embla Carousel, Recharts

---

## ✨ Features

- **User Authentication & Profiles**: Secure signup/login, JWT-based sessions, profile management, password hashing
- **Product Listings**: Browse, search, and filter official UTA merchandise by category, size, color, price, and more
- **AI-Powered Recommendations**: Personalized product suggestions based on user interests and shopping history
- **Shopping Cart & Checkout**: Add/remove items, update quantities, apply coupons, and complete secure checkout with payment info
- **Wishlist**: Save favorite products for later, manage wishlist items
- **Order Management**: View order history, track status (processing, shipped, delivered, cancelled), order details
- **Admin Dashboard**: View platform stats (users, orders, revenue, products), manage recent orders, analytics
- **Category Browsing**: Shop by apparel, accessories, spirit gear, school supplies, gifts, and more
- **Featured Products & Sales**: Highlight best sellers, discounts, and trending items
- **User Reviews & Testimonials**: Carousel of student feedback and marketplace experiences
- **Responsive UI**: Mobile-first, accessible, and fast-loading design
- **Real-time Updates**: Socket.IO for live notifications and updates
- **Newsletter & Social Links**: Stay updated with the latest deals and campus news
- **Support & FAQ**: Contact forms, help center, and admin support
- **Secure & Scalable**: Serverless deployment, environment variable management, CORS, and secure API endpoints

---

## 📝 Implementation Notes

- **Monorepo Structure:**
  - `/app` - Next.js pages, API routes, and main UI flows
  - `/components` - Reusable UI components (cards, carousels, forms, etc.)
  - `/services` - Business logic (pricing, coupons, etc.)
  - `/database` - Prisma schema, DB connection logic
  - `/public` - Static assets
  - `/constants` - Shared constants (categories, options)
  - `/utils` - Utility functions
- **TypeScript:** Used throughout for type safety and maintainability
- **UI/UX:** Built with Radix UI, Shadcn UI, and Tailwind CSS for a modern, accessible interface
- **Dynamic Pricing:** ProductCard uses a pricing service to adjust prices based on season, demand, and inventory
- **Serverless Ready:** Next.js configured for serverless deployment; Express API can be packaged for AWS Lambda
- **Environment Variables:** Sensitive data managed via `.env` and AWS Amplify/Lambda environment settings
- **Testing:** (If present) Located in `/tests`

---

## ☁️ Deployment Notes

See `Deployment.md` for full AWS deployment instructions.

**Summary:**
- **Frontend:** Deploy Next.js app via AWS Amplify Hosting (CI/CD from GitHub)
- **Backend:** Package Express API for AWS Lambda, deploy behind API Gateway
- **Database:** Use Amazon RDS for MySQL, configure security groups and environment variables
- **Environment:** Set all DB and API endpoint variables in Amplify and Lambda
- **Serverless:** Next.js set to `serverless` target for Lambda compatibility
- **Monitoring:** Use AWS CloudWatch for logs and error tracking

---

## 📚 Useful Links

- [Deployment Guide](./Deployment.md)
- [FAQ](/faq)
- [Contact](/contact)
- [Terms of Service](/terms)
- [Privacy Policy](/privacy)

---

## 🧑‍💻 Contributing

Contributions are welcome! Please open issues or pull requests for improvements, bug fixes, or new features.

---

## © UTAMarket

The ultimate marketplace for UTA students. All rights reserved.
