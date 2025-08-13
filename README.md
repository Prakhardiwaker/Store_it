# <img src="./public/assets/icons/logo-brand.svg" alt="StoreIt Logo" width="40" /> StoreIt

[![GitHub stars](https://img.shields.io/github/stars/Prakhardiwaker/Store_it?style=social)](https://github.com/Prakhardiwaker/Store_it/stargazers)
[![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Appwrite](https://img.shields.io/badge/Appwrite-F02E65?logo=appwrite&logoColor=white)](https://appwrite.io/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

A modern, secure, and user-friendly cloud storage platform where users can upload, organize, and manage their files with ease. Built with **Next.js**, **Appwrite**, and a sleek UI powered by **Tailwind CSS**.

---

## 🌐 **Live Demo**

🔗 **[Visit StoreIt](https://store-it-kappa-five.vercel.app/)**

---

## 🚀 **Features**

- 📂 **File Upload & Management** – Upload, view, and delete files effortlessly.
- 🔍 **Search & Filter** – Quickly find the files you need.
- 📊 **Storage Usage Tracking** – See how much space you’ve used.
- 🔒 **Authentication** – Secure user sign-up, login, and logout flows.
- 🖼 **Preview Support** – View thumbnails for images and documents.
- 📱 **Responsive Design** – Fully optimized for desktop, tablet, and mobile.

---

## 🛠 **Tech Stack**

- **Frontend:** [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/)
- **Backend & Storage:** [Appwrite](https://appwrite.io/)
- **UI Components:** [shadcn/ui](https://ui.shadcn.com/), Radix UI
- **Other Tools:** TypeScript, Appwrite SDK

---

## 📦 **Installation & Setup**

**1️ 1️⃣ Clone the Repository**

```bash
git clone https://github.com/your-username/storeit.git
cd storeit

```

---

## 2️⃣ Install Dependencies

```
npm install
```

---

## 3️⃣ Configure Environment Variables

Create a .env.local file in the root directory:

```
NEXT_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
NEXT_PUBLIC_APPWRITE_PROJECT=your_project_id
NEXT_PUBLIC_APPWRITE_BUCKET_ID=your_bucket_id
NEXT_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
NEXT_PUBLIC_APPWRITE_API_KEY=your_api_key
```

---

## 4️⃣ Run the Development Server

```
npm run dev
```

Visit http://localhost:3000 in your browser.

---

## 📸 Screenshots

### Dashboard

<img src="public\screeshots\screenshot-1755083192170.png" alt="Dashboard Screenshot" width="800" />

### Login/Singup

<img src="public\screeshots\screenshot-1755083166961.png" alt="Login Page" width="800" />
<img src="public\screeshots\screenshot-1755083077369.png" alt="Signup Page" width="800" />

### Search

<img src="public\screeshots\screenshot-1755083253872.png" alt="Search Screenshot" width="800" />

### Upload

<img src="public\screeshots\Screenshot_13-8-2025_163910_store-it-kappa-five.vercel.app.jpeg" alt="Upload Screenshot" width="800" />

### Subsections

<img src="public\screeshots\Screenshot_13-8-2025_163935_store-it-kappa-five.vercel.app.jpeg" alt="Upload Screenshot" width="800" />

---

## 🗂 How It Works

```

flowchart LR
    A[User Uploads File] --> B[Next.js Frontend]
    B --> C[Appwrite SDK]
    C --> D[Appwrite Storage Bucket]
    D --> E[File Stored Securely]
    E --> F[Database Updated]
    F --> G[User Dashboard Shows File]

```

---

---

## 📜 Usage

1.Sign Up / Log In to your StoreIt account.

2.Upload Files via the upload button or drag-and-drop.

3.Organize your files with search and filtering options.

4.Track Storage Usage from the dashboard.

---

---

## 🤝 Contributing

1.Fork the repo.

2.Create a new branch:

```
git checkout -b feature-name

```

3.Commit your changes and push:

```
git commit -m "Add new feature"
git push origin feature-name
```

4.Open a pull request.

---

## 💡 Acknowledgements

-Next.js

-Appwrite

-Tailwind CSS

-shadcn/ui

---

---

## 🤝 Open for Collaboration

-I’m always open to contributions, feature suggestions, and collaborations on this project.
If you’d like to work together, feel free to:

-Open an issue with your idea or feature request.

-Create a pull request for improvements.

-Connect with me on GitHub or LinkedIn.

📧 Contact: prakhardiwaker@gmail.com

---
