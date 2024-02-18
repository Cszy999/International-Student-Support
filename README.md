# International-Student-Support
A guide page for International Student in Japan
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>留学生支援</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <h1>留学生支援</h1>
  <h2>International Student Support</h2>

  <div id="big-image">
    <img src="image 1.jpg" alt="Image 1">
  </div>

  <div class="image-container">
    <div>
    <p><img src="image 2.png"></p>
    <figcaption><a href="携帯番号作り方.html">携帯番号作り方<br>[けいたいばんごつくりかた]</a></figcaption>
    </div>
    <div>
    <p><img src="image 3.jpg"></p>
    <figcaption><a href="在留&ビサ.html">在留&ビサ<br>[ざいりゅう&びさ]</a></figcaption>
    </div>
    <div>
    <p><img src="image 4.png"></p>
    <figcaption><a href="銀行.html">銀行<br>[ぎんこう]</a></figcaption>
    </div>
    <div>
    <p><img src="image 5.jpg"></p>
    <figcaption><a href="市役所.html">市役所<br>[しやくしょ]</a></figcaption>
    </div>
    </div>

    <div class="additional-text">
    <div>
      <p><a href="https://www.jreast.co.jp/map/">路線案内<br>[ろせんあんない]</a></p>
      <figcaption><img src="image 6.png"></figcaption>
     </div>
     <div>
      <p><a href="https://www.moj.go.jp/isa/content/930004449.pdf">日本のマナー<br>[にほんのまなー]</a></p>
      <figcaption><img src="image 7.png"></figcaption>
     </div>
     <div>
      <p><a href="https://townwork.net/magazine/knowhow/mensetsu/baito_mst/">アルバイト<br>[あるばいと]</a></p>
      <figcaption><img src="image 8.jpg"></figcaption>
     </div>
     </div>

</body>
</html>
body {
  text-align: center;
  font-family: Arial, sans-serif;
  margin: 0;
  padding-bottom: 50px; 
  padding-top: 50px;
}

h1 {
  color: #333;
  font-size: 70px;
  background-color: #eae4ab;
}

h2 {
  color: #eae4ab;
  font-size: 50px;
}

#big-image img {
  max-width: 100%; 
  height: auto; 
}

.subtitle {
  display: flex;
  flex-direction: column; 
  align-items: center;
  margin: 20px 0;
}

.subtitle h2 {
  font-size: 10px;
  margin-bottom: 5px; 
  background-color: #eae4ab;
}

.image-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin: 20px 0;
  background-color: #eae4ab;
}

.image-container img {
  width: 150px;
  cursor: pointer;
}

.additional-text {
  display: flex;
  justify-content: center;
  background-color: #eae4ab;
}

.additional-text div {
  margin: 0 130px; 
  background-color: #eae4ab;
}

.additional-text figcaption img {
  width: 150px; 
  height: 150px;
  object-fit: cover;
  background-color: #eae4ab;
  cursor: pointer;
  margin-bottom: 20px;
}
