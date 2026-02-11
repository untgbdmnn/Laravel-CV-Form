<div align="center">

# 🧑‍💼 Laravel CV Builder

**Build Professional CVs with Ease**

A modern, full-featured CV generator built with Laravel 11 that enables users to create, edit, and download professional resumes.

![Laravel](https://img.shields.io/badge/Laravel-11.x-FF2D20?style=flat-square&logo=laravel)
![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?style=flat-square&logo=php)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=flat-square&logo=bootstrap)

</div>

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Hashtags](#hashtags)

---

## 📖 About the Project

**Laravel CV Builder** is a web application designed to simplify the CV creation process. This project provides an intuitive interface for users to input their personal information, skills, education, and work experience, then generate a professional-looking CV.

The application is built using **Laravel 11**, leveraging modern PHP features and following Laravel best practices. It includes form validation, image handling, and a clean, responsive UI.

---

## ✨ Features

### 🔹 Core Functionality
- **📝 Comprehensive Input Form** - Collect all essential CV information
- **📷 Photo Upload** - Profile picture with image preview and validation
- **✏️ edit_file Existing CVs** - Update any previously created CV
- **👁️ Download/View CV** - Generate and view the final CV

### 🔹 CV Sections
- **Basic Information** - Name, title, email, phone, address
- **About/Bio** - Personal biography and professional summary
- **Skills** - Add multiple skills with proficiency level sliders (0-100%)
- **Education** - Multiple education entries with institution, year, and details
- **Experience** - Work experience with position, company, year, and description

### 🔹 Technical Features
- **Form Validation** - Server-side validation using Laravel validation rules
- **Image Processing** - Image upload handling with file type and size validation
- **Responsive Design** - Mobile-friendly interface using Bootstrap 5
- **Dynamic Form Fields** - Add/remove skills, education, and experience entries
- **Flash Messages** - Success notifications for data operations

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| **Backend** | Laravel 11, PHP 8.2 |
| **Frontend** | Blade Templates, Bootstrap 5 |
| **Styling** | Custom CSS, Bootstrap Icons |
| **Database** | MySQL (via Laravel Eloquent ORM) |
| **Image Handling** | Intervention Image |
| **JavaScript** | Vanilla JS for dynamic form handling |
| **Version Control** | Git |

---

## 🚀 Getting Started

### Prerequisites
- PHP 8.2 or higher
- Composer
- Laravel 11.x
- Node.js & NPM (for asset compilation)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Laravel-CV-Form
   ```

2. **Install dependencies**
   ```bash
   composer install
   npm install
   ```

3. **Configure environment**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Run migrations**
   ```bash
   php artisan migrate
   ```

5. **Start the development server**
   ```bash
   php artisan serve
   ```

---

## 📁 Project Structure

```
Laravel-CV-Form/
├── app/
│   ├── Http/
│   │   └── Controllers/
│   │       └── InsertDataController.php    # Main controller for CV operations
│   └── Models/
│       ├── InformasiDasar.php              # Basic information model
│       ├── TentangSaya.php                 # About/Bio model
│       ├── Keahlian.php                     # Skills model
│       ├── Pendidikan.php                   # Education model
│       └── Pengalaman.php                   # Experience model
├── database/
│   └── migrations/                          # Database schema
├── resources/
│   ├── views/
│   │   ├── input.blade.php                  # CV input form
│   │   ├── edit.blade.php                   # edit_file existing CV
│   │   ├── download.blade.php               # View/Download CV
│   │   └── layouts/                         # Layout templates
├── public/
│   ├── css/                                 # Stylesheets
│   ├── js/                                  # JavaScript files
│   └── pictures/                            # Uploaded images
└── routes/
    └── web.php                              # Application routes
```

---

## 📝 Usage

1. **Create a New CV**
   - Navigate to the homepage
   - Fill in all required fields (basic info, bio, skills, education, experience)
   - Upload a profile photo
   - Click "Buat CV" to generate

2. **Edit an Existing CV**
   - Access the edit page for any CV
   - Modify any section as needed
   - Submit changes

3. **View/Download CV**
   - After creation, view the formatted CV
   - Print or save as PDF

---

## #️⃣ Hashtags

```
#Laravel #Laravel11 #PHP #PHP82 #WebDevelopment #CVBuilder 
#ResumeBuilder #WebApp #FullStack #Bootstrap #BladeTemplates
#EloquentORM #MySQL #Portfolio #JobSearch #CareerDevelopment
#WebDeveloper #SoftwareEngineer #Programming #Coding #Developer
#Tech #Indonesia #Opensource #MITLicense #LearnToCode
```

---

<div align="center">

**Built with ❤️ using Laravel**

</div>

