# AfLink-Sino - The Ultimate China-Africa Trade Bridge 🌍🚢

## Overview
AfLink-Sino is a B2B & C2B eCommerce platform designed to simplify the sourcing, purchasing, and delivery of goods from China to Africa. We connect African businesses and individuals with trusted Chinese suppliers, ensuring affordable, fast, and secure transactions.

This platform is built using modern technologies to deliver a flexible, scalable, and seamless cross-border trade experience.

## 🚀 Tech Stack
AfLink-Sino is built with the following core technologies:

### Frontend:
- **Angular**: A powerful and dynamic JavaScript framework used for building the user-facing part of the platform. Angular handles routing, user interactions, and integrates with the backend to provide real-time data and functionality (like product listings, shipment tracking, etc.).

### Backend:
- **Strapi (Headless CMS)**: We use Strapi as a headless CMS to manage the platform's data, including product catalogs, user data, and transactional information. Strapi offers flexibility by allowing us to serve content to different frontends (e.g., mobile, web).

### Database:
- **PostgreSQL**: A robust relational database for storing transactional data, user information, and other critical system data. PostgreSQL ensures data integrity and scalability.

### Authentication:
- **JWT (JSON Web Tokens)**: Secure user authentication and authorization via JWT, ensuring only authorized users (buyers, sellers, admins) can access their respective functionalities.

### Payment Integration:
- **Stripe / PayPal**: Integration with Stripe and PayPal for secure, reliable payment processing.

### Cloud & Deployment:
- **Docker**: Containerization of both backend and frontend services for easy and consistent deployment across different environments.
- **AWS / Azure** (or any other preferred cloud service for deployment).

## 🛠 Development Setup

### Prerequisites
- Node.js (Recommended version: 14.x or higher)
- NPM (Node Package Manager)
- Docker (for containerized environments)
- PostgreSQL (for local development, if needed)

### Clone the Repository
```bash
git clone https://github.com/aflink-sino/aflink-sino.git
cd aflink-sino
```

## Backend Setup (Strapi)
Navigate to the backend directory:
```bash
cd backend
```
Install dependencies:
```bash
npm install
```
Set up environment variables by copying the `.env.example` file:
```bash
cp .env.example .env
```
Run the Strapi server locally:
```bash
npm run develop
```
This will start the Strapi backend on [http://localhost:1337](http://localhost:1337).

## Frontend Setup (Angular)
Navigate to the frontend directory:
```bash
cd frontend
```
Install dependencies:
```bash
npm install
```
Start the Angular development server:
```bash
ng serve
```
The app will be available at [http://localhost:4200](http://localhost:4200).

## 🧪 API Endpoints (Strapi)

### Products:
- `GET /products` – Fetch a list of all products.
- `POST /products` – Add a new product (admin only).
- `GET /products/:id` – Fetch product details by ID.

### Orders:
- `POST /orders` – Create a new order.
- `GET /orders` – Fetch all orders (admin only).
- `GET /orders/:id` – Fetch order details by ID.

### Users:
- `POST /auth/local` – User login with credentials (email & password).
- `POST /auth/local/register` – Register a new user.

## 🔧 Customization & Extensions

### Customizing Strapi
You can extend Strapi’s default features by adding plugins or creating custom controllers, services, and routes. The Strapi documentation provides detailed instructions for building and extending the backend: [Strapi Documentation](https://strapi.io/documentation).

### Frontend Customization
The Angular frontend is highly customizable. You can modify the following components:
- **Product Listings**: Customize how products are displayed, including filters, categories, and layouts.
- **User Authentication**: Modify the login and registration process based on business needs.

## 💡 Contributing
We welcome contributions! If you want to contribute to the project, please fork the repository, create a new branch, and submit a pull request.

### Steps:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Write tests (if applicable).
4. Run the tests to make sure everything is working.
5. Submit a pull request to the main repository.

## 📞 Contact Us
If you need help or have any questions, feel free to contact us:

- **Mainadev** - [0729301689]
- **Email**: contact@aflink-sino.com

---
This README should help developers get started quickly with both the frontend and backend of AfLink-Sino. Let me know if you need further changes or clarifications!
