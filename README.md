# MyFood - Food Bank Distribution App

A comprehensive web-based application designed to streamline food bank operations and connect donors, recipients, distributors, and administrators in an efficient food distribution ecosystem.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [User Roles](#user-roles)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Development Team](#development-team)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## 🌟 Overview

MyFood is a Food Bank Distribution App developed to address the inefficiencies in traditional food bank systems, especially during challenging times like the COVID-19 pandemic. The application facilitates seamless communication between those in need and those willing to help, while providing comprehensive management tools for food bank operations.

### Problem Statement

With increasing financial difficulties and the rise of movements like "Bendera Putih" in Malaysia, there's a growing need for efficient food distribution systems. Traditional food banks face challenges with:
- Inventory management
- Location services
- Volunteer coordination
- Communication between stakeholders

### Solution

MyFood provides a digital platform that:
- Enables instant communication between users
- Provides real-time inventory updates
- Facilitates volunteer coordination
- Shares news about charity events and food waste tips

## ✨ Features

### Core Functionality
- **Multi-role User Management**: Support for Donors, Recipients, Distributors, and Administrators
- **Real-time Food Inventory**: Track available and reserved food items
- **Location Services**: Find nearby food banks and distribution centers
- **Donation Management**: Handle both food and monetary donations
- **Reservation System**: Allow recipients to reserve food items
- **Community Feed**: Share tips, news, and updates about food waste and charity events
- **Delivery Tracking**: Monitor food distribution status in real-time

### Security Features
- User authentication and authorization
- Role-based access control
- Secure data management

## 👥 User Roles

### 1. Donor
- **Sign up/Login**: Create and access donor accounts
- **Profile Management**: View and edit personal information
- **Food Donation**: Donate various types of non-perishable foods
- **Money Donation**: Make monetary contributions to food banks
- **Donation History**: Track all previous donations
- **Stock Monitoring**: View foods that are low on stock
- **Location Services**: Find nearby food bank locations

### 2. Recipient
- **Account Management**: Sign up, login, and manage profiles
- **Food Menu**: Browse available food items
- **Reservation System**: Reserve and cancel food reservations
- **Community Engagement**: Access community feed and news
- **Support Services**: Contact administration for assistance

### 3. Distributor (Rider)
- **Profile Management**: Manage distributor account and information
- **Location Services**: Search for nearby food bank locations
- **Delivery Management**: Check status of reserved food, pick up and drop off items
- **Status Tracking**: Monitor delivery progress and estimated times

### 4. Administrator
- **User Management**: Add, edit, delete, and find users across all roles
- **Food Bank Reports**: Manage food bank reporting and analytics
- **Location Management**: Control distribution locations
- **Category Management**: Manage food categories and classifications
- **System Oversight**: Complete administrative control over the platform

## 🛠 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Bootstrap 4.4.1
- **Architecture**: Multi-tier web application
- **Development Model**: Waterfall methodology
- **Design Patterns**: MVC (Model-View-Controller)

## 📁 Project Structure

```
Food-Bank-Distribution-App/
├── Project 1/                          # Requirements and Documentation
│   ├── MyWork.docx
│   ├── Part1-Group15-TT1v.pdf
│   ├── Description/                     # Project guidelines and templates
│   └── References/                      # Reference materials
├── Project 2/                          # System Design
│   ├── Part2-Group15-SectionTT1V.pdf
│   ├── SD-template-2110.docx
│   └── References/
├── Project 3/                          # Implementation and Final Report
│   ├── Final Report.pdf
│   ├── Code/
│   │   ├── DonorPages/                 # Donor interface
│   │   │   └── DonorPages/
│   │   │       ├── Index.html          # Donor profile page
│   │   │       ├── donateMoney.html
│   │   │       ├── donHistory.html
│   │   │       ├── location.html
│   │   │       ├── login.html
│   │   │       ├── viewFood.html
│   │   │       ├── css/                # Styling files
│   │   │       ├── images/             # Image assets
│   │   │       └── js/                 # JavaScript files
│   │   ├── RecipientPages/             # Recipient interface
│   │   │   └── RecipientPages/
│   │   │       ├── homePage.html
│   │   │       ├── foodMenu.html
│   │   │       ├── reservedFood.html
│   │   │       ├── communityNews.html
│   │   │       ├── Contact Us.html
│   │   │       └── images/
│   │   ├── Distributor/                # Distributor interface
│   │   │   └── Distributor/
│   │   │       ├── Edit _ View Profile/
│   │   │       └── Sign up _ Login/
│   │   └── FoodBankAdmin/              # Admin interface
│   │       └── FoodBank/
│   │           ├── index.html          # Admin login
│   │           ├── admin_menu.html
│   │           ├── users_control.html
│   │           ├── categories_control.html
│   │           ├── distloc_control.html
│   │           ├── report_control.html
│   │           ├── assets/             # Admin assets
│   │           └── scripts/            # Admin scripts
│   └── References/                     # Development references
└── README.md
```

## 🚀 Installation

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Food-Bank-Distribution-App.git
   cd Food-Bank-Distribution-App
   ```

2. **Navigate to the desired user interface**
   ```bash
   # For Donor interface
   cd "Project 3/Code/DonorPages/DonorPages"
   
   # For Recipient interface
   cd "Project 3/Code/RecipientPages/RecipientPages"
   
   # For Distributor interface
   cd "Project 3/Code/Distributor/Distributor"
   
   # For Admin interface
   cd "Project 3/Code/FoodBankAdmin/FoodBank"
   ```

3. **Open the application**
   - Open the respective `index.html` or main HTML file in your web browser
   - For development, use a local server like Live Server (VS Code extension)

### Test Accounts

Use these test accounts for demonstration:

**Donor Account:**
- Username: JD101
- Password: 12345
- Name: John Doe

**Admin Account:**
- Username: AG908
- Password: abc123
- Name: Aaron Gomez

**Distributor Account:**
- Username: LK462
- Password: 12345
- Name: Long Kang

**Recipient Account:**
- Username: MA628
- Password: abc000
- Name: Mohd Afiq

## 📖 Usage

### For Donors
1. Access the donor interface through `DonorPages/DonorPages/login.html`
2. Login with donor credentials
3. Navigate through the menu to:
   - Donate food or money
   - View donation history
   - Check food stock levels
   - Find nearby food banks

### For Recipients
1. Access the recipient interface through `RecipientPages/RecipientPages/homePage.html`
2. Login with recipient credentials
3. Use the platform to:
   - Browse available food menu
   - Reserve food items
   - Access community news and tips
   - Contact support services

### For Distributors
1. Access the distributor interface
2. Login with distributor credentials
3. Manage deliveries by:
   - Searching nearby food banks
   - Checking reserved food status
   - Managing pickup and delivery

### For Administrators
1. Access the admin interface through `FoodBankAdmin/FoodBank/index.html`
2. Login with admin credentials
3. Manage the system:
   - Control user accounts
   - Manage food categories
   - Oversee distribution locations
   - Generate reports

## 📱 Screenshots

The application includes comprehensive user interfaces for all user roles:
- Responsive design with Bootstrap framework
- Intuitive navigation and user-friendly forms
- Real-time status updates and notifications
- Mobile-friendly interface design

## 👨‍💻 Development Team

**Group 15 - Section TT1V**

| Name | Student ID | Role |
|------|------------|------|
| Avinash Imanuel A/L Gana Raj Imanuel | 1181103370 | Donor Module |
| Kishen Kumar A/L Sivalingam | 1191101423 | Recipient Module |
| Narvenesh A/L Gevaratnam | 1181103203 | Distributor Module |
| Sheikh Naimullah Bin Sh Mohd Aminllah | 1201301338 | Admin Module |

**Course:** TSE2101 - Software Engineering Fundamentals  
**Institution:** [University Name]  
**Completion Date:** November 22, 2021

## 📚 Documentation

Comprehensive documentation is available in the project:

- **Final Report**: `Project 3/Final Report.pdf` - Complete system documentation
- **Requirements**: `Project 1/` - System requirements and specifications
- **Design Documents**: `Project 2/` - System design and architecture
- **User Guide**: Included in the final report
- **Technical Specifications**: Class diagrams, sequence diagrams, and component designs

### Key Documentation Sections
- System Overview and Use Cases
- Architecture Design
- Interface Design
- Component Design
- Testing Results
- Deployment Guidelines

## 🤝 Contributing

This project was developed as part of an academic assignment. For educational purposes:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is developed for educational purposes as part of the TSE2101 Software Engineering Fundamentals course.

## 📞 Contact

**MyFood Support**
- Email: MY.Food@gmail.com
- Phone: +603 2456-7890
- Address: Jalan Washington Temeloh, 49000 Johor, Malaysia

---

**Note**: This is an academic project developed for learning purposes. The application demonstrates software engineering principles and web development practices in the context of food bank management systems.
