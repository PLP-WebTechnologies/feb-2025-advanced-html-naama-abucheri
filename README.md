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



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Implementation</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>External Image</h2>
    <img src="https://www.pexels.com/photo/sample-image.jpg" alt="Sample Image from Pexels" width="500">

    <!-- Contact Table -->
    <h2>Contact List</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John kimani</td>
            <td>nyeri</td>
            <td>+2544567890</td>
            <td>john@gmail.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>eldoret</td>
            <td>+2547654321</td>
            <td>jane@gmail.com</td>
        </tr>
        <tr>
            <td>Mike Johnson</td>
            <td>kisumu</td>
            <td>+2542334455</td>
            <td>mike@gmail.com</td>
        </tr>
        <tr>
            <td>Emily Brown</td>
            <td>mombasa</td>
            <td>+254897844</td>
            <td>emily@gmail.com</td>
        </tr>
        <tr>
            <td>David Wilson</td>
            <td>nairobi</td>
            <td>+25470745688</td>
            <td>david@gmail.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select a country</option>
            <option value="usa">USA</option>
            <option value="uk">UK</option>
            <option value="canada">Canada</option>
        </select><br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label><br><br>

        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="reading" name="interests" value="reading">
        <label for="reading">Reading</label><br><br>

        <button type="submit">Register</button>
    </form>
</body>
</html>

