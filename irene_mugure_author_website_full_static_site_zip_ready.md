Below is the complete, ready-to-host static author website. Copy these files into a folder named `irene-mugure-website/` and zip it if needed. All demo images are hot-linked from free sources (Unsplash/Pexels) so you can go live immediately; you can later replace them with local files under `/images` if you prefer.

---

## 📁 File: `index.html` (Home)
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Irene Mugure Nderitu | Author</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet" />
  <meta name="description" content="Faith-inspired books and guidance by Irene Mugure Nderitu – To Becoming, To Becoming a Better Version of Me, To Becoming My Own Captain." />
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="index.html">Irene Mugure Nderitu</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav" aria-controls="nav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="nav">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0 align-items-lg-center">
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="books.html">Shop</a></li>
          <li class="nav-item"><a class="nav-link" href="blog.html">Blog</a></li>
          <li class="nav-item"><a class="nav-link" href="chat.html">Faith Companion</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
          <li class="nav-item ms-lg-3">
            <a class="btn btn-outline-primary position-relative" href="books.html#cart">
              <i class="fa-solid fa-cart-shopping"></i>
              <span class="badge text-bg-danger cart-count" id="navCartCount">0</span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <header class="hero">
    <div class="overlay"></div>
    <div class="container text-center text-white position-relative">
      <h1 class="display-5 fw-bold">Anchored in Faith, Becoming with Purpose</h1>
      <p class="lead mt-3">Practical, faith-filled guidance to navigate life’s valleys and mountaintops.</p>
      <a href="books.html" class="btn btn-primary btn-lg mt-3">Explore the Books</a>
    </div>
  </header>

  <!-- Featured Books -->
  <section class="py-5">
    <div class="container">
      <div class="text-center mb-4">
        <h2 class="fw-bold">Books by Irene Mugure Nderitu</h2>
        <p class="text-muted">Rooted in Scripture • Formed by Trials • Lived in Love</p>
      </div>
      <div class="row g-4">
        <!-- Book 1 -->
        <div class="col-md-4">
          <div class="card h-100 book-card">
            <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=1200&auto=format&fit=crop" class="card-img-top" alt="Open Bible on table"/>
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">To Becoming</h5>
              <p class="card-text small flex-grow-1">A devotional journey to embrace growth through seasons of waiting, pruning, and renewal—anchored in the Word of God.</p>
              <div class="d-flex justify-content-between align-items-center">
                <span class="fw-bold">$12.00</span>
                <button class="btn btn-outline-primary add-to-cart" data-id="becoming" data-title="To Becoming" data-price="12" data-image="https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=1200&auto=format&fit=crop">Add to Cart</button>
              </div>
            </div>
          </div>
        </div>
        <!-- Book 2 -->
        <div class="col-md-4">
          <div class="card h-100 book-card">
            <img src="https://images.unsplash.com/photo-1507842217343-583bb7270b66?q=80&w=1200&auto=format&fit=crop" class="card-img-top" alt="Flowers and journal"/>
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">To Becoming a Better Version of Me</h5>
              <p class="card-text small flex-grow-1">Re-evaluate thoughts, character, and self-limiting beliefs—discovering skills and passions that serve God and community.</p>
              <div class="d-flex justify-content-between align-items-center">
                <span class="fw-bold">$14.00</span>
                <button class="btn btn-outline-primary add-to-cart" data-id="better" data-title="To Becoming a Better Version of Me" data-price="14" data-image="https://images.unsplash.com/photo-1507842217343-583bb7270b66?q=80&w=1200&auto=format&fit=crop">Add to Cart</button>
              </div>
            </div>
          </div>
        </div>
        <!-- Book 3 -->
        <div class="col-md-4">
          <div class="card h-100 book-card">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1200&auto=format&fit=crop" class="card-img-top" alt="Anchor and calm waters"/>
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">To Becoming My Own Captain</h5>
              <p class="card-text small flex-grow-1">Courage to steer through storms with steadfast faith—trusting God’s process and divine redirection.</p>
              <div class="d-flex justify-content-between align-items-center">
                <span class="fw-bold">$16.00</span>
                <button class="btn btn-outline-primary add-to-cart" data-id="captain" data-title="To Becoming My Own Captain" data-price="16" data-image="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1200&auto=format&fit=crop">Add to Cart</button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="text-center mt-4">
        <a href="books.html" class="btn btn-outline-secondary">Visit the Shop</a>
      </div>
    </div>
  </section>

  <!-- Scripture Banner -->
  <section class="py-5 bg-light">
    <div class="container">
      <blockquote class="lead text-center m-0 fw-semibold">“We have this hope as an anchor for the soul, firm and secure.” — Hebrews 6:19</blockquote>
    </div>
  </section>

  <!-- Blog Preview -->
  <section class="py-5">
    <div class="container">
      <div class="d-flex justify-content-between align-items-center mb-3">
        <h3 class="fw-bold m-0">From the Blog</h3>
        <a href="blog.html" class="btn btn-sm btn-outline-primary">Read All</a>
      </div>
      <div class="row g-4">
        <div class="col-md-4">
          <a class="card h-100 text-decoration-none text-dark" href="blog/post1.html">
            <img class="card-img-top" src="https://images.unsplash.com/photo-1521433961030-0a1df7c3c2bf?q=80&w=1200&auto=format&fit=crop" alt="Stormy sea" />
            <div class="card-body">
              <h5 class="card-title">Finding Strength in the Storm</h5>
              <p class="card-text small text-muted">Matthew 8:23–27 • When waves rise, Christ is still Lord over the wind and the sea.</p>
            </div>
          </a>
        </div>
        <div class="col-md-4">
          <a class="card h-100 text-decoration-none text-dark" href="blog/post2.html">
            <img class="card-img-top" src="https://images.unsplash.com/photo-1473116763249-2faaef81ccda?q=80&w=1200&auto=format&fit=crop" alt="Fork in the road" />
            <div class="card-body">
              <h5 class="card-title">When God Redirects Your Path</h5>
              <p class="card-text small text-muted">Proverbs 16:9 • Misfortune may be a divine redirection—walk by faith, not sight.</p>
            </div>
          </a>
        </div>
        <div class="col-md-4">
          <a class="card h-100 text-decoration-none text-dark" href="blog/post3.html">
            <img class="card-img-top" src="https://images.unsplash.com/photo-1470770903676-69b98201ea1c?q=80&w=1200&auto=format&fit=crop" alt="Anchor" />
            <div class="card-body">
              <h5 class="card-title">Anchored in Hope</h5>
              <p class="card-text small text-muted">Hebrews 6:19 • Steadfast, immovable—Christ our sure anchor in every season.</p>
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- Newsletter -->
  <section class="py-5 bg-gradient-light">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="p-4 p-md-5 rounded-4 border bg-white shadow-sm">
            <h4 class="fw-bold text-center">Subscribe to the Devotional Newsletter</h4>
            <p class="text-muted text-center">Weekly encouragement, Scripture reflections, and book news.</p>
            <form class="row g-2" onsubmit="event.preventDefault(); alert('Thank you for subscribing! (placeholder)'); this.reset();">
              <div class="col-md-8"><input type="email" class="form-control form-control-lg" placeholder="Your email" required></div>
              <div class="col-md-4 d-grid"><button class="btn btn-primary btn-lg">Subscribe</button></div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-4 border-top bg-white">
    <div class="container d-flex flex-column flex-md-row align-items-center justify-content-between gap-2">
      <p class="m-0 small">© <span id="year"></span> Irene Mugure Nderitu. All rights reserved.</p>
      <ul class="list-inline m-0">
        <li class="list-inline-item"><a href="about.html" class="link-secondary">About</a></li>
        <li class="list-inline-item"><a href="books.html" class="link-secondary">Shop</a></li>
        <li class="list-inline-item"><a href="blog.html" class="link-secondary">Blog</a></li>
        <li class="list-inline-item"><a href="contact.html" class="link-secondary">Contact</a></li>
        <li class="list-inline-item ms-2">
          <a class="text-secondary" href="#" aria-label="Twitter"><i class="fa-brands fa-x-twitter"></i></a>
        </li>
        <li class="list-inline-item">
          <a class="text-secondary" href="#" aria-label="Facebook"><i class="fa-brands fa-facebook"></i></a>
        </li>
        <li class="list-inline-item">
          <a class="text-secondary" href="#" aria-label="Instagram"><i class="fa-brands fa-instagram"></i></a>
        </li>
      </ul>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `about.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>About | Irene Mugure Nderitu</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet" />
</head>
<body>
  <!-- Reuse Navbar -->
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">About the Author</h1>
      <p class="lead">Writer • Mentor • Faith Companion</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <div class="row g-4 align-items-center">
        <div class="col-md-5">
          <img class="rounded-4 shadow-sm w-100 object-cover" src="https://images.unsplash.com/photo-1544717305-2782549b5136?q=80&w=1200&auto=format&fit=crop" alt="Author placeholder" />
        </div>
        <div class="col-md-7">
          <h2 class="fw-bold">Irene Mugure Nderitu</h2>
          <p class="text-muted">Irene writes to help readers navigate life’s difficulties by relying on the Word of God, embracing divine redirection, and finding meaning in every season. Her work encourages steadfast faith—giving in to His will, obeying and trusting the process, while re-evaluating thoughts, character, and self-limiting beliefs to serve with love.</p>
          <p class="text-muted">Her books—<em>To Becoming</em>, <em>To Becoming a Better Version of Me</em>, and <em>To Becoming My Own Captain</em>—invite readers to discover skills, passions, talents, and past experiences that God can use for good, to seek fulfillment for self and community.</p>
          <a href="books.html" class="btn btn-primary me-2">Shop Books</a>
          <a href="chat.html" class="btn btn-outline-primary">Faith Companion</a>
        </div>
      </div>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `books.html` (Shop with cart placeholder & checkout option "placeholder")
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shop | Irene Mugure Nderitu</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet" />
</head>
<body>
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1470770903676-69b98201ea1c?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">Shop</h1>
      <p class="lead">Books, devotionals, journals, and courses (future-ready)</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <div class="row g-4">
        <!-- Products (same as home, can be extended) -->
        <div class="col-md-4">
          <div class="card h-100 book-card">
            <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=1200&auto=format&fit=crop" class="card-img-top" alt="Open Bible"/>
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">To Becoming</h5>
              <p class="card-text small flex-grow-1">A devotional journey to embrace growth through seasons of waiting, pruning, and renewal—anchored in Scripture.</p>
              <div class="d-flex justify-content-between align-items-center">
                <span class="fw-bold">$12.00</span>
                <button class="btn btn-outline-primary add-to-cart" data-id="becoming" data-title="To Becoming" data-price="12" data-image="https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=1200&auto=format&fit=crop">Add to Cart</button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100 book-card">
            <img src="https://images.unsplash.com/photo-1507842217343-583bb7270b66?q=80&w=1200&auto=format&fit=crop" class="card-img-top" alt="Flowers journal"/>
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">To Becoming a Better Version of Me</h5>
              <p class="card-text small flex-grow-1">Re-evaluate thoughts, character, and self-limiting beliefs—discover gifts that serve God and neighbor.</p>
              <div class="d-flex justify-content-between align-items-center">
                <span class="fw-bold">$14.00</span>
                <button class="btn btn-outline-primary add-to-cart" data-id="better" data-title="To Becoming a Better Version of Me" data-price="14" data-image="https://images.unsplash.com/photo-1507842217343-583bb7270b66?q=80&w=1200&auto=format&fit=crop">Add to Cart</button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100 book-card">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1200&auto=format&fit=crop" class="card-img-top" alt="Anchor waters"/>
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">To Becoming My Own Captain</h5>
              <p class="card-text small flex-grow-1">Courage to steer through storms with steadfast faith—trusting God’s process and redirection.</p>
              <div class="d-flex justify-content-between align-items-center">
                <span class="fw-bold">$16.00</span>
                <button class="btn btn-outline-primary add-to-cart" data-id="captain" data-title="To Becoming My Own Captain" data-price="16" data-image="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1200&auto=format&fit=crop">Add to Cart</button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Cart -->
      <hr class="my-5" />
      <div id="cart" class="cart">
        <h3 class="fw-bold mb-3">Your Cart</h3>
        <div class="table-responsive">
          <table class="table align-middle">
            <thead>
              <tr><th>Item</th><th>Price</th><th>Qty</th><th>Subtotal</th><th></th></tr>
            </thead>
            <tbody id="cartBody"></tbody>
          </table>
        </div>
        <div class="d-flex justify-content-between align-items-center">
          <div class="text-muted small">Taxes/shipping calculated at checkout (placeholder).</div>
          <div class="fs-5">Total: $<span id="cartTotal">0.00</span></div>
        </div>
        <div class="mt-3 d-flex gap-2">
          <button class="btn btn-outline-secondary" id="clearCart">Clear Cart</button>
          <!-- Checkout Option 3: Placeholder -->
          <button class="btn btn-primary" id="checkoutBtn">Checkout</button>
        </div>
        <p class="small text-muted mt-2">Checkout is a placeholder. You can integrate Stripe/PayPal later.</p>
      </div>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `blog.html` (List page)
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Blog | Irene Mugure Nderitu</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet" />
</head>
<body>
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">Devotional Blog</h1>
      <p class="lead">Scripture, reflection, and practical encouragement</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <div class="row g-4">
        <div class="col-md-4">
          <a class="card h-100 text-decoration-none text-dark" href="blog/post1.html">
            <img class="card-img-top" src="https://images.unsplash.com/photo-1521433961030-0a1df7c3c2bf?q=80&w=1200&auto=format&fit=crop" alt="Storm" />
            <div class="card-body">
              <h5 class="card-title">Finding Strength in the Storm</h5>
              <p class="card-text small text-muted">Matthew 8:23–27 • Christ over the wind and the sea.</p>
            </div>
          </a>
        </div>
        <div class="col-md-4">
          <a class="card h-100 text-decoration-none text-dark" href="blog/post2.html">
            <img class="card-img-top" src="https://images.unsplash.com/photo-1473116763249-2faaef81ccda?q=80&w=1200&auto=format&fit=crop" alt="Road" />
            <div class="card-body">
              <h5 class="card-title">When God Redirects Your Path</h5>
              <p class="card-text small text-muted">Proverbs 16:9 • Divine detours and surrendered plans.</p>
            </div>
          </a>
        </div>
        <div class="col-md-4">
          <a class="card h-100 text-decoration-none text-dark" href="blog/post3.html">
            <img class="card-img-top" src="https://images.unsplash.com/photo-1470770903676-69b98201ea1c?q=80&w=1200&auto=format&fit=crop" alt="Anchor" />
            <div class="card-body">
              <h5 class="card-title">Anchored in Hope</h5>
              <p class="card-text small text-muted">Hebrews 6:19 • Firm and secure in Christ.</p>
            </div>
          </a>
        </div>
      </div>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `blog/post1.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Finding Strength in the Storm | Devotional</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="../css/style.css" rel="stylesheet" />
