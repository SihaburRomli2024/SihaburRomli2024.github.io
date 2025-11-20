<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sihab's Digital Showcase</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="components/navbar.js"></script>
    <script src="components/footer.js"></script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">
    <custom-navbar></custom-navbar>

    <main class="container mx-auto px-4 py-8">
        <!-- Hero Section -->
        <section class="flex flex-col md:flex-row items-center justify-between gap-8 mb-16">
            <div class="md:w-1/2">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Sihabur Romli</h1>
                <p class="text-xl text-gray-600 mb-6">Full Stack Developer & Digital Creator</p>
                <div class="flex flex-wrap gap-4 mb-6">
                    <a href="mailto:aabsihaburromlli@gmail.com" class="flex items-center gap-2 text-blue-600 hover:text-blue-800">
                        <i data-feather="mail"></i> aabsihaburromlli@gmail.com
                    </a>
                    <a href="tel:085719527822" class="flex items-center gap-2 text-blue-600 hover:text-blue-800">
                        <i data-feather="phone"></i> 085719527822
                    </a>
                </div>
                <div class="flex gap-4">
                    <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-2 rounded-lg transition">Download CV</a>
                    <a href="#contact" class="border border-blue-600 text-blue-600 hover:bg-blue-50 px-6 py-2 rounded-lg transition">Contact Me</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden border-4 border-white shadow-xl">
                    <img src="http://static.photos/technology/640x360/42" alt="Sihabur Romli" class="w-full h-full object-cover">
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="mb-16">
            <h2 class="text-3xl font-bold mb-6 border-b pb-2">About Me</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-xl font-semibold mb-4">Professional Profile</h3>
                    <p class="text-gray-700 mb-4">Passionate full stack developer with expertise in web development, data analysis, and system design. Committed to creating efficient, scalable solutions that solve real-world problems.</p>
                    <p class="text-gray-700">With a strong foundation in computer science and hands-on experience in various technologies, I bridge the gap between technical requirements and business objectives.</p>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-4">Education</h3>
                    <div class="space-y-4">
                        <div class="border-l-4 border-blue-500 pl-4">
                            <h4 class="font-medium">Bachelor of Computer Science</h4>
                            <p class="text-gray-600">University of Technology, 2015-2019</p>
                        </div>
                        <div class="border-l-4 border-blue-500 pl-4">
                            <h4 class="font-medium">Data Science Certification</h4>
                            <p class="text-gray-600">Online Academy, 2020</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="mb-16">
            <h2 class="text-3xl font-bold mb-6 border-b pb-2">Skills & Expertise</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-xl font-semibold mb-4">Technical Skills</h3>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>PHP & Laravel</span>
                                <span>90%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 90%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>Python & Data Science</span>
                                <span>85%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 85%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>JavaScript & React</span>
                                <span>80%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 80%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>GIS & Spatial Analysis</span>
                                <span>75%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5">
                                <div class="bg-blue-600 h-2.5 rounded-full" style="width: 75%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-4">Professional Skills</h3>
                    <div class="space-y-4">
                        <div class="flex items-center gap-4">
                            <div class="p-3 bg-blue-100 rounded-full">
                                <i data-feather="users" class="text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Team Collaboration</h4>
                                <p class="text-gray-600">Experienced in agile teams and cross-functional projects</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-4">
                            <div class="p-3 bg-blue-100 rounded-full">
                                <i data-feather="message-square" class="text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Communication</h4>
                                <p class="text-gray-600">Clear technical and non-technical communication</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-4">
                            <div class="p-3 bg-blue-100 rounded-full">
                                <i data-feather="clock" class="text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Time Management</h4>
                                <p class="text-gray-600">Effective prioritization and deadline management</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-4">
                            <div class="p-3 bg-blue-100 rounded-full">
                                <i data-feather="award" class="text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Leadership</h4>
                                <p class="text-gray-600">Project lead experience with small to medium teams</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="mb-16">
            <h2 class="text-3xl font-bold mb-6 border-b pb-2">Featured Projects</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Project 1 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition">
                    <div class="h-48 overflow-hidden">
                        <img src="http://static.photos/technology/640x360/1" alt="Project 1" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">E-Commerce Platform</h3>
                        <p class="text-gray-600 mb-3">2022 | PHP, Laravel, MySQL, Vue.js</p>
                        <p class="text-gray-700 mb-4">Developed a full-featured e-commerce platform with payment integration and inventory management.</p>
                        <div class="flex justify-between items-center">
                            <a href="#" class="text-blue-600 hover:underline">View Details</a>
                            <a href="#" class="text-gray-500 hover:text-gray-700">
                                <i data-feather="github"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden hover
</body>
</html>
