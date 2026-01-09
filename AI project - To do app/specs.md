# 📐 Technical Specifications – Sticky Notes Todo App

## 1. Overview

This document describes the functional and technical specifications of the Sticky Notes Todo List web application.

---

## 2. Functional Requirements

### 2.1 Task Management
- Users can add a new task via an input field
- Users can mark a task as completed
- Users can delete a task
- Completed tasks are visually distinct

### 2.2 Data Persistence
- Tasks must be saved in the browser's Local Storage
- Tasks must persist after page refresh
- Data is stored in JSON format

---

## 3. Non-Functional Requirements

- No external libraries or frameworks
- Fast load time
- Responsive layout
- Clean and readable code
- Cross-browser compatibility (modern browsers)

---

## 4. UI / UX Specifications

### 4.1 Layout
- Centered container
- Vertical list of task cards
- Input field with add button

### 4.2 Sticky Note Design
- Light yellow background
- Slight rotation using CSS `transform`
- Soft shadow for depth
- Hover effect with lift animation

### 4.3 Task States
| State       | Visual Style |
|------------|-------------|
| Normal     | Yellow sticky note |
| Completed | Gray background + line-through text |

---

## 5. Data Model

### Task Object Structure

```json
{
  "text": "Buy groceries",
  "completed": false
}
