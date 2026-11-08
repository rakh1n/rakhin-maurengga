<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#102c3a">
  <meta name="description" content="Portofolio pribadi — profil, pendidikan, pengalaman, keahlian, minat, dan karya.">
  <meta property="og:type" content="website">
  <meta property="og:title" content="Portofolio Pribadi | Rakhin Maurengga">
  <meta property="og:description" content="Kenali profil, perjalanan, keahlian, dan karya saya.">
  <meta property="og:image" content="assets/cover.svg">
  <title>Portofolio Pribadi | Rakhin Maurengga</title>
  <link rel="icon" href="assets/favicon.svg" type="image/svg+xml">
  <link rel="stylesheet" href="styles.css">
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Nama Lengkap Anda",
    "description": "Portofolio pribadi dan profesional."
  }
  </script>
</head>
<body>
  <a class="skip-link" href="#konten">Lewati ke konten utama</a>
  <header class="site-header">
    <a class="brand" href="#beranda" aria-label="Beranda portofolio">
      <span class="brand-mark">P</span><span>PORTOFOLIO<span class="brand-dot">.</span></span>
    </a>
    <button class="menu-toggle" id="menuToggle" aria-label="Buka navigasi" aria-expanded="false">☰</button>
    <nav class="main-nav" id="mainNav" aria-label="Navigasi utama">
      <a href="#tentang">Tentang</a><a href="#pendidikan">Pendidikan</a><a href="#pengalaman">Pengalaman</a>
      <a href="#keahlian">Keahlian</a><a href="#karya">Karya</a><a href="#kontak" class="nav-cta">Hubungi saya ↗</a>
    </nav>
  </header>

  <main id="konten">
    <section class="hero section-wrap" id="beranda" aria-labelledby="heroTitle">
      <div class="hero-copy">
        <p class="eyebrow"><span class="eyebrow-line"></span> PROFIL &amp; PORTOFOLIO PERSONAL</p>
        <h1 id="heroTitle">Halo, saya<br><span class="accent">Rakhin Maurengga</span></h1>
        <p class="hero-role" id="heroRole">Profesi / Bidang yang Anda Tekuni</p>
        <p class="hero-intro" id="heroIntro">Saya adalah pribadi yang senang belajar, bertumbuh, dan mengubah ide menjadi karya yang bermanfaat. Selamat datang di ruang digital saya.</p>
        <div class="hero-actions">
          <a class="button button-primary" href="#tentang">Kenali saya <span aria-hidden="true">↘</span></a>
          <a class="text-link" href="#karya">Jelajahi karya <span aria-hidden="true">↗</span></a>
        </div>
        <div class="hero-social" id="heroSocial" aria-label="Tautan media sosial"></div>
      </div>
      <div class="hero-visual">
        <div class="portrait-frame">
          <img src="assets/avatar-placeholder.svg" alt="Ilustrasi tempat foto profil. Ganti dengan foto Anda." id="profilePhoto">
          <span class="portrait-label">RUANG PERSONAL / 01</span>
        </div>
        <div class="hero-note"><span class="note-star">✳</span><span>Terus bertumbuh.<br>Terus berkarya.</span></div>
        <div class="hero-index">01 — 06</div>
      </div>
      <div class="hero-bottom"><span>BERKENALAN LEBIH DEKAT</span><a href="#tentang" aria-label="Gulir ke bagian tentang">↓</a><span>SCROLL TO EXPLORE</span></div>
    </section>

    <section class="about section-wrap section-pad" id="tentang">
      <div class="section-heading"><p class="eyebrow">01 / TENTANG SAYA</p><h2>Lebih dari sekadar<br><span class="serif-accent">sebuah profil.</span></h2></div>
      <div class="about-content">
        <p class="about-lead" id="aboutLead">Saya percaya setiap pengalaman adalah kesempatan untuk belajar dan setiap proses memiliki cerita.</p>
        <p id="aboutText">Tuliskan perkenalan singkat tentang diri Anda di sini. Ceritakan latar belakang, nilai yang Anda pegang, hal yang sedang ditekuni, serta tujuan yang ingin dicapai.</p>
        <div class="quick-facts">
          <div><span class="fact-label">DOMISILI</span><strong id="domicile">Kota Singkawang, Indonesia</strong></div>
          <div><span class="fact-label">PENDIDIKAN TERAKHIR</span><strong id="lastEducation">D3 Teknik Informatika - Politeknik Negeri Pontianak</strong></div>
          <div><span class="fact-label">STATUS SAAT INI</span><strong id="currentStatus">Outsourcing (Tenaga Pendukung Multimedia) di Bappeda Kota Singkawang</strong></div>
        </div>
      </div>
    </section>

    <section class="education section-pad" id="pendidikan">
      <div class="section-wrap">
        <div class="section-heading"><p class="eyebrow">02 / LATAR BELAKANG</p><h2>Perjalanan <span class="serif-accent">pendidikan.</span></h2><p class="section-desc">Setiap ruang belajar membentuk cara saya melihat dunia.</p></div>
        <div class="timeline" id="educationList"></div>
      </div>
    </section>

    <section class="experience section-wrap section-pad" id="pengalaman">
      <div class="section-heading"><p class="eyebrow">03 / PENGALAMAN</p><h2>Langkah yang<br><span class="serif-accent">membentuk saya.</span></h2></div>
      <div class="experience-list" id="experienceList"></div>
    </section>

    <section class="skills section-pad" id="keahlian">
      <div class="section-wrap skills-layout">
        <div><p class="eyebrow">04 / KOMPETENSI</p><h2>Hal yang saya<br><span class="serif-accent">kuasai &amp; pelajari.</span></h2><p class="section-desc">Keahlian terus berkembang melalui praktik, kolaborasi, dan rasa ingin tahu.</p></div>
        <div class="skill-groups" id="skillGroups"></div>
      </div>
    </section>

    <section class="interests section-wrap section-pad" id="minat">
      <div class="section-heading"><p class="eyebrow">05 / DI LUAR PEKERJAAN</p><h2>Hal-hal yang membuat<br><span class="serif-accent">saya bersemangat.</span></h2></div>
      <div class="interest-grid" id="interestList"></div>
    </section>

    <section class="works section-pad" id="karya">
      <div class="section-wrap">
        <div class="works-heading"><div><p class="eyebrow">06 / RUANG BERKARYA</p><h2>Ide, proses,<br><span class="serif-accent">dan cerita.</span></h2></div><p class="section-desc">Tempat menyimpan hal-hal yang pernah saya buat, pelajari, dan bagikan.</p></div>
        <div class="work-grid" id="workGrid"></div>
        <div class="add-work-panel">
          <div><p class="eyebrow">PUNYA CERITA BARU?</p><h3>Tambahkan karya</h3><p>Isi formulir ini untuk menambahkan foto dan cerita ke galeri pada perangkat/browser ini.</p></div>
          <form id="workForm" class="work-form">
            <label>Judul karya<input name="title" required maxlength="80" placeholder="Contoh: Proyek desain identitas"></label>
            <label>Cerita singkat<textarea name="story" required maxlength="500" rows="3" placeholder="Ceritakan proses atau makna karya ini..."></textarea></label>
            <label>Foto / gambar<input name="image" type="file" accept="image/*"></label>
            <button class="button button-primary" type="submit">＋ Tambahkan karya</button>
            <p class="form-note" id="formNote" aria-live="polite">Catatan: karya yang ditambahkan tersimpan di browser ini, belum otomatis tampil di perangkat pengunjung lain.</p>
          </form>
        </div>
      </div>
    </section>

    <section class="contact section-wrap section-pad" id="kontak">
      <p class="eyebrow">MARI TERHUBUNG</p><h2>Selalu terbuka untuk<br><span class="serif-accent">percakapan baik.</span></h2>
      <p class="contact-copy">Punya ide, peluang kolaborasi, atau sekadar ingin menyapa? Silakan hubungi saya melalui kanal berikut.</p>
      <div class="contact-links" id="contactLinks"></div>
      <div class="contact-social" id="contactSocial"></div>
    </section>
  </main>

  <footer class="site-footer"><a class="brand" href="#beranda"><span class="brand-mark">P</span><span>PORTOFOLIO<span class="brand-dot">.</span></span></a><p>Dirancang sebagai ruang untuk bertumbuh dan berkarya.</p><span>© <span id="year"></span> Nama Anda</span></footer>

  <button class="access-trigger" id="accessTrigger" aria-expanded="false" aria-controls="accessPanel" aria-label="Buka menu aksesibilitas"><span aria-hidden="true">◉</span><span>Aksesibilitas</span></button>
  <aside class="access-panel" id="accessPanel" aria-label="Pengaturan aksesibilitas" hidden>
    <div class="access-head"><div><p class="eyebrow">PENGATURAN</p><h2>Aksesibilitas</h2></div><button id="closeAccess" class="icon-button" aria-label="Tutup menu aksesibilitas">×</button></div>
    <p class="access-hint">Sesuaikan tampilan atau dengarkan teks pada halaman.</p>
    <div class="access-control"><span>Ukuran teks</span><div class="inline-controls"><button id="fontDown" aria-label="Perkecil teks">A−</button><button id="fontReset" aria-label="Atur ulang teks">A</button><button id="fontUp" aria-label="Perbesar teks">A+</button></div></div>
    <div class="access-control"><label for="contrastMode">Kontras tampilan</label><select id="contrastMode"><option value="normal">Normal</option><option value="high">Kontras tinggi</option><option value="dark">Mode gelap</option></select></div>
    <div class="access-control"><label for="speechRate">Kecepatan suara</label><select id="speechRate"><option value="0.8">Lambat</option><option value="1" selected>Normal</option><option value="1.2">Cepat</option></select></div>
    <div class="speech-buttons"><button id="readPage" class="button button-primary">▶ Bacakan halaman</button><button id="readSelection" class="button button-outline">Bacakan teks pilihan</button><button id="stopSpeech" class="button button-quiet">■ Hentikan suara</button></div>
    <p id="speechStatus" class="speech-status" aria-live="polite">Pembaca teks siap digunakan.</p>
    <p class="access-footnote">Fitur suara menggunakan dukungan text-to-speech pada browser/perangkat. Ketersediaan suara Bahasa Indonesia bergantung pada perangkat.</p>
  </aside>
  <div class="toast" id="toast" role="status" aria-live="polite"></div>
  <script src="profile.js"></script>
  <script src="script.js"></script>
</body>
</html>
