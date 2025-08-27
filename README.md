<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name's GitHub Profile</title>
    <!-- Use Inter font from Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .animate-pulse-slow {
            animation: pulse-slow 3s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        @keyframes pulse-slow {
            0%, 100% {
                opacity: 0.8;
            }
            50% {
                opacity: 0.4;
            }
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">
    <div class="container mx-auto px-4 py-16 min-h-screen flex flex-col items-center justify-center">

        <!-- Profile Section -->
        <div class="bg-gray-800 p-8 md:p-12 rounded-2xl shadow-xl max-w-2xl w-full text-center">
            
            <!-- Profile Image -->
            <img src="https://placehold.co/128x128/334155/E2E8F0?text=JP" alt="Profile Picture" class="w-32 h-32 rounded-full mx-auto mb-6 border-4 border-teal-500 animate-pulse-slow">
            
            <!-- Bio & Social Links -->
            <h1 class="text-3xl md:text-4xl font-bold text-white mb-2">John P. Smith</h1>
            <p class="text-lg md:text-xl font-medium text-gray-400 mb-6">Software Engineer | Full Stack Developer | Cybersecurity Enthusiast</p>
            
            <div class="flex justify-center space-x-4 mb-8">
                <!-- GitHub Icon -->
                <a href="https://github.com/yourusername" target="_blank" rel="noopener noreferrer" class="text-white hover:text-teal-400 transition-colors duration-300">
                    <svg class="w-8 h-8 md:w-10 md:h-10" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path fill-rule="evenodd" d="M12 0C5.373 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.6.11.82-.26.82-.577v-2.007c-3.338.72-4.04-1.61-4.04-1.61-.546-1.386-1.332-1.758-1.332-1.758-1.09-.748.082-.733.082-.733 1.206.086 1.838 1.238 1.838 1.238 1.07 1.83 2.809 1.3 3.49.997.108-.775.42-1.3.766-1.59-2.66-.29-5.46-1.33-5.46-5.932 0-1.309.467-2.383 1.238-3.22-.124-.29-.536-1.52.117-3.175 0 0 1.01-.32 3.3.992 2.3-.642 5.09-1.286 7.4-1.286 2.31 0 5.1.644 7.4 1.286 2.29-1.312 3.3-.992 3.3-.992.653 1.655.24 2.885.116 3.175.772.837 1.238 1.91 1.238 3.22 0 4.61-2.8 5.64-5.46 5.932.43.37.825 1.066.825 2.15v2.793c0 .318.22.688.825.577C20.562 21.82 24 17.302 24 12c0-6.627-5.373-12-12-12z" clip-rule="evenodd" />
                    </svg>
                </a>
                <!-- LinkedIn Icon -->
                <a href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener noreferrer" class="text-white hover:text-teal-400 transition-colors duration-300">
                    <svg class="w-8 h-8 md:w-10 md:h-10" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5s-2.48-1.119-2.48-2.5c0-1.382 1.11-2.5 2.48-2.5s2.48 1.118 2.48 2.5zm.02 4.5h-5v16h5v-16zm7.982 0h-4.998v16h5v-8.28c0-3.322 2.68-4.722 4.41-2.969 1.73 1.753-1.062 4.708-3.412 5.362v5.887h5v-8.156c0-3.322-2.68-4.722-4.41-2.969-1.73 1.753-1.062 4.708-3.412 5.362v5.887h5v-8.156z"/>
                    </svg>
                </a>
            </div>
            
            <!-- Short Bio -->
            <p class="text-gray-300 text-base md:text-lg leading-relaxed">
                Welcome to my digital space! I'm a passionate software developer with a focus on building secure and scalable applications. My work spans from full-stack web development to delving into the world of cybersecurity. On this page, you'll find a selection of my projects, experiments, and contributions to the open-source community.
            </p>
        </div>

        <!-- Projects Section -->
        <div class="mt-16 w-full max-w-2xl">
            <h2 class="text-2xl md:text-3xl font-bold text-white mb-6 text-center">Featured Projects</h2>
            <div class="space-y-6">
                <!-- Project Card 1 -->
                <div class="bg-gray-800 p-6 rounded-2xl shadow-md transition-transform duration-300 hover:scale-105">
                    <h3 class="text-xl font-semibold text-teal-400 mb-2">Project Gemini - AI-Powered Chatbot</h3>
                    <p class="text-gray-400 mb-4">A conversational AI built using the Gemini API, featuring real-time chat, sentiment analysis, and a clean, user-friendly interface. This project demonstrates skills in API integration, front-end development, and natural language processing.</p>
                    <a href="#" class="text-white font-medium hover:text-teal-400 transition-colors duration-300 inline-flex items-center">
                        View on GitHub
                        <svg class="ml-2 w-4 h-4" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path d="M12 0C5.373 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.6.11.82-.26.82-.577v-2.007c-3.338.72-4.04-1.61-4.04-1.61-.546-1.386-1.332-1.758-1.332-1.758-1.09-.748.082-.733.082-.733 1.206.086 1.838 1.238 1.838 1.238 1.07 1.83 2.809 1.3 3.49.997.108-.775.42-1.3.766-1.59-2.66-.29-5.46-1.33-5.46-5.932 0-1.309.467-2.383 1.238-3.22-.124-.29-.536-1.52.117-3.175 0 0 1.01-.32 3.3.992 2.3-.642 5.09-1.286 7.4-1.286 2.31 0 5.1.644 7.4 1.286 2.29-1.312 3.3-.992 3.3-.992.653 1.655.24 2.885.116 3.175.772.837 1.238 1.91 1.238 3.22 0 4.61-2.8 5.64-5.46 5.932.43.37.825 1.066.825 2.15v2.793c0 .318.22.688.825.577C20.562 21.82 24 17.302 24 12c0-6.627-5.373-12-12-12z" />
                        </svg>
                    </a>
                </div>
                
                <!-- Project Card 2 -->
                <div class="bg-gray-800 p-6 rounded-2xl shadow-md transition-transform duration-300 hover:scale-105">
                    <h3 class="text-xl font-semibold text-teal-400 mb-2">Portfolio Website - A Showcase of Work</h3>
                    <p class="text-gray-400 mb-4">A responsive personal portfolio website built with HTML, CSS, and JavaScript. It features dynamic content loading and a clean layout to showcase my development projects and skills.</p>
                    <a href="#" class="text-white font-medium hover:text-teal-400 transition-colors duration-300 inline-flex items-center">
                        View on GitHub
                        <svg class="ml-2 w-4 h-4" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path d="M12 0C5.373 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.6.11.82-.26.82-.577v-2.007c-3.338.72-4.04-1.61-4.04-1.61-.546-1.386-1.332-1.758-1.332-1.758-1.09-.748.082-.733.082-.733 1.206.086 1.838 1.238 1.838 1.238 1.07 1.83 2.809 1.3 3.49.997.108-.775.42-1.3.766-1.59-2.66-.29-5.46-1.33-5.46-5.932 0-1.309.467-2.383 1.238-3.22-.124-.29-.536-1.52.117-3.175 0 0 1.01-.32 3.3.992 2.3-.642 5.09-1.286 7.4-1.286 2.31 0 5.1.644 7.4 1.286 2.29-1.312 3.3-.992 3.3-.992.653 1.655.24 2.885.116 3.175.772.837 1.238 1.91 1.238 3.22 0 4.61-2.8 5.64-5.46 5.932.43.37.825 1.066.825 2.15v2.793c0 .318.22.688.825.577C20.562 21.82 24 17.302 24 12c0-6.627-5.373-12-12-12z" />
                        </svg>
                    </a>
                </div>
            </div>
        </div>

    </div>
</body>
</html>
