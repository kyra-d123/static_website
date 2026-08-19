# Sports Gear Store

## Project Overview

The aim of the task was to create a responsive online shopping page using Bootstrap. The website displays sporting gear products in a grid layout and includes product images, prices, product names, and Buy buttons.

## Features

The website includes:

* 10 sports gear products.
* A responsive Bootstrap grid layout.
* Responsive product images using Bootstrap's `img-fluid` class.
* A hover effect that enlarges product images.
* A product name and price for every item.
* A Buy button for each product.
* A footer containing a customer contact form.
* A small company logo displayed next to the contact form.
* Bootstrap styling and responsive design.

## Products

The store contains the following sporting gear products:

1. Soccer Ball
2. Basketball
3. Running Shoes
4. Dumbbells
5. Yoga Mat
6. Hockey Stick
7. Tennis Racket
8. Cycling Helmet
9. Skipping Rope
10. Boxing Gloves

Each product has a corresponding image that matches the product name.

## Project Files

The project folder contains:

```text
Bootstrap Task/
│
├── shopping.html
├── README.md
│
└── images/
    ├── soccer-ball.jpg
    ├── basketball.jpg
    ├── running-shoes.jpg
    ├── dumbbells.jpg
    ├── yoga-mat.jpg
    ├── hockey-stick.jpg
    ├── tennis-racket.jpg
    ├── cycling-helmet.jpg
    ├── skipping-rope.jpg
    └── boxing-gloves.jpg
```

## Technologies Used

* HTML5
* CSS
* Bootstrap 5

## How to Run the Website

1. Download or open the project folder.
2. Make sure `shopping.html`, `README.md`, and the `images` folder are kept together.
3. Open `shopping.html` in a web browser such as Google Chrome.
4. The Sports Gear Store webpage will open in the browser.
5. Resize the browser window to see how Bootstrap automatically adjusts the product layout for different screen sizes.

## Image Paths

The product images are stored inside the `images` folder.

For example:

```html
<img src="images/soccer-ball.jpg"
     class="card-img-top img-fluid product-img"
     alt="Soccer Ball">
```

Using relative image paths ensures that the images continue to work when the entire project folder is moved or submitted.

## Bootstrap

Bootstrap is included in the project using a CDN.

The Bootstrap CSS file is included inside the `<head>` section of `shopping.html`, while the Bootstrap JavaScript bundle is included near the end of the `<body>` section.

Bootstrap's grid system is used to make the products responsive across different screen sizes.

## Contact Form

The footer contains a horizontal contact form that allows a customer to enter:

* Full name
* Email address
* Phone number

The form is included for demonstration purposes and does not currently submit or store information, as functionality is not required for this task.

## Author

Kyra Daines