</head>
<body>
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1521433961030-0a1df7c3c2bf?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">Finding Strength in the Storm</h1>
      <p class="lead">Matthew 8:23–27</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <article class="mx-auto" style="max-width: 800px;">
        <p>Sometimes life’s chapters begin with a crisis. The wind howls, the boat creaks, and our hearts tremble. Yet the Gospels remind us that even when the waves rise, Jesus is Lord over wind and sea (Matthew 8:23–27). He is not overwhelmed by our overwhelm.</p>
        <p>Misfortune may be a divine redirection. In the storm, we relearn our dependence on God. We find the limits of our own strength—and the limitless sufficiency of His. We are invited to trust, obey, and wait as He speaks peace over our waters.</p>
        <blockquote class="blockquote p-3 bg-light rounded">“Why are you afraid, O you of little faith?” Then he rose and rebuked the winds and the sea, and there was a great calm. — <em>Matthew 8:26</em></blockquote>
        <p>Today, breathe. Acknowledge the waves, but don’t magnify them above Christ. Ask: What can I surrender? Where is God redirecting me? How can I serve in love—even here?</p>
      </article>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="../js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `blog/post2.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>When God Redirects Your Path | Devotional</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="../css/style.css" rel="stylesheet" />
</head>
<body>
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1473116763249-2faaef81ccda?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">When God Redirects Your Path</h1>
      <p class="lead">Proverbs 16:9</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <article class="mx-auto" style="max-width: 800px;">
        <p>We plan our way, but the Lord establishes our steps (Proverbs 16:9). Detours can feel like failure. Often, they are mercy. God pries our hands off lesser things to place better gifts in them. He teaches us to walk by faith, not by sight.</p>
        <blockquote class="blockquote p-3 bg-light rounded">“The heart of man plans his way, but the LORD establishes his steps.” — <em>Proverbs 16:9</em></blockquote>
        <p>Instead of asking “Why this?” try “What now, Lord?” Re-evaluate your thoughts, habits, and gifts. Which of your skills and experiences might serve this new season? How can you bless your community while you wait?</p>
      </article>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="../js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `blog/post3.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Anchored in Hope | Devotional</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="../css/style.css" rel="stylesheet" />
