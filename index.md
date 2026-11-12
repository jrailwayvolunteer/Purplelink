
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Purplelink | 15 Stops for Less</title>

<style>
:root{
    --light-purple:#F3ECFF;
    --purple:#6F2DBD;
    --dark-purple:#4B1D80;
    --black:#1F1F1F;
    --white:#FFFFFF;
    --border:#D9C8F5;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:"Gill Sans MT","Gill Sans",Calibri,sans-serif;
    background:var(--light-purple);
    color:var(--black);
    line-height:1.6;
}

.container{
    width:90%;
    max-width:1100px;
    margin:auto;
}

/* HEADER */

header{
    background:var(--dark-purple);
    color:var(--white);
    position:sticky;
    top:0;
    z-index:1000;
}

.navbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:1rem 0;
}

.logo{
    font-size:2rem;
    font-weight:bold;
}

nav ul{
    list-style:none;
    display:flex;
    gap:1.5rem;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:600;
}

nav a:hover{
    color:#E8D9FF;
}

/* HERO */

.hero{
    padding:80px 0;
}

.hero-content{
    display:grid;
    grid-template-columns:2fr 1fr;
    gap:40px;
    align-items:center;
}

.hero h1{
    color:var(--dark-purple);
    font-size:3rem;
    margin-bottom:1rem;
}

.hero p{
    font-size:1.15rem;
    margin-bottom:1rem;
}

.tagline{
    display:inline-block;
    background:var(--purple);
    color:white;
    padding:10px 20px;
    border-radius:30px;
    font-weight:bold;
    margin-bottom:20px;
}

.hero-card{
    background:white;
    padding:25px;
    border-radius:12px;
    border:1px solid var(--border);
    box-shadow:0 4px 12px rgba(0,0,0,0.08);
}

.hero-card h2{
    color:var(--dark-purple);
    margin-bottom:10px;
}

/* SECTIONS */

section{
    padding:60px 0;
}

.section-title{
    color:var(--dark-purple);
    font-size:2.2rem;
    margin-bottom:30px;
    text-align:center;
}

.grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:12px;
    border:1px solid var(--border);
}

.card h3{
    color:var(--dark-purple);
    margin-bottom:10px;
}

.route-box{
    background:white;
    border-left:6px solid var(--purple);
    padding:25px;
    border-radius:10px;
}

/* FAQ */

.faq details{
    background:white;
    margin-bottom:15px;
    padding:18px;
    border-radius:10px;
    border:1px solid var(--border);
}

.faq summary{
    font-weight:bold;
    cursor:pointer;
    color:var(--dark-purple);
}

.faq p{
    margin-top:10px;
}

/* FOOTER */

footer{
    background:var(--dark-purple);
    color:white;
    text-align:center;
    padding:30px 20px;
}

/* RESPONSIVE */

@media(max-width:768px){

    .navbar{
        flex-direction:column;
        gap:15px;
    }

    nav ul{
        flex-direction:column;
        text-align:center;
    }

    .hero-content{
        grid-template-columns:1fr;
    }

    .grid{
        grid-template-columns:1fr;
    }

    .hero h1{
        font-size:2.2rem;
    }
}
</style>
</head>
<body>

<header>
    <div class="container navbar">
        <div class="logo">Purplelink</div>

        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#route">Route</a></li>
                <li><a href="#faq">FAQ</a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="hero" id="home">
    <div class="container hero-content">

        <div>
            <div class="tagline">15 Stops for Less</div>

            <h1>Low‑Cost Rail Travel Between London and Manchester via Birmingham</h1>

            <p>
                Purplelink is a student startup concept exploring affordable rail
                services for passengers travelling between London, Birmingham,
                Manchester and communities along the route.
            </p>

            <p>
                The idea focuses on providing accessible rail travel through a route
                with multiple stops while keeping costs lower for travellers.
            </p>
        </div>

        <div class="hero-card">
            <h2>Student Startup Concept</h2>
            <p>
                Purplelink is currently a university startup idea. This website
                explains the concept and does not represent an operating train
                company.
            </p>
        </div>

    </div>
</section>

<section id="about">
    <div class="container">

        <h2 class="section-title">What We Offer</h2>

        <div class="grid">

            <div class="card">
                <h3>Affordable Travel</h3>
                <p>
                    Exploring ways to make intercity rail travel more accessible and
                    cost-effective.
                </p>
            </div>

            <div class="card">
                <h3>Key City Connections</h3>
                <p>
                    A route concept connecting London, Birmingham and Manchester.
                </p>
            </div>

            <div class="card">
                <h3>More Communities Served</h3>
                <p>
                    Up to fifteen stops intended to connect more places along the
                    corridor.
                </p>
            </div>

        </div>

    </div>
</section>

<section id="route">
    <div class="container">

        <h2 class="section-title">Proposed Route</h2>

        <div class="route-box">
            <p>
                Purplelink proposes a low-cost route between
                <strong>London</strong> and <strong>Manchester</strong> via
                <strong>Birmingham</strong>, serving additional communities through
                multiple intermediate stops.
            </p>
        </div>

    </div>
</section>

<section id="faq" class="faq">
    <div class="container">

        <h2 class="section-title">Frequently Asked Questions</h2>

        <details>
            <summary>Is Purplelink currently operating trains?</summary>
            <p>
                No. Purplelink is a student startup concept and is not currently
                operating rail services.
            </p>
        </details>

        <details>
            <summary>Who is Purplelink for?</summary>
            <p>
                Rail travellers seeking affordable travel between major cities and
                communities along the route.
            </p>
        </details>

        <details>
            <summary>What does "15 Stops for Less" mean?</summary>
            <p>
                It reflects the concept of serving multiple locations while focusing
                on affordable travel.
            </p>
        </details>

        <details>
            <summary>Can I book tickets through this website?</summary>
            <p>
                No. This website is informational only and does not provide ticket
                sales or booking services.
            </p>
        </details>

        <details>
            <summary>Is Purplelink endorsed by a university?</summary>
            <p>
                No. No university endorsement is claimed. This is simply a student
                startup concept.
            </p>
        </details>

    </div>
</section>

<footer>
    <div class="container">
        <h3>Purplelink</h3>
        <p>15 Stops for Less</p>
        <p>
            Student startup concept for affordable rail travel between London,
            Birmingham and Manchester.
        </p>
    </div>
</footer>

</body>
</html>
