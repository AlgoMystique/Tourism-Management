# Tourism Management System  
**Bachelor of IT- ICT272 – Web Design and Development**  
**Technology: ASP.NET MVC**

## 📖 Overview

This project is a Tourism Management System developed using the **ASP.NET MVC** framework as part of the ICT272 unit. It enables users to explore, book, and manage tourism experiences while offering admin-level control for managing destinations, packages, and users.

The application demonstrates key web development concepts including:
- MVC architecture
- CRUD operations
- Database integration with Entity Framework
- Razor views
- Form validation
- Responsive web design using Bootstrap

---

## 🚀 Features

### 🧑‍💼 User Functionality
- Browse tourism destinations and packages
- View detailed descriptions, images, and pricing
- Make and manage bookings
- User registration and login
- Responsive layout for mobile and desktop

### 🛠 Admin Functionality
- Admin login dashboard
- Add/Edit/Delete destinations and travel packages
- View customer bookings
- Manage user data

---

## 🛠 Technologies Used

- **ASP.NET MVC (C#)**
- **Entity Framework**
- **SQL Server** (or LocalDB)
- **Razor View Engine**
- **Bootstrap 5**
- **HTML/CSS/JavaScript**

---

## 📁 Project Structure

```
/TourismManagement/
│
├── Controllers/ # MVC Controllers
├── Models/ # Data Models
├── Views/ # Razor Views for each feature
├── App_Data/ # Database files (if using LocalDB)
├── Scripts/ # JS and jQuery files
├── Content/ # CSS and image assets
├── App_Start/ # Route config and filters
└── Web.config # Configuration file
```

---

## 🧪 Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/tourism-management.git
   ```
  
2. **Open the solution in Visual Studio**
   
Open the .sln file using Visual Studio 2022 or newer.

3.**Restore NuGet Packages**

```
Tools > NuGet Package Manager > Package Manager Console
```
Then run:
```
Update-Package -reinstall
```

4.**Configure the database:**

-Use SQL Server Express or LocalDB.

-Update the Web.config connection string if needed.

-Enable Migrations and run:
```
Update-Database
```

5.**Run the project:**

Press F5 or click on Start Debugging.

## 👨‍💻 Authors

Sababa T – Developer / UI Designer

## 📝 License

This project is for academic use only. 


