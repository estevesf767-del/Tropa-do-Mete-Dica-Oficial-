<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Tropa do Mete Dica | Comunidade</title>

<meta name="description" content="Tropa do Mete Dica — uma família formada por Onach Smith, Rei Delas, Tiboss e Senhor Dorama. União, respeito, lealdade, disciplina e evolução.">

<meta name="keywords" content="Tropa do Mete Dica, Onach Smith, Rei Delas, Tiboss, Senhor Dorama">

<meta name="author" content="Tropa do Mete Dica">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    background:#050505;
    color:#fff;
    line-height:1.6;
}

/* BARRA DE NAVEGAÇÃO */

nav{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    z-index:1000;
    background:rgba(0,0,0,.92);
    border-bottom:1px solid #b30000;
    backdrop-filter:blur(10px);
}

.nav-container{
    max-width:1100px;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 20px;
}

.logo{
    color:#ff1a1a;
    font-size:20px;
    font-weight:bold;
    letter-spacing:2px;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

nav a:hover{
    color:#ff1a1a;
}

/* HERO */

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:100px 20px 60px;

    background:
    radial-gradient(circle at center, #300000 0%, #090000 35%, #000 75%);
}

.hero-content{
    max-width:850px;
}

.logo-circle{
    width:120px;
    height:120px;
    margin:0 auto 25px;

    display:flex;
    align-items:center;
    justify-content:center;

    border:3px solid #ff0000;
    border-radius:50%;

    background:#090909;

    box-shadow:
    0 0 15px #ff0000,
    0 0 40px rgba(255,0,0,.5);

    font-size:50px;

    animation:pulse 2s infinite;
}

@keyframes pulse{

    0%,100%{
        box-shadow:
        0 0 15px #ff0000,
        0 0 40px rgba(255,0,0,.4);
    }

    50%{
        box-shadow:
        0 0 30px #ff0000,
        0 0 70px rgba(255,0,0,.7);
    }

}

.hero h1{
    font-size:clamp(35px,8vw,75px);
    letter-spacing:4px;
    margin-bottom:15px;

    background:linear-gradient(90deg,#fff,#ff1a1a,#fff);
    -webkit-background-clip:text;
    color:transparent;
}

.hero p{
    font-size:20px;
    color:#ddd;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:15px 30px;

    background:#d00000;
    color:white;

    text-decoration:none;
    font-weight:bold;

    border-radius:30px;

    box-shadow:0 0 20px rgba(255,0,0,.4);

    transition:.3s;
}

.btn:hover{
    background:#ff0000;
    transform:translateY(-4px);
    box-shadow:0 0 35px rgba(255,0,0,.8);
}

/* SEÇÕES */

section{
    padding:90px 20px;
}

.container{
    max-width:1100px;
    margin:auto;
}

.section-title{
    text-align:center;
    font-size:38px;
    margin-bottom:45px;
    color:#ff1a1a;
}

/* SOBRE */

.about{
    background:#090909;
}

.about-box{
    background:linear-gradient(145deg,#151515,#080808);

    border:1px solid #3a0000;

    border-radius:20px;

    padding:35px;

    box-shadow:0 0 25px rgba(255,0,0,.1);
}

.about-box p{
    font-size:18px;
    color:#ddd;
    margin-bottom:15px;
}

/* MEMBROS */

.members{
    background:#050505;
}

.members-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:25px;
}

.member-card{
    background:linear-gradient(145deg,#151515,#080808);

    border:1px solid #3b0000;

    border-radius:20px;

    padding:30px;

    text-align:center;

    transition:.4s;

    position:relative;
    overflow:hidden;
}

.member-card::before{
    content:"";
    position:absolute;
    top:0;
    left:0;

    width:100%;
    height:4px;

    background:#ff0000;
}

.member-card:hover{
    transform:translateY(-8px);

    border-color:#ff0000;

    box-shadow:0 0 30px rgba(255,0,0,.25);
}

.member-icon{
    width:85px;
    height:85px;

    margin:0 auto 20px;

    border-radius:50%;

    display:flex;
    justify-content:center;
    align-items:center;

    background:#160000;

    border:2px solid #ff0000;

    font-size:35px;
}

.member-card h3{
    color:#ff3333;
    font-size:25px;
    margin-bottom:12px;
}

.member-card p{
    color:#ccc;
}

.social-name{
    margin-top:15px;
    font-size:14px;
    color:#999;
}

/* VALORES */

.values{
    background:
    linear-gradient(rgba(20,0,0,.8),rgba(0,0,0,.95));
}

.values-grid{
    display:grid;
    grid-template-columns:repeat(5,1fr);
    gap:15px;
}

.value{
    padding:25px 10px;

    text-align:center;

    background:#0c0c0c;

    border:1px solid #330000;

    border-radius:15px;

    transition:.3s;
}

.value:hover{
    border-color:#ff0000;
    transform:scale(1.04);
}

.value span{
    display:block;
    font-size:30px;
    margin-bottom:10px;
}

.value h3{
    color:#ff3333;
}

/* REDES SOCIAIS */

.social{
    background:#090909;
}

.social-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
}

.social-card{
    display:block;

    text-align:center;

    padding:25px 15px;

    background:#111;

    border:1px solid #330000;

    border-radius:15px;

    text-decoration:none;

    color:white;

    transition:.3s;
}

.social-card:hover{
    background:#1c0000;
    border-color:#ff0000;
    transform:translateY(-5px);
}

.social-card span{
    font-size:35px;
    display:block;
    margin-bottom:10px;
}

.social-card strong{
    color:#ff3333;
}

/* FRASE FINAL */

.quote{
    padding:100px 20px;

    text-align:center;

    background:
    radial-gradient(circle,#350000,#050505 65%);
}

.quote h2{
    font-size:clamp(30px,6vw,55px);
    color:white;
}

.quote p{
    margin-top:15px;
    color:#ff3333;
    font-size:20px;
}

/* FOOTER */

footer{
    background:#000;

    border-top:1px solid #330000;

    padding:30px 20px;

    text-align:center;

    color:#888;
}

footer strong{
    color:#ff1a1a;
}

/* ANIMAÇÃO */

.reveal{
    animation:reveal 1s ease;
}

@keyframes reveal{

    from{
        opacity:0;
        transform:translateY(30px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }

}

/* MOBILE */

@media(max-width:800px){

    nav ul{
        display:none;
    }

    .members-grid{
        grid-template-columns:1fr;
    }

    .values-grid{
        grid-template-columns:repeat(2,1fr);
    }

    .social-grid{
        grid-template-columns:repeat(2,1fr);
    }

}

@media(max-width:500px){

    .hero h1{
        letter-spacing:2px;
    }

    .hero p{
        font-size:17px;
    }

    .values-grid{
        grid-template-columns:1fr;
    }

    .social-grid{
        grid-template-columns:1fr;
    }

    .about-box{
        padding:25px;
    }

}

</style>
</head>

<body>

<!-- NAVEGAÇÃO -->

<nav>

<div class="nav-container">

<div class="logo">
⚔️ METE DICA
</div>

<ul>
<li><a href="#inicio">Início</a></li>
<li><a href="#sobre">Sobre</a></li>
<li><a href="#membros">Membros</a></li>
<li><a href="#valores">Valores</a></li>
<li><a href="#redes">Redes</a></li>
</ul>

</div>

</nav>


<!-- INÍCIO -->

<section class="hero reveal" id="inicio">

<div class="hero-content">

<div class="logo-circle">
⚔️
</div>

<h1>TROPA DO METE DICA</h1>

<p>
🖤 Mais que uma tropa, somos uma família. 🔴
</p>

<a href="#sobre" class="btn">
CONHECER A TROPA
</a>

</div>

</section>


<!-- SOBRE -->

<section class="about" id="sobre">

<div class="container">

<h2 class="section-title">
SOBRE A TROPA
</h2>

<div class="about-box">

<p>
⚔️ <strong>TROPA DO METE DICA</strong> ⚔️
</p>

<p>
Mais que uma tropa, somos uma família.
</p>

<p>
A Tropa do Mete Dica é uma comunidade formada por quatro membros que compartilham amizade, ideias, momentos e vontade de evoluir juntos.
</p>

<p>
Nossa força está na união, no respeito e na lealdade entre todos os membros.
</p>

<p>
📌 Nossa missão: crescer juntos, compartilhar ideias, criar momentos e fortalecer a amizade.
</p>

</div>

</div>

</section>


<!-- MEMBROS -->

<section class="members" id="membros">

<div class="container">

<h2 class="section-title">
NOSSOS MEMBROS
</h2>

<div class="members-grid">


<!-- ONACH -->

<div class="member-card">

<div class="member-icon">
👑
</div>

<h3>ONACH SMITH</h3>

<p>
Membro da Tropa do Mete Dica.
</p>

<div class="social-name">
Facebook: Onach Itach<br>
TikTok: @onach_smith
</div>

</div>


<!-- REI DELAS -->

<div class="member-card">

<div class="member-icon">
🔥
</div>

<h3>REI DELAS</h3>

<p>
Membro da Tropa do Mete Dica.
</p>

<div class="social-name">
Facebook: Tobla Rápido
</div>

</div>


<!-- TIBOSS -->

<div class="member-card">

<div class="member-icon">
⚡
</div>

<h3>TIBOSS</h3>

<p>
Membro da Tropa do Mete Dica.
</p>

<div class="social-name">
Facebook: Adriano Armindo Esteves
</div>

</div>


<!-- SENHOR DORAMA -->

<div class="member-card">

<div class="member-icon">
🎭
</div>

<h3>SENHOR DORAMA</h3>

<p>
Membro da Tropa do Mete Dica.
</p>

<div class="social-name">
Facebook: Mariano Monteiro
</div>

</div>


</div>

</div>

</section>


<!-- VALORES -->

<section class="values" id="valores">

<div class="container">

<h2 class="section-title">
NOSSOS VALORES
</h2>

<div class="values-grid">

<div class="value">
<span>🤝</span>
<h3>União</h3>
</div>

<div class="value">
<span>❤️</span>
<h3>Respeito</h3>
</div>

<div class="value">
<span>🛡️</span>
<h3>Lealdade</h3>
</div>

<div class="value">
<span>🎯</span>
<h3>Disciplina</h3>
</div>

<div class="value">
<span>🔥</span>
<h3>Evolução</h3>
