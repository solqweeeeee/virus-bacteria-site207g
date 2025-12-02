<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🔬 Вирустар мен бактериялар: айырмашылықтары мен маңызы</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
    body {
        font-family: 'Poppins', sans-serif;
        margin: 0;
        background: #F7F9FF;
        color: #455A64;
    }

    /* ------- TOP ORGANIZATION HEADER ------- */
    .top-block {
        background: #A3C9F4;
        color: white;
        text-align: center;
        padding: 22px;
        border-bottom: 7px solid #89B9EB;
    }
    .org-name { font-size: 20px; font-weight: bold; }
    .dep-name { font-size: 15px; margin-top: 4px; }

    header {
        font-size: 30px;
        font-weight: 700;
        padding: 20px;
        text-align: center;
    }

    .container {
        max-width: 1100px;
        margin: auto;
        padding: 15px;
    }

    section {
        background: #FFFFFF;
        margin: 25px 0;
        padding: 25px;
        border-radius: 18px;
        box-shadow: 0 6px 18px rgba(0,0,0,0.12);
        transition: .3s;
    }

    section:hover { transform: translateY(-4px); }

    h2 {
        font-size: 26px;
        color: #F4A3B4;
        border-left: 6px solid #F4A3B4;
        padding-left: 12px;
        margin-bottom: 15px;
    }

    h3 { font-size: 20px; color: #A3C9F4; }

    p, ul, ol, table { font-size: 17px; line-height: 1.65; }

    table {
        width: 100%;
        border-collapse: collapse;
        margin-top: 20px;
    }
    th, td {
        border: 1px solid #D7E4F5;
        padding: 12px;
    }
    th {
        background: #A3C9F4;
        color: white;
    }
    tr:nth-child(even) { background: #F2F6FF; }

    .note {
        background: #FFF5F7;
        border-left: 5px solid #F4A3B4;
        padding: 15px;
        border-radius: 8px;
        margin-top: 15px;
    }

    /* ------ DIAGRAMS ------ */
    .diagram-container {
        display: flex;
        gap: 20px;
        flex-wrap: wrap;
        justify-content: center;
    }
    .diagram-figure { flex: 1; min-width: 230px; text-align: center; }

    /* ------ FOOTER ------ */
    footer {
        background: #A3C9F4;
        color: white;
        text-align: center;
        padding: 20px;
        margin-top: 30px;
        font-size: 16px;
        border-top: 4px solid #89B9EB;
    }

    /* ---------- MOBILE ADAPTATION ---------- */
    @media (max-width: 600px) {
        header { font-size: 22px; padding: 10px; }
        
        .org-name { font-size: 17px; }
        .dep-name { font-size: 13px; }

        section { padding: 15px; }

        h2 { font-size: 20px; }
        h3 { font-size: 17px; }

        p, ul, ol, table { font-size: 15px; }

        table th, table td { padding: 8px; font-size: 13px; }

        .diagram-container {
            flex-direction: column;
            gap: 15px;
        }
    }
</style>
</head>

<body>

<!-- TOP INFO -->
<div class="top-block">
    <div class="org-name">КеАҚ “Астана медицина университеті”</div>
    <div class="dep-name">Ш.И.Сарбасова атындағы микробиология және вирусология кафедрасы</div>
</div>

<header>🔬 Вирустар мен бактериялар: Салыстырмалы Биология</header>

<div class="container">

<section>
<h2>✨ Кіріспе</h2>
<p><b>Вирус</b> – тірі жасуша ішінде ғана көбейетін, генетикалық материал мен ақуыз қабықтан тұратын бөлшек.</p>
<p><b>Бактерия</b> – толыққанды жасушалық құрылысы бар бір жасушалы тірі организм.</p>

<div class="note">
<b>Негізгі айырмашылық:</b> Вирустар – паразиттер, бактериялар – дербес организмдер.
</div>
</section>

<section>
<h2>🧬 Құрылымдық айырмашылықтар</h2>

<h3>Вирустар</h3>
<ul>
  <li>Генетикалық материал + капсид.</li>
  <li>Өлшемі: 20–300 нм.</li>
  <li>Жасушасыз, тек иесінде көбейеді.</li>
</ul>

<h3>Бактериялар</h3>
<ul>
  <li>Жасушалық құрылым толық: қабықша, қабырша, цитоплазма, рибосомалар.</li>
  <li>Өлшемі: 0.5–5 мкм.</li>
  <li>Өздігінен өмір сүре алады.</li>
</ul>
</section>

<section>
<h2>📝 Құрылымдық диаграммалар</h2>

<div class="diagram-container">

    <figure class="diagram-figure">
        <figcaption style="font-size: 13px;">Вирустың диаграммасы</figcaption>
        <svg viewBox="0 0 200 120">
            <defs>
                <linearGradient id="g1" x1="0" x2="1">
                    <stop offset="0%" stop-color="#D32F2F" />
                    <stop offset="100%" stop-color="#EF9A9A" />
                </linearGradient>
            </defs>
            <rect x="10" y="30" width="180" height="60" rx="30" fill="#F3F4F6" />
            <ellipse cx="100" cy="60" rx="48" ry="28" fill="url(#g1)" />
            <circle cx="100" cy="60" r="10" fill="#fff" />
        </svg>
    </figure>

    <figure class="diagram-figure">
        <figcaption style="font-size: 13px;">Бактерия диаграммасы</figcaption>
        <svg viewBox="0 0 200 120">
            <rect x="12" y="28" width="176" height="64" rx="28" fill="#F8FAFC" />
            <rect x="28" y="40" width="140" height="40" rx="20" fill="#3F51B5" />
            <circle cx="80" cy="60" r="8" fill="#fff" />
            <circle cx="130" cy="60" r="6" fill="#fff" />
        </svg>
    </figure>

</div>
</section>

<section>
<h2>🔄 Метаболизм және репродукция</h2>

<h3>Вирустар</h3>
<ol>
  <li>Адсорбция</li>
  <li>Ену</li>
  <li>Репликация</li>
  <li>Жинақталу</li>
  <li>Шығу</li>
</ol>

<h3>Бактериялар</h3>
<ul>
  <li>Бинарлық бөліну</li>
  <li>Конъюгация, трансформация, трансдукция</li>
  <li>Толыққанды метаболизм</li>
</ul>
</section>

<section>
<h2>💊 Емдеу әдістері</h2>

<h3>Вирустар</h3>
<ul>
  <li>Антивирустық дәрілер</li>
  <li>Вакцинация</li>
</ul>

<h3>Бактериялар</h3>
<ul>
  <li>Антибиотиктер әсер етеді</li>
  <li>Вакциналар бар</li>
  <li>Антибиотикке төзімділік дамиды</li>
</ul>
</section>

<section>
<h2>🌍 Экологиялық рөлі</h2>

<h3>Вирустар</h3>
<ul>
  <li>Микроорганизмдер санын реттейді</li>
  <li>Гендік терапияда қолданылады</li>
</ul>

<h3>Бактериялар</h3>
<ul>
  <li>Азот және көміртек айналымы</li>
  <li>Өндірісте қолданылады</li>
  <li>Ішек микрофлорасы</li>
</ul>
</section>

<section>
<h2>📊 Кестелік салыстыру</h2>

<table>
  <tr><th>Параметр</th><th>Вирус</th><th>Бактерия</th></tr>
  <tr><td>Құрылысы</td><td>Жасушасыз</td><td>Жасуша</td></tr>
  <tr><td>Өлшемі</td><td>20–300 нм</td><td>0.5–5 мкм</td></tr>
  <tr><td>Көбею</td><td>Жасуша ішінде</td><td>Бинарлық бөліну</td></tr>
  <tr><td>Метаболизм</td><td>Жоқ</td><td>Бар</td></tr>
  <tr><td>Генетикалық материал</td><td>ДНҚ немесе РНҚ</td><td>ДНҚ</td></tr>
  <tr><td>Емдеу</td><td>Антивирус</td><td>Антибиотик</td></tr>
  <tr><td>Аурулар</td><td>Тұмау, COVID-19</td><td>Туберкулез, Ангина</td></tr>
</table>
</section>

<section>
<p style="text-align: center; font-size: 14px;">
    Орындаған: 207-педиатрия <br>
    Айтмағанбет Іңкәр, Жаек Жұлдыз, Ромазан Ақнұр
</p>
</section>

</div>


</body>
</html>
<div class="feedback-section">
    <h2>📝 Ваш отзыв о макете</h2>
    <p>Оцените нашу работу:</p>

    <div class="stars" id="stars">
        <span data-star="1">★</span>
        <span data-star="2">★</span>
        <span data-star="3">★</span>
        <span data-star="4">★</span>
        <span data-star="5">★</span>
    </div>

    <textarea id="comment" placeholder="Напишите ваш комментарий..." rows="4"></textarea>

    <button id="sendFeedback">Отправить</button>

    <p id="thanksMessage" style="display:none; margin-top: 10px; color: green;">
        Спасибо за ваш отзыв! ⭐
    </p>
</div>



<footer>
© 2025 Вирустар мен бактериялар порталы. Ғылым үшін.
</footer>
