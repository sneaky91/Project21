order html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="order-online.css">
</head>
<body>
    <header class="main-header">
        <nav class="navbar">
            <a href="index.html" class="nav-link">Home</a>
            <a href="menu.html" class="nav-link">Menu</a>
            <a href="order-online.html" class="nav-link active">Order Online</a>
            <a href="#" class="nav-link">Contact</a>
            <span class="nav-separator"></span>
            <a href="#" class="nav-link login">
                <span class="icon-user"></span> Log In
            </a>
            <a href="#" class="nav-link cart">
                <span class="icon-cart"></span>
            </a>
        </nav>
    </header>
    <!-- Далі нада мейн -->
     <main class="main-content">
    <section class="order-txt">
        <h1 class="order-title">ORDER ONLINE</h1>
        <div class="order-block">
            <div class="order-status">
                <span class="status-dot"></span>
                <span>Accepting Orders</span>
            </div>
            <div class="order-type">
                <a href="order2.html" class="order-btn-active">Pickup</a>
                <a href="order3.html" class="order-btn">Delivery</a>
            </div>
            <div class="order-info">
                <span class="order-time">
                    <span class="icon-clock"></span>
                    Pickup time: Up to 30 minutes
                    <a href="#" class="change-link">Change</a>
                </span>
                <span class="order-address">
                    <span class="icon-location"></span>
                    Pickup Address: San Francisco, CA
                </span>
            </div>
        </div>
    </section>
    <section class="order-menu">
        <nav class="menu-nav">
            <a href="#Sandwich" class="menu-link active">CHICKEN SANDWICH</a>
            <a href="#TENDERS" class="menu-link">TENDERS</a>
            <a href="#WINGS" class="menu-link">WINGS</a>
            <a href="#SPECIAL OFFERS" class="menu-link">SPECIAL OFFERS</a>
            <a href="#SIDES" class="menu-link">SIDES</a>
            <a href="#DESSERTS" class="menu-link">DESSERTS</a>
        </nav>
        <div id="Sandwich" class="menu-content">
            <h2 class="menu-section-title">CHICKEN SANDWICH</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3 class="menu-item-title">Classic Chicken Sandwich</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$9.00</span>
                </div>
                <div class="menu-item">
                    <h3 class="menu-item-title">Mega Chicken Sandwich</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$12.00</span>
                </div>
            </div>
            <h2 id="TENDERS" class="menu-section-title">TENDERS</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3 class="menu-item-title">Chicken Tenders – 6pcs</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$9.00</span>
                </div>
                <div class="menu-item">
                    <h3 class="menu-item-title">Chicken Tenders – 9pcs</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$12.00</span>
                </div>
            </div>
            <h2 id="WINGS" class="menu-section-title">WINGS</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3 class="menu-item-title">Hot & Spicy Wings – 6pcs</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$9.00</span>
                </div>
                <div class="menu-item">
                    <h3 class="menu-item-title">Hot & Spicy Wings – 9pcs</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$12.00</span>
                </div>
            </div>
            <h2 id="SPECIAL OFFERS" class="menu-section-title">SPECIAL OFFERS</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3 class="menu-item-title">Da Crust Combo</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$19.99</span>
                </div>
                <div class="menu-item">
                    <h3 class="menu-item-title">Family Meal</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$19.99</span>
                </div>
            </div>
            <h2 id="SIDES" class="menu-section-title">SIDES</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3 class="menu-item-title">French Fries</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$4.00</span>
                </div>
                <div class="menu-item">
                    <h3 class="menu-item-title">Mac & Cheese</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$4.00</span>
                </div>
                <div class="menu-item">
                    <h3 class="menu-item-title">Coleslaw</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$4.00</span>
                </div>
            </div>
        </div>
                <h2 id="DESSERTS" class="menu-section-title">DESSERTS</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3 class="menu-item-title">Bubble Waffle</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$4.00</span>
                </div>
                <div class="menu-item">
                    <h3 class="menu-item-title">Milkshake</h3>
                    <p class="menu-item-desc"></p>
                    <span class="menu-item-price">$4.00</span>
                </div>
            </div>
        </div>
    </section>
</main>
</body>
</html>






order css


body {
    margin: 0;
    font-family: 'Montserrat', Arial, sans-serif;
    background: #fae68a;
}

