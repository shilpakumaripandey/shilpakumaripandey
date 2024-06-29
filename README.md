-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial- scale=1.0" />
<title>Footcap - Find your footware</title>

<!--
- favicon
-->
<link rel="shortcut icon" href="./favicon.svg" type="image/svg+xml" />

<!--
- custom css link
-->
<link rel="stylesheet" href="./assets/css/style.css" />

<!--
- google font link
-->
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link

href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@ 300;400;500;600;700&family=Roboto:wght@400;500;700&display=swap"
rel="stylesheet"
/>

<!--
 
 

- preload banner
-->
<link rel="preload" href="./assets/images/hero-banner.png" as="image" />
</head>

<body id="top">
<!--
- #HEADER
-->

<header class="header" data-header>
<div class="container">
<div class="overlay" data-overlay></div>

<a href="#" class="logo">
<img
src="./assets/images/logo.svg" width="160"
height="50" alt="Footcap logo"
/>
</a>

<button class="nav-open-btn" data-nav-open-btn aria- label="Open Menu">
<ion-icon name="menu-outline"></ion-icon>
</button>

<nav class="navbar" data-navbar>
<button
class="nav-close-btn" data-nav-close-btn
aria-label="Close Menu"
>
<ion-icon name="close-outline"></ion-icon>
</button>
 
 


<a href="#" class="logo">
<img
src="./assets/images/logo.svg" width="190"
height="50" alt="Footcap logo"
/>
</a>

<ul class="navbar-list">
<li class="navbar-item">
<a href="#" class="navbar-link">Home</a>
</li>

<li class="navbar-item">
<a href="#" class="navbar-link">About</a>
</li>

<li class="navbar-item">
<a href="#" class="navbar-link">Products</a>
</li>

<li class="navbar-item">
<a href="#" class="navbar-link">Shop</a>
</li>

<li class="navbar-item">
<a href="#" class="navbar-link">Blog</a>
</li>

<li class="navbar-item">
<a href="#" class="navbar-link">Contact</a>
</li>
</ul>

<ul class="nav-action-list">
 
 

<li>
<button class="nav-action-btn">
<ion-icon name="search-outline" aria- hidden="true"></ion-icon>

<span class="nav-action-text">Search</span>
</button>
</li>

<li>
<a href="#" class="nav-action-btn">
<ion-icon name="person-outline" aria- hidden="true"></ion-icon>

<span class="nav-action-text">Login /
Register</span>
</a>
</li>

<li>
<button class="nav-action-btn">
<ion-icon name="heart-outline" aria- hidden="true"></ion-icon>

<span class="nav-action-text">Wishlist</span>

 

hidden="true"
 
<data class="nav-action-badge" value="5" aria-

>5</data
>
</button>
 
</li>

<li>
<button class="nav-action-btn">
<ion-icon name="bag-outline" aria- hidden="true"></ion-icon>
 
 


<data class="nav-action-text" value="318.00"
>Basket: <strong>$318.00</strong></data
>

 

hidden="true"
 
<data class="nav-action-badge" value="4" aria-

>4</data
>
</button>
 
</li>
</ul>
</nav>
</div>
</header>

<main>
<article>
<!--
- #HERO
-->

<section class="section hero"
style="background-image: url('./assets/images/hero- banner.png')"
>
<div class="container">
<h2 class="h1 hero-title">
New Summer <strong>Shoes Collection</strong>
</h2>

<p class="hero-text">
Competently expedite alternative benefits whereas
leading-edge
catalysts for change. Globally leverage existing an
expanded array
 
 

of leadership.
</p>

<button class="btn btn-primary">
<span>Shop Now</span>

<ion-icon
name="arrow-forward-outline" aria-hidden="true"
></ion-icon>
</button>
</div>
</section>

<!--
- #COLLECTION
-->

<section class="section collection">
<div class="container">
<ul class="collection-list has-scrollbar">
<li>
<div
class="collection-card" style="
background-image: url('./assets/images/collection-1.jpg');
"
>
<h3 class="h4 card-title">Men Collections</h3>

