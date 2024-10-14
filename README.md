# Password Validator

A simple **Password Validator** that checks the strength and validity of a password based on its length. You can explore the live demo by clicking [here](https://pwdvalidator.ccbp.tech).

---

### Design Overview

The app is responsive and adjusts based on the device screen size. Here are some visual design references:

<details>
<summary>Click to view designs</summary>

- **Extra Small (Size < 576px) and Small (Size >= 576px)**:  
  ![Small Screen](https://assets.ccbp.in/frontend/content/react-js-hooks/password-validator-sm-output.png)
  
- **Medium (Size >= 768px), Large (Size >= 992px), and Extra Large (Size >= 1200px) - Empty Password**:  
  ![Empty Password](https://assets.ccbp.in/frontend/content/react-js-hooks/password-validator-empty-password-lg-output.png)
  
- **Invalid Password**:  
  ![Invalid Password](https://assets.ccbp.in/frontend/content/react-js-hooks/password-validator-invalid-password-lg-output.png)

- **Valid Password**:  
  ![Valid Password](https://assets.ccbp.in/frontend/content/react-js-hooks/password-validator-valid-password-lg-output.png)
  
</details>

---

### Setup Instructions

To run this project locally:

<details>
<summary>Click to view setup steps</summary>

1. Clone the repository
2. Run `npm install` to download the dependencies
3. Start the development server with `npm start`

</details>

---

### Features & Functionality

The app operates based on these key features:

<details>
<summary>Click to view functionality details</summary>

- **Initial State**: Displays an error message when no password is provided.
- **Error Handling**:
  - When the password has **less than eight characters**, the error message persists.
  - If the password length is **greater than or equal to eight characters**, the error message disappears.

</details>

---

### Project Structure

Key implementation files for this project:

<details>
<summary>Click to view files</summary>

- `src/components/PasswordValidator/index.js`
- `src/components/PasswordValidator/styledComponents.js`

</details>

---

### Important Notes

<details>
<summary>Click to view required instructions</summary>

To ensure the app functions correctly:

- Use **Styled Components** for CSS.
- Apply **Roboto** font for the "Password Validator" heading.

</details>

---

### Design Resources

Colors and fonts used in the project:

<details>
<summary>Click to view colors and fonts</summary>

#### **Colors**:

- **Background**: 
  - ![#24263c](https://via.placeholder.com/15/24263c/000000?text=+) `#24263c`
  - ![#edeeff](https://via.placeholder.com/15/edeeff/000000?text=+) `#edeeff`
  - ![#383a4e](https://via.placeholder.com/15/383a4e/000000?text=+) `#383a4e`
  - ![#475569](https://via.placeholder.com/15/475569/000000?text=+) `#475569`
  
- **Box Shadow**: 
  - ![#434451](https://via.placeholder.com/15/434451/000000?text=+) `#434451`
  
- **Text**: 
  - ![#ef4444](https://via.placeholder.com/15/ef4444/000000?text=+) `#ef4444`
  - ![#f8fafc](https://via.placeholder.com/15/f8fafc/000000?text=+) `#f8fafc`
  - ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+) `#ffffff`

#### **Font Family**:
- **Roboto**

</details>

---

### Key Considerations

- Ensure all components are located within the `src/components` directory.
- Do not modify any pre-filled code, as it may break the functionality or testing compatibility.
