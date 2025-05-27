<h2><strong>"I made 5,127 prototypes of my vacuum before I got it right. There were 5,126 failures. But I learned from each one. That's how I came up with a solution."</strong></h2>
<p><em>— James Dyson</em></p>

# Sigma DogCare System (SDCS) - UX Design Walkthrough

Welcome to the UX case study of the **Sigma DogCare System (SDCS)** — a dual-interface mobile application designed for  students. This project focuses on delivering an inclusive, accessible, and streamlined user experience for both dog owners and dog carers.

---

## 🧠 Project Overview

**Unit**: COMP2750/6750 - Application Modelling and Development  
**Role**: UX Designer & Developer  
**Platform**: Android/iOS Mobile App  
**Tools**: Figma, DALL·E, Canva

---

## 🎯 Objective

Transform a case study into an interactive mobile interface using UX principles. Design clear, functional mockups for two user roles—**Dog Owner** and **Dog Carer**—and demonstrate workflows with validation/error handling using a story-driven presentation.

---

## 🎨 Design Philosophy

![Design Tone](https://github.com/nur-exif/Dog-Care-UI-Design-Project/blob/main/Design%20Tone.png)

### Human-Computer Interaction (HCI)
This design is rooted in HCI principles, focusing on reducing cognitive load, enabling fast navigation, and improving task efficiency across devices.

### Color Palette
- **Tan and Brown Tones** — inspired by popular Australian dog breeds like Golden Retrievers and Poodles.
- Promotes warmth, simplicity, and emotional trust.

### Typography
- **Sans-serif font** family for minimal distraction and maximum readability.
- Effective across various lighting conditions and screen sizes.

### Universal Design
- Designed for all users regardless of ability or background.
- Accessible color contrast and intuitive icons.
- Layout follows Western top-down, left-right reading patterns.

---

## 🔐 Authentication Flow

![Authenticator](https://github.com/nur-exif/Dog-Care-UI-Design-Project/blob/main/Authenticator.png)


- Users begin by choosing their **role**: Dog Owner or Dog Carer.
- They then log in with **Authenticator ID**.
- Multi-Factor Authentication (MFA) is enabled via the Google Authenticator app.
- The interface is clean, ensuring a frictionless but secure entry point.

---

## 🐶 Dog Owner Workflow

![Dog Owner Design Flow](https://github.com/nur-exif/Dog-Care-UI-Design-Project/blob/main/Dog%20Owner%20Design%20Flow.png)

### 📸 Screenshots


### 1. Dashboard
- View total ads, current requests, and completed bookings.

### 2. Create a New Request
- Fill in fields: start date, end date, location, pet details, special needs, and carer preferences.
- Upon successful submission, "Request Successful" confirmation appears.

### 3. Manage Ads
- Owners can view, edit, or delete active ads.
- View applications submitted by carers.

### 4. Compare Applicants
- Review carer profiles and compare side-by-side.
- Proceed to book and pay.

### 5. Booking Confirmation
- Payment is held in **escrow**.
- Confirmation screen appears with calendar integration.

### 🔻 Error Workflows

![Dog Owner Error Workflow](https://github.com/nur-exif/Dog-Care-UI-Design-Project/blob/main/Error%20Workflow%20Dog%20Owner.png)
- **Internal Server Error** → Generic friendly error page
- **Missing Pet Info** → "Incomplete Ad Submission"
- **Payment Failure** → "Payment Failed, Try Again"
---

## 🧑‍⚕️ Dog Carer Workflow

![Dog Carer Design Flow](https://github.com/nur-exif/Dog-Care-UI-Design-Project/blob/main/Dog%20Carere%20Design%20Workflow%20.png)

### 📸 Screenshots


### 1. Dashboard
- Summary of monthly earnings, completed jobs, and application status.

### 2. Search Jobs
- Apply filters by availability, dog type, and care condition.
- View scannable job cards with all required info.

### 3. Apply for a Job
- Select availability and enter a message to the owner.

### 4. Manage Applications
- View applications with statuses: Pending, Accepted, Declined.

### 5. Earnings Summary
- See detailed breakdown: tips, tax, net pay.
- Visualized via graphs and numeric summaries.

### 🔻 Carer Error Workflow

![Dog Carer Error Workflow](https://github.com/nur-exif/Dog-Care-UI-Design-Project/blob/main/dog%20care%20error%20dog%20.png)

- **No Job Results** → Suggests retry with a reload button
- **Missing Message** → Prompt to fill in message
- **No Internet** → Offline page with recovery tips

---

## ✅ Key UX Features

- **Role-Based Dashboard Navigation**
- **Progressive Disclosure**: Only relevant data shown at each step
- **Card-Based Layouts** for visual grouping
- **Inline Validation** to prevent errors
- **Escrow Booking Logic** ensures transactional clarity
- **Mobile-first Responsive Design**
---

## 📬 Contact

Created by **Shafin Nur**  
3rd Year Cybersecurity Student at Macquarie University  
📧 shafinnur31@hotmail.com

---
