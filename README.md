# Afra-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>About Me - Afra Anjum</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0 20px 40px;
      background: #f9f9f9;
      color: #333;
    }
    /* Background banner */
    .banner {
      background-image: url('IMG_1932.jpeg');
      background-size: cover;
      background-position: center;
      width: 100%;
      height: 300px;
      position: relative;
      margin-bottom: 100px; /* space for profile pic */
    }
    /* Profile picture styling */
    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      position: absolute;
      bottom: -75px;
      left: 50%;
      transform: translateX(-50%);
      background: white;
    }
    /* Container to position profile pic relative to banner */
    .banner-container {
      position: relative;
      margin-bottom: 100px;
    }
    /* Sections styling */
    section {
      max-width: 600px;
      margin: auto;
    }
    h1, h2 {
      text-align: center;
      margin-top: 0;
    }
    ul {
      list-style-type: disc;
      padding-left: 20px;
    }
    /* Contact styling */
    .contact ul {
      list-style: none;
      padding-left: 0;
      text-align: center;
    }
    .contact li {
      margin-bottom: 10px;
      font-size: 1.1em;
    }
    .contact a {
      color: #0073e6;
      text-decoration: none;
    }
    .contact a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="banner-container">
    <div class="banner"></div>
    <img src="IMG_1933.jpeg" alt="Profile Picture" class="profile-pic" />
  </div>

  <h1>About Me</h1>
  <p>Hey there! I’m Afra Anjum. Here are some subtle collection of things I am fond of.</p>

  <section>
    <h2>Favorite Sitcoms</h2>
    <ul>
      <li>30 Rock</li>
      <li>The Simpsons</li>
      <li>Everybody Hates Chris</li>
    </ul>

    <h2>Favorite Books</h2>
    <ul>
      <li><em>Metamorphosis</em> by Franz Kafka</li>
      <li><em>The Chronicles of Narnia</em> by C.S. Lewis</li>
      <li><em>What If?</em> by Randall Munroe</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contact Me</h2>
    <ul>
      <li>📧 <a href="mailto:afra2008anjum@gmail.com">afra2008anjum@gmail.com</a></li>
      <li>𝕏 <a href="https://x.com/afroarr" target="_blank" rel="noopener noreferrer">afraIRL</a></li>
      <li>📞 <a href="tel:01322859456">01322859456</a></li>
    </ul>
  </section>

</body>
</html>
