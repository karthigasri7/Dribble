# Project Responsive Web Design using Bootstrap
## Date:

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">DribbbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="py-5 text-center bg-light">
    <div class="container">
      <h1 class="display-4 fw-bold">HEAVEN LAND , ORDERS ARE TAKEN , HOME DELIVERY IS AVAILABLE</h1>
      <p class="lead">people who are love to eat are the best people</p>
      <a href="#" class="btn btn-primary btn-lg">Get Started</a>
    </div>
  </section>

  <!-- Featured Shots -->
  <section class="py-5">
    <div class="container">
      <h2 class="mb-4 text-center">Featured Shots</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card">
            <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-15 204108.png" class="card-img-top" alt="Shot 1">
            <div class="card-body">
              <h5 class="card-title">BRIYANI</h5>
              <p class="card-text">briyani is not a food it's an emotion.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-15 204150.png" class="card-img-top" alt="Shot 2">
            <div class="card-body">
              <h5 class="card-title">CHOCOLATE CAKE</h5>
              <p class="card-text">a taste of love.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-15 204336.png" class="card-img-top" alt="Shot 3">
            <div class="card-body">
              <h5 class="card-title">PANI PURI</h5>
              <p class="card-text">pani puri is the perfect match for spicy.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <div class="container">
      <p class="mb-0">Designed by [KARTHIGA SRI]</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:
![alt text](<Screenshot 2025-10-15 204816.png>)
![alt text](<Screenshot 2025-10-15 204830.png>)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
