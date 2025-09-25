 # 🏠 Rental Management System

<div align="center">
  <img src="docs/images/astra-spaces-banner.png" alt="Astra Spaces Banner" width="500"/>
</div>

<p align="center">
  <strong>Astra Spaces</strong> is a comprehensive rental management platform that enables landlords to manage properties, assign tenants, track rent payments, and allow tenants to interact via <em>USSD</em> and <em>M-Pesa STK Push</em>.
</p>

<div align="center">
  
  ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
  ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
  ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  
</div>

---

## 🚀 📱 Key Features Screenshots

### 🏢 Landlord Dashboard
<div align="center">
  <img src="docs/images/landlord-dashboard.png" alt="Landlord Dashboard" width="700"/>
  <p><em>Complete landlord management interface with property overview, tenant management, and financial tracking</em></p>
</div>

### 👤 Tenant Dashboard  
<div align="center">
  <img src="docs/images/tenant-dashboard.png" alt="Tenant Dashboard" width="700"/>
  <p><em>User-friendly tenant portal for rent payments, maintenance requests, and communication</em></p>
</div>

### 🏠 Property & Unit Assignment
<div align="center">
  <img src="docs/images/property-unit-assignment.png" alt="Property and Unit Assignment" width="700"/>
  <p><em>Efficient property management with unit allocation and tenant assignment system</em></p>
</div>

### 💳 M-Pesa STK Push Integration
<div align="center">
  <img src="docs/images/mpesa-stk-push.png" alt="M-Pesa STK Push Payment" width="700"/>
  <p><em>Seamless rent collection through Safaricom's M-Pesa STK Push API</em></p>
</div>

### 📱 Africa's Talking USSD
<div align="center">
  <img src="docs/images/africas-talking-ussd.png" alt="Africa's Talking USSD Interface" width="700"/>
  <p><em>USSD-based tenant interaction for rent payments and account management</em></p>
</div>

---

## 🛠 Tech Stack
- *Backend*: Laravel-PHP ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
- *Database*: MySQL (v5.7+) ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
- *Payment API*: Safaricom Daraja API ![Daraja](https://img.shields.io/badge/Daraja-FF2D20?style=for-the-badge&logo=daraja&logoColor=white)
- *USSD API*: Africa’s Talking ![Africa’s Talking](https://img.shields.io/badge/Africa’s Talking-FF2D20?style=for-the-badge&logo=africas-talking&logoColor=white)
- *Hosting*: InfinityFree / Hostinger ![InfinityFree](https://img.shields.io/badge/InfinityFree-FF2D20?style=for-the-badge&logo=infinityfree&logoColor=white)

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



