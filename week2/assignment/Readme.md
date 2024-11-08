### Assignment: "Recipe Book Webpage with Feedback Form"
**Objective**: Create a visually appealing recipe webpage where users can browse recipes, view detailed instructions, and submit feedback. This project will involve HTML structure, CSS styling, form handling, and various HTML tags.

#### Requirements:

1. **Homepage (`index.html`)**:
   - **Header**: Include a website title ("Recipe Book") and a navigation bar with links to "Home," "Recipes," "About," and "Feedback."
   - **Recipe List**: Display three featured recipes (e.g., Pancakes, Spaghetti, Cookies), each with:
     - An image
     - Title (inside an `<h3>` tag)
     - Short description (in a `<p>` tag)
     - A “View Recipe” link that navigates to the recipe details page
   - **Footer**: A footer with copyright information, links to social media icons (`<a>` tags with placeholder links), and contact details.

2. **Recipe Details Page (`recipe.html`)**:
   - Choose one of the recipes from the homepage (e.g., Pancakes).
   - **Sections**:
     - **Recipe Title** (using an `<h2>` tag)
     - **Ingredients**: List the ingredients in an unordered list (`<ul>`).
     - **Instructions**: Provide a step-by-step guide in an ordered list (`<ol>`).
     - **Nutritional Information**: Add a table with columns for "Nutrient," "Amount," and "Daily Value" using the `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` tags.
   - **Back Button**: A link or button to navigate back to the homepage.

3. **About Page (`about.html`)**:
   - **About Section**: Write a short description about the purpose of the website and its featured recipes, using `<section>` and `<p>` tags.
   - **Contact Information**: Provide a "Contact Us" section with a fake email address and social media links.
   - **Team Section**: Use `<figure>`, `<img>`, and `<figcaption>` tags to display team members' photos with captions.

4. **Feedback Form Page (`feedback.html`)**:
   - **Form Purpose**: Include a form where users can provide feedback on recipes.
   - **Form Elements**:
     - **Name**: An input field (`<input type="text">`) for the user’s name.
     - **Email**: An input field (`<input type="email">`) for the user’s email address.
     - **Recipe Rating**: A dropdown menu (`<select>` with `<option>` tags) where users can rate recipes from 1 to 5.
     - **Comments**: A textarea (`<textarea>`) for additional comments.
     - **Submit Button**: A submit button (`<input type="submit">`) to send the form.
   - **Validation**: Add `required` attributes to the fields (e.g., Name, Email, Recipe Rating) for basic validation.
   - **Thank You Message**: After submission, display a thank-you message. (Note: This can be a placeholder message with JavaScript, or students can simply be instructed to display a confirmation message on the same page.)

#### CSS Styling:
- **Typography and Color Scheme**: Select a color scheme that’s inviting (e.g., warm colors), and set consistent font styles across pages.
- **Responsive Layout**: Use Flexbox or Grid to make the recipe cards align nicely on different screen sizes.
- **Hover Effects**: Apply hover effects to recipe images, links, and form buttons.
- **Form Styling**: Style the form elements to match the website’s theme, with padding, borders, and spacing.

#### Extra Challenge (Optional):
- **Form Success Message**: Use a simple CSS rule or JavaScript snippet to show a thank-you message after form submission (e.g., hide the form and display a message).
- **Responsive Design**: Ensure all pages are mobile-friendly and adjust gracefully for different screen sizes.

---

### Suggested HTML Tags and CSS Properties:
- HTML Tags: `<header>`, `<footer>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<a>`, `<table>`, `<form>`, `<input>`, `<textarea>`, `<select>`, `<option>`, `<button>`, `<ul>`, `<ol>`, `<li>`, `<figure>`, `<figcaption>`
- CSS Properties: `display`, `flex`, `grid`, `margin`, `padding`, `background-color`, `border`, `border-radius`, `box-shadow`, `text-align`, `hover` effects, `font-family`, `color`, `width`, `height`, `media queries`
