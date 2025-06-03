# WebDevelopment_Task6
This project implements a Contact Form with three main input fields — Name, Email, and Message — and validates them using JavaScript. The form uses regex to validate email format and provides user feedback for incorrect or empty inputs. It features a modern glassmorphism design, is fully responsive, and displays a success message on valid submission (form doesn't actually send data).

Tools Used

Visual Studio Code (VS Code) – for writing and editing code.
Chrome Browser – for testing and viewing the form.
HTML – to structure the form.
CSS – for styling (glassmorphism effect).
JavaScript – for client-side form validation.

 Step-by-Step Implementation 
 
HTML Form Creation
 Add input fields for:
    Name (Text)
    Email (Email format)
    Message (Textarea)
    Submit Button
Style with CSS:
     Use a background image and apply glassmorphism (backdrop-filter, transparency).
     Make the form mobile-friendly with media queries.
     Style labels, input fields, and button with clarity.
     
Add JavaScript Validation
  On form submit:
     Check if Name, Email, and Message are non-empty.
     Validate Email using regex pattern 
     Display error messages under each field if invalid.

Form Behavior
     Prevent form submission using event.preventDefault() if inputs are invalid.
     If all inputs are valid, display a success message.

Test Edge Cases
     Empty fields
     Invalid email (e.g., missing @, .com)
     Special characters in name/message

Features Summary

- Responsive glassmorphism contact form
- Input validation for all fields
- Email validation using regex
- Inline error messages and form feedback
- No backend – simulation only
- Works in all modern browsers

![image](https://github.com/user-attachments/assets/9a166417-f769-4b13-bd1a-40a49d25aa17)


