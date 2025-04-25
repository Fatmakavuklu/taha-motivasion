# taha-motivasion
<!DOCTYPE html>

<html lang="tr">

<head>

  <meta charset="UTF-8">

  <title>Taha İçin Motive Sayfası 💪</title>

  <style>

    body {

      background: linear-gradient(to right, #ffe0e9, #e0f7ff);

      font-family: 'Segoe UI', sans-serif;

      text-align: center;

      padding: 50px;

      color: #333;

    }

    h1 {

      font-size: 2.5em;

      margin-bottom: 20px;

    }

    #quote {

      font-size: 1.8em;

      font-weight: bold;

      margin: 40px auto;

      max-width: 700px;

    }

    #footer {

      margin-top: 50px;

      font-size: 1.2em;

      color: #888;

    }

    button {

      margin-top: 30px;

      padding: 10px 20px;

      font-size: 1em;

      background-color: #ffb3c1;

      border: none;

      border-radius: 10px;

      cursor: pointer;

      transition: 0.3s;

    }

    button:hover {

      background-color: #ff6f91;

      color: white;

    }

  </style>

</head>

<body>

  <h1>TAHA! 💪 Sen Her Şeyi Başarırsın!</h1>

  <div id="quote">Yükleniyor...</div>

  <button onclick="showQuote()">Bir tane daha göster!</button>



  <div id="footer">

    Bunu sana <strong>Fatma</strong> gönderdi. Çünkü seni seviyor. 💖<br>

    #AşkKazanacak

  </div>



  <!-- Danza Kuduro müzik -->

  <audio autoplay loop>

    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">

    Tarayıcın müziği desteklemiyor 😔

  </audio>



  <script>

    const quotes = [

      "Zor günler geçer, sen kalırsın. Güçlüsün!",

      "Bugün sıkı çalış, yarın hayallerine yaklaş!",

      "Kendine inan Taha, çünkü ben sana inanıyorum.",

      "Her adımda ben senin yanındayım.",

      "Sen bu dünyanın en çalışkan erkeğisin!",

      "Kahve molasında bile aklımdasın 💭",

      "Yorgunsun ama asla yalnız değilsin.",

      "Taha, bu dünyanın kodunu sen yazarsın!",

      "Gözlerin yorulsa da yüreğin hep parlıyor."

    ];



    function showQuote() {

      const quote = quotes[Math.floor(Math.random() * quotes.length)];

      document.getElementById("quote").textContent = quote;

    }



    window.onload = showQuote;

  </script>

</body>

</html>
