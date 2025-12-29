# Project Responsive Web Design using Bootstrap
# Date:
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
html

<!DOCTYPE html>
<html>
<head>
    <title>Creative Hub</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="{% static 'hub.css' %}">
</head>
<body>

<nav class="navbar navbar-expand-lg soft-nav px-4">
    <a class="navbar-brand fw-bold" href="#">CreativeHub</a>

    <ul class="navbar-nav ms-4">
        <li class="nav-item"><a class="nav-link" href="#">Photography</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Illustration</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Design</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Nature</a></li>
    </ul>

    <form class="d-flex ms-auto">
        <input class="form-control soft-search" type="search" placeholder="Search creatives">
    </form>
</nav>

<section class="hero text-center">
    <h2>Explore visual stories</h2>
    <p>Handpicked collections from talented creators</p>
    <button class="btn soft-btn">Get Started</button>
</section>

<div class="container my-4 filter-bar">
    <span>Trending</span>
    <span>Collections</span>
    <span>Recent</span>
</div>

<div class="container">
    <div class="row g-4">

        <div class="col-md-2">
            <div class="shot-card">
                <img src="mountain.jpg">
                <div class="card-info">
                    <div class="title">Mountains</div>
                    <div class="stats">2.1k views · 420 likes</div>
                </div>
            </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="city.jpg">
                <div class="card-info">
                    <div class="title">City Life</div>
                    <div class="stats">1.7k views · 310 likes</div>
                </div>
            </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="wildlife.jpg">
                <div class="card-info">
                    <div class="title">Wildlife</div>
                    <div class="stats">3.4k views · 760 likes</div>
                </div>
            </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="abstract.jpg">
                <div class="card-info">
                    <div class="title">Abstract</div>
                    <div class="stats">890 views · 160 likes</div>
                </div>
            </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="portrait.jpg">
                <div class="card-info">
                    <div class="title">Portrait</div>
                    <div class="stats">2.8k views · 540 likes</div>
                </div>
            </div>
        </div>

        <div class="col-md-2">
            <div class="shot-card">
                <img src="architecture.jpg">
                <div class="card-info">
                    <div class="title">Architecture</div>
                    <div class="stats">1.3k views · 250 likes</div>
                </div>
            </div>
        </div>

    </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>



hub.css

body {
    background-color: #f4f9f9;
    font-family: 'Segoe UI', sans-serif;
}

/* Navbar */
.soft-nav {
    background-color: #dff3f1;
}

.soft-nav .nav-link {
    color: #444;
    font-weight: 500;
}

.soft-search {
    border-radius: 25px;
    border: none;
    padding: 6px 18px;
}

/* Hero */
.hero {
    background-color: #e8f6ff;
    padding: 50px 20px;
}

.soft-btn {
    background-color: #6bc5d2;
    color: white;
    border: none;
    padding: 8px 25px;
    border-radius: 20px;
}

.soft-btn:hover {
    background-color: #4db3c0;
}

/* Filter */
.filter-bar span {
    margin-right: 20px;
    cursor: pointer;
    color: #666;
}

/* Cards */
.shot-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 12px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.shot-card:hover {
    transform: translateY(-6px);
}

.shot-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
}

.card-info {
    padding: 10px;
}

.title {
    font-weight: 600;
    font-size: 14px;
}

.stats {
    font-size: 11px;
    color: #777;
}
```
# OUTPUT:
<img width="1892" height="1017" alt="image" src="https://github.com/user-attachments/assets/2dd53d7c-49b4-42ea-ad69-d6051f91ba0f" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
