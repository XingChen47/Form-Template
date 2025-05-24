# HTML Form Template

This project provides a customizable HTML form template for user registration and data collection. The template includes fields for username, password, email, phone number, birthday, quantity, title selection, payment method, subscription checkbox, comments, and file uploads. It is designed to be easy to use and adaptable for your own web projects.

## Features

- **Username, Password, Email, and Phone Fields:** Collects standard user information with validation.
- **Date and Number Inputs:** Get user birthday and quantity with range constraints.
- **Radio Buttons for Title:** Choose between Mr., Ms., Dr., or Others.
- **Select Payment Method:** Dropdown for payment options (Visa, Mastercard, Giftcard).
- **Subscription Checkbox:** Option for users to subscribe.
- **Comments Box:** Users can add additional comments.
- **File Upload:** Allows users to upload files (e.g., images).
- **Form Reset and Submit Buttons:** Clear or send the form data.
- **Favicon Support:** Custom icon via `images/favicons.jpg`.

## Usage

### 1. Clone or Download the Repository

```sh
git clone https://github.com/XingChen47/Form-Template.git
cd Form-Template
```

### 2. Open the Form

Open `form_template.html` in any web browser (Linux, Windows, or macOS).

### 3. File Structure

```
Form-Template/
├── form_template.html
└── images/
    └── favicons.jpg
```

> Ensure that the `images` folder and `favicons.jpg` exist for the favicon to display correctly.

## Customization

- **Action Attribute:**  
  By default, the form submits to `index.php` using the POST method. You can change this to suit your backend.
- **Form Fields:**  
  Add, remove, or modify input fields as needed for your application.
- **Styling:**  
  Add your own CSS to improve the appearance and responsiveness.
- **Validation:**  
  Adjust validation patterns and constraints to meet your requirements.

## Notes

- The template uses built-in HTML5 validation for most fields.
- For the file upload, you can restrict accepted file types using the `accept` attribute.
- The form is functional for demonstration purposes; you will need a backend (e.g., PHP, Node.js) to process submissions.
