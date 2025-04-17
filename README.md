

# 🧪 Nykaa Clone Web Application - Testing Project

This project outlines a comprehensive manual testing approach for a Nykaa Clone web application. The goal is to identify and address potential issues in UI, functionality, usability, responsiveness, and accessibility.

---

## 📌 1. Usability Testing Suggestions

Based on usability feedback, the following improvements are suggested:

- Simplify homepage layout with uniform spacing and image alignment.
- Add clear labels and tooltips on interactive elements.
- Improve visibility and size of "Add to Cart" and "Checkout" buttons.
- Apply hover effects and active states for navigation links.
- Ensure color contrast meets accessibility standards.
- Display a dynamic cart icon that updates in real-time.
- Use a responsive hamburger menu on mobile devices.
- Show inline form validation messages for better user guidance.

---

## 🧩 2. Modules & Submodules

### Module 1: User Interface  
- Header & Navigation  
- Footer  
- Homepage Layout  

### Module 2: Product Management  
- Product Search  
- Product Filtering  
- Product Details  

### Module 3: Shopping Cart  
- Add/Remove Products  
- Update Product Quantity  
- Total Calculation  

### Module 4: Checkout System  
- Form Input Validation  
- Order Confirmation  

### Module 5: User Authentication  
- Login  
- Sign Up  

### Module 6: Responsiveness  
- Mobile Layout  
- Tablet/Desktop Adaptability  

### Module 7: Accessibility  
- Screen Reader Support  
- Alt Text for Images  
- Keyboard Navigation  

---

## 🧠 3. Mind Map

A visual mind map is created to represent all modules and submodules in a tree structure. It highlights relationships between key components like:

- UI → Navigation → Header/Footer
- Cart → Actions → Add/Remove, Update
- Auth → Forms → Login, Sign Up

![image](https://github.com/user-attachments/assets/d41d3465-1eca-4d96-b058-018493438ab0)


---

## 📋 4. Test Plan

### Objective:
Ensure seamless functionality and user experience across platforms.

### Scope:
Homepage, Product Listing, Cart, Checkout, Authentication, and Responsive UI.

### Test Types:
- Functional Testing  
- Usability Testing  
- Accessibility Checks  

### Environment:
- Browsers: Chrome, Firefox  
- Devices: Desktop, Mobile Emulators  

### Deliverables:
- Test Plan  
- Test Cases  
- Execution Report  
- Defect Report  

---

## 🧪 5. Test Scenarios & Test Cases

### Examples:

- **Homepage Loads Correctly**
- **Search Returns Valid/Invalid Results**
- **Add/Remove from Cart**
- **Form Submits with Validation**
- **User Login/Logout Functionality**
- **Mobile Responsiveness**
- **Keyboard and Screen Reader Accessibility**

---

## ✅ 6. Test Execution Reports

Detailed test cases were created and executed for:

- **Functional Testing:**  
  Total: 9 | Passed: 9 | Failed: 0

- **Usability Testing:**  
  Total: 6 | Passed: 6 | Failed: 0

_📄 Reports saved in:_
- `Nykaa_Functional_Test_Execution_Report.xlsx`  
- `Nykaa_Usability_Test_Execution_Report.xlsx`

---

## 🐞 7. Defect Report

| Defect ID | Module        | Description                                   | Severity  | Status |
|-----------|---------------|-----------------------------------------------|-----------|--------|
| DF_01     | Search        | Blank page on slow network                    | High      | Open   |
| DF_02     | Cart          | Quantity not updating                        | Medium    | Open   |
| DF_03     | Checkout      | Email not validated                          | High      | Open   |
| DF_04     | Responsiveness| Image overflow on mobile                     | High      | Open   |
| DF_05     | Accessibility | Screen reader fails to read checkout labels | Critical  | Open   |
| DF_06     | UI            | Text overlaps image banner in dark mode     | Low       | Open   |

_📄 Report file: `Nykaa_Defect_Report.xlsx`_

---

## 📂 Project Assets

- `A_mind_map_in_the_digital_image_illustrates_module.png`
- `Nykaa_Testing_Report_Presentation.pptx`
- `Nykaa_Testing_Report.pdf`
- `Nykaa_Functional_Test_Execution_Report.xlsx`
- `Nykaa_Usability_Test_Execution_Report.xlsx`
- `Nykaa_Defect_Report.xlsx`

---

## 📌 Conclusion

This documentation and testing suite ensures that the Nykaa Clone application maintains high standards for functionality, usability, and accessibility. All findings have been documented for further QA cycles and development fixes.

---
