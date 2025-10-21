<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Piece Hall - Content Portal</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Montserrat', sans-serif; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        .bg-sandstone-gold { background-color: #B3A369; }
        .text-sandstone-gold { color: #B3A369; }
        .border-sandstone-gold { border-color: #B3A369; }
        .form-input {
            background-color: #2d3748;
            border: 1px solid #4a5568;
            color: #e2e8f0;
        }
        .form-input:focus {
            outline: none;
            border-color: #B3A369;
            box-shadow: 0 0 0 2px rgba(179, 163, 105, 0.5);
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">

    <!-- Login View -->
    <div id="login-view" class="min-h-screen flex items-center justify-center">
        <div class="bg-gray-800 p-8 rounded-lg shadow-lg w-full max-w-md">
            <img src="https://www.thepiecehall.co.uk/wp-content/uploads/2021/06/ThePieceHall_Logo_white.png" alt="The Piece Hall Logo" class="h-12 w-auto mx-auto mb-6">
            <h1 class="text-3xl text-sandstone-gold text-center mb-6">Content Portal</h1>
            <form id="admin-login-form" class="space-y-6">
                <div>
                    <label for="admin-email" class="block text-sandstone-gold font-semibold mb-2">Email</label>
                    <input type="email" id="admin-email" required class="w-full rounded-lg p-3 form-input" placeholder="your-email@example.com">
                </div>
                <div>
                    <label for="admin-password" class="block text-sandstone-gold font-semibold mb-2">Password</label>
                    <input type="password" id="admin-password" required class="w-full rounded-lg p-3 form-input">
                </div>
                <button type="submit" class="w-full p-4 bg-sandstone-gold text-black font-bold text-lg rounded-lg shadow-lg hover:bg-yellow-500 transition-colors">Login</button>
                <p id="login-error" class="text-sm text-red-400 text-center h-4"></p>
            </form>
        </div>
    </div>

    <!-- Dashboard View -->
    <div id="dashboard-view" class="hidden container mx-auto p-6">
        <header class="flex justify-between items-center mb-8">
            <h1 class="text-4xl text-sandstone-gold">Dashboard</h1>
            <button id="logout-button" class="bg-red-600 hover:bg-red-500 text-white font-bold py-2 px-4 rounded-lg transition-colors">Logout</button>
        </header>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
            
            <!-- Push Notifications -->
            <div class="bg-gray-800 p-6 rounded-lg lg:col-span-2">
                <h2 class="text-2xl text-sandstone-gold mb-4">Send Push Notification</h2>
                   <form id="push-notification-form" class="space-y-4">
                        <div>
                            <label for="push-title" class="block font-semibold mb-1">Title</label>
                            <input type="text" id="push-title" required class="w-full rounded p-2 form-input" placeholder="e.g. New Event Announced!">
                        </div>
                        <div>
                            <label for="push-body" class="block font-semibold mb-1">Message</label>
                            <textarea id="push-body" rows="2" required class="w-full rounded p-2 form-input" placeholder="e.g. Tickets for Noel Gallagher are now on sale."></textarea>
                        </div>
                        <button type="submit" class="w-full p-3 bg-purple-600 hover:bg-purple-500 text-white font-bold rounded-lg">Send Notification to All Users</button>
                   </form>
                   <p id="push-status" class="text-sm mt-3 text-green-400"></p>
                   <p class="text-xs text-gray-500 mt-2">Note: This requires Firebase Cloud Messaging setup in the main app.</p>
            </div>

            <!-- News Management -->
            <div class="bg-gray-800 p-6 rounded-lg">
                <h2 class="text-2xl text-sandstone-gold mb-4">Latest News</h2>
                <form id="news-form" class="space-y-4">
                    <div>
                        <label for="news-title" class="block font-semibold mb-1">Headline</label>
                        <input type="text" id="news-title" required class="w-full rounded p-2 form-input">
                    </div>
                    <div>
                        <label for="news-summary" class="block font-semibold mb-1">Summary</label>
                        <textarea id="news-summary" rows="4" required class="w-full rounded p-2 form-input"></textarea>
                    </div>
                    <button type="submit" class="w-full p-3 bg-blue-600 hover:bg-blue-500 text-white font-bold rounded-lg transition-colors">Add News Article</button>
                </form>
                  <div id="news-list" class="mt-6 space-y-2"></div>
            </div>

            <!-- Offers Management -->
            <div class="bg-gray-800 p-6 rounded-lg">
                <h2 class="text-2xl text-sandstone-gold mb-4">Discounts & Offers</h2>
                <form id="offers-form" class="space-y-4">
                      <div>
                            <label for="offer-title" class="block font-semibold mb-1">Offer Title</label>
                            <input type="text" id="offer-title" required class="w-full rounded p-2 form-input">
                        </div>
                        <div>
                            <label for="offer-description" class="block font-semibold mb-1">Description</label>
                            <textarea id="offer-description" rows="3" required class="w-full rounded p-2 form-input"></textarea>
                        </div>
                         <div>
                            <label for="offer-terms" class="block font-semibold mb-1">Terms & Conditions</label>
                            <input type="text" id="offer-terms" required class="w-full rounded p-2 form-input">
                        </div>
                    <button type="submit" class="w-full p-3 bg-blue-600 hover:bg-blue-500 text-white font-bold rounded-lg transition-colors">Add Offer</button>
                </form>
                  <div id="offers-list" class="mt-6 space-y-2"></div>
            </div>

            <!-- Stock Management -->
            <div class="bg-gray-800 p-6 rounded-lg lg:col-span-2">
                <h2 class="text-2xl text-sandstone-gold mb-4">My Shop Inventory</h2>
                   <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                        <div>
                            <h3 class="text-xl text-sandstone-gold/80 mb-4">Add New Product</h3>
                            <form id="add-stock-form" class="space-y-4">
                                  <div>
                                      <label for="product-name" class="block font-semibold mb-1">Product Name</label>
                                      <input type="text" id="product-name" required class="w-full rounded p-2 form-input">
                                  </div>
                                   <div>
                                      <label for="product-desc" class="block font-semibold mb-1">Description</label>
                                      <textarea id="product-desc" rows="3" required class="w-full rounded p-2 form-input"></textarea>
                                  </div>
                                <div>
                                      <label for="product-price" class="block font-semibold mb-1">Price (£)</label>
                                      <input type="number" step="0.01" id="product-price" required class="w-full rounded p-2 form-input">
                                  </div>
                                <button type="submit" class="w-full p-3 bg-blue-600 hover:bg-blue-500 text-white font-bold rounded-lg transition-colors">Add Product</button>
                            </form>
                        </div>
                        <div>
                           <h3 class="text-xl text-sandstone-gold/80 mb-4">Current Listings</h3>
                             <div id="stock-list-container" class="space-y-4 max-h-96 overflow-y-auto">
                                   <p class="text-gray-400">Your products will appear here.</p>
                             </div>
                        </div>
                   </div>
            </div>

        </div>
    </div>

<!-- Firebase SDK -->
<script type="module">
    // Import the functions you need from the SDKs you need
    import { initializeApp } from "https://www.gstatic.com/firebasejs/12.4.0/firebase-app.js";
    import { getAuth, signInWithEmailAndPassword, signOut, onAuthStateChanged } from "https://www.gstatic.com/firebasejs/12.4.0/firebase-auth.js";
    import { getFirestore, collection, addDoc, onSnapshot, serverTimestamp } from "https://www.gstatic.com/firebasejs/12.4.0/firebase-firestore.js";

    // Your web app's Firebase configuration
    const firebaseConfig = {
        apiKey: "AIzaSyAkUzc7R6vwigj9Tlw3qhsZbrFHwICjV04",
        authDomain: "welcome-to-the-piece-hall.firebaseapp.com",
        projectId: "welcome-to-the-piece-hall",
        storageBucket: "welcome-to-the-piece-hall.appspot.com",
        messagingSenderId: "983606755725",
        appId: "1:983606755725:web:434060645154f88c2a7dc4"
    };

    // Initialize Firebase
    const app = initializeApp(firebaseConfig);
    const auth = getAuth(app);
    const db = getFirestore(app);

    document.addEventListener('DOMContentLoaded', () => {
        const loginView = document.getElementById('login-view');
        const dashboardView = document.getElementById('dashboard-view');
        const loginForm = document.getElementById('admin-login-form');
        const logoutButton = document.getElementById('logout-button');
        const loginError = document.getElementById('login-error');

        // --- REAL Authentication using Firebase ---
        onAuthStateChanged(auth, (user) => {
            if (user) {
                // User is signed in
                loginView.classList.add('hidden');
                dashboardView.classList.remove('hidden');
                // Start listening for real-time data from Firestore
                listenToCollections();
            } else {
                // User is signed out
                dashboardView.classList.add('hidden');
                loginView.classList.remove('hidden');
            }
        });

        loginForm.addEventListener('submit', (e) => {
            e.preventDefault();
            const email = document.getElementById('admin-email').value;
            const password = document.getElementById('admin-password').value;
            loginError.textContent = ''; // Clear previous errors

            signInWithEmailAndPassword(auth, email, password)
                .catch((error) => {
                    console.error("Login Error:", error);
                    loginError.textContent = "Invalid email or password.";
                });
        });
        
        logoutButton.addEventListener('click', () => {
            signOut(auth).catch(error => console.error("Logout Error:", error));
        });

        // --- REAL Content Management Forms with Firestore ---
        const newsForm = document.getElementById('news-form');
        const offersForm = document.getElementById('offers-form');
        const stockForm = document.getElementById('add-stock-form');
        
        // --- Firestore Collection References ---
        const newsCol = collection(db, 'news');
        const offersCol = collection(db, 'offers');
        const productsCol = collection(db, 'products');

        newsForm.addEventListener('submit', async e => {
            e.preventDefault();
            await addDoc(newsCol, {
                name: document.getElementById('news-title').value,
                description: document.getElementById('news-summary').value,
                createdAt: serverTimestamp()
            });
            newsForm.reset();
        });

        offersForm.addEventListener('submit', async e => {
            e.preventDefault();
            await addDoc(offersCol, {
                name: document.getElementById('offer-title').value,
                description: document.getElementById('offer-description').value,
                terms: document.getElementById('offer-terms').value,
                createdAt: serverTimestamp()
            });
            offersForm.reset();
        });

        stockForm.addEventListener('submit', async e => {
            e.preventDefault();
            await addDoc(productsCol, {
                name: document.getElementById('product-name').value,
                description: document.getElementById('product-desc').value,
                price: parseFloat(document.getElementById('product-price').value),
                createdAt: serverTimestamp()
            });
            stockForm.reset();
        });

        // --- REAL-TIME Data Listening and Rendering ---
        function listenToCollections() {
            onSnapshot(newsCol, (snapshot) => {
                const newsItems = snapshot.docs.map(doc => ({ id: doc.id, ...doc.data() }));
                renderNewsList(newsItems);
            });
            onSnapshot(offersCol, (snapshot) => {
                const offerItems = snapshot.docs.map(doc => ({ id: doc.id, ...doc.data() }));
                renderOffersList(offerItems);
            });
            onSnapshot(productsCol, (snapshot) => {
                const productItems = snapshot.docs.map(doc => ({ id: doc.id, ...doc.data() }));
                renderStockList(productItems);
            });
        }

        // --- Render Functions (Updated to accept data) ---
        function renderNewsList(newsDatabase) {
            const container = document.getElementById('news-list');
            container.innerHTML = newsDatabase.length === 0 ? '<p class="text-gray-400">No news articles added yet.</p>' : '';
            newsDatabase.sort((a, b) => b.createdAt - a.createdAt); // Show newest first
            newsDatabase.forEach(item => {
                const el = document.createElement('div');
                el.className = 'bg-gray-700 p-3 rounded';
                el.innerHTML = `<h4 class="font-semibold">${item.name}</h4><p class="text-sm text-gray-300">${item.description}</p>`;
                container.appendChild(el);
            });
        }

         function renderOffersList(offersDatabase) {
            const container = document.getElementById('offers-list');
            container.innerHTML = offersDatabase.length === 0 ? '<p class="text-gray-400">No offers added yet.</p>' : '';
            offersDatabase.sort((a, b) => b.createdAt - a.createdAt);
            offersDatabase.forEach(item => {
                const el = document.createElement('div');
                el.className = 'bg-gray-700 p-3 rounded';
                el.innerHTML = `<h4 class="font-semibold">${item.name}</h4><p class="text-sm text-gray-300">${item.description}</p><p class="text-xs text-gray-400 mt-1">Terms: ${item.terms}</p>`;
                container.appendChild(el);
            });
        }

        function renderStockList(traderDatabase) {
            const container = document.getElementById('stock-list-container');
            container.innerHTML = traderDatabase.length === 0 ? '<p class="text-gray-400">No products added yet.</p>' : '';
            traderDatabase.sort((a, b) => b.createdAt - a.createdAt);
            traderDatabase.forEach(product => {
                const productEl = document.createElement('div');
                productEl.className = 'bg-gray-700 p-3 rounded';
                productEl.innerHTML = `
                    <h4 class="font-semibold">${product.name}</h4>
                    <p class="text-sm text-gray-300">${product.description}</p>
                    <p class="text-right font-bold mt-1">£${parseFloat(product.price).toFixed(2)}</p>
                `;
                container.appendChild(productEl);
            });
        }
        
        // Push notification form is still present but will need separate Firebase Cloud Messaging setup.
        const pushForm = document.getElementById('push-notification-form');
        pushForm.addEventListener('submit', e => {
            e.preventDefault();
             const pushStatus = document.getElementById('push-status');
             pushStatus.textContent = 'Push notification logic needs to be connected to a server function.';
             setTimeout(() => pushStatus.textContent = '', 3000);
        });

    });
</script>
</body>
</html>

