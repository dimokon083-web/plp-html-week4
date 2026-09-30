# Personal Budget & Expense Tracker

## Project Description

This project is a Personal Budget & Expense Tracker created using HTML and CSS. The purpose of the project is to provide a simple and organized interface for recording and viewing expenses.

This week's work focused on improving the visual design of the existing Budget Tracker using CSS.

## Files

### index.html

The `index.html` file contains the structure and content of the Budget Tracker. It includes the page heading, Add Expense form, and expense table.

### style.css

The `style.css` file controls the visual appearance of the application. It includes the color palette, typography, form styling, table styling, spacing, borders, and other visual improvements.

## Design Improvements

### Color Palette

A green, white, and light gray color palette was used throughout the application. Green is used for important interface elements such as headings, buttons, and the table header.

### Typography

Google Fonts were used to improve readability and create visual hierarchy. Montserrat is used for headings, while Open Sans is used for body text, labels, form elements, and table content.

### Table and Form Styling

The expense table includes:

* Styled table headers
* Cell padding
* Borders
* Alternating row colors
* Hover effects

The Add Expense form includes:

* Styled input fields
* Consistent spacing
* Borders
* Rounded corners
* A styled button

### CSS Box Model

The CSS Box Model was used throughout the project.

* **Margin** creates space between sections.
* **Padding** creates space inside cards, forms, and table cells.
* **Borders** define the boundaries of different elements.
* **Border-radius** creates rounded corners.

The page heading, Add Expense form, and Expense Table are presented as separate card-style sections.

## Technologies Used

* HTML5
* CSS3
* Google Fonts

## Learning Outcomes

Through this project, I practiced using CSS to create a consistent visual design, style forms and tables, use custom fonts, apply colors, and use the CSS Box Model to organize page sections.




## Week 4: SpendWise Dashboard Shell

This week I transformed my Personal Budget & Expense Tracker into a modern SpendWise dashboard interface.

### Dashboard Features

The dashboard contains:

* A sidebar navigation menu
* A header with account and date information
* Six financial category cards
* A financial summary section
* Responsive layouts for smaller screens
* Hover and keyboard focus interactions
* A light and dark theme using CSS custom properties

### Financial Categories

The dashboard displays static information for:

1. Food
2. Transport
3. Rent
4. Entertainment
5. Savings
6. Utilities

### CSS Grid

CSS Grid is used to create the main two-column dashboard layout and the category card grid.

### Flexbox

Flexbox is used inside the sidebar, navigation menu, header, cards, and summary section to arrange their contents.

### CSS Custom Properties

The color theme is defined using variables inside the `:root` selector, including:

* Brand color
* Accent color
* Surface color
* Background color
* Primary text color
* Secondary text color

### Responsive Design

A media query at `max-width: 768px` changes the dashboard to a single-column layout for smaller screens.

The responsive layout was tested using the browser's DevTools Device Toolbar.

### Micro-interactions

The category cards use a 200ms transition with `transform` and `box-shadow`. The effects work for both mouse hover and keyboard focus.

### Dark Theme

As a stretch goal, a dark theme was added using `@media (prefers-color-scheme: dark)`. Only the CSS custom properties are overridden to create the dark appearance.
s
