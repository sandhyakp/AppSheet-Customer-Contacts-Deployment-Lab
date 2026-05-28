# AppSheet Customer Contacts Deployment Lab

## Project Overview

This project demonstrates the complete deployment workflow of an AppSheet application using Google AppSheet.

The lab focused on:

* Creating an app from a template
* Running deployment validation checks
* Fixing errors and warnings
* Deploying the application
* Testing app functionality
* Sharing the app with users

This project helped in understanding no-code application deployment, validation workflows, and business application management using AppSheet.

---

# Technologies Used

* Google AppSheet
* Google Sheets
* No-Code App Development
* Cloud-Based Deployment

---

# Project Workflow

## Step 1 — Create the App

* Opened AppSheet dashboard
* Copied the Customer Contacts template app
* Renamed the app to:

```text
Customer Contacts
```

---

## Step 2 — Run Deployment Check

Performed deployment validation to identify:

* Data structure issues
* Missing app information
* Branding warnings
* Offline content configuration warnings

---

## Step 3 — Fix Errors and Warnings

### Fixed Data Structure Error

Updated:

```text
Company ID → Company
```

Updated formula:

```text
REF_ROWS("contacts","Company")
```

### Added App Description

Configured:

* Short Description
* Industry

### Added Custom App Logo

Configured custom branding logo.

### Enabled Offline Content Storage

Enabled:

```text
Store content for offline use
```

---

## Step 4 — Re-run Deployment Check

Validated that:

* No deployment errors remained
* App was production-ready

---

## Step 5 — Deploy the App

Moved the app from:

```text
Prototype State → Deployed State
```

---

## Step 6 — Test the Application

Tested:

* Form submission
* Auto-filled shipping information
* Data saving functionality

---

## Step 7 — Share the App

Added users and shared application access through email invitations.

---

# Key Learning Outcomes

* AppSheet deployment workflow
* No-code application development
* Deployment validation and debugging
* Data relationship correction
* Business application testing
* App publishing lifecycle
* User access management

---

# Screenshots

Add screenshots inside the `/screenshots` folder.

Recommended screenshots:

* AppSheet Dashboard
* Template Copy Screen
* Deployment Check
* Error Fixes
* Deployed Status
* App Testing
* Share User Screen

---

# Challenges Faced

* Understanding AppSheet deployment workflow
* Fixing data structure mismatch
* Configuring app branding
* Understanding offline content settings

---

# Conclusion

This lab provided practical exposure to real-world no-code application deployment using Google AppSheet. It demonstrated how business applications can be created, validated, deployed, tested, and shared without writing traditional code.
