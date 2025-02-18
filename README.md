<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">

    <!-- Navbar -->
    <nav class="bg-white shadow-md p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">My Portfolio</h1>
            <ul class="flex space-x-4">
                <li><a href="#" class="hover:text-blue-500">Home</a></li>
                <li><a href="#about" class="hover:text-blue-500">About</a></li>
                <li><a href="#projects" class="hover:text-blue-500">Projects</a></li>
                <li><a href="#contact" class="hover:text-blue-500">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="h-screen flex items-center justify-center text-center bg-blue-500 text-white">
        <div>
            <h2 class="text-4xl font-bold">Hello, I'm Sneha ladani</h2>
            <p class="mt-2 text-lg">A Web Developer</p>
            <a href="#projects" class="mt-4 inline-block bg-white text-blue-500 px-4 py-2 rounded-lg shadow-md">View Projects</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-16 container mx-auto text-center">
        <h2 class="text-3xl font-bold">About Me</h2>
        <p class="mt-4 text-lg max-w-2xl mx-auto">I am a passionate web developer skilled in HTML, CSS, Tailwind CSS, and JavaScript.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 bg-gray-200">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold">Projects</h2>
            <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-white p-4 shadow-md rounded-lg">
                    <h3 class="text-xl font-semibold">Project 1</h3>
                    <p class="mt-2">Description of your project.</p>
                </div>
                <div class="bg-white p-4 shadow-md rounded-lg">
                    <h3 class="text-xl font-semibold">Project 2</h3>
                    <p class="mt-2">Description of your project.</p>
                </div>
                <div class="bg-white p-4 shadow-md rounded-lg">
                    <h3 class="text-xl font-semibold">Project 3</h3>
                    <p class="mt-2">Description of your project.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 container mx-auto text-center">
        <h2 class="text-3xl font-bold">Contact Me</h2>
        <p class="mt-4">snehaladani5@gmail.com</p>
        <p>GitHub: <a href="https://github.com/yourusername" class="text-blue-500">github.com/snehaladani</a></p>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center p-4">
        <p>&copy; 2025 sneha. All Rights Reserved.</p>
    </footer>

</body>
</html>
