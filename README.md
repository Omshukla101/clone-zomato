# Zomato Clone

This project is a simplified clone of Zomato, a popular food delivery and restaurant discovery platform, built with vanilla JavaScript, HTML, and CSS.

**Note:** This is a frontend-focused clone, and does not include backend functionality for data persistence, user authentication, or real-time ordering.

## Features

* **Restaurant Listing:** Displays a list of restaurants with basic information (name, rating, cuisine, image).
* **Search Functionality:** Allows users to search for restaurants by name or cuisine.
* **Basic Filtering:** (Optional) Allows users to filter restaurants by rating or cuisine.
* **Restaurant Details:** (Optional) Provides a detailed view of a selected restaurant, including menu items.
* **Responsive Design:** Adapts to different screen sizes for optimal viewing on various devices.

## Files

* `index.html`: Contains the HTML structure for the application.
* `style.css`: Styles the application using CSS.
* `script.js`: Implements the interactive functionality and data handling using JavaScript.
* `/images/`: (Optional) A directory containing restaurant images.
* `/data/restaurants.json` : (Optional) JSON file containing restaurant data.

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/Omshukla101/clone-zomato/new/main]
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd [https://omshukla101.github.io/clone-zomato/index.html]
    ```

3.  **Open `index.html` in your web browser.**

4.  If using a json file, make sure it is in the correct directory.

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla ES6+)
* (Optional) JSON data for restaurant information.

## Data Structure (Example - restaurants.json)

```json
[
  {
    "name": "Restaurant A",
    "rating": 4.5,
    "cuisine": "Italian",
    "image": "images/restaurant-a.jpg"
  },
  {
    "name": "Restaurant B",
    "rating": 3.8,
    "cuisine": "Indian",
    "image": "images/restaurant-b.jpg"
  },
  // ... more restaurants
]