<a href="#" class="btn btn-secondary">
<span>Explore All</span>

<ion-icon
name="arrow-forward-outline" aria-hidden="true"
 
 

></ion-icon>
</a>
</div>
</li>

<li>
<div
class="collection-card" style="
background-image: url('./assets/images/collection-2.jpg');
"
 
>

Collections</h3>
 

<h3 class="h4 card-title">Women
 

<a href="#" class="btn btn-secondary">
<span>Explore All</span>

<ion-icon
name="arrow-forward-outline" aria-hidden="true"
></ion-icon>
</a>
</div>
</li>

<li>
<div
class="collection-card" style="
background-image: url('./assets/images/collection-3.jpg');
"
 
>

Collections</h3>
 

<h3 class="h4 card-title">Sports
 
 


<a href="#" class="btn btn-secondary">
<span>Explore All</span>

<ion-icon
name="arrow-forward-outline" aria-hidden="true"
></ion-icon>
</a>
</div>
</li>
</ul>
</div>
</section>

<!--
- #PRODUCT
-->

<section class="section product">
<div class="container">
<h2 class="h2 section-title">Bestsellers Products</h2>

<ul class="filter-list">
<li>
<button class="filter-btn active">All</button>
</li>

<li>
<button class="filter-btn">Nike</button>
</li>

<li>
<button class="filter-btn">Adidas</button>
</li>
 
 

<li>
<button class="filter-btn">Puma</button>
</li>

<li>
<button class="filter-btn">Bata</button>
</li>

<li>
<button class="filter-btn">Apex</button>
</li>
</ul>

<ul class="product-list">
<li class="product-item">
<div class="product-card" tabindex="0">
<figure class="card-banner">
<img
src="./assets/images/product-1.jpg" width="312"
height="350" loading="lazy"
alt="Running Sneaker Shoes" class="image-contain"
/>

<div class="card-badge">New</div>

<ul class="card-action-list">
<li class="card-action-item">
<button
class="card-action-btn"
aria-labelledby="card-label-1"
 


icon>
 
>
<ion-icon name="cart-outline"></ion-
 
</button>
 
 



 
 

<div class="newsletter-header">
<h3 class="newsletter-title">Subscribe Newsletter.</h3>

<p class="newsletter-desc">
Subscribe the <b>FootCap</b> to get latest products and discount
update.
</p>
</div>

<input
type="email" name="email" class="email-field"
placeholder="Email Address" required
/>

<button type="submit" class="btn- newsletter">Subscribe</button>
</form>
</div>
</div>
</div>

<!--
- NOTIFICATION TOAST
-->

<div class="notification-toast" data-toast>
<button class="toast-close-btn" data-toast-close>
<ion-icon name="close-outline"></ion-icon>
</button>

<div class="toast-banner">
<img
 
 

src="./assets/images/products/jewellery-1.jpg" alt="Rose Gold Earrings"
width="80" height="70"
/>
</div>

<div class="toast-detail">
<p class="toast-message">Someone in new just bought</p>

<p class="toast-title">Rose Gold Earrings</p>

<p class="toast-meta"><time datetime="PT2M">2 Minutes</time> ago</p>
</div>
</div>

<!--
- HEADER
-->

<header>
<div class="header-top">
<div class="container">
<ul class="header-social-container">
<li>
<a href="#" class="social-link">
<ion-icon name="logo-facebook"></ion-icon>
</a>
</li>

<li>
<a href="#" class="social-link">
<ion-icon name="logo-twitter"></ion-icon>
</a>
</li>
 
 

<li>
<a href="#" class="social-link">
<ion-icon name="logo-instagram"></ion-icon>
</a>
</li>

<li>
<a href="#" class="social-link">
<ion-icon name="logo-linkedin"></ion-icon>
</a>
</li>
</ul>

<div class="header-alert-news">
<p>
<b>Free Shipping</b>
This Week Order Over - $55
</p>
</div>

