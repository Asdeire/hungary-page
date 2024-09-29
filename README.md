# Practical Work №2

## Topic
Page Layout using HTML5 and CSS3.

## Objective
To familiarize oneself with the basics of styling web pages using HTML5 and CSS3, and to create a responsive website without the use of JavaScript or CSS frameworks.

## Overview
In this practical work, you will style a website chosen from a provided list of topics. Focus on the correct use of CSS selectors and properties while adhering to modern web standards.

### Requirements:
1. **Topic Selection**: Choose a topic from the provided list and style the website from Practical Work №1 or create a new one.

2. **Folder Structure**: CSS files should be organized in a folder named "style" or "css".

3. **No JavaScript or CSS Frameworks**: JavaScript and CSS frameworks are not permitted.

4. **CSS Code Guidelines**:
   - Follow the [code conventions](https://codeguide.co/). If you successfully install a linter and formatter, this will be achieved automatically.
   - Use Reboot to normalize styles across all browsers.
   - Link styles using `<link>` without inline styles or styles within `<style>` tags.
   - You can use all CSS3 properties, but if you use something not covered in class, you must justify and explain what it is.

5. **CSS Selectors**: Utilize all five categories of CSS selectors (see slide 17):
   - **Simple Selectors**: All except the universal selector `*`.
   - **Combinator Selectors**: Use descendant combinators, child combinators, and others as desired.
   - **Pseudo-Classes**: Use at least "anchor pseudo-classes" and `:nth-child`, with others as desired.
   - **Pseudo-Elements**: Use `::selection`, `::before`, and `::after`, with others as desired.
   - **Attribute Selectors**: Include at least one example.

6. **CSS Colors**: You can use any colors, preferably using an alpha channel for transparency.

7. **Box Model**: Reboot sets all elements to `box-sizing: border-box;`, which means that you manage the box model differently than the standard. You should explain the standard box model principles and border-box during the defense.

8. **Avoid Fixed Sizes**: Try to avoid fixed dimensions (height and width). Use relative units where appropriate for responsive design.

9. **Background Images**: Use `background-image` in cases described in theoretical materials, typically for large content backgrounds.

10. **Styling Tasks**:
   - Style the website text.
   - Adjust sizes and positioning of elements.
   - Use pseudo-classes to create dynamics on the website.
   - Style images.
   - Style hyperlinks, lists, and other elements.
   - Style tables.
   - Style forms and form elements (the styling is not strict since related material will be covered in upcoming lectures).

## Tasks
### Task 1: Topic Selection
Choose a specific topic and develop a styled webpage that highlights the chosen topic using HTML5 and CSS3.

### Task 2: CSS Structure
Ensure that CSS files are organized in the designated folder and linked properly in the HTML.

### Task 3: CSS Implementation
Implement various CSS selectors and properties as outlined in the requirements. Ensure the webpage is visually appealing and functional.

### Task 4: Final Review
Conduct a final review of the webpage to ensure all requirements are met and make any necessary adjustments.

## Conclusion
By completing this practical work, you will gain practical experience in web design, learn to use CSS effectively, and create a visually appealing and responsive website.

## Usage
1. Clone this repository to your local machine.
2. Open the HTML file in any web browser to view the styled webpage.

## Contribution Guidelines
Contributions to this practical work are welcome. Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/new-feature`.
3. Make changes and commit them: `git commit -m "Add new feature"`.
4. Push changes to your fork: `git push origin feature/new-feature`.
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
