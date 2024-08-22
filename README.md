---

# Restaurant Menu

This is a simple restaurant menu web application that allows users to browse and filter menu items by categories such as Starters, Mains, Desserts, and Beverages. Users can also search for specific dishes using the search functionality.

## Project Overview

The "Restaurant Menu" project is a dynamic web application designed to showcase a restaurant's menu. The application provides an intuitive interface for users to explore menu items, filter them by category, and search for specific dishes.

## Technologies Used

- **HTML5**: For structuring the content of the website.
- **CSS3**: For styling and layout, including Bootstrap for responsive design.
- **JavaScript**: For dynamic content rendering and interactivity.
- **Bootstrap 4**: For responsive layout and pre-built UI components.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/RamR3899/Restaurant-Menu.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd Restaurant-Menu
    ```
3. **Open `index.html` in your Browser**:
    You can open the file directly by double-clicking `index.html` or running it through a local server if needed.

## Usage

- **View Menu Items**: Explore different dishes categorized as Starters, Mains, Desserts, and Beverages.
- **Filter Menu Items**: Click on the navigation links to filter the menu items by category.
- **Search for a Dish**: Use the search bar to find a specific dish by name.

## Features

- **Responsive Design**: The application is fully responsive, thanks to Bootstrap, and works on different devices and screen sizes.
- **Category Filtering**: Users can filter menu items by category.
- **Search Functionality**: The search bar allows users to find specific dishes quickly.
- **Dynamic Content Rendering**: Menu items are dynamically rendered using JavaScript.

## Code Explanation

### HTML (`index.html`)

The HTML structure includes a responsive navigation bar for category filtering, a search bar, and a container for displaying menu items.

### CSS (`styles.css`)

Custom styles can be added to `styles.css` for specific styling needs.

### JavaScript (`app.js`)

- **Menu Data**: The menu is stored as an array of objects, where each object represents a dish with properties like `id`, `title`, `category`, `price`, `description`, and `img`.
- **Dynamic Rendering**: The `renderMenuItem` function dynamically creates HTML for each menu item.
- **Filtering**: The `filterMenu` function filters the menu based on the selected category and renders the filtered items.
- **Search**: The search input listens for user input and filters the menu items based on the search term.

## Contact

- **Email:** [2115017@nec.edu.in](mailto:2115017@nec.edu.in)
- **LinkedIn:** [Ganesh Ram R](https://www.linkedin.com/in/ganesh-ram-r-0a2756229/)
- **GitHub:** [RamR3899](https://github.com/RamR3899)

---
