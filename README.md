# BtkAkademi - Course Application System

A modern, responsive ASP.NET Core MVC web application designed for managing course applications. This project provides a streamlined interface for candidates to apply for various courses and for administrators to view submitted applications.

## 🚀 Key Features

- **Course Listing**: Browse available educational opportunities.
- **Dynamic Application Form**: Robust form with real-time validation for candidate details (Name, Email, Age, etc.).
- **Application Tracking**: View and manage all submitted course applications in a structured list.
- **Duplicate Prevention**: System-level check to prevent multiple applications from the same email address.
- **User Feedback**: Instant confirmation upon successful application submission.

## 🛠 Tech Stack

- **Backend**: ASP.NET Core 9.0 (MVC Pattern)
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Bootstrap 5
- **Data Persistence**: In-memory repository (Static List)
- **Language**: C#

## 📁 Project Structure

```text
BtkAkademi/
├── Controllers/      # Application logic (Home, Course)
├── Models/           # Data structures and Repository
├── Views/            # Razor view templates
│   ├── Course/       # Application and Index views
│   ├── Home/         # Landing pages
│   └── Shared/       # Layouts and shared components
├── wwwroot/          # Static assets (CSS, JS, Libs)
├── Program.cs        # App configuration and entry point
└── BtkAkademi.sln     # Solution file
```

## 🏁 Getting Started

### Prerequisites

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
- Visual Studio 2022 or Visual Studio Code

### Installation & Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/BtkAkademi.git
   cd BtkAkademi
   ```

2. **Restore dependencies**:
   ```bash
   dotnet restore
   ```

3. **Run the application**:
   ```bash
   dotnet run
   ```

4. **Access the app**:
   Open your browser and navigate to `https://localhost:5001` (or the port shown in your terminal).

## 📸 Preview

*(Coming Soon - Screenshots of the Home and Application pages)*

---
Developed as part of the BtkAkademi training.