</head>
<body>
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1470770903676-69b98201ea1c?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">Anchored in Hope</h1>
      <p class="lead">Hebrews 6:19</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <article class="mx-auto" style="max-width: 800px;">
        <p>Hope in Christ is not wishful thinking—it is an anchor. In drifting seasons, we return to the One who does not move. His promises moor us when circumstances sway.</p>
        <blockquote class="blockquote p-3 bg-light rounded">“We have this hope as an anchor for the soul, firm and secure.” — <em>Hebrews 6:19</em></blockquote>
        <p>Today, choose practices that keep you anchored: prayer, Scripture, counsel, and service. Be of value. Be of love. Seek the good of your community—and find your joy in Him.</p>
      </article>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="../js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `chat.html` (Faith Companion – client‑side guided chat placeholder)
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Faith Companion | Irene Mugure Nderitu</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet" />
</head>
<body>
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">Faith Companion</h1>
      <p class="lead">A gentle guide rooted in Scripture and lessons from the books</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <div class="row g-4">
        <div class="col-lg-4">
          <div class="p-3 border rounded-3 bg-white shadow-sm">
            <h5 class="fw-bold">Try a prompt</h5>
            <ul class="small list-unstyled m-0">
              <li><button class="link-btn" data-prompt="I feel like my life just hit a crisis. Where is God in this?">Crisis & God’s presence</button></li>
              <li><button class="link-btn" data-prompt="How do I know if this setback is God’s redirection?">Divine redirection</button></li>
              <li><button class="link-btn" data-prompt="Help me re-evaluate my beliefs and gifts in this season.">Re-evaluating beliefs & gifts</button></li>
              <li><button class="link-btn" data-prompt="How can I serve my community while I wait?">Serving while waiting</button></li>
            </ul>
            <hr>
            <p class="small text-muted">Note: This is a client-side guided chat placeholder. For a live AI chat, integrate your preferred API later.</p>
          </div>
        </div>
        <div class="col-lg-8">
          <div class="chat-box border rounded-3 bg-white shadow-sm p-3">
            <div id="chatLog" class="chat-log"></div>
            <form id="chatForm" class="mt-3 d-flex gap-2" onsubmit="return startChat(event)">
              <input id="chatInput" class="form-control" type="text" placeholder="Share what’s on your heart…" required />
              <button class="btn btn-primary">Send</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `contact.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact | Irene Mugure Nderitu</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet" />
</head>
<body>
  <div id="siteNav"></div>

  <header class="inner-hero" style="--bg:url('https://images.unsplash.com/photo-1501785888041-af3ef285b470?q=80&w=1600&auto=format&fit=crop')">
    <div class="overlay"></div>
    <div class="container position-relative text-white">
      <h1 class="fw-bold">Contact</h1>
      <p class="lead">We’d love to hear from you</p>
    </div>
  </header>

  <main class="py-5">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="p-4 p-md-5 rounded-4 border bg-white shadow-sm">
            <h4 class="fw-bold">Send a Message</h4>
            <form onsubmit="event.preventDefault(); alert('Message sent! (placeholder)'); this.reset();">
              <div class="row g-3">
                <div class="col-md-6">
                  <label class="form-label">Name</label>
                  <input type="text" class="form-control" required />
                </div>
                <div class="col-md-6">
                  <label class="form-label">Email</label>
                  <input type="email" class="form-control" required />
                </div>
                <div class="col-12">
                  <label class="form-label">Message</label>
                  <textarea class="form-control" rows="5" required></textarea>
                </div>
              </div>
              <div class="d-flex gap-2 mt-3">
                <button class="btn btn-primary">Send</button>
                <a href="#" class="btn btn-outline-secondary">Download Media Kit (placeholder)</a>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </main>

  <div id="siteFooter"></div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
```

