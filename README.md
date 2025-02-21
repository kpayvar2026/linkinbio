# static-html-template

Use this template to create static HTML websites and deploy them on Render.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kyle Payvar - Link in Bio</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/js/all.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Raleway:wght@400&display=swap" rel="stylesheet">
    <style>
        body {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            background: linear-gradient(180deg, #00416A, #799F0C, #FFE000);
            font-family: "Raleway", sans-serif;
            color: white;
            text-align: center;
            margin: 0;
            padding: 40px;
        }
        .main-container {
            width: 100%;
            max-width: 640px;
        }
        .profile {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 20px;
        }
        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid white;
        }
        .name {
            font-family: "Playfair Display", serif;
            font-size: 24px;
            font-weight: bold;
            margin: 10px 0;
        }
        .link-list {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .link-item {
            display: flex;
            align-items: center;
            background: rgba(255, 255, 255, 0.2);
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            color: white;
            font-size: 18px;
            transition: all 0.3s ease;
        }
        .link-item:hover {
            background: rgba(255, 255, 255, 0.3);
        }
        .thumbnail {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 15px;
            object-fit: cover;
        }
        .link-list {
    display: flex;
    flex-direction: column;
    align-items: center; /* Centers links horizontally */
    gap: 15px;
}

.link-item {
    display: flex;
    align-items: center;
    justify-content: center; /* Centers text inside the link */
    width: 90%; /* Adjust width for responsiveness */
    max-width: 400px; /* Set max width so they don’t stretch too wide */
    background: rgba(255, 255, 255, 0.2);
    padding: 10px 20px;
    border-radius: 25px;
    text-decoration: none;
    color: white;
    font-size: 18px;
    transition: all 0.3s ease;
    text-align: center;
}

.link-item:hover {
    background: rgba(255, 255, 255, 0.3);
}

    </style>
</head>
<body>

<div class="main-container">
    <div class="profile">
        <img class="avatar" src="images/lorin-both-dePcyxfAJy8-unsplash (1).jpg" alt="Profile Image">
        <div class="name">Kyle Payvar</div>
    </div>

    <div class="link-list">
        <a class="link-item" href="https://www.instagram.com/kyle.payvar/" target="_blank">
            <img class="thumbnail" src="images/the-chaffins-d49_soO1BWg-unsplash.jpg" alt="Instagram Thumbnail">
            Instagram
        </a>
        <a class="link-item" href="https://github.com/kpayvar2026" target="_blank">
            <img class="thumbnail" src="images/kyle-hinkson-t9g8NvThTHY-unsplash.jpg" alt="GitHub Thumbnail">
            GitHub
        </a>
        <a class="link-item" href="https://www.linkedin.com/in/kylepayvar/" target="_blank">
            <img class="thumbnail" src="images/bharath-kumar-OgDjEjTqURQ-unsplash.jpg" alt="LinkedIn Thumbnail">
            LinkedIn
        </a>
    </div>
</div>

</body>
</html>