<div class="header-top-actions">
<select name="currency">
<option value="usd">INR</option>
<option value="eur">EUR &euro;</option>
</select>

<select name="language">
<option value="en-US">English</option>
<option value="es-ES">Espa&ntilde;ol</option>
<option value="fr">Fran&ccedil;ais</option>
</select>
</div>
</div>
</div>

<div class="header-main">
<div class="container">
 
 

<a href="#" class="header-logo">
<img
src="./assets/images/logo/logo.svg" alt="FootCap's logo"
width="120" height="36"
/>
</a>

<div class="header-search-container">
<input
type="search" name="search" class="search-field"
placeholder="Enter your product name..."
/>

<button class="search-btn">
<ion-icon name="search-outline"></ion-icon>
</button>
</div>

<div class="header-user-actions">
<button class="action-btn">
<ion-icon name="person-outline"></ion-icon>
</button>

<button class="action-btn">
<ion-icon name="heart-outline"></ion-icon>
<span class="count">0</span>
</button>

<button class="action-btn">
<ion-icon name="bag-handle-outline"></ion-icon>
<span class="count">0</span>
</button>
</div>
 
 

</div>
</div>

<nav class="desktop-navigation-menu">
<div class="container">
<ul class="desktop-menu-category-list">
<li class="menu-category">
<a href="#" class="menu-title">Home</a>
</li>

<li class="menu-category">
<a href="#" class="menu-title">Categories</a>

<div class="dropdown-panel">
<ul class="dropdown-panel-list">
<li class="menu-title">
<a href="#">Electronics</a>
</li>

<li class="panel-list-item">
<a href="#">Desktop</a>
</li>

<li class="panel-list-item">
<a href="#">Laptop</a>
</li>

<li class="panel-list-item">
<a href="#">Camera</a>
</li>

<li class="panel-list-item">
<a href="#">Tablet</a>
</li>

<li class="panel-list-item">
<a href="#">Headphone</a>
 
 

</li>

 





1.jpg"
 
<li class="panel-list-item">
<a href="#">
<img
src="./assets/images/electronics-banner-

alt="headphone collection" width="250"
height="119"
/>
</a>
</li>
</ul>
 
/*	*\
#style.css
\*	*/

/**
* copyright 2022 @codewithsadee
*/






/*	*\
#CUSTOM PROPERTY
\*	*/

:root {

/**
* colors
*/

--spanish-gray: hsl(0, 0%, 60%);
 
 

--sonic-silver: hsl(0, 0%, 47%);
--eerie-black: hsl(0, 0%, 13%);
--salmon-pink: hsl(353, 100%, 78%);
--sandy-brown: hsl(29, 90%, 65%);
--bittersweet: hsl(0, 100%, 70%);
--ocean-green: hsl(152, 51%, 52%);
--davys-gray: hsl(0, 0%, 33%);
--cultured: hsl(0, 0%, 93%);
--white: hsl(0, 100%, 100%);
--onyx: hsl(0, 0%, 27%);

/**
* typography
*/

--fs-1: 1.563rem;
--fs-2: 1.375rem;
--fs-3: 1.25rem;
--fs-4: 1.125rem;
--fs-5: 1rem;
--fs-6: 0.938rem;
--fs-7: 0.875rem;
--fs-8: 0.813rem;
--fs-9: 0.75rem;
--fs-10: 0.688rem;
--fs-11: 0.625rem;

--weight-300: 300;
--weight-400: 400;
--weight-500: 500;
--weight-600: 600;
--weight-700: 700;

/**
* border-radius
*/
 
 

--border-radius-md: 10px;
--border-radius-sm: 5px;

/**
* transition
*/

--transition-timing: 0.2s ease;

}






/*	*\
#RESET
\*	*/

*, *::before, *::after { margin: 0;
padding: 0;
box-sizing: border-box;
}

a { text-decoration: none; }

li { list-style: none; }

button { background: none; font: inherit; border: none; cursor: pointer;
}