---

## 📁 File: `css/style.css`
```css
:root{
  --ink:#1f2937; --muted:#6b7280; --light:#f8fafc; --brand:#2563eb;
}
body{font-family: system-ui,-apple-system,"Segoe UI",Roboto,Ubuntu,"Helvetica Neue",Arial,"Noto Sans",sans-serif; color:var(--ink);}
.navbar .navbar-brand{letter-spacing:.3px}
.hero{position:relative; min-height:60vh; display:grid; place-items:center; text-align:center;
  background:url('https://images.unsplash.com/photo-1470770903676-69b98201ea1c?q=80&w=2000&auto=format&fit=crop') center/cover fixed}
.hero .overlay{position:absolute; inset:0; background:linear-gradient(180deg, rgba(0,0,0,.45), rgba(0,0,0,.45))}
.inner-hero{position:relative; padding:6rem 0; background: var(--bg, none) center/cover no-repeat;}
.inner-hero .overlay{position:absolute; inset:0; background:linear-gradient(180deg, rgba(0,0,0,.35), rgba(0,0,0,.35))}
.book-card img{height:220px; object-fit:cover}
.object-cover{object-fit:cover}
.bg-gradient-light{background:linear-gradient(180deg,#ffffff,#f5f7fb)}
.chat-box{min-height:420px}
.chat-log{height:300px; overflow:auto; padding:10px; background:#f9fafb; border-radius:10px}
.chat-msg{margin:.25rem 0; padding:.5rem .75rem; border-radius:12px; max-width:85%}
.chat-msg.user{background:#e0ebff; margin-left:auto}
.chat-msg.bot{background:#eef2ff}
.link-btn{background:none; border:none; padding:0; color:var(--brand); cursor:pointer}
.cart img{height:48px; width:48px; object-fit:cover; border-radius:8px}
footer .list-inline-item a{text-decoration:none}
```

