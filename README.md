# Ex.07 Restaurant Website
## Date: 12/05/25

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Restaurant Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet"/>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #000; /* Dark black background */
      color: #fff;
    }

    /* Top Quote Section */
    .banner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background-color: #111;
      padding: 20px;
    }

    .logo {
      max-width: 120px;
    }

    .quote {
      flex: 1;
      text-align: center;
      font-size: 1.2rem;
      font-weight: 600;
      color: #ffb400;
    }

    /* Navigation */
    nav {
      background-color: #e50914;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      padding: 12px 18px;
      display: block;
      font-weight: bold;
    }

    nav ul li a:hover {
      background-color: #ffb400;
      color: black;
      border-radius: 5px;
    }

    /* Main Content */
    main {
      text-align: center;
      padding: 40px 20px;
    }

    h1, h2 {
      color: #ffb400;
      margin-bottom: 20px;
    }

    p {
      color: #ccc;
    }

    /* Menu Items */
    .menu-items {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }

    .menu-item {
      background-color: #222;
      padding: 15px;
      border-radius: 10px;
      width: 200px;
      text-align: center;
    }

    .menu-item img {
      width: 100%;
      border-radius: 8px;
    }

    .menu-item h3 {
      color: #ffb400;
      margin-top: 10px;
    }

    /* Administration */
    .team {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }

    .team-member {
      background-color: #222;
      padding: 15px;
      border-radius: 10px;
      width: 200px;
      text-align: center;
    }

    .team-member img {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 10px;
    }

    .team-member h3 {
      color: #ffb400;
      margin-top: 10px;
    }

    /* Contact */
    #contact {
      padding: 40px 20px;
      background-color: #111;
      text-align: center;
    }

    #contact p {
      color: #ccc;
      margin-bottom: 10px;
    }

    /* Footer */
    footer {
      background-color: #e50914;
      color: white;
      text-align: center;
      padding: 12px;
    }
  </style>
</head>
<body>

  <!-- Top Quote Section -->
  <header class="banner">
    <img src="chef-logo,cooking-logo,restaurant-logo-design-template-8048c6b88c3702da6e0804bc38ce7f33_screen.jpg" alt="Restaurant Logo" class="logo">
    <div class="quote">“One cannot think well, love well, sleep well, if one has not dined well.”</div>
  </header>

  <!-- Navigation -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#menu">Menu</a></li>
      <li><a href="#administration">Administration</a></li>
      <li><a href="#contact">Contact Us</a></li>
    </ul>
  </nav>

  <!-- Home Section -->
  <main id="home">
    <h1>Welcome to Our Restaurant!</h1>
    <p>Delicious food, delightful ambiance.</p>
  </main>

  <!-- Menu Section -->
  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-items">
      <div class="menu-item">
        <img src="fe49b26c78bbd50b02c85196fdf95365.avif" alt="Food Item 1">
        <h3>Dosa</h3>
        <p>Price: ₹50.00</p>
      </div>
      <div class="menu-item">
        <img src="FB_IMG_1698651522178.jpg" alt="Food Item 2">
        <h3>Idly</h3>
        <p>Price: ₹20.00</p>
      </div>
      <div class="menu-item">
        <img src="ChilliParotta4-e1659056789688.webp" alt="Food Item 3">
        <h3>Chilli Parotta</h3>
        <p>Price: ₹90.00</p>
      </div>
    </div>
  </section>

  <!-- Administration Section -->
  <section id="administration">
    <h2>Meet Our Team</h2>
    <div class="team">
      <div class="team-member">
        <img src="restaurant-manager-icon-vector-49250616.jpg" alt="Annachi">
        <h3>Manager</h3>
      </div>
      <div class="team-member">
        <img src="chef-logo-design-vector.jpg" alt="Ramesh">
        <h3>Chef</h3>
      </div>
      <div class="team-member">
        <img src="waiter-logo-vector-illustrations_686597-26014.avif" alt="Suresh">
        <h3>Waiter</h3>
      </div>
      <div class="team-member">
        <img src="waiter-logo-vector-illustrations_686597-26014.avif" alt="Dinesh">
        <h3>Waiter</h3>
      </div>
      <div class="team-member">
        <img src="360_F_831662113_ttkMPdMKmdr4bJbdp3MjJeQw4Paps66I.jpg" alt="Ganesh">
        <h3>Cashier</h3>
      </div>

      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Address: 45, Pallavaram Market Street, Pallavaram</p>
    <p>Phone: (044) 456-7890</p>
    <p>Email: uncleMasterchef@gmail.com</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>Prabhakaran P</p>
  </footer>

</body>
</html>
```


## OUTPUT:
![Screenshot 2025-05-12 211203](https://github.com/user-attachments/assets/e2bb8439-e3df-4ff0-b114-06dff5192ea5)

![Screenshot 2025-05-12 211216](https://github.com/user-attachments/assets/56eca340-cdfd-459e-be7c-d58f06226c0a)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
