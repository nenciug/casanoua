<!DOCTYPE html>
<html lang="ro">
<head>
    <link rel="icon" href="nenciug.webp" type="image/png">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="icon" href="favicon-96x96.png" type="image/png">
    <link rel="apple-touch-icon" href="apple-touch-icon.png">
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "Organization",
        "name": "Casa Ta Inteligentă",
        "url": "https://nenciug.github.io/casa-smart/index.html",
        "logo": "https://nenciug.github.io/casa-smart/apple-touch-icon.png",
        "sameAs": [
            "https://facebook.com/pagina-facebook",
            "https://instagram.com/pagina-instagram"
        ]
    }
    </script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produse - Casa Ta Inteligentă</title>
    <style>
        /* Stiluri pentru coșul de cumpărături și produse */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: black;
        }

        .product-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .product-item {
            background-color: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .product-item:hover {
            transform: translateY(-10px);
        }

        .product-info h5 {
            font-size: 1.2em;
            color: #333;
        }

        .product-price {
            font-size: 1.2em;
            color: #28a745;
            font-weight: bold;
        }

        #cart {
            position: fixed;
            top: 50%;
            right: 10px;
            background-color: #28a745;
            color: white;
            padding: 15px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }

        .cart-container {
            position: fixed;
            top: 20%;
            right: 5%;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 300px;
            display: none;
            z-index: 100;
        }

        .cart-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .cart-item span {
            font-size: 1.1em;
        }

        .cart-footer {
            text-align: center;
        }

        .total-price {
            font-size: 1.4em;
            color: #28a745;
            font-weight: bold;
        }

        .pay-btn {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            font-size: 1.2em;
        }

        .pay-btn:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="12.jpg" alt="Casa Ta Inteligentă">
        </div>
        <h2 class="slogan"></h2>
        <nav>
            <ul>
                <li><a href="index.html">Acasă</a></li>
                <li><a href="produse.html">Produse</a></li>
                <li><a href="info.html">Informații utile</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section>
        <h3>Produsele noastre:</h3>
        <div class="product-container">
            <!-- Exemplu de produs -->
            <div class="product-item" data-name="Termostat inteligent" data-price="550">
                <img src="termostat.PNG" alt="Termostat inteligent" class="product-image">
                <div class="product-info">
                    <h5>Termostat inteligent</h5>
                    <p>Te ajuta sa creezi scenarii pentru a mentine o temperatura/umiditate perfecte!</p>
                    <span class="product-price">550 RON</span>
                    <button class="add-to-cart">Adaugă în coș</button>
                </div>
            </div>

            <div class="product-item" data-name="Automatizare poarta" data-price="1800">
                <img src="poarta.PNG" alt="Automatizare poarta" class="product-image">
                <div class="product-info">
                    <h5>Automatizare poarta</h5>
                    <p>Deschide poarta in 2 moduri, cu telecomanda sau prin smartphone.</p>
                    <span class="product-price">1800 RON</span>
                    <button class="add-to-cart">Adaugă în coș</button>
                </div>
            </div>
        </div>

        <div id="cart" onclick="toggleCart()">Coș (0)</div>

        <div class="cart-container" id="cart-container">
            <h4>Coșul tău de cumpărături:</h4>
            <div id="cart-items"></div>
            <div class="cart-footer">
                <div class="total-price" id="total-price">Total: 0 RON</div>
                <button class="pay-btn" onclick="checkout()">Plătește cu ramburs</button>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Casa Ta Inteligentă</p>
        <p>Toate drepturile rezervate.</p>
        <p><a href="politica_privacy.html">Politica de confidențialitate</a></p>
    </footer>

    <script>
        let cart = [];
        const cartElement = document.getElementById('cart');
        const cartContainer = document.getElementById('cart-container');
        const cartItems = document.getElementById('cart-items');
        const totalPriceElement = document.getElementById('total-price');

        function toggleCart() {
            cartContainer.style.display = cartContainer.style.display === 'block' ? 'none' : 'block';
        }

        function addToCart(productName, productPrice) {
            cart.push({ name: productName, price: productPrice });
            updateCart();
        }

        function updateCart() {
            cartElement.innerHTML = `Coș (${cart.length})`;
            cartItems.innerHTML = '';
            let total = 0;

            cart.forEach((item, index) => {
                total += item.price;
                const cartItem = document.createElement('div');
                cartItem.classList.add('cart-item');
                cartItem.innerHTML = `<span>${item.name}</span><span>${item.price} RON</span>`;
                cartItems.appendChild(cartItem);
            });

            totalPriceElement.innerHTML = `Total: ${total} RON`;
        }

        function checkout() {
            alert('Ai ales plata ramburs. Vei fi contactat pentru confirmare.');
        }

        // Adăugare produse în coș
        document.querySelectorAll('.add-to-cart').forEach((button) => {
            button.addEventListener('click', (event) => {
                const productItem = event.target.closest('.product-item');
                const productName = productItem.getAttribute('data-name');
                const productPrice = parseFloat(productItem.getAttribute('data-price'));
                addToCart(productName, productPrice);
            });
        });
    </script>

</body>
</html>
