<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manato Takahashi - GitHub Profile</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Apply Inter font globally */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5; /* Light gray background */
            color: #333; /* Darker text for readability */
            line-height: 1.6;
        }
        /* Custom styles for a more polished look */
        .container-wrapper {
            background-color: #ffffff;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1); /* Soft shadow */
            border-radius: 1.5rem; /* More rounded corners */
            padding: 2rem;
            margin: 2rem auto; /* Center the container */
            max-width: 800px; /* Max width for desktop */
            width: 95%; /* Fluid width for responsiveness */
            box-sizing: border-box; /* Include padding in width */
        }
        .skill-badge {
            background-color: #e0f2fe; /* Light blue background */
            color: #0c4a6e; /* Dark blue text */
            padding: 0.5rem 1rem;
            border-radius: 9999px; /* Fully rounded pill shape */
            font-weight: 500;
            display: inline-block; /* Allows badges to wrap naturally */
            margin: 0.25rem; /* Small margin between badges */
            transition: transform 0.2s ease-in-out; /* Smooth hover effect */
        }
        .skill-badge:hover {
            transform: translateY(-2px); /* Lift effect on hover */
            background-color: #bae6fd; /* Slightly darker blue on hover */
        }
        .social-link {
            color: #3b82f6; /* Blue for links */
            text-decoration: none;
            font-weight: 600;
            transition: color 0.2s ease-in-out;
        }
        .social-link:hover {
            color: #2563eb; /* Darker blue on hover */
            text-decoration: underline;
        }
        /* Responsive adjustments for smaller screens */
        @media (max-width: 640px) {
            .container-wrapper {
                padding: 1.5rem;
                margin: 1rem auto;
            }
            h1 {
                font-size: 2rem; /* Adjust heading size */
            }
            h2 {
                font-size: 1.5rem; /* Adjust subheading size */
            }
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen">
    <div class="container-wrapper">
        <!-- Header Section -->
        <header class="text-center mb-8">
            <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-900 mb-2">
                こんにちは、Manato Takahashiです！ 👋
            </h1>
            <p class="text-lg sm:text-xl text-gray-600">
                ずとまよとアニメをこよなく愛するソフトウェアエンジニアです。
                日々の開発を楽しんでいます。
            </p>
        </header>

        <hr class="border-t-2 border-gray-200 my-8">

        <!-- About Me Section -->
        <section class="mb-8">
            <h2 class="text-2xl sm:text-3xl font-bold text-gray-800 mb-4 text-center">
                自己紹介
            </h2>
            <p class="text-gray-700 text-base sm:text-lg leading-relaxed text-center">
                主にWebアプリケーションの開発に携わっており、特にバックエンド技術に強みを持っています。
                ユーザーに価値を届けることを目標に、日々新しい技術の探求と品質向上に努めています。
            </p>
        </section>

        <!-- Skills Section -->
        <section class="mb-8">
            <h2 class="text-2xl sm:text-3xl font-bold text-gray-800 mb-4 text-center">
                💻 スキル
            </h2>
            <div class="flex flex-wrap justify-center gap-2">
                <span class="skill-badge">Ruby</span>
                <span class="skill-badge">Ruby on Rails</span>
                <span class="skill-badge">Docker</span>
                <span class="skill-badge">AWS</span>
            </div>
        </section>

        <!-- Learning & Interests Section -->
        <section class="mb-8">
            <h2 class="text-2xl sm:text-3xl font-bold text-gray-800 mb-4 text-center">
                🌱 学習と興味
            </h2>
            <div class="flex flex-wrap justify-center gap-2">
                <span class="skill-badge">JavaScript</span>
                <span class="skill-badge">TypeScript</span>
                <span class="skill-badge">React</span>
                <span class="skill-badge">Next.js</span>
            </div>
        </section>

        <!-- Connect Section -->
        <section class="mb-8 text-center">
            <h2 class="text-2xl sm:text-3xl font-bold text-gray-800 mb-4">
                🔗 繋がり
            </h2>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <a href="https://x.com/code_and_gaming?t=oUKAtzmZRj1alHVNyuUqw&s=09" target="_blank" rel="noopener noreferrer" class="social-link">
                    <span class="text-xl mr-2">🐦</span> X (旧Twitter)
                </a>
                <a href="https://zenn.dev/manamana" target="_blank" rel="noopener noreferrer" class="social-link">
                    <span class="text-xl mr-2">📝</span> Zenn
                </a>
            </div>
        </section>

        <hr class="border-t-2 border-gray-200 my-8">

        <!-- Footer Section -->
        <footer class="text-center text-gray-500 text-sm">
            <p>&copy; 2025 Manato Takahashi. All rights reserved.</p>
            <p>最後までご覧いただきありがとうございます！</p>
        </footer>
    </div>
</body>
</html>



[![trophy](https://github-profile-trophy.vercel.app/?username=manato-takahashi&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)
