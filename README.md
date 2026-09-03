# My Office

## 📌 Description

This repository contains the client-facing web application for an office space discovery and reservation platform. It allows users to browse available workspaces by city, explore detailed office amenities and photos, and complete their workspace bookings through a seamless digital experience.

---

## 🛠️ Tech Stack

| Category                    | Technologies Used                                                |
| :-------------------------- | :--------------------------------------------------------------- |
| 🌐 **Programming Language** | `TypeScript`                                                     |
| 🧩 **Framework**            | `Tailwind CSS`                                                   |
| ⚛️ **Libraries**            | `React`, `React Router`, `axios`, `Zod`, `Swiper`, `React Icons` |
| ⚡ **Tool**                 | `Vite`                                                           |

---

## ⚙️ Setup Instructions

1. **Prerequisites**
   - Node.js 24 or higher.
   - Git installed on your system.
   - PNPM 10 installed on your system (Optional).
   - A running backend API Server instance with access to its dashboard.

2. **Server & API Key Setup**
   - Start and run your backend API server component.
   - Copy both the **API Base URL** and **Storage URL** displayed in your terminal output.
   - Open the backend dashboard in your browser, navigate to the **API Keys** section, and generate a new API key.
   - Copy the generated **API Key** to use during the configuration phase.

3. **Clone the Repository**

```bash
git clone https://github.com/Fikri-Rouzan/my-office.git
cd my-office
```

4. **Install Packages**

```bash
# Using npm
npm i

# Using pnpm
pnpm i
```

5. **Configure Environment Variables**

```bash
cp .env.example .env
```

- Open the `.env` file and configure the following variables

  ```env
  VITE_REACT_API_KEY="YOUR_API_KEY"
  VITE_REACT_API_URL="YOUR_API_URL"
  VITE_REACT_STORAGE_URL="YOUR_STORAGE_URL"
  ```

6. **Run the Program**

```bash
# Using npm
npm run dev

# Using pnpm
pnpm dev
```
