# Tugas Praktikum Lab6Web
Nama : Ari Cakra Kurniawan \
Nim : 312410248 \
Kelas : TI.24.A2 \
Mata Kuliah : Pemrograman Web 1 \
Dosen Pengampu : Agung Nugroho, S.Kom., M.Kom. 

---

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WebPort - Home</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-cyan">
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow fixed-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="index.html">
                <i class="fas fa-code me-2"></i>Aricakra
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="index.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="artikel.html">Artikel</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="kontak.html">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section py-5" style="padding-top: 100px !important;">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <h1 class="display-4 fw-bold text-white mb-4">Hello World! 👋</h1>
                    <p class="lead text-light mb-4">Selamat datang di portfolio digital saya! Mari jelajahi dunia teknologi dan kreativitas bersama-sama.</p>
                    <button onclick="scrollToMain()" class="btn btn-light btn-lg px-4">
                        <i class="fas fa-rocket me-2"></i>Mulai Eksplorasi
                    </button>
                </div>
                <div class="col-lg-4 text-center">
                    <div class="hero-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Content -->
    <div class="container my-5" id="main-content">
        <div class="row">
            <!-- Main Content -->
            <div class="col-lg-8">
                <!-- Features Grid -->
                <div class="row mb-5">
                    <div class="col-md-4 mb-4">
                        <div class="feature-card text-center p-4 h-100">
                            <div class="feature-icon mb-3">
                                <i class="fas fa-palette"></i>
                            </div>
                            <h4>Creative Design</h4>
                            <p>Desain yang menarik dan user-friendly dengan pendekatan modern.</p>
                            <a href="#" class="btn btn-outline-primary btn-sm">View Detail</a>
                        </div>
                    </div>
                    <div class="col-md-4 mb-4">
                        <div class="feature-card text-center p-4 h-100">
                            <div class="feature-icon mb-3">
                                <i class="fas fa-code"></i>
                            </div>
                            <h4>Clean Code</h4>
                            <p>Kode yang terstruktur, efisien, dan mudah dipelihara.</p>
                            <a href="#" class="btn btn-outline-primary btn-sm">View Detail</a>
                        </div>
                    </div>
                    <div class="col-md-4 mb-4">
                        <div class="feature-card text-center p-4 h-100">
                            <div class="feature-icon mb-3">
                                <i class="fas fa-mobile-alt"></i>
                            </div>
                            <h4>Responsive</h4>
                            <p>Optimal di semua perangkat, dari desktop hingga mobile.</p>
                            <a href="#" class="btn btn-outline-primary btn-sm">View Detail</a>
                        </div>
                    </div>
                </div>

                <!-- Articles -->
                <article class="blog-post mb-5">
                    <div class="row align-items-center">
                        <div class="col-md-4">
                            <img src="https://dummyimage.com/300x200/00b4d8/fff.png&text=Innovation" alt="Innovation" class="img-fluid rounded shadow">
                        </div>
                        <div class="col-md-8">
                            <h2 class="text-primary">First Featurette Heading</h2>
                            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis.</p>
                            <a href="#" class="btn btn-primary">Baca Selengkapnya</a>
                        </div>
                    </div>
                </article>

                <article class="blog-post">
                    <div class="row align-items-center">
                        <div class="col-md-8">
                            <h2 class="text-primary">Second Featurette Heading</h2>
                            <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis.</p>
                            <a href="#" class="btn btn-primary">Baca Selengkapnya</a>
                        </div>
                        <div class="col-md-4">
                            <img src="https://dummyimage.com/300x200/0077b6/fff.png&text=Technology" alt="Technology" class="img-fluid rounded shadow">
                        </div>
                    </div>
                </article>
            </div>

            <!-- Sidebar -->
            <div class="col-lg-4">
                <!-- Widget Links -->
                <div class="sidebar-widget mb-4">
                    <div class="widget-header">
                        <h5><i class="fas fa-link me-2"></i>Quick Links</h5>
                    </div>
                    <div class="widget-body">
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item">
                                <a href="#" class="text-decoration-none">
                                    <i class="fas fa-arrow-right me-2"></i>Project Gallery
                                </a>
                            </li>
                            <li class="list-group-item">
                                <a href="#" class="text-decoration-none">
                                    <i class="fas fa-arrow-right me-2"></i>My Services
                                </a>
                            </li>
                            <li class="list-group-item">
                                <a href="#" class="text-decoration-none">
                                    <i class="fas fa-arrow-right me-2"></i>Testimonials
                                </a>
                            </li>
                            <li class="list-group-item">
                                <a href="#" class="text-decoration-none">
                                    <i class="fas fa-arrow-right me-2"></i>Blog Posts
                                </a>
                            </li>
                            <li class="list-group-item">
                                <a href="#" class="text-decoration-none">
                                    <i class="fas fa-arrow-right me-2"></i>Resources
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>

                <!-- Widget Text -->
                <div class="sidebar-widget">
                    <div class="widget-header">
                        <h5><i class="fas fa-info-circle me-2"></i>About This Site</h5>
                    </div>
                    <div class="widget-body">
                        <p class="mb-0">Website ini dibangun dengan teknologi terbaru menggunakan Bootstrap 5, dengan desain modern dan responsif untuk pengalaman pengguna yang optimal.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-light py-4 mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h5><i class="fas fa-code me-2"></i>Aricakra</h5>
                    <p class="mb-0">Membangun pengalaman digital yang luar biasa.</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <p class="mb-0">&copy; 2025 ari cakra kurniawan.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Scripts -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Fungsi scroll langsung ke main content
        function scrollToMain() {
            const mainContent = document.getElementById('main-content');
            if (mainContent) {
                window.scrollTo({
                    top: mainContent.offsetTop - 80,
                    behavior: 'smooth'
                });
            }
        }

        // Smooth scrolling untuk semua anchor links
        document.addEventListener('DOMContentLoaded', function() {
            // Smooth scroll untuk anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href');
                    const target = document.querySelector(targetId);
                    if (target) {
                        window.scrollTo({
                            top: target.offsetTop - 80,
                            behavior: 'smooth'
                        });
                    }
                });
            });

            // Navbar scroll effect
            window.addEventListener('scroll', function() {
                const navbar = document.querySelector('.navbar');
                if (window.scrollY > 100) {
                    navbar.style.background = 'linear-gradient(135deg, #0077b6 0%, #0096c7 100%)';
                    navbar.style.boxShadow = '0 4px 20px rgba(0, 0, 0, 0.1)';
                } else {
                    navbar.style.background = 'transparent';
                    navbar.style.boxShadow = 'none';
                }
            });

            console.log('Website loaded successfully!');
        });
    </script>
</body>
</html>
```

Outputnya yaitu :

<img width="1375" height="914" alt="image" src="https://github.com/user-attachments/assets/443de256-21c7-4edb-8a5b-f7c5a9506b13" />



<img width="770" height="555" alt="image" src="https://github.com/user-attachments/assets/cd425f00-6b13-407d-a167-403b21c04be0" />