img, ion-icon, button, a { display: block; }
 
 


span { display: inline-block; }

html {
font-family: "Poppins", sans-serif; overscroll-behavior: contain;
}

input {
display: block; width: 100%; font: inherit;
}

input::placeholder { font: inherit; }

body { background: var(--white); }

/**
* scrollbar style
*/

body::-webkit-scrollbar { width: 15px; }

body::-webkit-scrollbar-track { background: var(--white);
border-left: 1px solid var(--cultured);
}

body::-webkit-scrollbar-thumb { background: hsl(0, 0%, 80%); border: 3px solid var(--white); border-radius: 10px;
}

body::-webkit-scrollbar-thumb:hover { background: hsl(0, 0%, 70%); }
 
 







/*	*\
#REUSED STYLE
\*	*/

.container { padding: 0 15px; }

.has-scrollbar { padding-bottom: 5px; }

.has-scrollbar::-webkit-scrollbar { width: 12px; /* for vertical scroll */
height: 12px; /* for horizontal scroll */
}

.has-scrollbar::-webkit-scrollbar-thumb { background: transparent;
border: 3px solid var(--white); border-radius: 20px;
}

.has-scrollbar:hover::-webkit-scrollbar-thumb { background: hsl(0, 0%, 90%); }

.has-scrollbar::-webkit-scrollbar-thumb:hover { background: hsl(0, 0%, 80%); }

.title {
color: var(--eerie-black); font-size: var(--fs-5);
font-weight: var(--weight-600); letter-spacing: 0.4px;
text-transform: capitalize; padding-bottom: 10px;
 
 

border-bottom: 1px solid var(--cultured); margin-bottom: 30px;
}






/*	*\
#MAIN
\*	*/

/**
* overlay
*/

.overlay { position: fixed; top: 0;
left: 0;
width: 100%; height: 100vh;
background: hsla(0, 0%, 0%, 0.5);
opacity: 0;
pointer-events: none; z-index: 15; transition: 0.5s ease;
}

.overlay.active { opacity: 1;
pointer-events: all;
}



/**
 
 

* MODAL
*/ modal {
position: fixed; top: 0;
left: 0;
width: 100%; height: 100vh;
background: hsla(0, 0%, 0%, 0.5); display: flex;
justify-content: center; align-items: center; opacity: 0;
visibility: hidden; pointer-events: none; z-index: 10;
animation: popup 1s ease-in-out 5s forwards;
}

@keyframes popup {

0% {
opacity: 0; visibility: hidden; pointer-events: none;
}

100% {
opacity: 1; visibility: visible; pointer-events: all;
}

}

.modal.closed { display: none; }
 
 

.modal-close-overlay { position: absolute; top: 0;
left: 0;
width: 100%;
height: 100%;
z-index: 1;
}

.newsletter-img { display: none; }

.modal-content { position: relative; max-width: 350px; margin: 20px;
background: var(--white);
border-radius: var(--border-radius-md); overflow: hidden;
z-index: 2;
animation: scaleUp 0.5s ease-in-out 5s forwards;
}

@keyframes scaleUp {

0% { transform: scale(0.9); } 100% { transform: scale(1); }

}

.modal-close-btn { position: absolute; top: 15px;
right: 15px;
background: var(--salmon-pink); color: var(--white);
font-size: 16px; padding: 5px;
 
 

border-radius: var(--border-radius-sm);
}

.modal-close-btn:hover { opacity: 0.9; }

.modal-close-btn ion-icon { --ionicon-stroke-width: 70px; }

.newsletter { padding: 50px 30px; text-align: center;
}

.newsletter-header { margin-bottom: 20px; }

.newsletter-title { color: var(--onyx);
font-size: var(--fs-2);
font-weight: var(--weight-600); margin-bottom: 10px;
}

.newsletter-desc {
color: var(--sonic-silver); font-size: var(--fs-7); line-height: 1.6;
}

