# Assignment
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>CoST Ass</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
    }

    /* Header Image */
    .header img {
        width: 100%;
        height: auto;
    }

    /* Navbar */
    .navbar {
        background-color: #1e2f97;
        text-align: center;
        padding: 12px;
    }

    .navbar a {
        color: white;
        text-decoration: none;
        margin: 0 15px;
        font-size: 16px;
    }

    .navbar a:hover {
        text-decoration: underline;
    }

    /* Content */
    .content {
        padding: 20px;
    }

    .welcome {
        margin-bottom: 25px;
        font-size: 16px;
    }

    h2 {
        text-align: center;
        margin-bottom: 20px;
    }

    /* Gallery */
    .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
    }

    .gallery img {
        width: 300px;
        height: 200px;
        object-fit: cover;
        border: 5px solid gold;
    }

    /* Footer */
    .footer {
        background-color: #1e2f97;
        color: white;
        text-align: center;
        padding: 10px;
        margin-top: 20px;
    }

    /* Responsive */
    @media (max-width: 768px) {
        .gallery img {
            width: 90%;
        }
    }
</style>
</head>
<body>

<!-- Header -->
<div class="header">
    <img src="01.jpg" alt="CoST Header">
</div>

<!-- Navbar -->
<div class="navbar">
    <a href="#">Home</a>
    <a href="#">News</a>
    <a href="#">Faculty Members</a>
    <a href="#">Professional Training</a>
    <a href="#">Videos CoST</a>
    <a href="#">Bachelor Programs</a>
    <a href="#">Computer Labs</a>
</div>

<!-- Content -->
<div class="content">
    <div class="welcome">
        Welcome to College of Science and Technology of The University of Cambodia.
        For everyone who wishes to pursue AA and BA degree programs, please register now or visit the campus.
    </div>

    <h2>Studying Activities in CoST</h2>

    <div class="gallery">
        <img src="img1.jpg">
        <img src="img2.jpg">
        <img src="img3.jpg">
        <img src="img4.jpg">
    </div>
</div>

<!-- Footer -->
<div class="footer">
    © 2026 College of Science and Technology. All Rights Reserved.
</div>

</body>
</html>
