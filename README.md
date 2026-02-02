# React Flexi

A flexible and modern React blogging platform built with Vite and React Router, built by incrementally solving 7 real-world frontend challenges.

---

## 🚀 Project Overview

React Flexi is a fully functional blogging application that supports creating, viewing, searching, commenting on, and managing blog posts with a responsive and accessible UI.  
The project was developed by implementing **7 structured challenges**, each focusing on a core feature of a modern React application.

---

## 🧩 Implemented Challenges

### 🔹 Challenge 1: Blog Post Listing
- Built a responsive blog post listing using **CSS Grid**, adapting to mobile, tablet, and desktop views.
- Displayed essential post metadata: **title, summary, and publication date**.
- Implemented reusable `BlogPostList` and `BlogPostItem` components for clean separation of concerns.
- Used **React Router links** to enable seamless navigation to individual posts.
- Handled empty states gracefully with user-friendly messaging. :contentReference[oaicite:0]{index=0}

---

### 🔹 Challenge 2: Blog Post Viewing
- Implemented a detailed blog post view displaying **title, content, author, and date**.
- Ensured full HTML content rendering while maintaining readability.
- Added responsive typography and layout for optimal reading across devices.
- Handled invalid or missing post data safely with fallback messaging.
- Followed semantic HTML and accessibility best practices. :contentReference[oaicite:1]{index=1}

---

### 🔹 Challenge 3: Blog Post Creation & Editing
- Built a reusable `BlogPostForm` supporting both **create and edit modes**.
- Implemented form validation for all required fields with inline error messages.
- Pre-filled form data when editing an existing post.
- Ensured responsive layout changes between desktop (two-column) and mobile (single-column).
- Designed with accessibility in mind using proper labels and focus handling. :contentReference[oaicite:2]{index=2}

---

### 🔹 Challenge 4: Blog Post Deletion
- Added a delete workflow with a **confirmation modal** to prevent accidental deletions.
- Built reusable `DeleteButton` and `ConfirmationDialog` components.
- Implemented keyboard navigation and focus trapping inside the modal.
- Ensured mobile-friendly touch targets and responsive dialog sizing.
- Maintained consistent UI feedback with loading and disabled states. :contentReference[oaicite:3]{index=3}

---

### 🔹 Challenge 5: Responsive Navigation & Layout
- Implemented a fixed navigation bar with **React Router–based navigation**.
- Added a hamburger menu with smooth transitions for mobile devices.
- Built a reusable `Layout` component wrapping all pages consistently.
- Ensured accessibility with ARIA attributes and keyboard navigation.
- Designed a responsive header, main content area, and footer. :contentReference[oaicite:4]{index=4}

---

### 🔹 Challenge 6: Comment System
- Implemented a full comment system with **viewing and adding comments per post**.
- Created modular components: `Comment`, `CommentList`, and `CommentForm`.
- Supported logged-in and guest users with conditional form behavior.
- Ensured real-time UI updates without page reloads.
- Designed responsive and accessible layouts for both desktop and mobile views. :contentReference[oaicite:5]{index=5}

---

### 🔹 Challenge 7: Search Functionality
- Added a global search bar to filter posts by **title and content**.
- Implemented case-insensitive and dynamic search behavior.
- Displayed highlighted search terms in result snippets.
- Handled empty results with clear user feedback.
- Designed responsive search behavior for both desktop and mobile navigation. :contentReference[oaicite:6]{index=6}

---

## 🛠 Technologies Used

- **React** – Component-based UI development
- **React Router** – Client-side routing
- **Vite** – Fast build and development tooling
- **CSS Modules** – Scoped and maintainable styling
- **JavaScript (ES6+)** – Application logic

---

## 📁 Project Structure



```
src/
├── components/        # Reusable React components
├── pages/            # Page components
├── assets/           # Static assets
├── App.jsx          # Main application component
└── main.jsx         # Application entry point
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn

### Installation
```bash
npm install

### Development
```bash
npm run dev


## Technologies Used

- **React** - UI framework
- **React Router** - Client-side routing
- **Vite** - Build tool
- **CSS** - Styling

## License

MIT
