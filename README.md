<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blazor Learning Journey</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
            display: flex;
            justify-content: center;
            align-items: flex-start; /* Align items to the start, not center vertically */
            min-height: 100vh;
            padding: 2rem; /* Add some padding around the whole page */
            box-sizing: border-box;
        }
        .container {
            max-width: 900px;
            width: 100%;
            background-color: #ffffff; /* White background for the content area */
            border-radius: 1rem; /* Rounded corners */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* Soft shadow */
            padding: 2.5rem;
            margin-top: 2rem; /* Margin from the top to prevent it from sticking to the very top */
            margin-bottom: 2rem; /* Margin at the bottom */
        }
        .link-category {
            margin-bottom: 2rem;
        }
        .link-category:last-child {
            margin-bottom: 0;
        }
        .link-item {
            margin-bottom: 0.75rem;
        }
        .link-item:last-child {
            margin-bottom: 0;
        }
        .link-item a {
            color: #3b82f6; /* Blue link color */
            text-decoration: none;
            transition: color 0.2s ease-in-out;
            font-weight: 500;
            display: block;
            padding: 0.5rem 0;
        }
        .link-item a:hover {
            color: #2563eb; /* Darker blue on hover */
            text-decoration: underline;
        }
        h1 {
            color: #1f2937; /* Dark gray for headings */
        }
        h2 {
            color: #374151; /* Slightly lighter gray for subheadings */
            border-bottom: 1px solid #e5e7eb; /* Subtle separator */
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
        }
        ul {
            list-style: none; /* Remove default bullet points */
            padding: 0;
        }
    </style>
</head>
<body class="selection:bg-blue-300 selection:text-white">
    <div class="container">
        <h1 class="text-4xl font-bold text-center mb-6">Blazor Learning Journey</h1>
        <p class="text-center text-gray-600 mb-8">
            Explore a comprehensive collection of resources for learning Blazor,
            from its introduction and evolution to hands-on exercises and debugging tips.
            Click on any link to dive deeper!
        </p>

        <div class="link-category">
            <h2 class="text-2xl font-semibold mb-4">Foundation & Evolution</h2>
            <ul>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/blazor-building-web-apps-with-c.html" target="_blank" rel="noopener noreferrer">
                        Introduction: Blazor - Building Web Apps with C#
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/evolution-of-aspnet-from-web-forms-to.html" target="_blank" rel="noopener noreferrer">
                        Evolution of ASP.NET: From Web Forms to Blazor
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/blazor-server-vs-blazor-webassembly-vs.html" target="_blank" rel="noopener noreferrer">
                        Templates of Blazor: Blazor Server vs. Blazor WebAssembly vs. Blazor United
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/2-introduction-to-blazor-application.html" target="_blank" rel="noopener noreferrer">
                        Module 2: Introduction to Blazor Application
                    </a>
                </li>
            </ul>
        </div>

        <div class="link-category">
            <h2 class="text-2xl font-semibold mb-4">Hands-on Exercises</h2>
            <ul>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/exercise-1-your-first-interactive.html" target="_blank" rel="noopener noreferrer">
                        Exercise 1: Your First Interactive Counter
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/exercise-2-personalized-welcome-message.html" target="_blank" rel="noopener noreferrer">
                        Exercise 2: Personalized Welcome Message
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/exercise-3-simple-to-do-list-blazor.html" target="_blank" rel="noopener noreferrer">
                        Exercise 3: Simple To-Do List
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/exercise-building-interactive-to-do.html" target="_blank" rel="noopener noreferrer">
                        Exercise 3.1: To-Do List with Delete and Update
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/exercise-4-debugging-detective.html" target="_blank" rel="noopener noreferrer">
                        Exercise 4: Debugging Detective
                    </a>
                </li>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/building-interactive-shopping-list-with.html" target="_blank" rel="noopener noreferrer">
                        Exercise: Building an Interactive Shopping List with Debugging
                    </a>
                </li>
            </ul>
        </div>

        <div class="link-category">
            <h2 class="text-2xl font-semibold mb-4">A Blazor Story</h2>
            <ul>
                <li class="link-item">
                    <a href="https://learndotnetwithraushan.blogspot.com/2025/06/story-blazor-journey-building-modern.html" target="_blank" rel="noopener noreferrer">
                        Story to Understand Blazor: Building a Modern Web Application
                    </a>
                </li>
            </ul>
        </div>
    </div>
</body>
</html>
