#  Simple Responsive Website

This is a **basic responsive website** built using **HTML and CSS only**. It includes a header, navigation bar, responsive card layout using CSS Grid, and a footer. The layout automatically adjusts to different screen sizes, making it mobile-friendly.

##  Features

-  Responsive layout using **CSS Grid**
-  Simple, clean **header and footer**
-  Interactive **hover effects** on cards
-  **Responsive navigation** using Flexbox and media queries
-  Lightweight: No JavaScript or frameworks required


##  Responsive Behavior

- On **larger screens**: Cards are displayed in multiple columns.
- On **smaller screens**: Cards stack vertically, and the nav links stack too.
- Card hover adds a zoom-in effect and shadow.

### 🔹 Header
Displays the website title inside a colored banner.

### 🔹 Navigation Bar
A horizontal menu with links (non-functional placeholders) that become vertical on very small screens.

### 🔹 Main Section (Grid Cards)
A responsive `.grid` container uses:
```css
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

