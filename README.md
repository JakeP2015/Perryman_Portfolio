# Perryman_Portfolio
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GIS Portfolio Template</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Font - Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Navigation Bar -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold text-indigo-600">John Doe</a>
            <div class="space-x-4 hidden md:flex">
                <a href="#about" class="text-gray-600 hover:text-indigo-600 font-medium">About</a>
                <a href="#projects" class="text-gray-600 hover:text-indigo-600 font-medium">Projects</a>
                <a href="#skills" class="text-gray-600 hover:text-indigo-600 font-medium">Skills</a>
                <a href="#contact" class="text-gray-600 hover:text-indigo-600 font-medium">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600 hover:text-indigo-600 focus:outline-none">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white px-4 py-2">
            <a href="#about" class="block py-2 text-gray-600 hover:text-indigo-600 font-medium border-b border-gray-100">About</a>
            <a href="#projects" class="block py-2 text-gray-600 hover:text-indigo-600 font-medium border-b border-gray-100">Projects</a>
            <a href="#skills" class="block py-2 text-gray-600 hover:text-indigo-600 font-medium border-b border-gray-100">Skills</a>
            <a href="#contact" class="block py-2 text-gray-600 hover:text-indigo-600 font-medium">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-indigo-600 text-white py-20 md:py-32">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 animate-fade-in-down">John Doe</h1>
            <p class="text-lg md:text-xl mb-8 animate-fade-in-up">
                GIS Analyst | Geospatial Developer
            </p>
            <p class="max-w-3xl mx-auto text-gray-200">
                A passionate GIS professional with expertise in spatial analysis, remote sensing, and web mapping. I leverage my skills to solve real-world problems and create insightful geospatial solutions.
            </p>
            <a href="#projects" class="mt-8 inline-block bg-white text-indigo-600 font-bold py-3 px-8 rounded-full shadow-lg transition-transform transform hover:scale-105">
                View My Projects
            </a>
        </div>
    </header>

    <!-- About Me Section -->
    <section id="about" class="py-16 md:py-24">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">About Me</h2>
            <div class="flex flex-col md:flex-row items-center gap-8 md:gap-16">
                <!-- Profile Image -->
                <div class="w-full md:w-1/3 flex justify-center">
                    <img src="https://placehold.co/300x300/a5b4fc/ffffff?text=Profile" alt="Profile Picture" class="rounded-full shadow-lg border-4 border-indigo-200">
                </div>
                <!-- About Text -->
                <div class="w-full md:w-2/3">
                    <p class="text-lg mb-4 leading-relaxed">
                        Hello! My name is John Doe, and I am a dedicated GIS professional with a strong background in environmental science and data analysis. I have experience working with a wide range of geospatial technologies to collect, process, and visualize spatial data.
                    </p>
                    <p class="text-lg leading-relaxed">
                        My passion lies in using maps and data to tell compelling stories and inform decision-making. Whether it's building interactive web maps, performing complex spatial queries, or developing automated workflows, I am always seeking new challenges to expand my skills and contribute to impactful projects.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="bg-gray-100 py-16 md:py-24">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project Card 1 -->
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow duration-300">
                    <img src="https://placehold.co/600x400/94a3b8/ffffff?text=Project+1" alt="Project 1" class="rounded-md mb-4 w-full h-48 object-cover">
                    <h3 class="text-xl font-semibold mb-2">Urban Canopy Analysis</h3>
                    <p class="text-gray-600 mb-4">
                        A project focused on analyzing urban tree cover and its impact on city heat islands using satellite imagery and spatial statistics.
                    </p>
                    <div class="flex flex-wrap gap-2 mb-4">
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">ArcGIS Pro</span>
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">Python</span>
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">Remote Sensing</span>
                    </div>
                    <a href="#" class="inline-block bg-indigo-600 text-white font-medium py-2 px-4 rounded-md hover:bg-indigo-700 transition-colors duration-300">
                        View Project <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>

                <!-- Project Card 2 -->
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow duration-300">
                    <img src="https://placehold.co/600x400/94a3b8/ffffff?text=Project+2" alt="Project 2" class="rounded-md mb-4 w-full h-48 object-cover">
                    <h3 class="text-xl font-semibold mb-2">Interactive Web Map</h3>
                    <p class="text-gray-600 mb-4">
                        Developed a web application visualizing public transit data, allowing users to filter routes and view real-time vehicle locations.
                    </p>
                    <div class="flex flex-wrap gap-2 mb-4">
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">Leaflet.js</span>
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">JavaScript</span>
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">PostgreSQL</span>
                    </div>
                    <a href="#" class="inline-block bg-indigo-600 text-white font-medium py-2 px-4 rounded-md hover:bg-indigo-700 transition-colors duration-300">
                        View Project <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>

                <!-- Project Card 3 -->
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow duration-300">
                    <img src="https://placehold.co/600x400/94a3b8/ffffff?text=Project+3" alt="Project 3" class="rounded-md mb-4 w-full h-48 object-cover">
                    <h3 class="text-xl font-semibold mb-2">Automated Data Pipeline</h3>
                    <p class="text-gray-600 mb-4">
                        Created a Python script to automate the ingestion and cleaning of daily sensor data into a geospatial database for analysis.
                    </p>
                    <div class="flex flex-wrap gap-2 mb-4">
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">Python</span>
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">FME</span>
                        <span class="bg-gray-200 text-gray-700 text-xs font-medium px-2 py-1 rounded-full">SQL</span>
                    </div>
                    <a href="#" class="inline-block bg-indigo-600 text-white font-medium py-2 px-4 rounded-md hover:bg-indigo-700 transition-colors duration-300">
                        View Project <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-16 md:py-24">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Skills</h2>
            <div class="flex flex-wrap justify-center gap-6 md:gap-8">
                <!-- Skill Category 1 -->
                <div class="bg-white p-6 rounded-lg shadow-md w-full sm:w-1/2 md:w-1/3 lg:w-1/4">
                    <h3 class="text-xl font-semibold mb-4 text-indigo-600">GIS Software</h3>
                    <ul class="space-y-2">
                        <li><i class="fas fa-map-marker-alt text-indigo-400 mr-2"></i> ArcGIS Pro / Desktop</li>
                        <li><i class="fas fa-map-marker-alt text-indigo-400 mr-2"></i> QGIS</li>
                        <li><i class="fas fa-map-marker-alt text-indigo-400 mr-2"></i> ArcGIS Online / Portal</li>
                        <li><i class="fas fa-map-marker-alt text-indigo-400 mr-2"></i> FME</li>
                    </ul>
                </div>
                <!-- Skill Category 2 -->
                <div class="bg-white p-6 rounded-lg shadow-md w-full sm:w-1/2 md:w-1/3 lg:w-1/4">
                    <h3 class="text-xl font-semibold mb-4 text-indigo-600">Programming</h3>
                    <ul class="space-y-2">
                        <li><i class="fas fa-code text-indigo-400 mr-2"></i> Python (ArcPy, Pandas)</li>
                        <li><i class="fas fa-code text-indigo-400 mr-2"></i> JavaScript (Leaflet, Esri JS API)</li>
                        <li><i class="fas fa-code text-indigo-400 mr-2"></i> SQL</li>
                        <li><i class="fas fa-code text-indigo-400 mr-2"></i> HTML / CSS</li>
                    </ul>
                </div>
                <!-- Skill Category 3 -->
                <div class="bg-white p-6 rounded-lg shadow-md w-full sm:w-1/2 md:w-1/3 lg:w-1/4">
                    <h3 class="text-xl font-semibold mb-4 text-indigo-600">Databases & Tools</h3>
                    <ul class="space-y-2">
                        <li><i class="fas fa-database text-indigo-400 mr-2"></i> PostgreSQL / PostGIS</li>
                        <li><i class="fas fa-database text-indigo-400 mr-2"></i> Microsoft SQL Server</li>
                        <li><i class="fas fa-database text-indigo-400 mr-2"></i> Docker</li>
                        <li><i class="fas fa-database text-indigo-400 mr-2"></i> Git</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gray-100 py-16 md:py-24">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-8">Get in Touch</h2>
            <p class="max-w-2xl mx-auto text-lg text-gray-600 mb-8">
                I'm always open to new opportunities and collaborations. Feel free to reach out to me via email or connect with me on my professional networks.
            </p>
            <div class="flex justify-center space-x-6 mb-8">
                <a href="mailto:johndoe@example.com" class="text-gray-600 hover:text-indigo-600 transition-colors duration-300">
                    <i class="fas fa-envelope text-3xl"></i>
                </a>
                <a href="#" class="text-gray-600 hover:text-indigo-600 transition-colors duration-300">
                    <i class="fab fa-linkedin text-3xl"></i>
                </a>
                <a href="#" class="text-gray-600 hover:text-indigo-600 transition-colors duration-300">
                    <i class="fab fa-github text-3xl"></i>
                </a>
            </div>
            <!-- Simple contact form -->
            <div class="max-w-xl mx-auto bg-white p-8 rounded-lg shadow-lg">
                <form action="#" method="POST">
                    <div class="mb-4">
                        <input type="text" id="name" name="name" placeholder="Your Name" class="w-full px-4 py-2 rounded-md border border-gray-300 focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    <div class="mb-4">
                        <input type="email" id="email" name="email" placeholder="Your Email" class="w-full px-4 py-2 rounded-md border border-gray-300 focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    <div class="mb-4">
                        <textarea id="message" name="message" rows="4" placeholder="Your Message" class="w-full px-4 py-2 rounded-md border border-gray-300 focus:outline-none focus:ring-2 focus:ring-indigo-500"></textarea>
                    </div>
                    <button type="submit" class="w-full bg-indigo-600 text-white font-medium py-3 px-6 rounded-md hover:bg-indigo-700 transition-colors duration-300">
                        Send Message
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300 py-6">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2024 John Doe. All rights reserved.</p>
        </div>
    </footer>

    <!-- JavaScript for smooth scrolling and mobile menu toggle -->
    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);

                if (targetElement) {
                    targetElement.scrollIntoView({
                        behavior: 'smooth'
                    });
                    // Close mobile menu after clicking a link
                    document.getElementById('mobile-menu').classList.add('hidden');
                }
            });
        });

        // Toggle mobile menu
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            document.getElementById('mobile-menu').classList.toggle('hidden');
        });
    </script>
</body>
