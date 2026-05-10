<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Wasteland Rust</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#0f0f0f;
    color:white;
    overflow-x:hidden;
}

header{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.65), rgba(0,0,0,.85)),
    url("https://images.unsplash.com/photo-1511512578047-dfb367046420?q=80&w=1600&auto=format&fit=crop");
    background-size:cover;
    background-position:center;
    padding:20px 8%;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:#ff7b00;
    font-size:32px;
    font-weight:bold;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav a{
    color:white;
    text-decoration:none;
    transition:.2s;
}

nav a:hover{
    color:#ff7b00;
}

.hero{
    margin-top:140px;
    max-width:700px;
}

.hero h1{
    font-size:75px;
    line-height:1;
    margin-bottom:20px;
}

.hero p{
    color:#ddd;
    font-size:20px;
    margin-bottom:35px;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    background:#ff7b00;
    color:white;
    text-decoration:none;
    border-radius:10px;
    font-weight:bold;
    transition:.2s;
}

.btn:hover{
    transform:translateY(-3px);
}

section{
    padding:90px 8%;
}

.section-title{
    font-size:42px;
    margin-bottom:40px;
    color:#ff7b00;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1a1a1a;
    padding:30px;
    border-radius:14px;
    border:1px solid #2d2d2d;
}

.card h3{
    margin-bottom:15px;
    color:#ff7b00;
}

.server-info{
    background:#151515;
}

.info-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.info-box{
    background:#202020;
    padding:25px;
    border-radius:12px;
}

.info-box span{
    color:#999;
    display:block;
    margin-bottom:10px;
}

.discord{
    text-align:center;
}

.discord p{
    margin:20px 0 35px;
    color:#ccc;
}

footer{
    padding:30px;
    text-align:center;
    border-top:1px solid #222;
    color:#888;
}

@media(max-width:700px){

.hero h1{
    font-size:48px;
}

nav{
    flex-direction:column;
    gap:15px;
}

nav ul{
    flex-wrap:wrap;
    justify-content:center;
}
}
</style>
</head>

<body>

<header>

<nav>
<div class="logo">Wasteland Rust</div>

<ul>
<li><a href="#features">Особенности</a></li>
<li><a href="#server">Сервер</a></li>
<li><a href="#discord">Дискорд</a></li>
</ul>
</nav>

<div class="hero">
<h1>Выживай. Рейдь. Доминируй.</h1>

<p>
Лучший Rust сервер с активной администрацией,
честным PvP, ежемесячными вайпами и крутыми ивентами.
</p>

<a class="btn" href="steam://connect/127.0.0.1:28015">
ПОДКЛЮЧИТЬСЯ
</a>
</div>

</header>

<section id="features">
<h2 class="section-title">Почему именно мы</h2>

<div class="features">

<div class="card">
<h3>Кастомные Ивенты</h3>
<p>
Рейд-базы, PvP турниры,
битвы за карго и случайные события каждую неделю.
</p>
</div>

<div class="card">
<h3>Сбалансированная Игра</h3>
<p>
Честный лут, никаких Pay-to-Win наборов
и активная модерация.
</p>
</div>

<div class="card">
<h3>Высокая Производительность</h3>
<p>
Минимальный пинг, стабильный онлайн
и плавная игра даже во время рейдов.
</p>
</div>

</div>
</section>

<section class="server-info" id="server">

<h2 class="section-title">Информация о Сервере</h2>

<div class="info-grid">

<div class="info-box">
<span>IP Адрес</span>
<h3>127.0.0.1:28015</h3>
</div>

<div class="info-box">
<span>Размер Карты</span>
<h3>4250</h3>
</div>

<div class="info-box">
<span>Вайп Чертежей</span>
<h3>Каждый Месяц</h3>
</div>

<div class="info-box">
<span>Лимит Команды</span>
<h3>Макс. 5 Игроков</h3>
</div>

</div>
</section>

<section class="discord" id="discord">

<h2 class="section-title">Присоединяйся к Сообществу</h2>

<p>
Следи за вайпами, находи тиммейтов
и узнавай новости сервера первым.
</p>

<a class="btn" href="#">
JOIN DISCORD
</a>

</section>

<footer>
© 2026 Wasteland Rust — All Rights Reserved
</footer>

</body>
</html>
