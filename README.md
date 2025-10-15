# Project Responsive Web Design using Bootstrap
## Date:15-10-2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Modern Art Gallery</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: #fafafa;
    }

    header {
      background: linear-gradient(90deg, #6a11cb, #2575fc);
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 50px;
    }

    header h1 {
      font-size: 26px;
      font-weight: 600;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 25px;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffe082;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
      padding: 50px;
    }

    .card {
      position: relative;
      overflow: hidden;
      border-radius: 15px;
      background-color: #fff;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      transition: transform 0.4s ease, box-shadow 0.4s ease;
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      transition: transform 0.4s ease;
    }

    .card:hover img {
      transform: scale(1.1);
    }

    .card-content {
      padding: 15px 18px 25px;
    }

    .card-content h3 {
      margin: 0;
      color: #333;
      font-size: 19px;
    }

    .card-content p {
      color: #666;
      font-size: 14px;
      margin-top: 6px;
    }

    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      margin-top: 40px;
    }

  </style>
</head>
<body>

  <header>
    <h1>Modern Art Gallery</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Collections</a>
      <a href="#">Artists</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="gallery">
    <div class="card">
      <img src="https://picsum.photos/id/1003/400/300" alt="Abstract Design">
      <div class="card-content">
        <h3>Abstract Imagination</h3>
        <p>Vibrant colors and surreal shapes merging creativity.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1012/400/300" alt="Nature Art">
      <div class="card-content">
        <h3>Natural Harmony</h3>
        <p>Tranquil landscapes captured with minimal strokes.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1020/400/300" alt="Digital Art">
      <div class="card-content">
        <h3>Digital Flow</h3>
        <p>Modern design elements with futuristic motion art.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://picsum.photos/id/1041/400/300" alt="Typography">
      <div class="card-content">
        <h3>Typography Vision</h3>
        <p>Bold letter art meets modern composition ideas.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Modern Art Gallery | Designed with creativity ❤️</p>
  </footer>

</body>
</html>





```


## OUTPUT:
![alt text](<Screenshot 2025-10-15 103745.png>)
![alt text](<Screenshot 2025-10-15 103754.png>)
![alt text](<Screenshot 2025-10-15 103917.png>)

![alt text](<Screenshot 2025-10-15 103927.png>)




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