---

## 📁 File: `js/main.js`
```javascript
// Shared navbar/footer injection for inner pages
const navHTML = `
<nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm sticky-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="index.html">Irene Mugure Nderitu</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav" aria-controls="nav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0 align-items-lg-center">
        <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
        <li class="nav-item"><a class="nav-link" href="books.html">Shop</a></li>
        <li class="nav-item"><a class="nav-link" href="blog.html">Blog</a></li>
        <li class="nav-item"><a class="nav-link" href="chat.html">Faith Companion</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        <li class="nav-item ms-lg-3">
          <a class="btn btn-outline-primary position-relative" href="books.html#cart">
            <i class="fa-solid fa-cart-shopping"></i>
            <span class="badge text-bg-danger cart-count" id="navCartCount">0</span>
          </a>
        </li>
      </ul>
    </div>
  </div>
</nav>`;

const footerHTML = `
<footer class="py-4 border-top bg-white mt-auto">
  <div class="container d-flex flex-column flex-md-row align-items-center justify-content-between gap-2">
    <p class="m-0 small">© <span id="year"></span> Irene Mugure Nderitu. All rights reserved.</p>
    <ul class="list-inline m-0">
      <li class="list-inline-item"><a href="about.html" class="link-secondary">About</a></li>
      <li class="list-inline-item"><a href="books.html" class="link-secondary">Shop</a></li>
      <li class="list-inline-item"><a href="blog.html" class="link-secondary">Blog</a></li>
      <li class="list-inline-item"><a href="contact.html" class="link-secondary">Contact</a></li>
      <li class="list-inline-item ms-2"><a class="text-secondary" href="#"><i class="fa-brands fa-x-twitter"></i></a></li>
      <li class="list-inline-item"><a class="text-secondary" href="#"><i class="fa-brands fa-facebook"></i></a></li>
      <li class="list-inline-item"><a class="text-secondary" href="#"><i class="fa-brands fa-instagram"></i></a></li>
    </ul>
  </div>
