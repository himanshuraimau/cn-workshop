### **Assignment: Personal Profile Page**

**Goal:**  
Create a personal profile page using HTML and CSS to practice structure, forms, tables, lists, and basic styling with colors and fonts.

---

### **Requirements**

1. **HTML Structure**
   - A container `<div>` with a class of `profile-container`.
   - A header with your name and a title (using `<h1>` and `<h2>`).
   - A profile image using an `<img>` tag.
   - An “About Me” section with a short paragraph.
   - A “Skills” section listing three skills in an unordered list.
   - A “Contact Me” section with basic contact details.
   - Feedback Form: A simple form with:
      - Name (<input>),
      - Email (<input>),
      - Message (<textarea>),
      - A submit button (<button>).  

2. **CSS Styling**
   - **Background color** for the page and different sections.
   - **Font family** for the headers and body text.
   - **Font colors** for different sections (experiment with light and dark colors).
   - Use **classes** and **ids** to target specific elements and apply custom styles.
   - Basic styling for form inputs, table borders, and list items.

---

### **Example Code**

#### HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div class="profile-container">
        <header>
            <h1 class="profile-name">Your Name</h1>
            <h2 class="profile-title">Web Developer</h2>
        </header>

        <img class="profile-image" src="profile.jpg" alt="Profile Picture">

        <section id="about-me">
            <h3>About Me</h3>
            <p>Hello! I’m a web developer passionate about creating engaging and accessible websites.</p>
        </section>

        <section id="skills">
            <h3>Skills</h3>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </section>

        <section id="contact-info">
            <h3>Contact Information</h3>
            <table>
                <tr>
                    <th>Type</th>
                    <th>Details</th>
                </tr>
                <tr>
                    <td>Phone</td>
                    <td>+1234567890</td>
                </tr>
                <tr>
                    <td>Email</td>
                    <td>yourname@example.com</td>
                </tr>
                <tr>
                    <td>Address</td>
                    <td>123 Main St, Anytown</td>
                </tr>
            </table>
        </section>

        <section id="feedback">
            <h3>Feedback</h3>
            <form action="#">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </section>
    </div>

</body>
</html>

```

#### CSS (styles.css)

```css
/* Basic page setup */
/* Basic page setup */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f8ff;
    color: #333;
}

/* Profile container */
.profile-container {
    background-color: #ffffff;
    text-align: center;
}

/* Profile name and title */
.profile-name {
    font-size: 2rem;
    color: #4a90e2;
}

.profile-title {
    font-size: 1.2rem;
    color: #888;
}

/* Profile image styling */
.profile-image {
    width: 150px;
    border-radius: 50%;
}

/* About and Skills section */
#about-me, #skills {
    color: #4a90e2;
}

ul {
    list-style-type: square;
}

/* Contact Info Table */
table {
    width: 100%;
    border-collapse: collapse;
}

th, td {
    border: 1px solid #4a90e2;
    padding: 8px;
    text-align: left;
}

th {
    background-color: #4a90e2;
    color: #ffffff;
}

/* Feedback Form */
form {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
}

label {
    margin-top: 10px;
    color: #4a90e2;
}

input, textarea, button {
    margin-top: 5px;
    width: 100%;
    max-width: 300px;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    background-color: #4a90e2;
    color: white;
    border: none;
    cursor: pointer;
    padding: 10px;
}

button:hover {
    background-color: #357ab7;
}

```

---

**Instructions:**

1. **Setup**:  
   - Create a new folder for this project.
   - Inside the folder, create an `index.html` file and a `styles.css` file.

2. **HTML Structure**:
   - Use the provided HTML structure to create your profile page.
   - Include sections for your name, title, about, skills, and contact details.

3. **CSS Styling**:
   - Style your page by experimenting with colors, fonts, and basic image styling.
   - Use the example CSS as a guide, but feel free to customize.

