# Ex.06 Restaurant Website
## Date:
22.12.2025
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
<html>
<head>
    <title>ITC Grand Cholas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff8f0;
        }

        header {
            background-color: #ff7043;
            color: white;
            padding: 30px 0;
            text-align: center;
        }

        nav {
            background-color: #ffab91;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: black;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 50px 20px;
            text-align: center;
        }

        section h2 {
            color: #d84315;
            margin-bottom: 20px;
        }

        .menu-item {
            margin: 15px 0;
            font-size: 18px;
        }

        .order {
            background-color: #ffe0b2;
            border-radius: 10px;
            padding: 20px;
            margin: 20px auto;
            width: 60%;
        }

        footer {
            background-color: #ff7043;
            color: white;
            padding: 20px 0;
            font-weight: bold;
            text-align: center;
        }

        input, textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
        }

        button {
            padding: 10px 20px;
            background-color: #ffab91;
            border: none;
            font-weight: bold;
            cursor: pointer;
        }

        button:hover {
            background-color: #ff8a65;
        }
    </style>
</head>
<body>

    <header>
        <h1>ITC Grand Cholas</h1>
        <p>Hangover with Food!!!!</p>
    </header>

    <nav>
        <a href="#menu">Menu</a>
        <a href="#order">Order Here</a>
    </nav>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">Biryani - Rs:150</div>
        <div class="menu-item">Falooda - Rs:80</div>
        <div class="menu-item">Salad - Rs:50</div>
        <div class="menu-item">Ice Cream - Rs:120</div>
    </section>

    <section id="order" class="order">
        <h2>Order Here</h2>
        <form>
            <input type="text" placeholder="Your Name" required><br>
            <input type="tel" placeholder="Your Phone Number" required><br>
            <textarea rows="4" placeholder="Your Order Details" required></textarea><br>
            <button type="submit">Place Order</button>
        </form>
    </section>

    <footer>
        Thank You
    </footer>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-12-20 201715.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