.email-field {
font-size: var(--fs-7); padding: 8px 16px;
border-radius: var(--border-radius-sm); border: 1px solid var(--cultured); margin-bottom: 16px;
}

.btn-newsletter {
background: var(--eerie-black);
 
 

color: var(--white);
font-size: var(--fs-7);
font-weight: var(--weight-600); text-transform: uppercase; padding: 10px 15px;
border-radius: var(--border-radius-sm); margin: auto;
transition: var(--transition-timing);
}

.btn-newsletter:hover { background: var(--salmon-pink); }






/**
* NOTIFICATION TOAST
*/

.notification-toast { position: fixed; bottom: 80px;
left: 20px; right: 20px;
background: var(--white); max-width: 300px; display: flex;
align-items: flex-start; gap: 15px;
padding: 15px;
border-radius: var(--border-radius-md);
box-shadow: 0 5px 20px hsla(0, 0%, 0%, 0.15); transform: translateX(calc(-100% - 40px)); transition: 0.5s ease-in-out;
z-index: 5;
animation: slideInOut 10s ease-in-out infinite;
 
 

}

@keyframes slideInOut {

0%,
45%,
100% {
transform: translateX(calc(-100% - 40px)); opacity: 0;
visibility: hidden;
}

50%,
95% {
transform: translateX(0); opacity: 1;
visibility: visible;
}

}

.notification-toast.closed { display: none; }

.toast-close-btn { position: absolute; top: 10px;
right: 10px;
color: var(--sonic-silver);
}

.toast-close-btn ion-icon { --ionicon-stroke-width: 50px; }

.toast-banner { width: 70px; height: 70px;
border: 1px solid var(--cultured); border-radius: var(--border-radius-sm);
 
 

}

.toast-banner img { width: 100%;
height: 100%;
object-fit: contain; object-position: center;
}

.toast-detail {
width: calc(100% - 85px); padding-right: 10px;
}

.toast-message {
font-size: var(--fs-10); color: var(--sonic-silver); margin-bottom: 8px;
}

.toast-title {
font-size: var(--fs-7);
font-weight: var(--weight-500); color: var(--onyx);
}

.toast-meta {
font-size: var(--fs-10); color: var(--sonic-silver);
}






/*	*\
#HEADER
 
 

\*	*/

.header-top,
.header-user-actions,
.desktop-navigation-menu { display: none; }

.header-main { padding: 20px 0;
border-bottom: 1px solid var(--cultured);
}

.header-logo { margin-bottom: 20px; }

.header-logo img { margin: auto; }

.header-search-container { position: relative; }

.header-search-container .search-field { font-size: var(--fs-7);
color: var(--onyx); padding: 10px 15px; padding-right: 50px;
border: 1px solid var(--cultured); border-radius: var(--border-radius-md);
}

.search-field::-webkit-search-cancel-button { display: none; }

.search-btn {
background: var(--white); position: absolute;
top: 50%; right: 2px;
transform: translateY(-50%); color: var(--onyx);
font-size: 18px; padding: 8px 15px;
 
 

border-radius: var(--border-radius-md); transition: color var(--transition-timing);
}

.search-btn:hover { color: var(--salmon-pink); }

.mobile-bottom-navigation { background: var(--white); position: fixed;
bottom: 0;
left: 50%;
transform: translateX(-50%); width: 100%;
max-width: 500px; margin: auto; display: flex;
justify-content: space-around; align-items: center;
padding: 5px 0;
box-shadow: 0 0 10px hsla(0, 0%, 0%, 0.25);
z-index: 5;
}

.mobile-bottom-navigation .action-btn { position: relative;
font-size: 26px;
color: var(--eerie-black); padding: 10px;
}

.mobile-bottom-navigation .count { background: var(--bittersweet); color: var(--white);
position: absolute; top: 0;
right: 0;
font-size: 12px;
 
 

font-weight: var(--weight-500); line-height: 1;
padding: 2px 4px; border-radius: 20px;
}

