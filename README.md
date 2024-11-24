# **Next.js Template**

A comprehensive Next.js template designed to streamline development for modern web applications. This template comes pre-configured with essential tools for styling, authentication, validation, and state management, making it ideal for reusable client projects.

## **Features**

- **Next.js**: Fast and scalable framework for React applications.
- **Authentication**: Integrated with NextAuth.js and JWT support via Jose.
- **Styling**:
  - TailwindCSS with plugins for forms and animations.
  - Preconfigured utility classes for rapid development.
- **Form Handling**: React Hook Form with Zod for validation.
- **Validation**: Schema-based validation using Zod.
- **State Management**: Lightweight and efficient.

---

## **Getting Started**

### **1. Clone the Repository**

```bash
git clone https://github.com/syedridzuan/next_js_template.git
cd next_js_template
```

---

### **2. Install Dependencies**

```bash
npm install
```

---

### **3. Configure Environment Variables**

1. Create a `.env.local` file in the root directory.
2. Use the `.env.example` as a reference and fill in the required values.

Example:

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key
```

---

### **4. Run the Development Server**

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## **Built With**

- **Next.js**: Framework for server-rendered React applications.
- **NextAuth.js**: Authentication solution for Next.js.
- **TailwindCSS**: Utility-first CSS framework.
- **React Hook Form**: Performant form handling.
- **Zod**: Type-safe schema validation.
- **Jose**: Secure JWT management.
- **Lucide Icons**: Modern and customizable SVG icons.

---

## **Folder Structure**

```
next_js_template/
├── src/
│   ├── app/               # Next.js App Directory
│   ├── components/        # Reusable UI Components
│   │   └── ui/            # Preconfigured ShadCN components
│   ├── lib/               # Utilities and helper functions
│   └── pages/             # Traditional routing
├── public/                # Static assets
├── styles/                # Global CSS
├── tailwind.config.ts     # TailwindCSS Configuration
├── package.json           # Project metadata
└── README.md              # Documentation
```

---

## **Scripts**

- `npm run dev`: Start the development server.
- `npm run build`: Build the application for production.
- `npm run start`: Run the production server.
- `npm run lint`: Run the linter for code quality.

---

## **Contributing**

Contributions are welcome! If you'd like to improve this template:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a Pull Request.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contact**

Created by [Syed Ridzuan](https://github.com/syedridzuan). Feel free to reach out for any inquiries or suggestions.
