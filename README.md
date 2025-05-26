# 💼 HR Performance Dashboard (Advanced)

A responsive and feature-rich HR Dashboard built using **Next.js (App Router)**, **Tailwind CSS**, and **React**. It allows HR Managers to monitor employee performance, manage bookmarks, view analytics, and more.

---

## 🚀 Live Project

🌐 **Live Demo:** [View Live Dashboard](https://your-live-project-link.vercel.app)  
🔗 **GitHub Repository:** [View on GitHub]()

---

## 📸 Sample Screenshots

| Login Page | Dashboard | Employee Detail |
|------------|-----------|-----------------|
| ![Login](sample-images/login.png) | ![Dashboard](sample-images/dashboard.png) | ![Employee](sample-images/employee.png) |

| Bookmarks Page | Analytics Page |
|----------------|----------------|
| ![Bookmarks](sample-images/bookmarks.png) | ![Analytics](sample-images/analytics.png) |

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **UI:** Tailwind CSS
- **Language:** JavaScript (ES6+)
- **Authentication:** Dummy login (mocked)
- **State Management:** Zustand
- **Charting Library:** Chart.js
- **Theme Support:** Dark/Light Mode with Tailwind

---

## 🔍 Features Implemented

### 🔐 Authentication
- Mock login with dummy credentials
- Route protection and redirection after login

### 🏠 Dashboard (`/dashboard`)
- Fetches user data from `https://dummyjson.com/users?limit=20`
- Displays:
  - Name, Email, Age, Department (mocked)
  - Performance rating stars
  - View, Bookmark, Promote actions

### 🔎 Search & Filter
- Search by name, email, or department
- Multi-select filter by department and rating

### 👤 Employee Details (`/employee/[id]`)
- Detailed profile with:
  - Bio, Address, Phone, Performance History
- Tabbed UI:
  - Overview, Projects, Feedback (mocked content)

### 📌 Bookmarks (`/bookmarks`)
- View all bookmarked employees
- Remove, Promote, or Assign to Project from list

### 📊 Analytics (`/analytics`)
- Charts for:
  - Department-wise average rating
  - Bookmark trends (mocked)
- Built using Chart.js

### 🌙 Dark/Light Mode
- Toggleable theme with Tailwind classes

### ⚛️ Custom Hooks & Components
- `useBookmarks`, `useSearch`
- Reusable Card, Badge, Button, Modal, Tabs

---

## 📱 Responsive Design

- Works across all screen sizes
- Optimized for both desktop and mobile
- Includes keyboard accessibility support

---

## 📦 Getting Started

### 🔧 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/your-username/hr-dashboard.git

# 2. Navigate to the project folder
cd hr-dashboard

# 3. Install dependencies
npm install

# 4. Run the development server
npm run dev