.mobile-navigation-menu { background: var(--white); position: fixed;
top: 0;
left: -100%;
width: 100%;
max-width: 320px; height: 100vh; padding: 20px;
box-shadow: 0 0 10px hsla(0, 0%, 0%, 0.1); overflow-y: scroll;
overscroll-behavior: contain; visibility: hidden; transition: 0.5s ease;
z-index: 20;
}

.mobile-navigation-menu.active { left: 0;
visibility: visible;
}

.menu-top {
padding-bottom: 15px; margin-bottom: 10px; display: flex;
justify-content: space-between; align-items: center;
border-bottom: 2px solid var(--cultured);
}
 
 

.menu-top .menu-title { color: var(--salmon-pink); font-size: var(--fs-4);
font-weight: var(--weight-600);
}

.menu-close-btn {
color: var(--eerie-black); font-size: 22px;
} .menu-top {
padding-bottom: 15px; margin-bottom: 10px; display: flex;
justify-content: space-between; align-items: center;
border-bottom: 2px solid var(--cultured);
}

.menu-top .menu-title { color: var(--salmon-pink); font-size: var(--fs-4);
font-weight: var(--weight-600);
}

.menu-close-btn {
color: var(--eerie-black); font-size: 22px;
}

.menu-close-btn ion-icon { --ionicon-stroke-width: 50px; }

.mobile-menu-category-list { margin-bottom: 30px; }

.menu-category .accordion-menu { width: 100%;
display: flex;
justify-content: space-between;
 
 

align-items: center;
}

.mobile-menu-category-list .menu-category { border-bottom: 1px solid var(--cultured); }

.mobile-menu-category-list .menu-title { color: var(--onyx);
font-size: var(--fs-6);
font-weight: var(--weight-500); padding: 12px 0;
}

.accordion-menu > div { font-size: 14px; }

.accordion-menu ion-icon { color: var(--onyx);
--ionicon-stroke-width: 90px;
}

.accordion-menu.active .add-icon,
.accordion-menu .remove-icon { display: none; }

.accordion-menu .add-icon,
.accordion-menu.active .remove-icon { display: block; }

.menu-category .submenu-category-list { margin-left: 10px; }

.submenu-title { padding: 6px 0;
font-size: var(--fs-6); color: var(--sonic-silver);
font-weight: var(--weight-300);
}
 
 

/*	*\
#BANNER
\*	*/

.banner { margin: 30px 0; }

.slider-container { display: flex;
align-items: center; gap: 10px;
border-radius: var(--border-radius-md); overflow: auto hidden;
scroll-snap-type: inline mandatory; overscroll-behavior-inline: contain;
}

.slider-item { position: relative; min-width: 100%; max-height: 450px;
aspect-ratio: 1 / 1;
border-radius: var(--border-radius-md); overflow: hidden;
scroll-snap-align: start;
}

.slider-item .banner-img { width: 100%;
height: 100%; object-fit: cover;
object-position: right;
}

.banner-content {
background: hsla(0, 0%, 100%, 0.8); position: absolute;
bottom: 25px;
 
 

left: 25px; right: 25px;
padding: 20px 25px;
border-radius: var(--border-radius-md);
}

.banner-subtitle {
color: var(--salmon-pink); font-size: var(--fs-7);
font-weight: var(--weight-500); text-transform: capitalize; letter-spacing: 2px;
margin-bottom: 10px;
}

.banner-title {
color: var(--eerie-black); font-size: var(--fs-1); text-transform: uppercase; line-height: 1;
margin-bottom: 10px;
}

.banner-text { display: none; }

.banner-btn {
background: var(--salmon-pink); color: var(--white);
width: max-content;
font-size: var(--fs-11);
font-weight: var(--weight-600); text-transform: uppercase; padding: 4px 10px;
border-radius: var(--border-radius-sm); transition: var(--transition-timing);
}
 
 

.banner-btn:hover { background: var(--eerie-black); }






/*	*\
#CATEGORY
\*	*/

.category { margin-bottom: 30px; }

