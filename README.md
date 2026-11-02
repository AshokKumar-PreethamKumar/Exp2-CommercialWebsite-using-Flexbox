# Exp2-CommercialWebsite-using-Flexbox
## Date:02/11/2026


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
### index.html
```

<!DOCTYPE html>
<html>
<head>
    <title>ShopEase - Online Shopping</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>ShopEase</h1>
        <p>Your Favourite Online Shopping Store</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">My Account</a>
    </nav>

    <!-- Homepage -->
    <section id="home" class="home">
        <h2>Welcome to ShopEase!</h2>
        <p>Discover the best products at affordable prices.</p>
        <button>Shop Now</button>
    </section>

    <!-- Products Section -->
    <section id="products">
        <h2>Our Products</h2>

        <div class="container">
            <div class="product">
                <img src="https://placehold.co/250x160?text=Headphones" alt="Headphones">
                <h3>Headphones</h3>
                <p>Price: ₹999</p>
                <button>Buy Now</button>
            </div>

            <div class="product">
                <img src="https://placehold.co/250x160?text=Smart+Watch" alt="Smart Watch">
                <h3>Smart Watch</h3>
                <p>Price: ₹1499</p>
                <button>Buy Now</button>
            </div>

            <div class="product">
                <img src="https://placehold.co/250x160?text=Speaker" alt="Speaker">
                <h3>Bluetooth Speaker</h3>
                <p>Price: ₹799</p>
                <button>Buy Now</button>
            </div>
        </div>
    </section>

    <!-- About Us -->
    <section id="about">
        <h2>About Us</h2>
        <p>
            ShopEase is an online shopping website that provides
            quality products at affordable prices. Our goal is to
            make shopping simple and convenient for everyone.
        </p>
    </section>

    <!-- Contact Details -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@shopease.com</p>
        <p>Phone: +91 8925488502</p>
        <p>Location: Chennai, India</p>
    </section>

    <!-- User Account -->
    <section id="account">
        <h2>User Account</h2>
        <p>Welcome! Manage your shopping account here.</p>
        <button>Login</button>
        <button>Register</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow Us: Instagram | Facebook | YouTube</p>
        <p>© 2026 ShopEase. All Rights Reserved.</p>
    </footer>

</body>
</html>
```

### style.css
```

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 25px;
}

/* Navigation Bar */
nav {
    background-color: #007bff;
    display: flex;
    justify-content: center;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 20px;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: yellow;
}

/* Homepage */
.home {
    text-align: center;
    padding: 60px;
    background-color: #dceeff;
}

.home h2 {
    font-size: 30px;
    margin-bottom: 15px;
}

/* Sections */
section {
    padding: 40px;
    text-align: center;
}

section h2 {
    margin-bottom: 25px;
    color: #007bff;
}

/* Flexbox Product Layout */
.container {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

.product {
    background-color: white;
    padding: 20px;
    width: 260px;
    border-radius: 10px;
    box-shadow: 0 2px 8px gray;
    transition: 0.3s;
}

.product:hover {
    transform: translateY(-8px);
}

.product img {
    width: 100%;
    border-radius: 8px;
}

.product h3 {
    margin: 12px;
}

/* Buttons */
button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
    margin: 10px;
    cursor: pointer;
    border-radius: 5px;
    transition: 0.3s;
}

button:hover {
    background-color: #0056b3;
}

/* About and Contact */
#about, #contact, #account {
    background-color: white;
    margin-top: 10px;
    line-height: 1.8;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 25px;
    line-height: 2;
}
```

## OUTPUT

![alt text](<Screenshot 2026-11-02 154329.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
