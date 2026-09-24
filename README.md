# Furniro E-Commerce

A modern furniture e-commerce web application built with Next.js, TypeScript, and MongoDB. The project focuses on a clean shopping experience with product browsing, wishlist management, cart functionality, secure authentication, and an admin dashboard for store management.

## Project Overview

Furniro is a full-stack online furniture store inspired by premium home decor brands. It is designed to provide users with an intuitive shopping flow while giving administrators tools to manage products, orders, users, and contact messages.

## Key Features

- Responsive storefront for furniture products
- Product catalog with browsing and category-based filtering
- Add to cart and shopping cart flow
- Wishlist/favourites management
- User registration and login
- Role-based authentication with NextAuth
- Checkout and billing form
- Admin area for product, user, and order management
- Contact form for customer inquiries
- MongoDB-backed data storage

## Tech Stack

- Frontend: Next.js 15, React 19, TypeScript
- Styling: Tailwind CSS
- State Management: Redux Toolkit, Redux Persist
- Authentication: NextAuth with credentials login
- Database: MongoDB with Mongoose
- UI Enhancements: Framer Motion, Swiper, Lucide React

## Project Structure

```bash
src/
├── app/                 # App router pages and API routes
├── components/          # Reusable UI and page sections
├── lib/                 # DB connection and auth configuration
├── models/              # MongoDB schemas
├── middleware.ts        # Route middleware
└── redux/               # Redux slices and store setup
```

## Prerequisites

Before running this project, make sure you have:

- Node.js 18+
- npm or yarn
- MongoDB database

## Environment Variables

Create a `.env.local` file in the root directory and add the following variables:

```env
MONGO_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_secret_key
NEXTAUTH_URL=http://localhost:3000
```

## Installation

```bash
git clone https://github.com/your-username/furniro-e-commerce.git
cd furniro-e-commerce
npm install
```

## Run the Project

```bash
npm run dev
```

Then open:

```text
http://localhost:3000
```

## Available Scripts

```bash
npm run dev      # Start dev server
npm run build    # Production build
npm run start    # Start production server
npm run lint     # Run lint checks
```

## Admin Features

The application includes an admin panel for:

- Managing products
- Viewing registered users
- Monitoring orders
- Handling contact submissions

## Notes

This project is a practical full-stack e-commerce application built to demonstrate frontend design, backend integration, authentication, and database-driven workflows in a realistic commercial product context.

## License

This project is for educational and portfolio purposes.
