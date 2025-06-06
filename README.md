# Project Responsive Web Design using Bootstrap
# Date:26.05.2025
# REGISTER NUMBER: 212224240024
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
index.html

<html>
    <meta charset="UTF-8">
<head>
    <title>#Dribble </title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    
</head>
<body>
 <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <div class="container d-flex align-items-center justify-content-between">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav me-auto">
                <li class="nav-item"><a class="nav-link" href="#">Caramelize</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Bake</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Baste</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Broil</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Al dente</a></li>
            </ul>
        </div>
        <a class="btn  text-white" href="#">Sign in</a>
        <a class="btn  text-white" href="#">Sign Up</a>
        <input type="search" class=" form-control fs-8" style="margin: 7px; width: 150px; margin-right:7px ;" placeholder="Search">
    </div>
    
    </nav>
    <section id="home" style="background-color: rgb(32, 14, 14);">
       <div class="row" style="background-color: rgb(22, 19, 19);">
            <div class="col-lg-6 col-md-6 col-12 order-1 pt-5" style="background-color: rgb(149, 192, 225);">
               
                    <h1 class="display-4">What are you waiting for?</h1>
                    <p class="my-lg-3 my-3">Dribbble is a online food platform for customers.</p>
                        <button class="btn" style="background-color: rgb(113, 209, 234);">View More</a>
                        <button class="btn text-white" style="background-color: rgb(199, 142, 223);">Sign up</a>
            </div>
                    <div class="col-lg-6 col-md-6 col-12 py-lg-0 py-3 order-sm-2">
                        <img src="bg.jpg" class="img-fluid">
                    </div>
            
        </div>
    </section>
    
    <section class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="mb-0">Trending</h2>
                </div>
                <div class="col-md-4 text-center">
                    <button class="btn btn-light btn-sm" style="background-color: #cfd2da;">New</button>
                    <button class="btn btn-light btn-sm" style="background-color: #cfd2da;">Bites</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="1.jpg" width="300" height="225">
                      
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Sandwich And Fries</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="2.jpg" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Falooda</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="3.jpg" width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Fried Chicken</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="4.jpg" class="card-img-top" alt="Shot 2">
                       
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Momos</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="5.jpg" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Pista Milkshake</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="6.jpg" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Kunafa</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="7.jpg"width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Choco Shake</p>
                        </div>
                    </div>
                </div>
            <div class="col-md-3 col-sm-6">
                <div class="card shot-card">
                    <img src="8.jpg"width="300" height="225">
                    <div class="card-body text-center">
                        <p class="card-text mb-0">@ Strawberry Cake</p>
                    </div>
                  </div>
                </div>
            <div class="col-md-3 col-sm-6">
                <div class="card shot-card">
                    <img src="9.jpg"width="300" height="225">
                    <div class="card-body text-center">
                        <p class="card-text mb-0">@ Pizza</p>
                    </div>
                  </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="10.jpg" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">@ Mcflurry</p>
                        </div>
                    </div>
                </div>
    <div class="col-md-3 col-sm-6">
        <div class="card shot-card">
            <img src="11.jpg"width="300" height="225">
            <div class="card-body text-center">
                <p class="card-text mb-0">@ Chocobar</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="12.jpg"width="300" height="225">
                <div class="card-body text-center">
                    <p class="card-text mb-0">@ Paneer Noodles</p>
                    </div>
                </div>
            </div>
           </section>
    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">Designed and developed by YASWANTH KUMAR(212224230310)</p>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
![Screenshot 2025-05-26 083944](https://github.com/user-attachments/assets/33b9aec9-ef32-4098-a5ce-8488c966f23b)
![Screenshot 2025-05-26 084002](https://github.com/user-attachments/assets/bc74a980-d6fd-44e0-bbfc-32a50cf6663c)


![Screenshot 2025-05-26 084013](https://github.com/user-attachments/assets/53fa3b01-4bed-498c-aa17-04949f39e30a)



# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
