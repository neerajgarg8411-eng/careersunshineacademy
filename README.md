# careersunshineacademy
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Career Sunshine Academy</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#f5f7fb;
}

header{
    background:#0b2c5f;
    padding:15px 40px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:1000;
}

header h2{
    color:#ff9800;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:500;
}

nav a:hover{
    color:#ff9800;
}

.hero{
    background:linear-gradient(to right,#0b2c5f,#123b85);
    color:white;
    padding:100px 20px;
    text-align:center;
}

.hero h1{
    font-size:42px;
    margin-bottom:20px;
}

.hero span{
    color:#ff9800;
}

.btn{
    padding:12px 28px;
    border:none;
    border-radius:5px;
    margin:10px;
    cursor:pointer;
    font-weight:600;
}

.btn-primary{
    background:#ff9800;
    color:white;
}

.btn-secondary{
    background:white;
    color:#0b2c5f;
}

.section{
    padding:70px 40px;
    text-align:center;
}

.section h2{
    margin-bottom:40px;
    color:#0b2c5f;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:10px;
    box-shadow:0 4px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.achievement{
    background:#0b2c5f;
    color:white;
}

form{
    max-width:500px;
    margin:auto;
}

input, textarea{
    width:100%;
    padding:12px;
    margin:10px 0;
    border-radius:5px;
    border:1px solid #ccc;
}

footer{
    background:#0b2c5f;
    color:white;
    padding:20px;
    text-align:center;
}

@media(max-width:768px){
    .hero h1{
        font-size:28px;
    }
}
</style>
</head>

<body>

<header>
    <h2>Career Sunshine Academy</h2>
    <nav>
        <a href="#home">Home</a>
        <a href="#courses">Courses</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">
    <h1>Crack <span>SSC, HSSC, Railway, Army</span><br> & Teaching Exams</h1>
    <p>Best Coaching Institute in Jind for Government Exams</p>
    <button class="btn btn-primary">Enroll Now</button>
    <button class="btn btn-secondary">Free Demo</button>
</section>

<section class="section" id="courses">
    <h2>Our Courses</h2>
    <div class="grid">
        <div class="card"><h3>SSC</h3><p>CGL, CHSL, MTS</p></div>
        <div class="card"><h3>HSSC</h3><p>Haryana Govt Exams</p></div>
        <div class="card"><h3>Railway</h3><p>RRB NTPC & Group D</p></div>
        <div class="card"><h3>Army & Airforce</h3><p>Defence Preparation</p></div>
        <div class="card"><h3>CTET & HTET</h3><p>Teaching Exams</p></div>
        <div class="card"><h3>VLDA</h3><p>Village Development</p></div>
    </div>
</section>

<section class="section" id="about">
    <h2>Why Choose Us?</h2>
    <div class="grid">
        <div class="card"><p>Experienced Faculty</p></div>
        <div class="card"><p>Daily Mock Tests</p></div>
        <div class="card"><p>Doubt Clearing Sessions</p></div>
        <div class="card"><p>Online + Offline Classes</p></div>
    </div>
</section>

<section class="section achievement">
    <h2>Our Achievements</h2>
    <p>500+ Students Trained</p>
    <p>High Selection Ratio</p>
    <p>Regular Test Series</p>
    <br>
    <h3>Call Now: 9050818283</h3>
    <p>Location: Jind, Haryana</p>
</section>

<section class="section" id="contact">
    <h2>Contact Us</h2>
    <form onsubmit="submitForm(event)">
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="4" placeholder="Your Message"></textarea>
        <button class="btn btn-primary" type="submit">Send Message</button>
    </form>
</section>

<footer>
    © 2026 Career Sunshine Academy | All Rights Reserved
</footer>

<script>
function submitForm(e){
    e.preventDefault();
    alert("Thank you! We will contact you soon.");
}
</script>

</body>
</html>
