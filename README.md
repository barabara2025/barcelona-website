<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقع نادي برشلونة</title>
  <style>
    body {
      margin: 0;
      font-family: "Cairo", sans-serif;
      direction: rtl;
      background: linear-gradient(to bottom right, #004d98, #a50044);
      color: white;
      transition: all 0.3s ease-in-out;
    }

    header {
      background: rgba(0, 0, 0, 0.7);
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: gold;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }

    nav {
      margin-top: 15px;
    }

    nav a {
      margin: 0 12px;
      text-decoration: none;
      color: white;
      padding: 10px 15px;
      font-weight: bold;
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 8px;
      transition: background 0.3s, transform 0.2s;
    }

    nav a:hover {
      background-color: rgba(255, 255, 255, 0.3);
      transform: scale(1.1);
    }

    main {
      padding: 30px;
      animation: fadeIn 1s ease;
    }

    main h2 {
      font-size: 2em;
      color: gold;
      margin-bottom: 15px;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      justify-items: center;
    }

    .card {
      background: rgba(0, 0, 0, 0.5);
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      width: 100%;
      max-width: 200px;
      transition: transform 0.3s, box-shadow 0.3s;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
    }

    .card:hover {
      transform: scale(1.1);
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      background: rgba(0, 0, 0, 0.5);
      margin: 5px 0;
      padding: 10px;
      border-radius: 8px;
      text-align: center;
    }

    ul li:hover {
      background: rgba(0, 0, 0, 0.7);
      transform: scale(1.05);
      transition: 0.3s;
    }

    button.share-btn {
      display: block;
      margin: 20px auto;
      background: gold;
      color: black;
      padding: 12px 25px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      font-size: 18px;
      font-weight: bold;
      transition: background 0.3s, transform 0.3s;
      box-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);
    }

    button.share-btn:hover {
      background: orange;
      transform: scale(1.1);
    }

    footer {
      background: rgba(0, 0, 0, 0.8);
      text-align: center;
      padding: 15px;
      color: white;
      font-size: 0.9em;
      margin-top: 30px;
    }

    footer a {
      color: gold;
      text-decoration: none;
      font-weight: bold;
    }

    footer a:hover {
      text-decoration: underline;
    }

    .social-share {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin: 20px 0;
    }

    .social-share a {
      text-decoration: none;
      color: white;
      font-size: 24px;
      padding: 10px;
      border-radius: 50%;
      background-color: rgba(0, 0, 0, 0.5);
      transition: background 0.3s, transform 0.3s;
    }

    .social-share a:hover {
      background-color: gold;
      transform: scale(1.2);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<header>
  <h1>نادي برشلونة</h1>
  <nav>
    <a href="#home">الرئيسية</a>
    <a href="#players">اللاعبين</a>
    <a href="#matches">المباريات</a>
    <a href="#history">تاريخ النادي</a>
  </nav>
</header>

<main id="home">
  <h2>مرحباً بك في الموقع الرسمي لمحبي برشلونة</h2>
  <p>كل جديد عن الفريق، اللاعبين، والمباريات ستجده هنا!</p>
  <button class="share-btn" onclick="shareSite()">📤 شارك الموقع</button>
  <div class="social-share">
    <a href="https://www.instagram.com/?url=https://example.com" target="_blank" title="شارك على إنستجرام">📷</a>
    <a href="https://www.facebook.com/sharer/sharer.php?u=https://example.com" target="_blank" title="شارك على فيسبوك">📘</a>
    <a href="https://twitter.com/intent/tweet?url=https://example.com&text=شاهد%20هذا%20الموقع%20الرائع%20لعشاق%20نادي%20برشلونة!" target="_blank" title="شارك على تويتر">🐦</a>
  </div>
</main>

<main id="players">
  <h2>لاعبي برشلونة الأساسيين</h2>
  <div class="grid">
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Robert_Lewandowski_2023.jpg" alt="ليفاندوفسكي">
      <p>ليفاندوفسكي</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Pedri_Spain.jpg" alt="بيدري">
      <p>بيدري</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/75/Lamine_Yamal_2023.jpg" alt="لامين يامال">
      <p>لامين يامال</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/Marc-Andr%C3%A9_ter_Stegen.jpg" alt="تير شتيغن">
      <p>تير شتيغن</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Frenkie_de_Jong_2022.jpg" alt="فرينكي دي يونغ">
      <p>فرينكي دي يونغ</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Raphinha_2023.jpg" alt="رافينيا">
      <p>رافينيا</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/1d/Joao_Felix_2023.jpg" alt="جواو فيليكس">
      <p>جواو فيليكس</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/03/Joao_Cancelo_2023.jpg" alt="جواو كانسيلو">
      <p>جواو كانسيلو</p>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Ilkay_Gundogan_2023.jpg" alt="غوندوغان">
      <p>إلكاي غوندوغان</p>
    </div>
  </div>
</main>

<main id="matches">
  <h2>جدول المباريات القادمة</h2>
  <ul>
    <li>برشلونة vs ريال بيتيس - 10 ماي 2025</li>
    <li>برشلونة vs ريال مدريد - 17 ماي 2025</li>
    <li>برشلونة vs إشبيلية - 24 ماي 2025</li>
  </ul>
</main>

<main id="history">
  <h2>تاريخ نادي برشلونة</h2>
  <p>
    تأسس نادي برشلونة سنة 1899. يعتبر من أنجح الفرق في العالم.
    فاز بعدة بطولات محلية وقارية، واشتهر بأسلوب التيكي تاكا ومدرسة لاماسيا.
  </p>
  <ul>
    <li>26 لقب لا ليغا</li>
    <li>31 كأس ملك إسبانيا</li>
    <li>5 دوري أبطال أوروبا</li>
  </ul>
</main>

<footer>
  <p>جميع الحقوق محفوظة © 2025 | <a href="#home">نادي برشلونة</a></p>
</footer>

<script>
  function shareSite() {
    if (navigator.share) {
      navigator.share({
        title: 'موقع نادي برشلونة',
        text: 'شاهد هذا الموقع لمحبي نادي برشلونة!',
        url: window.location.href
      }).catch(console.error);
    } else {
      alert("المشاركة غير مدعومة في هذا المتصفح 😕");
    }
  }
</script>

</body>
</html>
