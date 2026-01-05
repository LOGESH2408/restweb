<img width="1904" height="919" alt="image" src="https://github.com/user-attachments/assets/3dd02f7e-ed45-4de5-82c3-c7c6880a11c0" /># Ex.06 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            overflow-y: scroll; /* Always show vertical scroll bar */
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 20px 0 0 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* Main Content */
        main {
            padding: 20px;
            margin: 0 10px;
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            color: #333;
            text-align: center;
        }

        h3 {
            color: #444;
            margin-bottom: 10px;
        }

        p {
            font-size: 1.1rem;
            line-height: 1.6;
        }

        /* Menu Section */
        .menu-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .menu-item {
            background-color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            width: 250px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .menu-item h3 {
            margin-top: 0;
        }

        .menu-item:hover {
            transform: translateY(-5px);
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
        }

        /* Responsive Design */
        @media screen and (max-width: 768px) {
            .menu-list {
                flex-direction: column;
                align-items: center;
            }

            .menu-item {
                width: 80%;
                margin-bottom: 20px;
            }

            nav ul li {
                display: block;
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to Our Restaurant</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Home Section -->
        <section id="home">
            <h2>Welcome to Our Cozy Restaurant</h2>
            <p>Enjoy delicious meals with a wonderful ambiance. We are passionate about fresh ingredients and delightful dishes!</p>
        </section>

        <!-- Menu Section -->
        <section id="menu">
            <h2>Our Menu</h2>
            <div class="menu-list">
                <div class="menu-item">
                    <h3>Pizza Margherita</h3>
                    <p>A classic Italian pizza with fresh mozzarella, basil, and a crispy crust.</p>
                </div>
                <div class="menu-item">
                    <h3>Pasta Carbonara</h3>
                    <p>Spaghetti with creamy egg sauce, pancetta, and Parmesan cheese. A timeless favorite!</p>
                </div>
                <div class="menu-item">
                    <h3>Caesar Salad</h3>
                    <p>Fresh greens with Caesar dressing, croutons, and a sprinkle of Parmesan cheese.</p>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>About Us</h2>
            <p>Our restaurant has been serving delicious meals for over 20 years. We pride ourselves on using only the freshest ingredients and providing a warm, welcoming atmosphere for our guests. Join us for an unforgettable dining experience.</p>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or want to make a reservation, feel free to reach out to us!</p>
            <p>Phone: <strong>123-456-7890</strong></p>
            <p>Email: <strong>info@restaurant.com</strong></p>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Our Restaurant | All rights reserved</p>
    </footer>

</body>
</html>
```

## OUTPUT:

<img width="1904" height="919" alt="image" src="https://github.com/user-attachments/assets/4c9aaee3-0491-42b3-8bae-755a7a63ac32" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
