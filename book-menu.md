# 📘 Book Menu Guide

The Book Menu is used to manage all book records within the library system.

---

## ➕ Add New Book
Use this option to register a new book in the system.

Required information:
- Book Number (must be unique)
- Book Name
- Author
- Publisher
- Total Copies
- Available Copies
- Price

**Constraint:**  
Available copies must not exceed total copies.

---

## ✏️ Modify Book
Use this option to update existing book details, such as:
- Price changes
- Copy count adjustments
- Corrections to title, author, or publisher

Leaving a field blank retains the current value.

---

## 🗑️ Delete Book
A book can be deleted only if it is **not currently issued**.

If the book is linked to an active transaction, deletion is blocked.

---

## 📋 List All Books
Displays a complete overview of:
- All registered books
- Total copies
- Currently available copies

---

## 🔍 Search Books

### By Book Number
- Exact match search
- Displays full book details

### By Keyword
Search using:
- Book name  
- Author  
- Publisher  

---

## 💡 Notes
- Keyword search is useful when exact details are unknown
