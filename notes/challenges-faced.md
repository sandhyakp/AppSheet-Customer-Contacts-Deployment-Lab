# Challenges Faced

## 1. Understanding Prototype vs Deployed Apps

Initially it was confusing how AppSheet separates development apps from deployed production apps.

---

## 2. Data Structure Error

A mismatch between:

```text
Company ID
```

and:

```text
Company
```

caused deployment validation errors.

The issue was fixed by:

* Renaming the column
* Updating the REF_ROWS formula

---

## 3. Deployment Validation Warnings

Warnings related to:

* Missing app description
* Default app logo
* Offline content storage

needed to be reviewed and configured properly.

---

## 4. Learning Deployment Workflow

This project helped in understanding:

* Validation checks
* Error fixing
* Deployment process
* Application testing
* User sharing workflow