.category-item-container { display: flex;
align-items: center; gap: 10px;
overflow: auto hidden;
scroll-snap-type: inline mandatory; overscroll-behavior-inline: contain;
}

.category-item { min-width: 100%; display: flex;
align-items: center; gap: 10px;
padding: 15px;
border: 1px solid var(--cultured); border-radius: var(--border-radius-md); scroll-snap-align: start;
}

.category-img-box { background: var(--cultured);
border: 1px solid hsl(0, 0%, 80%); padding: 10px;
border-radius: var(--border-radius-sm);
 
 

}

.category-content-box { width: 100%; }

.category-content-flex { display: flex;
justify-content: space-between; align-items: center;
margin-bottom: 10px;
}

.category-item-title { color: var(--eerie-black); font-size: var(--fs-9);
font-weight: var(--weight-600); text-transform: uppercase;
}

.category-item-amount { color: var(--sonic-silver); font-size: var(--fs-11);
}

.category-btn {
color: var(--salmon-pink); font-size: var(--fs-9);
font-weight: var(--weight-500); text-transform: capitalize;
}






/*	*\
#SIDEBAR
\*	*/
 
 


.sidebar {
background: var(--white); position: fixed;
top: 0;
left: -100%;
bottom: 0;
width: 100%;
max-width: 320px; padding: 30px; overflow-y: scroll;
overscroll-behavior: contain; visibility: hidden; transition: 0.5s ease;
z-	index: 20;
}

.sidebar-submenu-title:hover { color: var(--eerie-black); }

.sidebar .product-name { text-transform: capitalize; }

.sidebar-accordion-menu.active .add-icon,
.sidebar-accordion-menu .remove-icon { display: none; }

.sidebar-accordion-menu .add-icon,
.sidebar-accordion-menu.active .remove-icon { display: block; }

.sidebar .showcase-heading { font-size: var(--fs-5);
font-weight: var(--weight-600); color: var(--onyx);
text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 15px;
}

.sidebar .showcase {
 
 

display: flex;
align-items: center; gap: 15px;
}

.sidebar .showcase:not(:last-child) { margin-bottom: 15px; }

.sidebar .showcase-img { border-radius: var(--border-radius-sm);
}

.sidebar .showcase-content { width: calc(100% - 90px); }

.sidebar .showcase-title { color: var(--onyx);
font-size: var(--fs-7);
font-weight: var(--weight-400); text-transform: capitalize; overflow: hidden;
white-space: nowrap; text-overflow: ellipsis; letter-spacing: 0.5px;
}

.sidebar .showcase-rating { display: flex;
align-items: center; color: var(--sandy-brown); font-size: 13px;
padding: 4px 0;
}

.sidebar .price-box { display: flex;
align-items: center; gap: 15px;
}
 
 

.sidebar .price-box del { color: var(--sonic-silver); font-size: 13px;
}

.sidebar .price-box .price { font-size: var(--fs-7);
font-weight: var(--weight-600); color: var(--davys-gray);
}






/*	*\
#PRODUCT MINIMAL
\*	*/

.product-minimal { margin-bottom: 30px; }

.product-minimal .product-showcase { margin-bottom: 10px; }

.product-minimal .showcase-wrapper { display: flex;
align-items: center; overflow-x: auto;
overscroll-behavior-inline: contain; scroll-snap-type: inline mandatory;
}

.product-minimal .showcase-container { min-width: 100%;
padding: 0 5px;
scroll-snap-align: start;
}
 
 

.product-minimal .showcase { display: flex;
justify-content: flex-start; align-items: center;
gap: 15px;
border: 1px solid var(--cultured); padding: 15px;
border-radius: var(--border-radius-md);
}

.product-minimal .showcase:not(:last-child) { margin-bottom: 15px; }

.product-minimal .showcase-content { width: calc(100% - 85px); }

.product-minimal .showcase-title { color: var(--eerie-black);
font-size: var(--fs-7);
font-weight: var(--weight-600); text-transform: capitalize; white-space: nowrap;
overflow: hidden;
text-overflow: ellipsis; margin-bottom: 2px;
}

