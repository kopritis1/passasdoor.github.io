<!doctype html>
<html lang="el">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>PASSASDOOR — Αλουμίνια & Σίδερα</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <header class="site-header">
    <h1>PASSASDOOR</h1>
    <p class="tagline">Αλουμίνια • Σίδερα • Πέργκολες</p>
  </header>

  <main class="container">
    
    <section id="about">
      <h2>Σχετικά με εμάς</h2>
      <p>
        Η <strong>PASSASDOOR</strong> ειδικεύεται στην κατασκευή, συντήρηση και τοποθέτηση
        κατασκευών αλουμινίου και σιδήρου. Με πολυετή εμπειρία και συνέπεια, προσφέρουμε
        λύσεις υψηλής ποιότητας για οικιακούς και επαγγελματικούς χώρους.
      </p>
    </section>

    <section id="services">
      <h2>Υπηρεσίες</h2>
      <ul>
        <li>Κατασκευή, συντήρηση και τοποθέτηση αλουμινίων</li>
        <li>Κάγκελα, πόρτες ασφαλείας & γκαραζόπορτες</li>
        <li>Αυλόπορτες, πέργκολες & αυτοματισμοί</li>
      </ul>
    </section>

    <section id="gallery">
      <h2>Φωτογραφίες Έργων</h2>
      <div class="gallery">
        <img src="images/example1.jpg" alt="Πόρτα αλουμινίου">
        <img src="images/example2.jpg" alt="Πέργκολα">
        <img src="images/example3.jpg" alt="Κάγκελα">
      </div>
      <p class="note">➡️ Ανέβασε τις δικές σου φωτογραφίες στον φάκελο <strong>images</strong>.</p>
    </section>

    <section id="clock">
      <h2>Ώρα Ελλάδας</h2>
      <iframe src="https://free.timeanddate.com/clock/i94a0k6r/n26/tle/gr" frameborder="0" width="100%" height="90"></iframe>
    </section>

    <section id="youtube">
      <h2>Δείτε μας στο YouTube</h2>
      <iframe width="100%" height="315"
        src="https://www.youtube.com/embed?listType=user_uploads&list=nikospassas9833"
        title="YouTube channel" frameborder="0" allowfullscreen></iframe>
    </section>

    <section id="tiktok">
      <h2>PASSASDOOR στο TikTok</h2>
      <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@PASSASDOOR" data-video-id="" style="max-width: 605px;min-width: 325px;" >
        <section>Δες τα βίντεό μας!</section>
      </blockquote>
      <script async src="https://www.tiktok.com/embed.js"></script>
    </section>

    <section id="radio">
      <h2>Ακούστε Happy Efem</h2>
      <audio controls>
        <source src="https://stream.radiojar.com/happyefem" type="audio/mpeg">
        Ο browser σας δεν υποστηρίζει audio element.
      </audio>
    </section>

    <section id="map">
      <h2>Πού θα μας βρείτε</h2>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3110.0000000000005!2d23.875000!3d37.950000!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x14a1b8e6c8e1f87b%3A0x0!2sKoropi%2C+Greece!5e0!3m2!1sel!2sus!4v1698200000000" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>

    <section id="contact">
      <h2>Επικοινωνία</h2>
      <p>📞 Τηλέφωνο: <strong>6988 560643</strong></p>
      <p>✉️ Email: <a href="mailto:passasdoor@gmail.com">passasdoor@gmail.com</a></p>
    </section>

  </main>

  <footer class="site-footer">
    <p>© <span id="year"></span> PASSASDOOR</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>

</body>
</html>

