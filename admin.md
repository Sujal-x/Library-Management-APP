# 🛡️ Admin & Settings Guide

This guide explains the **Admin section**, how to safely manage system settings, and what actions should be avoided to prevent data loss.

The Admin menu is restricted and should be used only by authorized staff.

---

## 🔐 Admin Access
Only users with the **admin password** can access this menu.

Default password is "1234". 

Admin actions affect the **entire system**, so they should be performed carefully.

---

## 🗄️ Create Database (First-Time Use)

Use this option **only when setting up the system for the first time** or when starting fresh.

What happens:
- All required system tables are created
- You are asked whether to load demo data
- The database becomes ready for normal use

### When to use
- First installation
- Complete system reset (after backup)

### What to avoid
- Do not create the database again during normal use
- Recreating the database can remove existing data

---

## 💾 Backup Database (Highly Recommended)

Backup creates a **safe copy of all data**.

Use backup:
- Before restoring data
- Before major changes
- At regular intervals (daily or weekly)

Backups protect:
- Books
- Members
- Transactions
- Payments
- Reports data

💡 Always take a backup before any risky action.

---

## 🔄 Restore Database (Use with Caution)

Restore replaces the **current data** with data from a backup file.

What happens:
- Current database is overwritten
- All current records are replaced by backup data

### When to use
- Data corruption
- Accidental deletion
- System recovery

### What to avoid
- Do not restore without checking the backup file
- Do not restore without taking a fresh backup first

⚠️ Restore cannot be undone.

---

## 🔑 Change Admin Password

Use this to:
- Improve security
- Prevent unauthorized access

Best practices:
- Change default password immediately
- Use a password known only to trusted staff
- Update it periodically

---

## 💰 Set Fine Amount

This option controls:
- Fine charged per late day

Changes affect:
- Future returns only
- Existing fines remain unchanged

Use this carefully to maintain fairness.

---

## 🗑️ Drop Database (Dangerous Action)

This option **permanently deletes all data**.

Before dropping:
- Backup is created automatically
- Confirmation is required

### When to use
- Complete system reset
- Moving to a new installation

### What to avoid
- Never use during regular operation
- Never use without understanding the consequences

Once dropped, data cannot be recovered without backup.

---

## ⚠️ Common Mistakes to Avoid

- Creating database again during regular use  
- Restoring without backup  
- Sharing admin password openly  
- Dropping database unnecessarily  

---

## ✅ Safe Admin Practices

- Keep admin access limited
- Take backups regularly
- Restore only when necessary
- Avoid experimental actions on live data

Following these practices ensures system stability and data safety.
