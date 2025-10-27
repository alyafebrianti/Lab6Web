# Lab6Web
# Nama  : Alya Febrianti
# NIM   : 312410692
# Matkul : Pemograman Web 1

# Input HTML, CSS, Dan JS
## HTML
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Layout Sederhana</title>

  <!-- Bootstrap CSS (CDN) -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
    crossorigin="anonymous"
  />

  <!-- Custom CSS -->
  <link rel="stylesheet" href="style.css" />
</head>
<body class="bg-page">

  <!-- Header -->
  <header class="brandbar py-3">
    <div class="container">
      <h1 class="brandtitle fw-bold text-secondary">Layout Sederhana</h1>
    </div>
  </header>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow-sm">
    <div class="container">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#mainNav"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div id="mainNav" class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            <a href="home.html" class="nav-link active">Home</a>
          </li>
          <li class="nav-item">
            <a href="artikel.html" class="nav-link">Artikel</a>
          </li>
          <li class="nav-item">
            <a href="about.html" class="nav-link">About</a>
          </li>
          <li class="nav-item">
            <a href="kontak.html" class="nav-link">Kontak</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="container mt-3">
    <div class="p-4 bg-light rounded shadow-sm">
      <h2 class="fw-bold mb-2">Hello World!</h2>
      <p class="lead text-secondary mb-3">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
        tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec
        pretium nunc pretium ac.
      </p>
      <a class="btn btn-primary btn-lg" href="#">Learn more »</a>
    </div>
  </section>

  <!-- Main Content -->
  <main class="container my-4">
    <div class="row gx-4 gy-4">
      <!-- Main Column -->
      <div class="col-lg-8">

        <!-- 3 Circles -->
        <div class="row text-center g-4 mt-2">
          <div class="col-md-4">
            <div>
              <div class="circle bg-warning text-white mx-auto d-flex align-items-center justify-content-center">120 × 120</div>
              <h5 class="mt-3 fw-semibold">Heading</h5>
              <p class="small text-secondary">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a class="btn btn-light btn-sm" href="#">View detail</a>
            </div>
          </div>
          <div class="col-md-4">
            <div>
              <div class="circle bg-primary text-white mx-auto d-flex align-items-center justify-content-center">120 × 120</div>
              <h5 class="mt-3 fw-semibold">Heading</h5>
              <p class="small text-secondary">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a class="btn btn-light btn-sm" href="#">View detail</a>
            </div>
          </div>
          <div class="col-md-4">
            <div>
              <div class="circle bg-info text-white mx-auto d-flex align-items-center justify-content-center">120 × 120</div>
              <h5 class="mt-3 fw-semibold">Heading</h5>
              <p class="small text-secondary">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a class="btn btn-light btn-sm" href="#">View detail</a>
            </div>
          </div>
        </div>

        <hr class="my-4" />

        <!-- Featurette 1 -->
        <article class="row align-items-start gy-3">
          <div class="col-4 col-sm-3">
            <div class="bg-secondary bg-opacity-50 text-center py-5 rounded">150 × 150</div>
          </div>
          <div class="col">
            <h3 class="h4 fw-bold text-dark mb-2">First featurette heading.</h3>
            <p class="mb-0 text-secondary">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat,
              malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra
              est nunc, nec pretium nunc pretium ac.
            </p>
          </div>
        </article>

        <hr class="my-4" />

        <!-- Featurette 2 -->
        <article class="row align-items-start gy-3">
          <div class="col">
            <h3 class="h4 fw-bold text-dark mb-2">First featurette heading.</h3>
            <p class="mb-0 text-secondary">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat,
              malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra
              est nunc, nec pretium nunc pretium ac.
            </p>
          </div>
          <div class="col-4 col-sm-3">
            <div class="bg-secondary bg-opacity-50 text-center py-5 rounded">150 × 150</div>
          </div>
        </article>
      </div>

      <!-- Sidebar -->
      <aside class="col-lg-4">
        <div class="card mb-4">
          <div class="card-header bg-primary text-white fw-bold">Widget Header</div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
          </ul>
        </div>

        <div class="card">
          <div class="card-header bg-primary text-white fw-bold">Widget Text</div>
          <div class="card-body text-secondary">
            Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
            vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.
          </div>
        </div>
      </aside>
    </div>
  </main>

  <!-- Footer -->
  <footer class="bg-dark text-white py-3">
    <div class="container small">
      © 2025 - Universitas Pelita Bangsa
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"
  ></script>
</body>
</html>
```
## CSS
```CSS
/* ====== LATAR & TIPOGRAFI ====== */
body {
  font-family: 'Open Sans', sans-serif;
  color: #333;
  background-color: #f2f2f2;
  margin: 0;
  padding: 0;
}

