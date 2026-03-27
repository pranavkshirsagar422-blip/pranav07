<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#0f172a;
color:white;
line-height:1.6;
}

header{
background:#020617;
padding:20px;
position:sticky;
top:0;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
max-width:1100px;
margin:auto;
}

nav h1{
color:#38bdf8;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
text-decoration:none;
color:white;
transition:0.3s;
}

nav ul li a:hover{
color:#38bdf8;
}

.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero h2{
font-size:48px;
}

.hero span{
color:#38bdf8;
}

section{
padding:80px 20px;
max-width:1100px;
margin:auto;
}

.section-title{
text-align:center;
margin-bottom:40px;
font-size:32px;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#1e293b;
padding:20px;
border-radius:10px;
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card h3{
margin-bottom:10px;
}

.contact{
text-align:center;
}

.contact a{
display:inline-block;
margin-top:15px;
padding:10px 20px;
background:#38bdf8;
color:black;
text-decoration:none;
border-radius:5px;
}

footer{
text-align:center;
padding:20px;
background:#020617;
margin-top:40px;
}
</style>
</head>

<body>

<header>
<nav>
<h1>MyPortfolio</h1>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#html">Projects</a></li>
<li><a href="#9021090859">Contact</a></li>
</ul>
</nav>
</header>

<div class="hero">
<div>
<h2>Hello, I'm <span>pranav kshirsagar</span></h2>
<p>Web Developer | Designer | Freelancer</p>
</div>
</div>

<section id="about">
<h2 class="section-title">About Me</h2>
<p>
I am a passionate developer who loves building websites and web apps.
I specialize in HTML, CSS, JavaScript and modern web technologies.
</p>
</section>

<section id="projects">
<h2 class="section-title">Projects</h2>

<div class="projects">

<div class="card">
<h3>Project One</h3>
<p>A modern responsive website.</p>
</div>

<div class="card">
<h3>Project Two</h3>
<p>A web app built using JavaScript.</p>
</div>

<div class="card">
<h3>Project Three</h3>
<p>A creative UI design project.</p>
</div>

</div>
</section>

<section id="contact">
<h2 class="section-title">Contact</h2>

<div class="contact">
<p>Email: pranavkshirsagar422@gmail.com</p>
<a href="#">Send Message</a>
</div>

</section>

<footer>
<p>© 2026 Your Name | Portfolio</p>
</footer>

</body>
</html>
