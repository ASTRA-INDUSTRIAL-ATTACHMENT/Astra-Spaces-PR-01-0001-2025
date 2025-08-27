For the readme 
# Astra Spaces – Rental Management System

Astra Spaces is a rental management platform that enables landlords to manage properties, assign tenants, track rent payments, and allow tenants to interact via *USSD* and *M-Pesa STK Push*.

---

## 🚀 Features
- Landlord & tenant role management
- Property & unit assignment
- Rent payments via *M-Pesa STK Push* (Daraja API)
- USSD access for tenants via *Africa’s Talking*
- Arrears tracking & reporting
- Hosted deployment (InfinityFree / Hostinger)

---

## 🛠 Tech Stack
- *Backend*: Laravel-PHP
- *Database*: MySQL (v5.7+)
- *Payment API*: Safaricom Daraja API
- *USSD API*: Africa’s Talking
- *Hosting*: InfinityFree / Hostinger

---

## 📦 Installation & Setup

### Requirements
-composer
-laravel framework
- PHP 
- MySQL 5.7+
- Git
- Hosting account or XAMPP/Laragon

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ASTRA-INDUSTRIAL-ATTACHMENT/Astra-Spaces-PR-01-0001-2025.git
   cd Astra-Spaces-PR-01-0001-2025
2. **Install PHP dependencies**
   ```bash
   composer install
   ```
3. **Install Node.js dependencies**
   ```bash
   npm install
   ```
4. **Environment setup**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```    
5. Configure database in .env
   ```bash
   '.env'
   ```
6.  **Run migrations and seeders**
   ```bash
   php artisan migrate --seed
   ```
7. **Compile assets**
   ```bash
   npm run dev
   ```
8. **Start the development server**
   ```bash
   php artisan serve
   ```



