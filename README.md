# 🛡️ Insurance Platform

A dynamic, user-centric insurance platform for both customers and insurance companies. This platform enables customers to calculate their **prominence score**, receive personalized policy recommendations, and purchase insurance policies. Meanwhile, insurance companies can manage policies, track sales, and gain insights into customer behavior.

---

## ✨ Features

### 👤 For Customers
- 🔐 **User Authentication**: Secure login and registration
- 📊 **Prominence Calculation**: Calculate your score based on personal and financial details
- 🧠 **Policy Recommendations**: Personalized suggestions based on your prominence score
- 💬 **Chatbot Assistance**: Ask questions and get help with policies
- 🛍️ **Policy Purchase**: Buy insurance with multiple payment methods
- 📈 **Activity Tracking**: View actions, transactions, and history
- 🧾 **User Dashboard**: Access active policies, scores, and recent activity

### 🏢 For Insurance Companies
- 🔐 **Company Authentication**: Secure login for providers
- 🛠️ **Policy Management**: Create, edit, and remove insurance products
- 📂 **Customer Insights**: Analyze policyholder data and trends
- 📊 **Sales Analytics**: Monitor revenue and distribution metrics
- 📋 **Company Dashboard**: Visual stats and management tools

---

## 🛠️ Tech Stack

### 🌐 Frontend
- **React** – UI Library
- **TypeScript** – Type-safe JavaScript
- **Tailwind CSS** – Utility-first styling
- **React Router** – Routing and navigation
- **Shadcn UI** – Beautiful component library
- **React Query** – Server-state management
- **React Hook Form + Zod** – Form handling & validation

### 🔧 Backend
- **Node.js + Express** – RESTful API backend
- **MongoDB + Mongoose** – NoSQL database and ODM
- **JWT** – JSON Web Token authentication
- **bcrypt** – Secure password hashing

---

## 📁 Project Structure

```plaintext
insurance/
├── frontend/               # React frontend
│   ├── components/         # UI components
│   ├── pages/              # Route pages
│   ├── hooks/              # Custom hooks
│   ├── context/            # Global state/context
│   └── assets/             # Images, logos, icons
├── backend/                # Node.js API
│   ├── models/             # Mongoose schemas
│   ├── routes/             # REST API endpoints
│   ├── services/           # Business logic
│   └── utils/              # Helper utilities
└── shared/                 # Shared logic across frontend/backend
    └── types/              # TypeScript interfaces and types
