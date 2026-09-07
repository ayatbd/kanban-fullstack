Live Link: https://mini-kanban-zeta.vercel.app/
# Mini Kanban Board — Full-Stack Challenge

A functional Mini Kanban Board application where users can create boards, organize workflow columns, and manage tasks with drag-and-drop functionality. This project demonstrates full-stack proficiency, focusing on secure collaboration, data integrity during reordering, and a responsive UI.

## 🚀 Tech Stack

### Frontend
- **Framework:** Next.js 14 (App Router)
- **State Management:** Redux Toolkit
- **Styling:** Tailwind CSS & Shadcn UI
- **Drag & Drop:** @hello-pangea/dnd
- **Icons:** Lucide React

### Backend
- **Runtime:** Node.js with TypeScript
- **Framework:** Express.js
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT (JSON Web Tokens) & Bcrypt.js

---

## ✨ Key Features

1.  **Authentication & Security**: Secure user registration and login. Protected routes ensure users only see boards they own or are members of.
2.  **Collaboration**: Owners can share boards with other users via email, granting them access to view and edit.
3.  **Advanced Task Reordering**:
    *   Reorder tasks within the same column.
    *   Move tasks across different columns to specific positions.
    *   **Order Consistency**: Uses a numerical `order` field logic to ensure positions remain stable and conflict-free.
4.  **Interactive UI**: Smooth drag-and-drop experience with optimistic UI updates.

---

## 📂 Project Structure

```text
.
├── backend/        # Express.js API + MongoDB Models
└── frontend/       # Next.js Application + Redux Store
