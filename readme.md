## OBJECTIVE:
To Create a simplified clone of Dribbble (https://dribbble.com/) landing page.

## DESCRIPTION:
Created a simplified clone of Dribble Landing Page With the use of HTML and CSS

## HTML CODE:
Style.css
```c
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #000000;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #000000;
    padding: 10px 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.logo {
    font-family: monospace;
    font-size: 24px;
    font-weight: italic;
    color: #ff0000;
}

nav ul {
    justify-content: center;
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff;
}

.auth-buttons {
    display: flex;
}

.auth-buttons button {
    margin-left: 10px;
    padding: 5px 10px;
    border: none;
    cursor: pointer;
}

.auth-buttons .sign-in {
    background-color: #ffffff;
    color: #ea4c89;
    border: 1px solid #ea4c89;
}

.auth-buttons .sign-up {
    background-color: #ea4c89;
    color: #ffffff;
}

.hero {
    text-align: center;
    padding: 50px 20px;
    background-color: #ff0000;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 20px;
}

.hero h1 {
    margin: 0 0 10px;
    font-size: 36px;
}

.hero p {
    margin: 0;
    font-size: 18px;
    color: #666;
}
nav ul {
    justify-content: center;
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff;
}

.shots {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 20px;
}

.shot {
    margin: 10px;
}

.shot img {
    width: 200px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
```
Advance.html
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Dribbble</div>
        <nav>
            <ul>
                <li><a href="#">Inspiration</a></li>
                <li><a href="#">Find Work</a></li>
                <li><a href="#">Learn Design</a></li>
                <li><a href="#">Go Pro</a></li>
                <li><a href="#">Marketplace</a></li>
            </ul>
        </nav>
        <div class="auth-buttons">
            <button class="sign-in">Sign In</button>
            <button class="sign-up">Sign Up</button>
        </div>
    </header>

    <main>
        <section class="hero">
            <h1>Discover the world's top designers & creatives</h1>
            <p>Dribbble is the leading destination to find & showcase creative work and home to the world's best design professionals.</p>
        </section class="nav">
        <section>
            <nav>
                <ul>
                    <li><a href="#">Popular</a></li>
                    <li><a href="#">Shots</a></li>
                    <li><a href="#">Now</a></li>
                </ul>
            </nav>
        </section>
        <section class="shots">
            <!-- Example shot thumbnails -->
            <div class="shot">
                <img src="d:\original-2a6e9d3c083b024ef678863b8ef2bb59.png" alt="Design Shot 1">
            </div>
            <div class="shot">
                <img src="d:\original-5096bdbdf2194e9ddcb5dd3de6bbaf78.jpg" alt="Design Shot 2">
            </div>
            <div class="shot">
                <img src="d:\original-e5af34af45d25b2c242d843c405b5d8a.png" alt="Design Shot 3">
            </div>
            <div class="shot">
                <img src="d:\original-d8c376a174a96c975d6c035bd8970a83.png" alt="Design Shot 4">
            </div>
            <div class="shot">
                <img src="d:\original-5457e2df930249f0de452341bca7f54a.png" alt="Design Shot 5">
            </div>
            <div class="shot">
                <img src="d:\original-01c6de41fe975e19f8965d75fe26e535.png" alt="Design Shot 6">
            </div>
            <div class="shot">
                <img src="d:\still-84887d07eb3cad95f2c109950479b473.png" alt="Design Shot 7">
            </div>
        </section>
    </main>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (51).png>)