.main-header {
    width: 100%;
    background: #fff;
    border-bottom: 1px solid #eee;
    position: sticky;
    top: 0;
    z-index: 100;
}

.navbar {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    max-width: 1600px;
    margin: 0 auto;
    padding: 16px 32px;
    gap: 24px;
}

.nav-link {
    color: #222;
    text-decoration: none;
    font-size: 1.1em;
    font-weight: 500;
    transition: color 0.2s;
    position: relative;
}

.nav-link.active,
.nav-link:hover {
    color: #e74c3c;
}

.nav-separator {
    display: inline-block;
    width: 24px;
}

.login .icon-user {
    display: inline-block;
    width: 18px;
    height: 18px;
    background: url('https://img.icons8.com/ios-filled/50/000000/user.png') no-repeat center/contain;
    vertical-align: middle;
    margin-right: 4px;
}

.cart .icon-cart {
    display: inline-block;
    width: 18px;
    height: 18px;
    background: url('https://img.icons8.com/ios-filled/50/000000/shopping-cart.png') no-repeat center/contain;
    vertical-align: middle;
}

@media (max-width: 700px) {
    .navbar {
        flex-wrap: wrap;
        gap: 12px;
        padding: 12px 8px;
    }
    .nav-link {
        font-size: 1em;
    }
}

.order-txt {
    background: #fae68a;
    width: 100%;
    min-height: 400px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding-top: 40px;
    padding-left: 80px;
}

.order-title {
    color: #d72600;
    font-size: 5rem;
    font-weight: bold;
    margin-bottom: 30px;
    text-align: left;
    padding: 0;
}

.order-block {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 18px;
}

.order-status {
    display: inline-flex;
    align-items: center;
    background: #fff;
    border-radius: 20px;
    padding: 6px 16px;
    font-size: 1rem;
    margin-bottom: 0;
}

.order-type {
    display: flex;
    width: 260px;
    margin-bottom: 0;
}

.order-info {
    display: flex;
    gap: 32px;
    font-size: 1rem;
    align-items: center;
    margin-top: 0;
    justify-content: flex-start;
}

.icon-clock::before {
    content: "⏰";
    margin-right: 6px;
}

.icon-location::before {
    content: "📍";
    margin-right: 6px;
}

.change-link {
    color: #d72600;
    margin-left: 8px;
    text-decoration: underline;
    cursor: pointer;
}

.order-btn-active {
    background-color: #d72600;
    color: white;
    font-size: 14px;
    text-decoration: none;
    padding: 15px 25px;
    gap: 4px;
}

.order-btn {
    border: 1px solid black;
    background: #fae68a;
    color: black;
    font-size: 14px;
    text-decoration: none;
    padding: 15px 25px;
    gap: 4px;
}

/* --- Menu section styles --- */
.order-menu {
    background: #fcf5e8;
    padding: 40px 80px;
    width: 100%;
}

.menu-nav {
    display: flex;
    gap: 24px;
    border-bottom: 2px solid #e74c3c;
    margin-bottom: 32px;
}

.menu-link {
    color: #222;
    text-decoration: none;
    font-size: 1.1em;
    font-weight: 500;
    padding-bottom: 6px;
    border-bottom: 2px solid transparent;
    transition: color 0.2s, border-bottom 0.2s;
}

.menu-link.active,
.menu-link:hover {
    color: #d72600;
    border-bottom: 2px solid #d72600;
}

.menu-content {
    margin-top: 32px;
}

.menu-section-title {
    font-size: 2rem;
    font-weight: bold;
    margin: 32px 0 18px 0;
    color: #222;
}

.menu-items {
    display: flex;
    gap: 32px;
    margin-bottom: 32px;
    flex-wrap: wrap;
}

.menu-item {
    background: #fff;
    border: 2px solid #d72600;
    padding: 18px 18px 12px 18px;
    width: 320px;
    min-height: 120px;
    box-sizing: border-box;
    margin-bottom: 0;
    display: flex;
    flex-direction: column;
    gap: 8px;
}

.menu-item-title {
    font-size: 1.15rem;
    font-weight: bold;
    margin: 0 0 4px 0;
    color: #222;
}

.menu-item-desc {
    font-size: 1rem;
    color: #222;
    margin: 0 0 8px 0;
}

.menu-item-price {
    font-size: 1rem;
    color: #222;
    font-weight: 500;
    margin-top: auto;
}

