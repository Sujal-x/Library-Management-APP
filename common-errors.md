# ⚠️ Common Errors, Fixes & What to Avoid

This guide lists common problems users may face, how to fix them, and what actions should be avoided to keep the system running safely.

---

## ❌ Database Not Created

### Problem
- Menus do not work properly  
- No data appears  
- Errors occur while adding or issuing books  

### Cause
- The database was not created during first-time setup

### Fix
- Go to **Admin Menu**
- Select **Create Database**
- Complete the setup process

### What to Avoid
- Do not try to use the system before creating the database

---

## ❌ Cannot Issue Book

### Problem
- Book cannot be issued to a member

### Possible Causes
- No available copies
- Member has reached issue limit
- Book or member number is incorrect

### Fix
- Check book availability
- Verify member details
- Ensure the member has not exceeded the issue limit

### What to Avoid
- Do not try to force issue when limits are reached

---

## ❌ Cannot Delete Book or Member

### Problem
- Deletion is blocked

### Cause
- Book or member is linked to an active transaction

### Fix
- Return all issued books first
- Then delete the book or member

### What to Avoid
- Do not attempt deletion before returning books

---

## ❌ Fine Not Matching Expectation

### Problem
- Fine amount seems incorrect

### Cause
- Book was returned late
- Fine amount per day was changed by admin

### Fix
- Check return date and actual return date
- Verify fine amount set in Admin settings

### What to Avoid
- Do not manually adjust fines
- Do not assume fines apply to on-time returns

---

## ❌ Payment Already Completed

### Problem
- System does not allow further payment

### Cause
- Fine has already been fully paid

### Fix
- Check payment status
- No further action required

### What to Avoid
- Do not attempt duplicate payments

---

## ❌ Lost Transaction Number

### Problem
- Unable to return a book or accept payment

### Cause
- Transaction number was not noted

### Fix
- Use transaction list or unreturned books list
- Identify the correct transaction number

### What to Avoid
- Do not guess transaction numbers

---

## ❌ Data Lost After Restore

### Problem
- Recent data is missing after restore

### Cause
- Old backup was restored

### Fix
- Restore the most recent backup if available
- Resume work from restored data

### What to Avoid
- Do not restore without checking backup date
- Do not restore without taking a current backup

---

## ⚠️ Critical Actions to Avoid

- Dropping the database during regular use  
- Restoring data without backup  
- Sharing admin password with everyone  
- Skipping backups  

---

## ✅ Best Practices

- Always complete first-time setup properly
- Keep transaction numbers recorded
- Take regular backups
- Use admin options carefully

Following these practices helps prevent errors and ensures smooth operation.
