Answer
<!DOCTYPE html>
<html>
<head>
  <title>Responsive Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <nav class="nav-bar">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
  <main class="grid-container">
    <section class="grid-item item1">Section 1</section>
    <section class="grid-item item2">Section 2</section>
    <section class="grid-item item3">Section 3</section>
  </main>
</body>
</html>


CSS (style.css)
/* Global Styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
}

/* Navigation Bar */
.nav-bar {
  background-color: #333;
  color: #fff;
  padding: 1em;
  text-align: center;
}

.nav-bar ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
}
.nav-bar a {
  color: #fff;
  text-decoration: none;
}

/* Grid Container */
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 20px;
}

.grid-item {
  background-color: #f7f7f7;
  padding: 20px;
 }
}
/* Media Queries */
@media (max-width: 768px) {
  .grid-container {
    grid-template-columns: repeat(2, 1fr);
  }


@media (max-width: 480px) {
  .grid-container {
    grid-template-columns: 1fr;
  }
  .nav-bar ul {
    flex-direction: column;
  }
  .nav-bar li {
    margin-bottom: 10px;
  }
}



# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨
