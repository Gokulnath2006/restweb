# Ex.07 Restaurant Website
## Date:13-05-2025

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
home.html
```
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TastyBites - Home</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>TastyBites</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <main>
    <section class="banner">
      <h2>Welcome to TastyBites!</h2>
      <p>Delicious food served fresh every day.</p>
    </section>

    <section class="intro">
      <h3>Why Choose Us?</h3>
      <p>At TastyBites, we bring you the finest dishes with the freshest ingredients. Experience great taste and hospitality like never before!</p>
    </section>

    <!-- New Gallery Section -->
    <section class="gallery">
      <h3>Our Ambiance</h3>
      <div class="gallery-grid">
        <div><img src="/static/theme1.jpg" alt="Cozy Seating Area" /></div>
        <div><img src="/static/theme2.jpg" alt="Open Kitchen" /></div>
        <div><img src="/static/theme3.jpg" alt="Delightful Decor" /></div>
        <div><img src="/static/theme4.jpg" alt="Outdoor Dining" /></div>
      </div>
    </section>
  </main>

  <footer>
    © 2025 Gokul Nath
  </footer>
</body>
</html>
```
menu.html
```
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TastyBites - Menu</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>TastyBites</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <main>
    <h2>Our Menu</h2>
    <div class="menu-grid">
      <div class="item"><img src="/static/burger.jpg" alt="Burger" /><p>Burger - $5</p></div>
      <div class="item"><img src="/static/pizza.jpg" alt="Pizza" /><p>Pizza - $8</p></div>
      <div class="item"><img src="/static/pasta.jpg" alt="Pasta" /><p>Pasta - $7</p></div>
      <div class="item"><img src="/static/salad.jpg" alt="Salad" /><p>Salad - $4</p></div>
      <div class="item"><img src="/static/fries.jpg" alt="Fries" /><p>Fries - $3</p></div>
      <div class="item"><img src="/static/sandwich.jpg" alt="Sandwich" /><p>Sandwich - $6</p></div>
      <div class="item"><img src="/static/steak.jpg" alt="Steak" /><p>Steak - $12</p></div>
      <div class="item"><img src="/static/soup.jpg" alt="Soup" /><p>Soup - $4</p></div>
      <div class="item"><img src="/static/dosa.jpg" alt="Dosa" /><p>Dosa - $5</p></div>
      <div class="item"><img src="/static/icecream.jpg" alt="Ice Cream" /><p>Ice Cream - $3</p></div>
      <div class="item"><img src="/static/noodles.jpg" alt="Noodles" /><p>Noodles - $6</p></div>
      <div class="item"><img src="/static/biryani.jpg" alt="Biryani" /><p>Biryani - $10</p></div>
    </div>
  </main>

  <footer>
    © 2025 Gokul Nath
  </footer>
</body>
</html>
```
admin.html
```
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TastyBites - Administration</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>TastyBites</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <main>
    <h2>Our Administration</h2>
    <div class="admin-grid">
      <div class="admin"><img src="/static/person1.jpg" alt="Admin 1" /><p>John - Manager</p></div>
      <div class="admin"><img src="/static/person2.jpg" alt="Admin 2" /><p>Mary - Head Chef</p></div>
      <div class="admin"><img src="/static/person3.jpg" alt="Admin 3" /><p>David - Assistant Chef</p></div>
      <div class="admin"><img src="/static/person4.jpg" alt="Admin 4" /><p>Sarah - Receptionist</p></div>
      <div class="admin"><img src="/static/person5.jpg" alt="Admin 5" /><p>Leo - Supervisor</p></div>
      <div class="admin"><img src="/static/person6.jpg" alt="Admin 6" /><p>Dev - Marketing Head</p></div>
    </div>
  </main>

  <footer>
    © 2025 Gokul Nath
  </footer>
</body>
</html>
```
contact.html
```
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TastyBites - Contact Us</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>TastyBites</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <main>
    <h2>Contact Us</h2>
    <p>📍 123 Food Street, Tindivanam, Tamil Nadu</p>
    <p>📞 +91 98765 43210</p>
    <p>✉️ tastybites@email.com</p>
  </main>

  <footer>
    © 2025 Gokul Nath
  </footer>
</body>
</html>
```
## OUTPUT:
![alt text](home.png)
![alt text](menu.png)
![alt text](admin.png)
![alt text](contact.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
