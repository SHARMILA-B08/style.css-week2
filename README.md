# style.css-week2
This project is an extension of the Week 1 HTML portfolio. In Week 2, CSS (Cascading Style Sheets) was used to enhance the visual appearance, layout, responsiveness, and user interaction of the portfolio website. The goal was to apply styling principles and create a responsive, modern, and user-friendly interface.
PROJECT DOCUMENTATION
Week 2 – CSS: Styled Portfolio Website
1. Introduction

This project is an extension of the Week 1 HTML portfolio.
In Week 2, CSS (Cascading Style Sheets) was used to enhance the visual appearance, layout, responsiveness, and user interaction of the portfolio website.
The goal was to apply styling principles and create a responsive, modern, and user-friendly interface.

2. Project Objectives

Apply external CSS to style an existing HTML portfolio

Learn and use different CSS selectors

Implement layouts using Flexbox/Grid

Add hover effects and transitions

Make the website responsive for mobile devices

Apply consistent fonts and color schemes

3. Technologies Used

HTML5

CSS3

Visual Studio Code

Google Fonts

Google Chrome (Testing & Debugging)

4. GitHub Project Structure
portfolio-website/
│
├── index.html
├── style.css
├── README.md
├── images/
│   └── profile.jpg
├── screenshots/
│   └── homepage.png

5. CSS Concepts Implemented
5.1 External CSS

Created a separate style.css file

Linked it to HTML using:

<link rel="stylesheet" href="style.css">

5.2 CSS Selectors Used

Universal selector (*)

Class selectors (.header, .section)

ID selectors (#about, #skills)

Element selectors (body, header, nav)

5.3 CSS Variables (Color Scheme)
:root {
  --primary-color: #3498db;
  --secondary-color: #2c3e50;
  --accent-color: #e74c3c;
}


Used for consistency and easy theme management.

5.4 Typography

Imported Google Fonts

Styled headings and body text

Maintained consistent font hierarchy

5.5 Layout Techniques

Flexbox used for:

Header navigation

Skill cards

Project sections

Ensured proper spacing using margin and padding

5.6 Hover Effects & Interactions
a:hover {
  color: var(--accent-color);
}
button:hover {
  transform: scale(1.05);
}


Improves user experience

Adds interactivity

5.7 Responsive Design

Used media queries for mobile screens:

@media (max-width: 768px) {
  header {
    flex-direction: column;
  }
}


Ensures usability on phones and tablets

5.8 Styling Forms & Images

Styled input fields and buttons

Rounded images using border-radius

Applied box shadows for depth

6. Design Decisions

Chose a minimal and professional color palette

Used Flexbox for clean, flexible layouts

Ensured readable typography

Prioritized mobile responsiveness

7. Step-by-Step Development Process
Day 1: CSS Setup

Created style.css

Linked CSS to HTML

Reset default browser styles

Day 2: Typography & Colors

Added Google Fonts

Defined color variables

Styled headings and text

Day 3: Layout & Spacing

Implemented Flexbox/Grid

Adjusted margins and padding

Day 4: Interactive Elements

Added hover effects

Applied transitions and animations

Day 5: Responsive Design

Added media queries

Tested mobile layouts

Day 6: Advanced Styling

Styled forms, images, cards

Added visual enhancements

Day 7: Testing & Optimization

Tested on Chrome

Debugged using DevTools

Optimized CSS structure

8. Testing and Validation

Tested on desktop and mobile screens

Verified responsiveness

Checked hover effects and transitions

Ensured layout consistency

9. Limitations

No backend form submission

Static content only

Advanced animations not included

10. Learning Outcomes

Understood CSS selectors and properties

Learned Flexbox and responsive design

Improved UI/UX design skills

Gained experience in styling real projects

11. Conclusion

The Styled Portfolio Website successfully enhances the HTML structure using CSS.
This project demonstrates practical knowledge of styling, layout design, responsiveness, and interactivity, forming a strong base for advanced frontend development.
