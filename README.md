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
    <title>HTML LISTS</title>
</head>
<body>
 
    <header>
        <h1>HTML listings</h1>
    </header>

    <section>
        <h2>My courses</h2>
        <ol type="I">
            <li>Database </li>
            <li>Web development</li>
            <li>Python</li>
        </ol>
    </section>

    <section>
        <h2>Featured Image</h2>
        <img src="https://images.pexels.com/photos/417074/pexels-photo-417074.jpeg" alt="Beautiful lake with mountains" width="500">
    </section>

    <section>
        <h2>Contact List</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Nickson Brian</td>
                    <td>00100, Nairobi</td>
                    <td>25400002883</td>
                    <td>nick@gmail.com</td>
                </tr>
                <tr>
                    <td>Dickens Matush</td>
                    <td>456 40400, Kisii</td>
                    <td>075555678</td>
                    <td>dickie@yahoo.com</td>
                </tr>
                <tr>
                    <td>Alice Atieno</td>
                    <td>789 $0, Bondo</td>
                    <td>+23389012</td>
                    <td>atieno@gmail.com</td>
                </tr>
                <tr>
                    <td>Diego Maradona</td>
                    <td>321 455, Rosario</td>
                    <td>+55737456</td>
                    <td>D.maradosh@arg.co.ag</td>
                </tr>
                <tr>
                    <td>Eve Adam</td>
                    <td>65423,Statehouse</td>
                    <td>23237890</td>
                    <td> eve@outlook.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Register Here</h2>
        <form action="/submit" method="post">
          
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="you@example.com" required><br><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="At least 8 characters" minlength="8" required><br><br>

            <label for="birthdate">Date of Birth:</label><br>
            <input type="date" id="birthdate" name="birthdate" required><br><br>

            <label for="country">Country:</label><br>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
            </select><br><br>

            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label><br><br>

            <label>Interests:</label><br>
            <input type="checkbox" id="tech" name="interest" value="tech">
            <label for="tech">Technology</label>
            <input type="checkbox" id="music" name="interest" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="sports" name="interest" value="sports">
            <label for="sports">Sports</label><br><br>

            <input type="submit" value="Register">
        </form>
    </section>

    <section>
        <h2>Multimedia</h2>
        <audio controls>
            <source src="https://www.w3schools.com/html/horse.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio><br><br>
        <video width="320" height="240" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2025 HTML lISTS</p>
    </footer>
</body>
</html>
