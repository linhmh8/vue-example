# Vue.js Practice Assignment - User Management System

## Assignment Overview

Build a complete User Management System using Vue 3 and json-server to practice CRUD operations and modern frontend development skills.

## Learning Objectives

- Master Vue 3 Composition API
- Implement full CRUD operations (Create, Read, Update, Delete)
- Work with REST API endpoints
- Handle form validation and error states
- Practice responsive UI design
- Understand state management patterns

## Assignment Requirements

### 1. Setup Mock API Server
- Use json-server to create a mock REST API
- Create a `db.json` file with initial user data structure
- Users should have: id, name, email, phone, role, createdAt

### 2. User List Page
- Display all users in a table/card layout
- Implement search functionality by name or email
- Add pagination or infinite scroll
- Include sorting options (by name, email, creation date)

### 3. Create User Feature
- Build a form to add new users
- Implement client-side validation
- Handle success/error responses
- Reset form after successful creation

### 4. Edit User Feature
- Create an edit form (can reuse create form component)
- Pre-populate form with existing user data
- Update user information via API
- Show confirmation messages

### 5. Delete User Feature
- Add delete functionality with confirmation dialog
- Handle delete operation via API
- Update UI after successful deletion
- Prevent accidental deletions

## Technical Requirements

- Use Vue 3 with Composition API
- Implement proper TypeScript types
- Use a CSS framework (Tailwind, Bootstrap, or similar)
- Follow Vue.js best practices
- Write clean, readable code with proper comments

## Evaluation Criteria

1. **Functionality** - All CRUD operations work correctly
2. **Code Quality** - Clean, organized, and well-commented code
3. **User Experience** - Intuitive interface with proper feedback
4. **Error Handling** - Graceful handling of API errors
5. **Responsive Design** - Works well on different screen sizes

## Getting Started

1. Install dependencies: `bun install`
2. Set up json-server for mock API
3. Create initial user data structure
4. Start development server: `bun run dev`
5. Begin with the user list component



