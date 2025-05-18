# OnlineBankingSystem

# 💳 Online Banking System

An end-to-end online banking system built using Spring Boot, Thymeleaf, and MySQL. The application supports multiple user roles — **Customer**, **Accountant**, **Manager**, and **Admin** — with functionalities for account management, transactions, and secure access control.

## 🚀 Technologies Used

- **Backend:** Java, Spring Boot  
- **Frontend:** Thymeleaf  
- **Database:** MySQL  
- **Deployment:** Docker, Render (Backend), AWS RDS (Database)  
- **Development:** IntelliJ IDEA  
- **Version Control:** Git, GitHub  

## 👥 User Roles & Functionalities

### Customer
- Sign up (status: pending, accountId: pending)
- Login & view profile
- View account summary & transaction history
- Transfer funds

### Accountant
- Approve new customer accounts  
- Deposit/Withdraw funds on customer behalf  
- View profiles, accounts, and transactions of all users  

### Manager
- Approve customers and accountant registrations  
- Perform deposits/withdrawals  
- View all profiles and transactions  
- Close customer accounts

### Admin
- Approve all types of user accounts (Customer, Accountant, Manager)  
- Perform deposits/withdrawals  
- View all user data  
- Close customer accounts

## 🧠 System Features

### OLTP (Online Transaction Processing)
- **Create:** Register users, add accounts, record transactions  
- **Read:** View user data, transaction history, account summary  
- **Update:** Modify account balances, approve users  
- **Delete:** Close and delete user accounts and their data  

### OLAP (Online Analytical Processing)
- Transaction summaries and reports  
- Role-based aggregated views  
- Drill-down into user activity and account stats

## 📦 Installation & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/online-banking-system.git
   cd online-banking-system

📌 Contributors

Sai Manoj Karanam – Grad @ Purdue

Renee Suresh Manukonda - Grad @ Purdue 