</footer>`;

if (document.getElementById('siteNav')) document.getElementById('siteNav').outerHTML = navHTML;
if (document.getElementById('siteFooter')) document.getElementById('siteFooter').outerHTML = footerHTML;

// Footer year
const yearEl = document.getElementById('year');
if (yearEl) yearEl.textContent = new Date().getFullYear();

// ---------- Cart (localStorage) ----------
const CART_KEY = 'im_cart_v1';
function loadCart(){ try {return JSON.parse(localStorage.getItem(CART_KEY))||[]} catch(e){return []} }
function saveCart(items){ localStorage.setItem(CART_KEY, JSON.stringify(items)); updateCartBadge(items); }
function updateCartBadge(items){ const c=document.getElementById('navCartCount'); if(c) c.textContent= items.reduce((n,i)=>n+i.qty,0); }

function addToCart(item){
  const cart = loadCart();
  const idx = cart.findIndex(x=>x.id===item.id);
  if (idx>-1) cart[idx].qty += 1; else cart.push({...item, qty:1});
  saveCart(cart);
}

function renderCart(){
  const body = document.getElementById('cartBody');
  const totalEl = document.getElementById('cartTotal');
  if (!body||!totalEl) return;
  const cart = loadCart();
  body.innerHTML = '';
  let total = 0;
  cart.forEach((it, i)=>{
    const sub = it.price * it.qty; total += sub;
    const tr = document.createElement('tr');
    tr.innerHTML = `
      <td>
        <div class="d-flex align-items-center gap-2">
          <img src="${it.image}" alt="${it.title}">
          <div>
            <div class="fw-semibold">${it.title}</div>
          </div>
        </div>
      </td>
      <td>$${it.price.toFixed(2)}</td>
      <td><div class="input-group input-group-sm" style="max-width:120px">
            <button class="btn btn-outline-secondary" data-action="dec" data-index="${i}">–</button>
            <input class="form-control text-center" value="${it.qty}" readonly>
            <button class="btn btn-outline-secondary" data-action="inc" data-index="${i}">+</button>
          </div></td>
      <td>$${sub.toFixed(2)}</td>
      <td><button class="btn btn-sm btn-outline-danger" data-action="del" data-index="${i}"><i class="fa fa-trash"></i></button></td>`;
    body.appendChild(tr);
  });
  totalEl.textContent = total.toFixed(2);
}

function handleCartClicks(e){
  const btn = e.target.closest('button'); if(!btn) return;
  const action = btn.dataset.action; const index = +btn.dataset.index;
  const cart = loadCart();
  if (action==='inc') cart[index].qty++;
  if (action==='dec') cart[index].qty = Math.max(1, cart[index].qty-1);
  if (action==='del') cart.splice(index,1);
  saveCart(cart); renderCart();
}

function clearCart(){ saveCart([]); renderCart(); }

function checkout(){
  const cart = loadCart();
  if (!cart.length) return alert('Your cart is empty.');
  alert('Checkout placeholder: integrate Stripe/PayPal later. Thank you!');
}

// Bindings after DOM ready
window.addEventListener('DOMContentLoaded', ()=>{
  // Add-to-cart buttons
  document.querySelectorAll('.add-to-cart').forEach(btn=>{
    btn.addEventListener('click', ()=>{
      addToCart({ id: btn.dataset.id, title: btn.dataset.title, price: +btn.dataset.price, image: btn.dataset.image });
    });
  });
  updateCartBadge(loadCart());

  // Cart page bindings
  const cartBody = document.getElementById('cartBody');
  if (cartBody){
    renderCart();
    cartBody.addEventListener('click', handleCartClicks);
    const clearBtn = document.getElementById('clearCart'); if (clearBtn) clearBtn.addEventListener('click', clearCart);
    const checkoutBtn = document.getElementById('checkoutBtn'); if (checkoutBtn) checkoutBtn.addEventListener('click', checkout);
  }
});

// ---------- Faith Companion (guided) ----------
const RESPONSES = [
  { key: 'crisis', q: 'I feel like my life just hit a crisis. Where is God in this?', a: `Some chapters begin with a crisis. Scripture shows God is present in storms (Matthew 8:23–27). You are not abandoned. Breathe, pray, invite wise counsel, and ask: What is God forming in me here?` },
  { key: 'redirect', q: 'How do I know if this setback is God’s redirection?', a: `Proverbs 16:9 reminds us: we plan, God establishes. Misfortune may be a divine redirection. Hold plans with open hands, test with Scripture, and seek peace in prayer.` },
  { key: 'reevaluate', q: 'Help me re-evaluate my beliefs and gifts in this season.', a: `List your thoughts, skills, passions, and prior experiences. Which serve love and community now? Romans 12 encourages offering our gifts—renew your mind and discern His will.` },
  { key: 'serve', q: 'How can I serve my community while I wait?', a: `Choose one small act of love today. Service reframes waiting. Galatians 5:13—through love serve one another. Your value is not paused because a door is.` }
];

function startChat(e){
  e.preventDefault();
  const input = document.getElementById('chatInput');
  const log = document.getElementById('chatLog');
  const text = input.value.trim(); if(!text) return false;
  appendMsg('user', text);
  // Simple routing
  const lower = text.toLowerCase();
  let reply = `Thank you for sharing. Even here, God is near (Psalm 34:18). Consider journaling, praying Hebrews 6:19, and taking one faithful step.`;
  if (lower.includes('crisis')) reply = RESPONSES[0].a;
  else if (lower.includes('redirect')) reply = RESPONSES[1].a;
  else if (lower.includes('belief')||lower.includes('gift')) reply = RESPONSES[2].a;
  else if (lower.includes('serve')||lower.includes('community')) reply = RESPONSES[3].a;
  appendMsg('bot', reply);
  input.value='';
  return false;
}

function appendMsg(sender, text){
  const log = document.getElementById('chatLog');
  const div = document.createElement('div');
  div.className = `chat-msg ${sender}`;
  div.textContent = text;
  log.appendChild(div);
  log.scrollTop = log.scrollHeight;
}

// Quick-prompt buttons
window.addEventListener('click', (e)=>{
  const btn = e.target.closest('.link-btn');
  if (!btn) return;
  const val = btn.dataset.prompt || '';
  const input = document.getElementById('chatInput');
  if (input){ input.value = val; input.focus(); }
});
```

---

## ✅ How to deploy
1) Create a repo and upload these files.  
2) Enable GitHub Pages (Settings → Pages → Branch: `main` / root).  
3) Visit your live URL.  
4) Replace demo image URLs with your own when ready (optional).

---

If you want, I can also produce a compact **ZIP-ready text manifest** you can feed into a packer script, or I can generate downloadable files directly when my file tool is available. Let me know!

