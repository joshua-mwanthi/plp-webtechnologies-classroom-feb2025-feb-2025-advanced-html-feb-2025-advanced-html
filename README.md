# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

Answers

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>HTML5 Elements Example</h1>
    </header>

    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
        </ol>
    </section>

    <section>
        <h2>External Image from Pexels</h2>
        <img src="https://www.pexels.com/photo/beautiful-scenery-12345/" alt="Beautiful Scenery from Pexels">
    </section>

    <section>
        <h2>Contact Table</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>555-1234</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>555-5678</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Sam Brown</td>
                <td>789 Oak St</td>
                <td>555-8765</td>
                <td>sam@example.com</td>
            </tr>
            <tr>
                <td>Sara White</td>
                <td>101 Pine St</td>
                <td>555-4321</td>
                <td>sara@example.com</td>
            </tr>
            <tr>
                <td>Mike Green</td>
                <td>202 Maple St</td>
                <td>555-6543</td>
                <td>mike@example.com</td>
            </tr>
        </table>
    </section>

    <section>
        <h2>Registration Form</h2>
        <form action="/submit-form" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            
            <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            
            <label for="interests">Interests:</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
            </select>
            
            <button type="submit">Register</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 HTML5 Elements Example</p>
    </footer>
</body>
</html>
