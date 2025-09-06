<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>7ravens Studio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .bg-custom-dark {
            background-color: #020420;
        }
        .card-gradient {
            background: linear-gradient(135deg, #182848, #050d1e);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card-gradient:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.5);
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .fade-in {
            animation: fadeIn 1.5s ease-out forwards;
        }
        .logo-text {
            animation: fadeIn 2s ease-out forwards;
        }
    </style>
</head>
<body class="bg-custom-dark text-gray-100">

    <!-- Header Section -->
    <header class="min-h-screen flex items-center justify-center text-center p-6">
        <div>
            <div class="logo-text text-8xl sm:text-9xl font-extrabold text-white mb-4 drop-shadow-2xl">
                <span class="bg-clip-text text-transparent bg-gradient-to-r from-teal-400 to-indigo-500">7</span>RAVENS <span class="text-3xl sm:text-4xl font-semibold">Studios</span>
            </div>
            <h1 class="text-3xl sm:text-4xl text-gray-300 font-light max-w-2xl mx-auto fade-in" style="animation-delay: 0.5s;">
                Capturing moments, crafting stories. We are the architects of your visual narrative.
            </h1>
        </div>
    </header>

    <!-- About Us Section -->
    <section id="about" class="container mx-auto py-16 px-6 sm:px-10">
        <h2 class="text-5xl font-bold text-center mb-12">About Us</h2>
        <div class="card-gradient rounded-3xl p-8 sm:p-12 shadow-2xl border border-gray-700">
            <p class="text-lg text-gray-300 leading-relaxed text-justify">
                7ravens Studio is a dynamic creative hub specializing in a wide range of visual arts. Our expertise spans from high-quality photography that captures the essence of every moment to cinematic video production that tells compelling stories. We are also pioneers in unique flaming video techniques, adding a fiery and unforgettable touch to your content. We believe in creativity without limits, pushing boundaries to deliver exceptional and professional work for all our clients.
            </p>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="bg-gray-900 py-16 px-6 sm:px-10">
        <div class="container mx-auto">
            <h2 class="text-5xl font-bold text-center mb-12">Our Pricing</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Pricing Card 1 -->
                <div class="card-gradient rounded-3xl p-8 shadow-2xl border border-gray-700">
                    <h3 class="text-3xl font-semibold mb-4 text-center bg-clip-text text-transparent bg-gradient-to-r from-teal-400 to-blue-500">Standard Photoshoot</h3>
                    <p class="text-sm text-gray-400 text-center mb-6">Perfect for portraits, social media content, and events.</p>
                    <div class="text-center mb-6">
                        <span class="text-6xl font-bold text-white">₦50,000</span>
                    </div>
                    <ul class="text-base text-gray-300 space-y-3">
                        <li>&#x2714; 1-Hour Session</li>
                        <li>&#x2714; 20 High-Resolution Edited Photos</li>
                        <li>&#x2714; 2 Outfit Changes</li>
                        <li>&#x2714; Online Private Gallery</li>
                    </ul>
                </div>
                <!-- Pricing Card 2 -->
                <div class="card-gradient rounded-3xl p-8 shadow-2xl border border-gray-700">
                    <h3 class="text-3xl font-semibold mb-4 text-center bg-clip-text text-transparent bg-gradient-to-r from-purple-400 to-indigo-500">Premium Photoshoot</h3>
                    <p class="text-sm text-gray-400 text-center mb-6">Ideal for commercial, brand, and professional portfolios.</p>
                    <div class="text-center mb-6">
                        <span class="text-6xl font-bold text-white">₦150,000</span>
                    </div>
                    <ul class="text-base text-gray-300 space-y-3">
                        <li>&#x2714; 3-Hour Session</li>
                        <li>&#x2714; 50 High-Resolution Edited Photos</li>
                        <li>&#x2714; 4 Outfit Changes</li>
                        <li>&#x2714; All Raw Files Included</li>
                    </ul>
                </div>
                <!-- Pricing Card 3 -->
                <div class="card-gradient rounded-3xl p-8 shadow-2xl border border-gray-700">
                    <h3 class="text-3xl font-semibold mb-4 text-center bg-clip-text text-transparent bg-gradient-to-r from-yellow-400 to-orange-500">Cinematic Package</h3>
                    <p class="text-sm text-gray-400 text-center mb-6">For breathtaking cinematic and flaming videos.</p>
                    <div class="text-center mb-6">
                        <span class="text-6xl font-bold text-white">₦350,000</span>
                    </div>
                    <ul class="text-base text-gray-300 space-y-3">
                        <li>&#x2714; Full Day Shoot</li>
                        <li>&#x2714; 3-5 Minute Edited Cinematic Video</li>
                        <li>&#x2714; Professional Color Grading</li>
                        <li>&#x2714; Original Soundtrack</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact & Social Media Section -->
    <section id="contact" class="container mx-auto py-16 px-6 sm:px-10">
        <h2 class="text-5xl font-bold text-center mb-12">Contact Us & Our Channels</h2>
        <div class="card-gradient rounded-3xl p-8 sm:p-12 shadow-2xl border border-gray-700 flex flex-col md:flex-row items-center justify-between space-y-8 md:space-y-0 md:space-x-8">
            <div class="w-full md:w-1/2">
                <h3 class="text-3xl font-semibold mb-6 bg-clip-text text-transparent bg-gradient-to-r from-teal-400 to-indigo-500">Get in Touch</h3>
                <p class="text-lg mb-6 text-gray-300">For bookings, inquiries, or custom packages, feel free to reach out to us.</p>
                <div class="space-y-6">
                    <div class="flex items-center space-x-4">
                        <img src="https://api.iconify.design/logos:whatsapp-icon.svg?color=%23ffffff" alt="WhatsApp" class="w-8 h-8">
                        <a href="https://wa.me/2348000000000" class="text-gray-200 text-lg hover:text-indigo-400 transition-colors duration-300">+234 800 000 0000</a>
                    </div>
                    <div class="flex items-center space-x-4">
                        <img src="https://api.iconify.design/logos:instagram-icon.svg?color=%23ffffff" alt="Instagram" class="w-8 h-8">
                        <a href="https://instagram.com/7ravens_studio" class="text-gray-200 text-lg hover:text-indigo-400 transition-colors duration-300">@7ravens_studio</a>
                    </div>
                    <div class="flex items-center space-x-4">
                        <img src="https://api.iconify.design/logos:x-icon.svg?color=%23ffffff" alt="Twitter(X)" class="w-8 h-8">
                        <a href="https://twitter.com/7ravens_studio" class="text-gray-200 text-lg hover:text-indigo-400 transition-colors duration-300">@7ravens_studio</a>
                    </div>
                    <div class="flex items-center space-x-4">
                        <img src="https://api.iconify.design/ic:outline-phone.svg?color=%23ffffff" alt="Phone" class="w-8 h-8">
                        <a href="tel:+2348000000001" class="text-gray-200 text-lg hover:text-indigo-400 transition-colors duration-300">+234 800 000 0001</a>
                    </div>
                </div>
            </div>
            <div class="w-full md:w-1/2">
                <h3 class="text-3xl font-semibold mb-6 bg-clip-text text-transparent bg-gradient-to-r from-purple-400 to-fuchsia-500">Our Address</h3>
                <p class="text-lg text-gray-300 leading-relaxed mb-4">
                    123 Creative Street,<br>
                    Lagos, Nigeria.
                </p>
                <div>
                    <iframe 
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3964.555208460677!2d3.3768158147703816!3d6.586618495240369!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x103b925b3a4a162d%3A0xc3f16104e7c7a38b!2sLagos%2C%20Nigeria!5e0!3m2!1sen!2sus!4v1678229864230!5m2!1sen!2sus"
                        class="w-full h-64 rounded-xl shadow-lg border border-gray-700"
                        allowfullscreen=""
                        loading="lazy"
                        referrerpolicy="no-referrer-when-downgrade">
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-950 text-center text-gray-500 py-8 text-sm">
        &copy; 2024 7ravens Studio. All Rights Reserved.
    </footer>

</body>
</html>
