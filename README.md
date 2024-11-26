
# Dashboard Design Project

Welcome to the Dashboard Design Project!
## Table of Contents

1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Project Structure](#project-structure)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgements](#acknowledgements)

## Introduction

The goal of this project is to build a fully functional dashboard layout using CSS Grid. I practiced building responsive designs and leveraging Grid to handle the majority of the layout work.

## Technologies Used

- HTML5
- CSS3 (with a focus on CSS Grid)

## Project Structure

```
dashboard-design/
├── index.html
├── styles/
│   └── styles.css
├── assets/
    └── images/
        └── (any images you use)
```

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone git@github.com:fabortwell/dashboard.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd dashboard-design
    ```
3. **Open `index.html` in your preferred browser**.

## Usage

Modify the `index.html` and `styles/styles.css` files to create your dashboard layout. Use CSS Grid for the majority of the layout work. Here is an example of a basic layout using CSS Grid:

### Example `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard</title>
    <link rel="stylesheet" href="styles/styles.css">
</head>
<body>
    <div class="container">
        <header class="header">Header</header>
        <nav class="sidebar">Sidebar</nav>
        <main class="main-content">Main Content</main>
    </div>
</body>
</html>
```

### Example `styles/styles.css`

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

.dashboard-wrap{
    display: grid;
    grid-template-columns: 300px 1fr;
    grid-template-rows: 60px 1fr;
    height: 100vh;
}

.header{
    display: flex;
    background-color: hsla(173 0% 97% / 0.98);
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;

}

.sidebar{
    background-color: hsla(202 87% 48% / 0.99);
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 3;   
}

```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. **Commit your changes**:
    ```sh
    git commit -m 'Add some feature'
    ```
4. **Push to the branch**:
    ```sh
    git push origin feature/your-feature-name
    ```
5. **Open a Pull Request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the [CSS Grid Layout Module](https://css-tricks.com/snippets/css/complete-guide-grid/) documentation and all the contributors to open-source tools and libraries used in this project.

---

