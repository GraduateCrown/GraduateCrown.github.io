---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://unpkg.com/@tailwindcss/browser@4"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" rel="stylesheet">
    <title>Simple HTML Page</title>
</head>

<body class="bg-gray-100 font-sans">
    <!-- 导航栏 -->
    <nav class="bg-white shadow-md">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="text-xl font-bold text-gray-800">My Website</a>
            <div class="md:hidden">
                <button id="menu-toggle" class="text-gray-600 focus:outline-none">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
            <div class="hidden md:block">
                <ul class="flex space-x-4">
                    <li><a href="#" class="text-gray-600 hover:text-gray-800">Home</a></li>
                    <li><a href="#" class="text-gray-600 hover:text-gray-800">About</a></li>
                    <li><a href="#" class="text-gray-600 hover:text-gray-800">Contact</a></li>
                </ul>
            </div>
        </div>
        <div id="menu-collapse" class="hidden md:hidden bg-white px-4 py-2">
            <ul class="space-y-2">
                <li><a href="#" class="text-gray-600 hover:text-gray-800">Home</a></li>
                <li><a href="#" class="text-gray-600 hover:text-gray-800">About</a></li>
                <li><a href="#" class="text-gray-600 hover:text-gray-800">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- 内容区域 -->
    <div class="container mx-auto px-4 py-8">
        <h1 class="text-3xl font-bold text-gray-800 mb-4">Welcome to My Website</h1>
        <p class="text-gray-600 mb-8">This is a simple HTML page using Tailwind CSS and Font Awesome. It has a responsive
            design and some basic interactivity.</p>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
            <div class="bg-white shadow-md rounded-md p-6">
                <i class="fas fa-lightbulb text-yellow-500 text-3xl mb-4"></i>
                <h2 class="text-xl font-bold text-gray-800 mb-2">Feature 1</h2>
                <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac velit eget
                    libero aliquet feugiat.</p>
            </div>
            <div class="bg-white shadow-md rounded-md p-6">
                <i class="fas fa-cog text-blue-500 text-3xl mb-4"></i>
                <h2 class="text-xl font-bold text-gray-800 mb-2">Feature 2</h2>
                <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac velit eget
                    libero aliquet feugiat.</p>
            </div>
            <div class="bg-white shadow-md rounded-md p-6">
                <i class="fas fa-chart-bar text-green-500 text-3xl mb-4"></i>
                <h2 class="text-xl font-bold text-gray-800 mb-2">Feature 3</h2>
                <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac velit eget
                    libero aliquet feugiat.</p>
            </div>
            <div class="bg-white shadow-md rounded-md p-6">
                <i class="fas fa-star text-purple-500 text-3xl mb-4"></i>
                <h2 class="text-xl font-bold text-gray-800 mb-2">Feature 4</h2>
                <p class="text-gray-600">New feature added to the page. It also has some description here.</p>
            </div>
        </div>
    </div>

    <!-- 页脚 -->
    <footer class="bg-white shadow-md">
        <div class="container mx-auto px-4 py-4 text-center text-gray-600">
            &copy; 2025 My Website. All rights reserved.
        </div>
    </footer>

    <script>
        const menuToggle = document.getElementById('menu-toggle');
        const menuCollapse = document.getElementById('menu-collapse');

        menuToggle.addEventListener('click', () => {
            menuCollapse.classList.toggle('hidden');
        });
    </script>
</body>

</html>
    
