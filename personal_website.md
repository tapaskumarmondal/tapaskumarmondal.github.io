<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal Website of Tapas Kumar Mondal">
    <title>Tapas Kumar Mondal | Personal Website</title>
    <!-- Tailwind CSS CDN for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-900 text-gray-100 font-sans antialiased selection:bg-indigo-500 selection:text-white">

    <!-- Navigation Bar -->
    <nav class="fixed top-0 w-full bg-gray-900/80 backdrop-blur-md z-50 border-b border-gray-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <a href="#" class="text-xl font-bold tracking-wider text-indigo-400 hover:text-indigo-300 transition">
                    Tapas Kumar Mondal
                </a>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-6">
                        <a href="#about" class="text-gray-300 hover:text-indigo-400 transition">About</a>
                        <a href="#skills" class="text-gray-300 hover:text-indigo-400 transition">Skills</a>
                        <a href="#projects" class="text-gray-300 hover:text-indigo-400 transition">Projects</a>
                        <a href="#contact" class="text-gray-300 hover:text-indigo-400 transition">Contact</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center pt-16 px-4">
        <div class="text-center max-w-3xl mx-auto">
            <div class="mb-6 inline-block p-1 rounded-full bg-gradient-to-r from-indigo-500 to-purple-500">
                <div class="w-32 h-32 rounded-full bg-gray-800 flex items-center justify-center border-2 border-gray-900 text-4xl text-indigo-400">
                    <i class="fa-solid font-bold">TM</i>
                </div>
            </div>
            <h1 class="text-4xl sm:text-6xl font-extrabold text-white tracking-tight mb-4">
                Hi, I'm <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-purple-400">Tapas Kumar Mondal</span>
            </h1>
            <p class="text-lg sm:text-xl text-gray-400 mb-8 max-w-2xl mx-auto">
                Welcome to my personal space on the web. I build dynamic web applications, explore modern technologies, and craft creative digital solutions.
            </p>
            <div class="flex justify-center gap-4 flex-wrap">
                <a href="#projects" class="px-6 py-3 bg-indigo-600 hover:bg-indigo-500 text-white font-medium rounded-lg shadow-lg hover:shadow-indigo-500/25 transition">
                    View My Work
                </a>
                <a href="#contact" class="px-6 py-3 bg-gray-800 hover:bg-gray-700 text-gray-200 font-medium rounded-lg border border-gray-700 transition">
                    Get In Touch
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-800/50">
        <div class="max-w-4xl mx-auto px-4 sm:px-6">
            <h2 class="text-3xl font-bold text-center text-white mb-8">About Me</h2>
            <div class="bg-gray-800 p-8 rounded-2xl border border-gray-700 shadow-xl">
                <p class="text-gray-300 leading-relaxed text-lg mb-4">
                    Hello! I'm Tapas Kumar Mondal. I am passionate about technology, coding, and problem-solving. I love learning new tools, building web applications, and sharing knowledge with others.
                </p>
                <p class="text-gray-300 leading-relaxed text-lg">
                    This website serves as my online portfolio to showcase my latest projects, my technical skills, and how to reach me.
                </p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20">
        <div class="max-w-4xl mx-auto px-4 sm:px-6">
            <h2 class="text-3xl font-bold text-center text-white mb-10">Skills & Technologies</h2>
            <div class="flex flex-wrap justify-center gap-3">
                <span class="px-4 py-2 bg-gray-800 text-indigo-400 border border-gray-700 rounded-full font-medium">HTML5</span>
                <span class="px-4 py-2 bg-gray-800 text-indigo-400 border border-gray-700 rounded-full font-medium">CSS3 / Tailwind</span>
                <span class="px-4 py-2 bg-gray-800 text-indigo-400 border border-gray-700 rounded-full font-medium">JavaScript</span>
                <span class="px-4 py-2 bg-gray-800 text-indigo-400 border border-gray-700 rounded-full font-medium">Git & GitHub</span>
                <span class="px-4 py-2 bg-gray-800 text-indigo-400 border border-gray-700 rounded-full font-medium">Web Development</span>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-gray-800/50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6">
            <h2 class="text-3xl font-bold text-center text-white mb-12">Featured Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Project Card 1 -->
                <div class="bg-gray-800 rounded-xl p-6 border border-gray-700 hover:border-indigo-500/50 transition">
                    <h3 class="text-xl font-bold text-white mb-2">Project One</h3>
                    <p class="text-gray-400 mb-4">A brief description of your project goes here. Explain what it does and what technology stack you used.</p>
                    <div class="flex gap-2 text-sm text-indigo-400">
                        <span>#HTML</span> <span>#CSS</span> <span>#JavaScript</span>
                    </div>
                </div>
                <!-- Project Card 2 -->
                <div class="bg-gray-800 rounded-xl p-6 border border-gray-700 hover:border-indigo-500/50 transition">
                    <h3 class="text-xl font-bold text-white mb-2">Project Two</h3>
                    <p class="text-gray-400 mb-4">Another highlight project description. You can link your live apps or GitHub repositories here.</p>
                    <div class="flex gap-2 text-sm text-indigo-400">
                        <span>#Tailwind</span> <span>#GitHub</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 text-center">
            <h2 class="text-3xl font-bold text-white mb-4">Get In Touch</h2>
            <p class="text-gray-400 mb-8 max-w-lg mx-auto">
                Feel free to connect with me or reach out for collaboration!
            </p>
            <div class="flex justify-center gap-6">
                <a href="https://github.com/tapaskumarmondal" target="_blank" rel="noopener noreferrer" class="p-4 bg-gray-800 hover:bg-gray-700 text-gray-200 rounded-full border border-gray-700 transition">
                    <i class="fa-brands fa-github text-xl"></i>
                </a>
                <a href="mailto:your-email@example.com" class="p-4 bg-gray-800 hover:bg-gray-700 text-gray-200 rounded-full border border-gray-700 transition">
                    <i class="fa-solid fa-envelope text-xl"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-6 border-t border-gray-800 text-center text-gray-500 text-sm">
        <p>&copy; <span id="year"></span> Tapas Kumar Mondal. Hosted on GitHub Pages.</p>
    </footer>

    <script>
        // Set current year dynamically
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>