.product-minimal .showcase-category { width: max-content;
color: var(--davys-gray); font-size: var(--fs-8); text-transform: capitalize; margin-bottom: 3px;
}

.product-minimal .showcase-category:hover { color: var(--salmon- pink); }
 
 

.product-minimal .price-box { display: flex;
align-items: center; gap: 10px;
}

.product-minimal .price { font-size: var(--fs-7);
font-weight: var(--weight-700); color: var(--salmon-pink);
}

.product-minimal .price-box del { font-size: var(--fs-9);
color: var(--sonic-silver);
}






/*	*\
#PRODUCT FEATURED
\*	*/

.product-featured { margin-bottom: 30px; }

.product-featured .showcase-wrapper { display: flex;
align-items: center; gap: 20px;
overflow-x: auto;
overscroll-behavior-inline: contain; scroll-snap-type: inline mandatory;
}

.product-featured .showcase-container {
 
 

min-width: 100%; padding: 30px;
border: 1px solid var(--cultured); border-radius: var(--border-radius-md); scroll-snap-align: start;
}

.product-featured .showcase-img { width: 100%;
height: 100%; object-fit: cover;
}

.product-featured .showcase-content { margin-top: 30px; }

.product-featured .showcase-rating { color: var(--sandy-brown); display: flex;
align-items: center; font-size: 16px; margin-bottom: 15px;
}

.product-featured .showcase-title { font-size: var(--fs-7);
color: var(--eerie-black); overflow: hidden;
white-space: nowrap; text-overflow: ellipsis;
text-transform: uppercase; margin-bottom: 3px;
}

.product-featured .showcase-desc { color: var(--sonic-silver); font-size: var(--fs-7);
font-weight: var(--weight-300);
 
 

margin-bottom: 10px;
}

.product-featured .price-box { font-size: var(--fs-3); display: flex;
gap: 10px;
margin-bottom: 10px;
}

.product-featured .price { color: var(--salmon-pink);
font-weight: var(--weight-700);
}

.product-featured del { color: var(--sonic-silver);
font-weight: var(--weight-300);
}

.product-featured .add-cart-btn { background: var(--salmon-pink); padding: 8px 15px;
color: var(--white);
font-weight: var(--fs-9);
font-weight: var(--weight-700); text-transform: uppercase;
border-radius: var(--border-radius-md); margin-bottom: 15px;
transition: var(--transition-timing);
}

.product-featured .add-cart-btn:hover { background: var(--eerie-black); color: var(--white);
}
 
 

.product-featured .showcase-status { margin-bottom: 15px; }

.product-featured .showcase-status .wrapper { display: flex;
justify-content: space-between; align-items: center;
color: var(--eerie-black); font-size: var(--fs-9);
font-weight: var(--weight-400); text-transform: uppercase; margin-bottom: 10px;
}

.product-featured .showcase-status-bar { background: var(--cultured); position: relative;
height: 10px; border-radius: 5px;
}

.product-featured .showcase-status-bar::before { position: absolute;
content: ''; top: 3px; left: 3px; height: 4px; width: 40%;
background: var(--salmon-pink); border-radius: 4px;
}

.product-featured .countdown-desc { color: var(--eerie-black);
font-size: var(--fs-9);
font-weight: var(--weight-600); text-transform: uppercase; margin-bottom: 10px;
 
 

}

.product-featured .countdown { display: flex;
gap: 5px;
}

.product-featured .countdown-content { padding: 5px;
background: var(--cultured);
border-radius: var(--border-radius-md); text-align: center;
}

.product-featured .display-number { color: var(--eerie-black);
font-size: var(--fs-5);
font-weight: var(--weight-500); min-width: 40px;
}

.product-featured .display-text { color: var(--davys-gray);
font-size: var(--fs-11);
}






/*	*\
#PRODUCT GRID
\*	*/


<!---
shilpakumaripandey/shilpakumaripandey is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