/* ====== BRAND AREA ====== */
.brandbar {
  background: #ffffff;
  border-bottom: 1px solid #e5e5e5;
}

.brandtitle {
  font-size: 28px;
  font-weight: 700;
  margin: 16px 0;
  color: #b7b7b7;
  letter-spacing: 0.2px;
}

/* ====== NAVBAR ====== */
.navblue {
  background-color: #1e66b2;
}

.navblue .nav-link {
  color: #fff !important;
  padding: 0.55rem 0.9rem;
  transition: background 0.2s;
}

.navblue .nav-link.active,
.navblue .nav-link:hover {
  background-color: #155a9a;
}

/* ====== PANEL UMUM ====== */
.panel {
  background: #ffffff;
  border: 1px solid #e3e3e3;
  border-radius: 3px;
  box-shadow: 0 1px 2px rgba(0,0,0,0.03);
  margin-bottom: 1rem;
}

.panel-hero {
  padding: 26px;
  background: #eeeeee;
  border-bottom: 1px solid #dcdcdc;
}

.panel-content {
  padding: 22px;
}

/* ====== DIVIDER ====== */
.soft {
  border: 0;
  border-top: 1px solid #ececec;
  margin: 1rem 0;
}

/* ====== CIRCLE ====== */
.circle {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-weight: 600;
  color: #fff;
  margin-bottom: 0.5rem;
}

.bg-orange { background: #de7d2a; }
.bg-blue   { background: #3d6fe3; }
.bg-teal   { background: #66dbcf; }

/* ====== BUTTON GHOST ====== */
.btn-ghost {
  border: 1px solid #cfcfcf !important;
  color: #555 !important;
  background: #f2f2f2 !important;
  padding: 0.35rem 0.7rem !important;
  border-radius: 4px;
  font-size: 0.9rem;
  transition: all 0.2s;
}

.btn-ghost:hover {
  background: #e9e9e9 !important;
}

/* ====== THUMBNAIL ====== */
.thumb {
  width: 150px;
  height: 150px;
  background: #7b8a70;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 6px;
  font-weight: 600;
}

/* ====== SIDEBAR WIDGET ====== */
.widget {
  border: 1px solid #e3e3e3;
  border-radius: 3px;
  background: #fff;
  overflow: hidden;
}

.widget-header {
  background: #1e66b2;
  color: #fff;
  font-weight: 600;
  padding: 0.6rem 0.9rem;
  border-bottom: 1px solid #1b5da4;
}

.widget-item {
  padding: 0.55rem 0.9rem;
  border-bottom: 1px solid #efefef;
  background: #fff;
}

.widget-item:last-child {
  border-bottom: 0;
}

.widget-link {
  text-decoration: none;
  color: #3b3b3b;
  display: block;
}

.widget-link:hover {
  text-decoration: underline;
}

/* ====== FOOTER ====== */
.site-footer {
  background: #0f0f0f;
  padding: 14px 0;
  margin-top: 20px;
  border-top: 1px solid #080808;
  color: #ccc;
  text-align: center;
  font-size: 0.9rem;
}

/* ====== RESPONSIVE ====== */
@media (max-width: 575.98px) {
  .thumb {
    width: 120px;
    height: 120px;
  }

  .brandtitle {
    font-size: 22px;
  }

  .circle {
    width: 100px;
    height: 100px;
  }
}
```
## JS
```JS
// jQuery untuk interaksi ringan sesuai kebutuhan mockup
$(document).ready(function () {

  /* ====== SET NAV ITEM AKTIF ====== */
  const currentFile = location.pathname.split("/").pop() || "index.html";
  $(".navbar .nav-link").each(function () {
    const linkFile = $(this).attr("href");

    // Hindari # dan link kosong
    if (linkFile && linkFile !== "#" && linkFile === currentFile) {
      $(this).addClass("active");
    }
  });

  /* ====== DEMO KLIK "VIEW DETAIL" ====== */
  $(".btn-ghost").on("click", function (e) {
    e.preventDefault();

    // Cari judul item (kalau tidak ada <h5>, tampilkan 'Item tidak dikenal')
    const title = $(this).closest("div").find("h5").text().trim() || "Item tidak dikenal";
    alert("Detail item: " + title);
  });

});

```
# Output

<img width="2826" height="1507" alt="Screenshot 2025-10-27 203548" src="https://github.com/user-attachments/assets/842ec3e0-feab-4d33-abcb-4e7dc12d77be" />

<img width="2787" height="1439" alt="Screenshot 2025-10-27 203604" src="https://github.com/user-attachments/assets/452eaa03-3c9a-4068-b8b8-7e4d27ed890f" />


