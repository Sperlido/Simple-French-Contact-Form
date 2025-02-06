# Contact Form  

This project is a simple contact form in French, built using HTML and CSS. It allows users to enter their personal information and send a message.  

## Features  

- Required fields: Name, Surname, Email, Message, Country selection, and Terms of Use acceptance.  
- Dropdown list to select a country.  
- Field validation to ensure correct data entry.  
- Simple and user-friendly interface with CSS styling.  

## Technologies Used  

- **HTML5**: Provides the structure of the form.  
- **CSS3**: Ensures the design and layout.  

## How to Use  

1. Clone the repository:  
   ```sh  
   git clone https://github.com/your-username/your-repo.git  
   ```  
2. Open the `index.html` file in a web browser.  

## Customization  

To adapt the form to your website, you may need to modify the following elements:  

- **Form Submission** (`<form action="#">` in `index.html`)  
  - Change `action="#"` to specify the URL where form data should be sent (e.g., a PHP script or an API endpoint).  
  - Example:  
    ```html  
    <form action="https://yourwebsite.com/contact-form-handler.php" method="POST">
    ```  

- **Terms of Use Link**  
  - The current form contains a link to Google's Terms of Use. Replace it with your own website's terms:  
    ```html  
    <a href="https://yourwebsite.com/terms">terms of use</a>
    ```  

- **Styling**  
  - Modify `styles/styles.css` to match your site's design (colors, fonts, button styles, etc.).  

- **Country List**  
  - If you want to limit the country options, remove or add `<option>` elements in the `<select>` dropdown.  

## Preview  
![Contact Form Preview](images/screenshot.png)

## Author  

This project was created by **Sperlido**.  
