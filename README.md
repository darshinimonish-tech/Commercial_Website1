# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
index.html 


<!DOCTYPE html>
<html>
<head>
    <title>Darshini Shopping Store</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <h1>Darshini Store</h1>
        <p>Your Online Shopping Destination</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">Account</a>
    </nav>

    <section id="home" class="home">
        <h2>Welcome to Darshini Store!</h2>
        <p>Shop your favourite products at the best prices.</p>
        <button>Shop Now</button>
    </section>

    <section id="products">
        <h2>Our Products</h2>

        <div class="container">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=400" alt="Shoes">
                <h3>Shoes</h3>
                <p>Price: ₹999</p>
                <button>Buy Now</button>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=400" alt="Headphones">
                <h3>Headphones</h3>
                <p>Price: ₹1499</p>
                <button>Buy Now</button>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=400" alt="Watch">
                <h3>Watch</h3>
                <p>Price: ₹1999</p>
                <button>Buy Now</button>
            </div>

        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Darshini Store provides quality products at affordable prices.
        Our goal is to make online shopping easy and enjoyable.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: darshinistore@gmail.com</p>
        <p>Phone: 9876543210</p>
    </section>

    <section id="account">
        <h2>User Account</h2>
        <input type="text" placeholder="Enter Username">
        <input type="password" placeholder="Enter Password">
        <button>Login</button>
    </section>

    <footer>
        <p>Follow Us: Instagram | Facebook | YouTube</p>
        <p>© 2026 Darshini Store. All Rights Reserved.</p>
    </footer>

</body>
</html>


```


style.css 

```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial;
    background-color: #f5f5f5;
}

header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 25px;
}

nav {
    background-color: #444;
    display: flex;
    justify-content: center;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 15px;
}

nav a:hover {
    color: orange;
}

section {
    padding: 40px;
    text-align: center;
}

.home {
    background-color: #ffe0b2;
    padding: 70px;
}

button {
    background-color: #ff6600;
    color: white;
    border: none;
    padding: 10px 20px;
    margin: 10px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #222;
}

.container {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
    margin-top: 25px;
}

.card {
    background-color: white;
    padding: 15px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 0 2px 8px gray;
}

.card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

#account input {
    padding: 12px;
    margin: 10px;
    border: 1px solid gray;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
}

```

## OUTPUT

"C:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2026-11-20 152204.png"
## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
