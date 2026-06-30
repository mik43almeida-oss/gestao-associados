# Gestão de Associados

Professional Association Management System built with Node.js, TypeScript, and Clean Architecture.

## 🚀 Features

- 🔐 Complete Authentication (JWT, Refresh Tokens, Password Recovery)
- 👥 Member Management (CRUD, Search, Filters, Import/Export)
- 💳 Payment Processing (Multiple Methods, Receipts, Invoices)
- 📊 Real-time Dashboard (Analytics, Charts, Alerts)
- 📧 Email Notifications (Nodemailer, HTML Templates)
- 📄 PDF Generation (Receipts, Reports, Documents)
- 🎯 Role-Based Access Control (RBAC)
- 📝 Comprehensive Audit Logging
- 🔒 Enterprise-Grade Security (Helmet, XSS, SQL Injection Protection)
- 📱 PWA Ready
- 🎨 Modern UI with Dark/Light Mode
- 📊 DataTables, Charts, and Advanced Search

## 🛠️ Tech Stack

### Backend
- Node.js LTS
- TypeScript
- Express.js
- Prisma ORM
- PostgreSQL via Supabase
- JWT Authentication
- Winston Logger
- Nodemailer
- PDFKit & ExcelJS

### Frontend
- HTML5/CSS3/Bootstrap 5
- JavaScript ES2023
- DataTables & Chart.js
- SweetAlert2 & Toastify
- Font Awesome

### DevOps
- Docker & Docker Compose
- GitHub Actions
- ESLint & Prettier
- Husky & Commitlint

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/yourusername/gestao-associados.git

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env
# Edit .env with your configuration

# Setup database
npx prisma migrate dev
npx prisma generate
npm run prisma:seed

# Start development server
npm run dev
