# https-gudolgroup.github.io-gudol-mart-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Freshness Delivered</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: #f9f9f9; }
        header { background: #2e7d32; color: white; padding: 1rem; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 100; }
        .logo { font-size: 1.5rem; font-weight: bold; }
        .search-bar { width: 50%; padding: 8px; border-radius: 4px; border: none; }
        
        .hero { background: #e8f5e9; padding: 40px; text-align: center; border-bottom: 5px solid #2e7d32; }
        
        .container { max-width: 1100px; margin: auto; padding: 20px; }
        .section-title { border-left: 5px solid #2e7d32; padding-left: 10px; margin-bottom: 20px; }
        
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
        .product-card { background: white; padding: 15px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
        .product-card img { max-width: 100%; height: 150px; object-fit: cover; }
        .price { color: #2e7d32; font-weight: bold; font-size: 1.2rem; }
        .btn { background: #2e7d32; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer; margin-top: 10px; }
        .btn:hover { background: #1b5e20; }
    </style>
</head>
<body>

<header>
    <div class="logo">Gudol Mart</div>
    <input type="text" class="search-bar" placeholder="Search for groceries (milk, bread, eggs...)">
    <div>🛒 Cart (0)</div>
</header>

<div class="hero">
    <h1>Fresh Groceries, Better Living.</h1>
    <p>Get free delivery on your first order over $50!</p>
</div>

<div class="container">
    <h2 class="section-title">Weekly Specials</h2>
    <div class="product-grid">
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1550989460-0adf9ea622e2?q=80&w=300&h=300&auto=format&fit=crop" alt="Apples">
            <h3>Organic Red Apples</h3>
            <p class="price">$3.99 / lb</p>
            <button class="btn">Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1550583724-1255818c053b?q=80&w=300&h=300&auto=format&fit=crop" alt="Milk">
            <h3>Whole Milk (1 gal)</h3>
            <p class="price">$4.50</p>
            <button class="btn">Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff?q=80&w=300&h=300&auto=format&fit=crop" alt="Bread">
            <h3>Artisan Sourdough</h3>
            <p class="price">$5.25</p>
            <button class="btn">Add to Cart</button>
        </div>
    </div>
</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Dhanera & Deesa Grocery</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 font-sans">

    <div class="bg-green-800 text-white text-center py-2 text-sm font-medium">
        🚚 Free Delivery to Dhanera & panthavada on orders over ₹500
    </div>

    <nav class="bg-white shadow-sm sticky top-0 z-50 px-6 py-4 flex justify-between items-center">
        <div class="text-2xl font-bold text-green-700">GUDOL MART</div>
        <div class="hidden md:flex space-x-8 font-medium text-gray-600">
            <a href="#" class="hover:text-green-700">Fruits & Veg</a>
            <a href="#" class="hover:text-green-700">Dairy</a>
            <a href="#" class="hover:text-green-700">Snacks</a>
            <a href="#" class="hover:text-green-700">Household</a>
        </div>
        <div class="flex items-center space-x-4">
            <button class="text-gray-600">🔍</button>
            <button class="bg-orange-500 text-white px-4 py-2 rounded-lg font-bold">Cart (0)</button>
        </div>
    </nav>

    <section class="bg-white border-b p-8 text-center">
        <h2 class="text-xl font-semibold mb-4">Check Delivery in Your Area</h2>
        <div class="flex justify-center gap-2">
            <input id="zipInput" type="text" placeholder="Enter Zip Code" class="border p-2 rounded-l-md w-64 focus:outline-green-600">
            <button onclick="checkZip()" class="bg-green-700 text-white px-6 py-2 rounded-r-md hover:bg-green-800 transition">Check</button>
        </div>
        <p id="zipMessage" class="mt-3 font-medium text-gray-600"></p>
    </section>

    <header class="relative bg-green-100 h-64 flex items-center justify-center overflow-hidden">
        <div class="text-center z-10">
            <h1 class="text-4xl font-extrabold text-gray-800 mb-2">Freshness at your doorstep.</h1>
            <p class="text-gray-600">Serving the heart of Banaskantha.</p>
        </div>
    </header>

    <main class="max-w-7xl mx-auto p-6">
        <h2 class="text-2xl font-bold mb-6">Trending Near You</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
            <div class="bg-white p-4 rounded-xl shadow-sm hover:shadow-md transition">
                <div class="h-40 bg-gray-200 rounded-lg mb-4"></div> <span class="text-xs font-bold text-green-600 uppercase">Dairy</span>
                <h3 class="font-semibold text-gray-800">Fresh Paneer (500g)</h3>
                <p class="text-lg font-bold mt-2">₹140</p>
                <button class="w-full mt-4 border-2 border-green-700 text-green-700 py-2 rounded-lg font-bold hover:bg-green-700 hover:text-white transition">Add to Cart</button>
            </div>
            </div>
    </main>

    <script>
        function checkZip() {
            const zip = document.getElementById('zipInput').value;
            const message = document.getElementById('zipMessage');
            const allowed = ["385545", "385310"];

            if (allowed.includes(zip)) {
                message.innerHTML = "✅ Great! We offer **Express Delivery** to your area.";
                message.className = "mt-3 font-medium text-green-600";
            } else {
                message.innerHTML = "❌ Sorry, we don't deliver to " + zip + " yet.";
                message.className = "mt-3 font-medium text-red-600";
            }
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Express Grocery</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
</head>
<body class="bg-gray-50 font-sans text-gray-900">

    <div class="bg-black text-white text-center py-2 text-xs md:text-sm font-bold tracking-wide uppercase">
        ⚡ Express Delivery to 385535 & 385310 | Min. Order ₹500
    </div>

    <nav class="bg-white border-b sticky top-0 z-50 px-6 py-4 flex justify-between items-center">
        <div class="text-2xl font-black tracking-tighter text-green-700">GUDOL MART</div>
        <div class="flex items-center space-x-6">
            <span class="hidden md:inline text-sm font-medium text-gray-500">Banaskantha, GJ</span>
            <div class="relative cursor-pointer" onclick="openCart()">
                <span class="text-2xl">🛒</span>
                <span id="cart-count" class="absolute -top-2 -right-2 bg-red-600 text-white text-[10px] font-bold px-1.5 rounded-full">0</span>
            </div>
        </div>
    </nav>

    <section class="bg-green-50 py-12 px-6 text-center border-b">
        <h1 class="text-3xl font-bold mb-4">Fresh Groceries Delivered in 60 Mins</h1>
        <p class="text-gray-600 mb-6">Check if we deliver to your doorstep:</p>
        <div class="max-w-md mx-auto flex shadow-lg rounded-lg overflow-hidden">
            <input id="zipInput" type="text" placeholder="Enter Zip Code (e.g. 385535)" class="w-full p-4 outline-none">
            <button onclick="validateArea()" class="bg-green-700 text-white px-8 font-bold hover:bg-green-800 transition">GO</button>
        </div>
        <p id="zipStatus" class="mt-4 font-bold"></p>
    </section>

    <main class="max-w-7xl mx-auto p-6">
        <div class="flex justify-between items-end mb-8">
            <h2 class="text-2xl font-bold">Daily Essentials</h2>
            <a href="#" class="text-green-700 font-bold border-b-2 border-green-700">View All</a>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="bg-white border rounded-xl p-4 hover:shadow-xl transition">
                <div class="aspect-square bg-gray-100 rounded-lg mb-4 flex items-center justify-center text-4xl">🥦</div>
                <h3 class="font-bold text-lg">Fresh Farm Vegetables (Combo)</h3>
                <p class="text-gray-500 text-sm mb-4">1kg Seasonal Mix</p>
                <div class="flex justify-between items-center">
                    <span class="text-xl font-black">₹249</span>
                    <button onclick="addToCart(249)" class="bg-black text-white px-6 py-2 rounded-full text-sm font-bold hover:bg-gray-800">Add +</button>
                </div>
            </div>

            <div class="bg-white border rounded-xl p-4 hover:shadow-xl transition">
                <div class="aspect-square bg-gray-100 rounded-lg mb-4 flex items-center justify-center text-4xl">🥛</div>
                <h3 class="font-bold text-lg">Pure Buffalo Milk (1L)</h3>
                <p class="text-gray-500 text-sm mb-4">Fresh from local dairy</p>
                <div class="flex justify-between items-center">
                    <span class="text-xl font-black">₹65</span>
                    <button onclick="addToCart(65)" class="bg-black text-white px-6 py-2 rounded-full text-sm font-bold hover:bg-gray-800">Add +</button>
                </div>
            </div>

            <div class="bg-white border rounded-xl p-4 hover:shadow-xl transition">
                <div class="aspect-square bg-gray-100 rounded-lg mb-4 flex items-center justify-center text-4xl">🍎</div>
                <h3 class="font-bold text-lg">Premium Apple Pack</h3>
                <p class="text-gray-500 text-sm mb-4">Imported - 4 Units</p>
                <div class="flex justify-between items-center">
                    <span class="text-xl font-black">₹199</span>
                    <button onclick="addToCart(199)" class="bg-black text-white px-6 py-2 rounded-full text-sm font-bold hover:bg-gray-800">Add +</button>
                </div>
            </div>
        </div>
    </main>

    <div id="checkout-bar" class="fixed bottom-0 w-full bg-white border-t p-6 shadow-2xl hidden transform transition-transform">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div>
                <p class="text-sm text-gray-500 font-bold uppercase tracking-widest">Total Amount</p>
                <p id="total-price" class="text-2xl font-black text-green-700">₹0</p>
            </div>
            <button onclick="startPayment()" class="bg-green-700 text-white px-12 py-4 rounded-xl font-black text-lg hover:bg-green-800">
                PAY WITH RAZORPAY
            </button>
        </div>
    </div>

    <script>
        let cartTotal = 0;
        let isAreaValid = false;

        function validateArea() {
            const zip = document.getElementById('zipInput').value;
            const status = document.getElementById('zipStatus');
            const validZips = ["385535", "385310"];

            if (validZips.includes(zip)) {
                status.innerText = "✅ Express Delivery Available for " + zip;
                status.className = "mt-4 font-bold text-green-600";
                isAreaValid = true;
            } else {
                status.innerText = "❌ Sorry, we don't deliver to this area yet.";
                status.className = "mt-4 font-bold text-red-600";
                isAreaValid = false;
            }
        }

        function addToCart(price) {
            cartTotal += price;
            document.getElementById('cart-count').innerText = "!";
            document.getElementById('total-price').innerText = "₹" + cartTotal;
            document.getElementById('checkout-bar').classList.remove('hidden');
        }

        function startPayment() {
            if (!isAreaValid) {
                alert("Please verify your Zip Code first!");
                return;
            }
            if (cartTotal < 500) {
                alert("Minimum order for Express Delivery is ₹500. Add ₹" + (500 - cartTotal) + " more!");
                return;
            }

            // Razorpay Integration Logic
            var options = {
                "key": "YOUR_RAZORPAY_KEY", // Enter your API Key here
                "amount": cartTotal * 100, // Amount in paise
                "currency": "INR",
                "name": "Gudol Mart",
                "description": "Grocery Delivery Deesa/Dhanera",
                "handler": function (response){
                    alert("Payment Successful! ID: " + response.razorpay_payment_id);
                },
                "theme": { "color": "#15803d" }
            };
            var rzp1 = new Razorpay(options);
            rzp1.open();
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Express Grocery</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
</head>
<body class="bg-gray-50 font-sans text-gray-900">

    <div class="bg-black text-white text-center py-2 text-xs md:text-sm font-bold tracking-wide uppercase">
        ⚡ Express Delivery to 385535 & 385310 | Min. Order ₹500
    </div>

    <nav class="bg-white border-b sticky top-0 z-50 px-6 py-4 flex justify-between items-center">
        <div class="text-2xl font-black tracking-tighter text-green-700">GUDOL MART</div>
        <div class="flex items-center space-x-6">
            <span class="hidden md:inline text-sm font-medium text-gray-500">Banaskantha, GJ</span>
            <div class="relative cursor-pointer" onclick="openCart()">
                <span class="text-2xl">🛒</span>
                <span id="cart-count" class="absolute -top-2 -right-2 bg-red-600 text-white text-[10px] font-bold px-1.5 rounded-full">0</span>
            </div>
        </div>
    </nav>

    <section class="bg-green-50 py-12 px-6 text-center border-b">
        <h1 class="text-3xl font-bold mb-4">Fresh Groceries Delivered in 60 Mins</h1>
        <p class="text-gray-600 mb-6">Check if we deliver to your doorstep:</p>
        <div class="max-w-md mx-auto flex shadow-lg rounded-lg overflow-hidden">
            <input id="zipInput" type="text" placeholder="Enter Zip Code (e.g. 385535)" class="w-full p-4 outline-none">
            <button onclick="validateArea()" class="bg-green-700 text-white px-8 font-bold hover:bg-green-800 transition">GO</button>
        </div>
        <p id="zipStatus" class="mt-4 font-bold"></p>
    </section>

    <main class="max-w-7xl mx-auto p-6">
        <div class="flex justify-between items-end mb-8">
            <h2 class="text-2xl font-bold">Daily Essentials</h2>
            <a href="#" class="text-green-700 font-bold border-b-2 border-green-700">View All</a>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="bg-white border rounded-xl p-4 hover:shadow-xl transition">
                <div class="aspect-square bg-gray-100 rounded-lg mb-4 flex items-center justify-center text-4xl">🥦</div>
                <h3 class="font-bold text-lg">Fresh Farm Vegetables (Combo)</h3>
                <p class="text-gray-500 text-sm mb-4">1kg Seasonal Mix</p>
                <div class="flex justify-between items-center">
                    <span class="text-xl font-black">₹249</span>
                    <button onclick="addToCart(249)" class="bg-black text-white px-6 py-2 rounded-full text-sm font-bold hover:bg-gray-800">Add +</button>
                </div>
            </div>

            <div class="bg-white border rounded-xl p-4 hover:shadow-xl transition">
                <div class="aspect-square bg-gray-100 rounded-lg mb-4 flex items-center justify-center text-4xl">🥛</div>
                <h3 class="font-bold text-lg">Pure Buffalo Milk (1L)</h3>
                <p class="text-gray-500 text-sm mb-4">Fresh from local dairy</p>
                <div class="flex justify-between items-center">
                    <span class="text-xl font-black">₹65</span>
                    <button onclick="addToCart(65)" class="bg-black text-white px-6 py-2 rounded-full text-sm font-bold hover:bg-gray-800">Add +</button>
                </div>
            </div>

            <div class="bg-white border rounded-xl p-4 hover:shadow-xl transition">
                <div class="aspect-square bg-gray-100 rounded-lg mb-4 flex items-center justify-center text-4xl">🍎</div>
                <h3 class="font-bold text-lg">Premium Apple Pack</h3>
                <p class="text-gray-500 text-sm mb-4">Imported - 4 Units</p>
                <div class="flex justify-between items-center">
                    <span class="text-xl font-black">₹199</span>
                    <button onclick="addToCart(199)" class="bg-black text-white px-6 py-2 rounded-full text-sm font-bold hover:bg-gray-800">Add +</button>
                </div>
            </div>
        </div>
    </main>

    <div id="checkout-bar" class="fixed bottom-0 w-full bg-white border-t p-6 shadow-2xl hidden transform transition-transform">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div>
                <p class="text-sm text-gray-500 font-bold uppercase tracking-widest">Total Amount</p>
                <p id="total-price" class="text-2xl font-black text-green-700">₹0</p>
            </div>
            <button onclick="startPayment()" class="bg-green-700 text-white px-12 py-4 rounded-xl font-black text-lg hover:bg-green-800">
                PAY WITH RAZORPAY
            </button>
        </div>
    </div>

    <script>
        let cartTotal = 0;
        let isAreaValid = false;

        function validateArea() {
            const zip = document.getElementById('zipInput').value;
            const status = document.getElementById('zipStatus');
            const validZips = ["385535", "385310"];

            if (validZips.includes(zip)) {
                status.innerText = "✅ Express Delivery Available for " + zip;
                status.className = "mt-4 font-bold text-green-600";
                isAreaValid = true;
            } else {
                status.innerText = "❌ Sorry, we don't deliver to this area yet.";
                status.className = "mt-4 font-bold text-red-600";
                isAreaValid = false;
            }
        }

        function addToCart(price) {
            cartTotal += price;
            document.getElementById('cart-count').innerText = "!";
            document.getElementById('total-price').innerText = "₹" + cartTotal;
            document.getElementById('checkout-bar').classList.remove('hidden');
        }

        function startPayment() {
            if (!isAreaValid) {
                alert("Please verify your Zip Code first!");
                return;
            }
            if (cartTotal < 500) {
                alert("Minimum order for Express Delivery is ₹500. Add ₹" + (500 - cartTotal) + " more!");
                return;
            }

            // Razorpay Integration Logic
            var options = {
                "key": "YOUR_RAZORPAY_KEY", // Enter your API Key here
                "amount": cartTotal * 100, // Amount in paise
                "currency": "INR",
                "name": "Gudol Mart",
                "description": "Grocery Delivery Deesa/Dhanera",
                "handler": function (response){
                    alert("Payment Successful! ID: " + response.razorpay_payment_id);
                },
                "theme": { "color": "#15803d" }
            };
            var rzp1 = new Razorpay(options);
            rzp1.open();
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Supermarket & Kirana Mall</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
    <style>
        :root { --brand-blue: #1e4b9a; --brand-red: #d32f2f; }
        .bg-brand-blue { background-color: var(--brand-blue); }
        .text-brand-blue { color: var(--brand-blue); }
        .border-brand-blue { border-color: var(--brand-blue); }
    </style>
</head>
<body class="bg-gray-50">

    <div class="bg-red-600 text-white text-center py-2 text-xs font-bold uppercase tracking-widest">
        Free Delivery to 385545 & 385310 on orders above ₹500
    </div>

    <nav class="bg-white shadow-md sticky top-0 z-50 px-6 py-2 flex justify-between items-center">
        <img src="logo.png" alt="Gudol Mart Logo" class="h-16 md:h-20">
        
        <div class="flex items-center space-x-4">
            <div class="text-right hidden md:block">
                <p class="text-[10px] text-gray-500 font-bold uppercase">Express Delivery</p>
                <p class="text-sm font-bold text-brand-blue">Deesa & Dhanera</p>
            </div>
            <button class="bg-brand-blue text-white px-5 py-2 rounded-full font-bold shadow-lg">
                🛒 Cart
            </button>
        </div>
    </nav>

    <section class="bg-brand-blue py-12 px-6 text-center text-white">
        <h1 class="text-3xl font-bold mb-4">Supermarket & Kirana Mall at Home</h1>
        <div class="max-w-md mx-auto flex rounded-lg overflow-hidden shadow-2xl">
            <input id="zipInput" type="text" placeholder="Enter Zip Code" class="w-full p-4 text-black outline-none font-bold">
            <button onclick="checkZip()" class="bg-red-600 px-6 font-bold hover:bg-red-700 transition">CHECK</button>
        </div>
        <p id="zipMsg" class="mt-4 font-bold"></p>
    </section>

    <main class="max-w-6xl mx-auto p-8">
        <h2 class="text-2xl font-bold mb-8 border-b-4 border-red-600 inline-block">Weekly Kirana Specials</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-4">
            <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transition border-t-4 border-brand-blue text-center">
                <div class="text-5xl mb-4">📦</div>
                <h3 class="font-bold text-lg uppercase">Monthly Ration Kit</h3>
                <p class="text-gray-500 text-sm mb-4">Essential grains & spices</p>
                <p class="text-2xl font-black text-brand-blue mb-4">₹1,499</p>
                <button onclick="payNow(1499)" class="w-full bg-brand-blue text-white py-3 rounded-lg font-bold hover:bg-blue-900">BUY NOW</button>
            </div>
        </div>
    </main>

    <script>
        let isEligible = false;
        const validZips = ["385545", "385310"];

        function checkZip() {
            const val = document.getElementById('zipInput').value;
            const msg = document.getElementById('zipMsg');
            if(validZips.includes(val)) {
                msg.innerText = "✅ We are ready to deliver to " + val + "!";
                isEligible = true;
            } else {
                msg.innerText = "❌ Currently only delivering to Deesa & Dhanera.";
                isEligible = false;
            }
        }

        function payNow(amt) {
            if(!isEligible) { return alert("Please verify your Zip Code first."); }
            if(amt < 500) { return alert("Minimum order is ₹500"); }

            var options = {
                "key": "YOUR_RAZORPAY_KEY",
                "amount": amt * 100,
                "currency": "INR",
                "name": "Gudol Mart",
                "description": "Kirana Mall Express Order",
                "image": "logo.png",
                "handler": function (res){ alert("Order Placed! ID: " + res.razorpay_payment_id); },
                "theme": { "color": "#1e4b9a" }
            };
            new Razorpay(options).open();
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Supermarket & Kirana Mall</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
    <style>
        :root { --brand-blue: #1e4b9a; --brand-red: #d32f2f; }
        .bg-brand-blue { background-color: var(--brand-blue); }
        .text-brand-blue { color: var(--brand-blue); }
        .border-brand-blue { border-color: var(--brand-blue); }
    </style>
</head>
<body class="bg-gray-50">

    <div class="bg-red-600 text-white text-center py-2 text-xs font-bold uppercase tracking-widest">
        Free Delivery to 385545 & 385310 on orders above ₹500
    </div>

    <nav class="bg-white shadow-md sticky top-0 z-50 px-6 py-2 flex justify-between items-center">
        <img src="logo.png" alt="Gudol Mart Logo" class="h-16 md:h-20">
        
        <div class="flex items-center space-x-4">
            <div class="text-right hidden md:block">
                <p class="text-[10px] text-gray-500 font-bold uppercase">Express Delivery</p>
                <p class="text-sm font-bold text-brand-blue">Deesa & Dhanera</p>
            </div>
            <button class="bg-brand-blue text-white px-5 py-2 rounded-full font-bold shadow-lg">
                🛒 Cart
            </button>
        </div>
    </nav>

    <section class="bg-brand-blue py-12 px-6 text-center text-white">
        <h1 class="text-3xl font-bold mb-4">Supermarket & Kirana Mall at Home</h1>
        <div class="max-w-md mx-auto flex rounded-lg overflow-hidden shadow-2xl">
            <input id="zipInput" type="text" placeholder="Enter Zip Code" class="w-full p-4 text-black outline-none font-bold">
            <button onclick="checkZip()" class="bg-red-600 px-6 font-bold hover:bg-red-700 transition">CHECK</button>
        </div>
        <p id="zipMsg" class="mt-4 font-bold"></p>
    </section>

    <main class="max-w-6xl mx-auto p-8">
        <h2 class="text-2xl font-bold mb-8 border-b-4 border-red-600 inline-block uppercase">Weekly Specials</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-4">
            <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transition border-t-4 border-brand-blue text-center">
                <div class="text-5xl mb-4">📦</div>
                <h3 class="font-bold text-lg uppercase">Monthly Ration Kit</h3>
                <p class="text-gray-500 text-sm mb-4">Essential grains & spices</p>
                <p class="text-2xl font-black text-brand-blue mb-4">₹1,499</p>
                <button onclick="payNow(1499)" class="w-full bg-brand-blue text-white py-3 rounded-lg font-bold hover:bg-blue-900">BUY NOW</button>
            </div>
        </div>
    </main>

    <script>
        let isEligible = false;
        const validZips = ["385545", "385310"];

        function checkZip() {
            const val = document.getElementById('zipInput').value;
            const msg = document.getElementById('zipMsg');
            if(validZips.includes(val)) {
                msg.innerText = "✅ We deliver to " + val + "!";
                isEligible = true;
            } else {
                msg.innerText = "❌ Currently only delivering to Deesa & Dhanera.";
                isEligible = false;
            }
        }

        function payNow(amt) {
            if(!isEligible) { return alert("Please verify your Zip Code first."); }
            if(amt < 500) { return alert("Minimum order is ₹500"); }

            var options = {
                "key": "YOUR_RAZORPAY_KEY",
                "amount": amt * 100,
                "currency": "INR",
                "name": "Gudol Mart",
                "description": "Kirana Mall Express Order",
                "image": "logo.png",
                "handler": function (res){ alert("Order Placed! ID: " + res.razorpay_payment_id); },
                "theme": { "color": "#1e4b9a" }
            };
            new Razorpay(options).open();
        }
    </script>
</body>
</html>
<a href="https://wa.me/91YOURNUMBERHERE?text=I%20need%20help%20with%20my%20Gudol%20Mart%20order" 
   style="position:fixed; bottom:100px; right:20px; background:#25d366; color:white; padding:15px; border-radius:50px; font-weight:bold; z-index:1000; box-shadow: 0px 4px 10px rgba(0,0,0,0.3);">
   💬 Chat with Us
</a>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Supermarket Express</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
    <style>
        :root { --brand-blue: #1e4b9a; --brand-red: #d32f2f; }
        .bg-brand-blue { background-color: var(--brand-blue); }
        .text-brand-blue { color: var(--brand-blue); }
        .whatsapp-float {
            position: fixed; bottom: 100px; right: 20px;
            background-color: #25d366; color: #FFF;
            border-radius: 50px; text-align: center; font-size: 14px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.2); z-index: 1000;
            padding: 12px 20px; font-weight: bold; display: flex; align-items: center; gap: 8px;
        }
    </style>
</head>
<body class="bg-gray-50">

    <a href="https://wa.me/910000000000?text=Hello%20Gudol%20Mart!%20I%20have%20a%20question%20about%20my%20order." class="whatsapp-float" target="_blank">
        <span>💬 Order on WhatsApp</span>
    </a>

    <div class="bg-red-600 text-white text-center py-2 text-xs font-bold uppercase tracking-widest">
        Free Delivery to 385545 & 385310 | Min. Order ₹500
    </div>

    <nav class="bg-white shadow-md sticky top-0 z-50 px-6 py-2 flex justify-between items-center">
        <img src="logo.png" alt="Gudol Mart Logo" class="h-14 md:h-16">
        <div class="flex items-center space-x-4">
            <button class="bg-brand-blue text-white px-5 py-2 rounded-full font-bold shadow-lg">🛒 Cart</button>
        </div>
    </nav>

    <section class="bg-brand-blue py-10 px-6 text-center text-white">
        <h1 class="text-2xl font-bold mb-4 uppercase">Supermarket & Kirana Mall</h1>
        <div class="max-w-md mx-auto flex rounded-lg overflow-hidden shadow-xl">
            <input id="zipInput" type="text" placeholder="Zip Code (385545/385310)" class="w-full p-4 text-black outline-none font-bold">
            <button onclick="checkZip()" class="bg-red-600 px-6 font-bold">CHECK</button>
        </div>
        <p id="zipMsg" class="mt-4 font-bold text-sm"></p>
    </section>

    <main class="max-w-6xl mx-auto p-8">
        <h2 class="text-xl font-bold mb-6 border-l-4 border-red-600 pl-3 uppercase">Weekly Kirana Deals</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-white p-6 rounded-xl shadow border-t-4 border-brand-blue text-center">
                <div class="text-4xl mb-4">🍚</div>
                <h3 class="font-bold uppercase text-sm">Premium Basmati Rice (5kg)</h3>
                <p class="text-2xl font-black text-brand-blue my-3">₹550</p>
                <button onclick="payNow(550)" class="w-full bg-brand-blue text-white py-3 rounded font-bold uppercase tracking-tighter">Buy Now</button>
            </div>
        </div>
    </main>

    <script>
        let isEligible = false;
        const validZips = ["385545", "385310"];

        function checkZip() {
            const val = document.getElementById('zipInput').value;
            const msg = document.getElementById('zipMsg');
            if(validZips.includes(val)) {
                msg.innerText = "✅ Express Delivery available for " + val;
                isEligible = true;
            } else {
                msg.innerText = "❌ Area not covered yet.";
                isEligible = false;
            }
        }

        function payNow(amt) {
            if(!isEligible) return alert("Verify your Zip Code first.");
            if(amt < 500) return alert("Minimum order for delivery is ₹500.");

            var options = {
                "key": "YOUR_RAZORPAY_KEY",
                "amount": amt * 100,
                "currency": "INR",
                "name": "Gudol Mart",
                "description": "Express Grocery Checkout",
                "image": "logo.png",
                "handler": function (res){ alert("Order Placed! ID: " + res.razorpay_payment_id); },
                "theme": { "color": "#1e4b9a" }
            };
            new Razorpay(options).open();
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gudol Mart | Supermarket & Kirana Mall</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
    <style>
        :root { --brand-blue: #1e4b9a; --brand-red: #d32f2f; }
        .bg-brand-blue { background-color: var(--brand-blue); }
        .text-brand-blue { color: var(--brand-blue); }
        /* Professional Floating WhatsApp Button */
        .whatsapp-btn {
            position: fixed; bottom: 30px; right: 20px;
            background-color: #25d366; color: white;
            padding: 12px 20px; border-radius: 50px;
            font-weight: bold; font-size: 14px;
            display: flex; align-items: center; gap: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            z-index: 9999; text-decoration: none;
            transition: transform 0.3s ease;
        }
        .whatsapp-btn:hover { transform: scale(1.05); }
    </style>
</head>
<body class="bg-gray-50 font-sans">

    <a href="https://wa.me/918141953535?text=Hello%20Gudol%20Mart!%20I%20want%20to%20order%20groceries." class="whatsapp-btn" target="_blank">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.438 9.889-9.886.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884 0 2.225.63 4.043 1.834 5.709l-.993 3.634 3.648-.961zm11.233-7.245c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg>
        <span>Order on WhatsApp</span>
    </a>

    <div class="bg-red-600 text-white text-center py-2 text-xs font-bold uppercase tracking-widest">
        Free Delivery to 385545 & 385310 | Min. Order ₹500
    </div>

    <nav class="bg-white shadow-md sticky top-0 z-50 px-6 py-2 flex justify-between items-center">
        <img src="logo.png" alt="Gudol Mart Logo" class="h-14 md:h-16">
        <div class="flex items-center space-x-4">
            <span class="text-xs font-bold text-gray-400 uppercase hidden md:block">Customer Support: +91 81419 53535</span>
            <button class="bg-brand-blue text-white px-5 py-2 rounded-full font-bold">🛒 Cart</button>
        </div>
    </nav>

    <section class="bg-brand-blue py-10 px-6 text-center text-white">
        <h1 class="text-2xl font-bold mb-4">DEESA & DHANERA EXPRESS GROCERY</h1>
        <div class="max-w-md mx-auto flex rounded-lg overflow-hidden shadow-2xl">
            <input id="zipInput" type="text" placeholder="Enter Zip Code" class="w-full p-4 text-black outline-none font-bold">
            <button onclick="checkZip()" class="bg-red-600 px-6 font-bold hover:bg-red-700 transition">GO</button>
        </div>
        <p id="zipMsg" class="mt-4 font-bold"></p>
    </section>

    <main class="max-w-6xl mx-auto p-8">
        <h2 class="text-xl font-bold mb-8 border-l-8 border-red-600 pl-4 uppercase">Popular in Your Area</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-brand-blue text-center">
                <div class="text-5xl mb-4">🛒</div>
                <h3 class="font-bold uppercase text-gray-700">Daily Kirana Pack</h3>
                <p class="text-gray-500 text-xs mb-4 italic">Oil, Sugar, Tea & Pulse Mix</p>
                <p class="text-3xl font-black text-brand-blue mb-6">₹899</p>
                <button onclick="payNow(899)" class="w-full bg-brand-blue text-white py-4 rounded-lg font-black uppercase hover:bg-blue-900 transition">Buy via Razorpay</button>
            </div>
        </div>
    </main>

    <script>
        let isEligible = false;
        const validZips = ["385545", "385310"];

        function checkZip() {
            const val = document.getElementById('zipInput').value;
            const msg = document.getElementById('zipMsg');
            if(validZips.includes(val)) {
                msg.innerText = "✅ Express Delivery Available!";
                msg.className = "mt-4 font-bold text-green-400";
                isEligible = true;
            } else {
                msg.innerText = "❌ Sorry, we don't deliver to " + val + " yet.";
                msg.className = "mt-4 font-bold text-red-400";
                isEligible = false;
            }
        }

        function payNow(amt) {
            if(!isEligible) return alert("Please check your Zip Code first!");
            if(amt < 500) return alert("Minimum order is ₹500.");

            var options = {
                "key": "YOUR_RAZORPAY_KEY", 
                "amount": amt * 100,
                "currency": "INR",
                "name": "Gudol Mart",
                "description": "Express Delivery Order",
                "image": "logo.png",
                "handler": function (res){ alert("Order Placed! Payment ID: " + res.razorpay_payment_id); },
                "theme": { "color": "#1e4b9a" }
            };
            new Razorpay(options).open();
        }
    </script>
</body>
</html>
