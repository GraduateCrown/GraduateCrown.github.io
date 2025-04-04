---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Academic Website</title>
    
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <style>
        .sidebar-bg {
            background-color: theme('colors.blue.600');
        }
        .content-bg {
            background-color: theme('colors.gray.100');
        }
    </style>
</head>
<body class="min-h-screen flex flex-col">
    <aside class="sidebar-bg p-6 lg:w-1/4">
        <h1 class="text-3xl font-bold text-white mb-4">Your Name</h1>
        <p class="text-gray-300 mb-6">
            Short biography placeholder: Research interests include ...
        </p>
        
        <nav>
            <a href="#about" class="block text-white hover:opacity-75 py-2">About</a>
            <a href="#publications" class="block text-white hover:opacity-75 py-2">Publications</a>
            <a href="#contact" class="block text-white hover:opacity-75 py-2">Contact</a>
        </nav>
    </aside>

    <main class="flex-1 content-bg p-8 lg:p-12">
        <h1 class="text-4xl font-bold mb-6">Welcome to My Academic Website</h1>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="bg-white rounded-lg p-6 shadow-md">
                <h3 class="text-xl font-semibold mb-3">Research Interests</h3>
                <p>Machine Learning · Computer Vision · Natural Language Processing</p>
            </div>
            
            <div class="bg-white rounded-lg p-6 shadow-md">
                <h3 class="text-xl font-semibold mb-3">Current Projects</h3>
                <ul class="list-disc pl-6">
                    <li>Project 1: Advanced Image Recognition System</li>
                    <li>Project 2: Multilingual Translation Model</li>
                </ul>
            </div>
        </div>

        <div class="mt-12 bg-white rounded-lg p-6 shadow-md">
            <h3 class="text-xl font-semibold mb-4">Latest News</h3>
            <p class="text-gray-700">
                Paper accepted to <strong>NeurIPS 2024</strong> - Title: "Innovative Approaches in Deep Learning"
            </p>
        </div>
    </main>

    <footer class="sidebar-bg text-white text-center py-4 mt-auto">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
        <div class="mt-2">
            <a href="#social" class="mx-2 text-gray-300 hover:text-white">
                <i class="fab fa-github"></i>
            </a>
            <a href="#social" class="mx-2 text-gray-300 hover:text-white">
                <i class="fab fa-linkedin"></i>
            </a>
        </div>
    </footer>
</body>
</html>
    
