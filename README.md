# Jutro-medical-test-cases

# 📋 Test Cases – Web & Mobile Application

This repository contains a set of manually written test cases for a login and account registration flow, based on real-life scenarios tested on both a **web application** and a **mobile application**.

## 📱🖥️ Application Context

The tested system is a user-facing platform that allows individuals to log in, create an account, and interact with contact support features (e.g., send an email, call helpline). The test cases have been developed for:

- **Web application (desktop browser)**
- **Mobile application (native)**

## 📌 Purpose

These test cases were prepared as part of a **portfolio project** to showcase manual test design skills, attention to edge cases, and ability to structure test documentation in a professional and readable format.

## 📂 Contents

- `mobile app test-cases.md` – Test scenarios covering login panel functionality and account creation for the **mobile application** (iOS/Android).  
- `web app test-cases.md` – Test cases related to the **web application** login flow and field validation.  
- `README.md` – This document. Overview of the project, context, and structure.

## 📝 Scope of Testing

The test cases in this repository focus on the following key aspects of the application:

- **Login functionality**: Validating correct behavior when users log in with valid or invalid credentials (e.g., phone number, PESEL).
- **Account creation**: Verifying that users can register an account using valid details and receive appropriate error messages when input is incorrect or incomplete.
- **Field validation**: Ensuring that fields such as phone numbers and PESEL are properly validated for correct length and format.
- **User interaction with support features**: Verifying the correct behavior of features like contacting support via email or calling a helpline.

Each test case includes:
- Test ID
- Preconditions
- Test steps
- Expected results
- (Optional) Additional notes

## ✅ Sample Test Case Format

| ID     | Preconditions | Test steps | Expected result | Additional notes |
|--------|---------------|------------|------------------|------------------|
| TC.01  | Valid phone and password | Click 'Log in' | User is logged in | — |

## 🛠 How to Use This Repository

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/yourusername/test-cases.git
2. **Browse the test cases**: Open the ```mobile app test-cases.md or ```web app test-cases.md file to view detailed test scenarios.
3. **Execute the tests**: You can implement these test cases using testing frameworks like Selenium (for web), Appium (for mobile), or any other framework of your choice. These test cases are written in a readable format and can be easily adapted for automation.

## 💡 Notes

- Tests are designed based on black-box testing principles.
- Validation includes both functional and UI behavior (e.g., input length limits, field validation, visibility toggles).
- These tests can be adapted into automated scripts (e.g., Selenium, Appium) if needed.

---

🧪 Created by Ewelina Wisińska  
