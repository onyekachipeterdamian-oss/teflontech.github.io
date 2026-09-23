<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TeflonTech Education Portal</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f5f7fa;
}

header{
    background:#0066cc;
    color:white;
    text-align:center;
    padding:30px;
}

nav{
    background:#004d99;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

.hero{
    text-align:center;
    padding:60px 20px;
}

.hero h1{
    color:#0066cc;
    margin-bottom:10px;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:20px;
}

.card{
    background:white;
    padding:20px;
    margin:15px 0;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

.login-form{
    max-width:400px;
    margin:30px auto;
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

input{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:1px solid #ddd;
    border-radius:5px;
}

button{
    background:#0066cc;
    color:white;
    border:none;
    padding:12px;
    width:100%;
    border-radius:5px;
    cursor:pointer;
}

button:hover{
    background:#004d99;
}

footer{
    background:#003366;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>
</head>

<body>

<header>
    <h1>TeflonTech Education Portal</h1>
    <p>Empowering Students Through Learning</p>
</header>

<nav>
    #homeHome</a>
    #coursesCourses</a>
    #aboutAbout</a>
    #contactContact</a>
</nav>

<section class="hero" id="home">
    <h1>Welcome to TeflonTech Education</h1>
    <p>Learn, Grow and Achieve Academic Excellence</p>
</section>

<div class="container">

    <div class="card" id="courses">
        <h2>Available Subjects</h2>
        <p>Mathematics</p>
        <p>English Language</p>
        <p>Physics</p>
        <p>Chemistry</p>
        <p>Computer Science</p>
    </div>

    <div class="login-form">
        <h2>Student Login</h2>

        <input type="text" id="username" placeholder="Student Name">
        <input type="password" id="password" placeholder="Password">

        <button onclick="login()">Login</button>
    </div>

    <div class="card" id="about">
        <h2>About Owner</h2>
        <p><strong>Owner:</strong> Ibemma Peter Damian Onyekadichi</p>
        <p>Founder of TeflonTech Education Portal.</p>
    </div>

    <div class="card" id="contact">
        <h2>Contact Information</h2>
        <p><strong>WhatsApp:</strong> 09022197870</p>
        <p><strong>Email:</strong> onyekachipeterdamian@gmail.com</p>
    </div>

</div>

<footer>
    <p>© 2026 TeflonTech Education Portal. All Rights Reserved.</p>
</footer>

<script>
function login() {
    let username = document.getElementById("username").value;

    if(username.trim() === ""){
        alert("Please enter your name.");
        return;
    }

    alert("Welcome " + username + " to TeflonTech Education Portal!");
}
</script>

</body>
</html>
