# ALX Listing App

## About the Project

The **ALX Listing App** is the foundation for a modern Airbnb clone, focusing on the initial scaffolding and setup for a property listing page. This project utilizes **Next.js**, **TypeScript**, **TailwindCSS**, and **ESLint** to ensure a scalable, maintainable, and production-ready codebase. The goal is to establish a clean structure, reusable components, and best practices for building dynamic and responsive web applications.

---

## Learning Objectives

By completing this milestone, you will:

- Set up a production-ready **Next.js** project.
- Implement **TypeScript** for type safety and reusable interfaces.
- Configure **TailwindCSS** for responsive and accessible UI design.
- Learn industry-standard project organization and scalability practices.
- Develop foundational reusable components like `Card` and `Button`.

---

## Folder Structure

The project follows a clean and organized folder structure:
# Project Folder Structure
```plaintext
alx-listing-app/
├── components/
│   ├── common/
│       ├── Card.tsx        # Reusable Card component
│       ├── Button.tsx      # Reusable Button component
├── constants/
│   ├── index.ts            # Centralized constants for configuration and reusable data
├── interfaces/
│   ├── index.ts            # TypeScript interfaces for type safety
├── pages/
│   ├── index.tsx           # Main page for the listing app
├── public/
│   ├── assets/             # Organized images, SVGs, and other assets
├── styles/
│   ├── globals.css         # TailwindCSS configuration
├── README.md               # Project documentation
```
## Getting Started

### Prerequisites

Ensure you have the following installed:

- **Node.js** v16+
- **npm** or **yarn**
- **Text Editor** (e.g., Visual Studio Code) with TypeScript and TailwindCSS extensions

---

### Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/alx-listing-app
   cd alx-listing-app
   ```
   
2. **Install dependencies**:
   ```npm install```
3. **Run the development server**:
    ```npm run dev```