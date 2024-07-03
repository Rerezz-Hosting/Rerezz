<IM REREZ HOSTING>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Projects</title>

    <!-- My CSS -->
    <link rel="stylesheet" href="../css/style.css" />

    <!-- Font Awesome -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
      integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />

    <!-- AOS -->
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  </head>
  <body>
    <header>
      <button onclick="alert('Hello People! Welcome to My Project.')">
        <div class="share-button">
          <i class="fa-solid fa-hand"></i>
          <!-- <p>Share</p> -->
        </div>
      </button>
    </header>
    <div class="container">
      <h1 class="name"><a href="https://t.me/rerez_x_hosting">PROJECT REREZZ HOSTING</a></h1>

      <!-- 1 -->
      <a
        href="https://www.mediafire.com/file/eeq25dtyu4izz7q/Project+Rerez+V+10.0.0.zip/file"
        class="tile"
        data-aos="zoom-in"
        data-aos-duration="500"
      >
        <div class="icon" link="https://www.mediafire.com/file/eeq25dtyu4izz7q/Project+Rerez+V+10.0.0.zip/file">
          <i class=""></i>
        </div>
        <p>SECRIPT MULTI DEVICE V 1.0.0.0</p>
        <div class="tile-share-button">
          <i class="fa-solid fa-share"></i>
        </div>
      </a>

      <!-- 2 -->
      <a
        href="https://www.mediafire.com/file/9v3mo3wr8zlmppn/Sc+cpanel+by+Rerez+v+1.0.0.zip/file"
        class="tile"
        data-aos="zoom-in"
        data-aos-duration="1000"
      >
        <div class="icon" link="https://www.mediafire.com/file/9v3mo3wr8zlmppn/Sc+cpanel+by+Rerez+v+1.0.0.zip/file">
          <i class=""></i>
        </div>
        <p>SECRIPT CPANEL V 2.0.0</p>
        <div class="tile-share-button">
          <i class="fa-solid fa-share"></i>
        </div>
      </a>

      <!-- 3 -->
      <a
        href="https://www.mediafire.com/file/ufwls561gezdjcr/Cpanel+v3+by+Rerez.zip/file"
        class="tile"
        data-aos="zoom-in"
        data-aos-duration="1500"
      >
        <div class="icon" link="https://www.mediafire.com/file/ufwls561gezdjcr/Cpanel+v3+by+Rerez.zip/file">
          <i class=""></i>
        </div>
        <p>SECRIPT CPANEL V 3.0.0</p>
        <div class="tile-share-button">
          <i class="fa-solid fa-share"></i>
        </div>
      </a>

      <!-- 4 -->
      <a
        href="https://whatsapp.com/channel/0029VacxTsC8F2p5dshCmq3r"
        class="tile"
        data-aos="zoom-in"
        data-aos-duration="2000"
      >
        <div class="icon" link="https://whatsapp.com/channel/0029VacxTsC8F2p5dshCmq3r">
          <i class=""></i>
        </div>
        <p>CHANEL WHATSAP</p>
        <div class="tile-share-button">
          <i class="fa-solid fa-share"></i>
        </div>
      </a>

      <footer class="footer">
        <span id="typing"></span>
      </footer>
    </div>

    <!-- My JS -->
    <script src="js/app.js"></script>

    <!-- AOS JS -->
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>

    <!-- Typeit Open -->
    <!-- TypeitJS -->
    <script src="https://unpkg.com/typeit@8.7.1/dist/index.umd.js"></script>
    <script>
      const nameInput = prompt("Whats your name");
      alert("Hello " + nameInput);

      new TypeIt("#typing", {
        speed: 50,
        waitUntilVisible: true,
      })
        .type("IM", { delay: 500 })
        .move(-2)
        .delete(1)
        .type("a")
        .move(null, { to: "END" })
        .type(" XYREZ", { delay: 100 })
        .pause(300)
        .type(" HOS")
        .move(-1)
        .delete(1)
        .type("TI")
        .move(null, { to: "END" })
        .type("NG")
        .pause(300)
        .move(-5)
        .type("📡")
        .move(null, { to: "END" })
        .type(" ")
        .go();
    </script>
  </body>
</html>
