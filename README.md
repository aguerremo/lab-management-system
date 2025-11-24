# Laboratory Management System – Angular

A web application designed for the internal management of a clinical laboratory.  
This project was developed as a **team collaboration** during my Web Application Development (DAW) internship.

The system includes modules for managing samples, inventory, and internal users, using **Angular** on the frontend and **Supabase** for authentication and database services.

> 💡 This repository is a fork of the original team project and focuses on showcasing my individual contributions and the overall architecture of the application.

---

## 🚀 Main Features

- 🔐 User authentication via Supabase  
- 🧪 Sample management (full CRUD: create, read, update, delete)  
- 📦 Inventory and laboratory material management  
- 👥 User management (roles, records, profiles)  
- 📄 Reactive forms with validation  
- 🔄 Angular services for communicating with Supabase  
- 📊 Modular structure with clean separation of features  

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Framework** | Angular 17+ |
| **Language** | TypeScript |
| **UI / Styling** | Angular Material, CSS, Font Awesome |
| **Backend / BaaS** | Supabase (Auth + Database) |
| **Tools** | Git, GitHub, Angular CLI |

---

## 🧩 Project Architecture

```txt
src/
 ├─ app/
 │   ├─ core/           # Shared services, guards, interceptors
 │   ├─ modules/        # Functional modules: samples, inventory, users...
 │   ├─ shared/         # Reusable components
 │   ├─ app-routing/    # Global routing configuration
 │   └─ app.component.* # Root component
 ├─ assets/             # Static resources
 └─ environments/       # Environment configuration (dev/prod)

## ▶️ Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/aguerremo/lab-management-system.git
cd lab-management-system
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
ng serve
```

The application will be available at:  
👉 `http://localhost:4200/`

---

## 🔑 Supabase Environment Variables

To connect the project with your own Supabase instance, create a file:

```
src/environments/environment.ts
```

With the following content:

```ts
export const environment = {
  production: false,
  supabaseUrl: "YOUR_SUPABASE_URL",
  supabaseKey: "YOUR_PUBLIC_API_KEY"
};
```

> ❗ Environment variables are not included in this repository for security reasons.

---

## 👤 My Role in the Project

Although this was a team project, my main contributions included:

- Development of Angular components (views, forms, UI logic)  
- Implementation of **reactive forms** with custom validations  
- Integration with Supabase (fetching data, writing data, authentication flows)  
- Refactoring and building shared services  
- Version control workflows: branches, commits, conflict resolution  

---

## 🎯 Key Learnings

- Real-world architecture for Angular applications  
- Advanced routing, guards, modules, and service structure  
- Frontend integration with modern BaaS solutions (Supabase)  
- Collaborative development using Git and GitHub  
- TypeScript best practices within Angular  

---

## 📌 Project Status

This repository reflects the version I worked on during my internship.  
The original project continues evolving in the main team repository.

---

