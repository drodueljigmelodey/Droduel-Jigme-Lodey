<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Droduel Jigme Loday | 9th Grade Football & Farm Enthusiast</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Montserrat:wght@400;700;900&display=swap');
        
        /* Define a custom theme using Tailwind's script config for better color management */
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'sport-blue': '#005f73', /* Deeper, richer blue */
                        'sport-yellow': '#ffbe0b', /* Vibrant, energetic yellow */
                        'bg-light': '#f5f5f5', /* Off-white background */
                        'text-dark': '#1e1e1e',
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
        
        body {
            background-color: #f5f5f5;
        }

        /* Hero Section Background (Modern Gradient with a strong feel) */
        #home {
            background-image: linear-gradient(135deg, #005f73 0%, #00b4d8 100%);
            min-height: 85vh;
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0% 100%); /* Diagonal cut at the bottom */
        }

        /* Utility class for a noticeable, lift-off shadow effect */
        .card-lift {
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .card-lift:hover {
            transform: translateY(-5px);
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
        }

        /* Dynamic button styling */
        .btn-primary {
            transition: all 0.3s ease;
        }
        .btn-primary:hover {
            transform: translateY(-2px) scale(1.02);
            box-shadow: 0 8px 20px rgba(255, 190, 11, 0.6);
        }
        
        /* Styling for the passion cards */
        .passion-card {
            border-bottom: 5px solid;
            transition: all 0.3s ease;
        }

    </style>
</head>
<body class="antialiased text-text-dark">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#home" class="text-3xl font-black text-sport-blue tracking-wider font-display">
                Droduel J. Loday
            </a>
            <nav class="flex space-x-6 text-sm font-medium">
                <a href="#home" class="text-gray-700 hover:text-sport-blue transition duration-300 border-b-2 border-transparent hover:border-sport-blue pb-1">Home</a>
                <a href="#passion" class="text-gray-700 hover:text-sport-blue transition duration-300 border-b-2 border-transparent hover:border-sport-blue pb-1">My Passion</a>
                <a href="#career" class="text-gray-700 hover:text-sport-blue transition duration-300 border-b-2 border-transparent hover:border-sport-blue pb-1">My Career</a>
            </nav>
        </div>
    </header>

    <!-- Home/Hero Section -->
    <section id="home" class="flex items-center justify-center p-8 text-white card-lift">
        <div class="text-center py-24 px-6 max-w-5xl">
            <div class="mb-8">
                <!-- 
                    *** 1. PROFILE PICTURE: REPLACE THE URL BELOW WITH A LINK TO YOUR PHOTO ***
                    Example: src="https://example.com/droduel_profile.jpg" 
                -->
                <img class="w-40 h-40 mx-auto rounded-full object-cover border-4 border-sport-yellow shadow-xl" 
                     src="https://placehold.co/160x160/ffffff/005f73?text=DJL" 
                     onerror="this.onerror=null; this.src='https://placehold.co/160x160/cccccc/000000?text=AD';"
                     alt="Profile image placeholder">
            </div>
            <h2 class="text-6xl sm:text-8xl font-black mb-4 drop-shadow-2xl font-display leading-tight">
                Hello, I'm Droduel!
            </h2>
            <p class="text-2xl sm:text-3xl font-light mb-10 opacity-90 tracking-wide">
                9th Grade Student, 14 Years Old, Focused on Football and Farming.
            </p>
            <a href="#passion" class="inline-block bg-sport-yellow text-sport-blue font-extrabold py-4 px-12 rounded-full btn-primary shadow-2xl uppercase text-lg">
                Explore My Passions &rarr;
            </a>
        </div>
    </section>

    <!-- My Passion Section (Football & Outdoor Work) -->
    <section id="passion" class="py-20 sm:py-32 bg-bg-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h3 class="text-lg font-semibold tracking-widest text-sport-blue uppercase">What I Live For</h3>
                <h2 class="mt-4 text-4xl sm:text-6xl font-extrabold text-text-dark font-display">
                    Passions: On the Pitch and In the Field
                </h2>
            </div>
            
            <div class="grid lg:grid-cols-2 lg:gap-10">
                
                <!-- Column 1: Football Passion -->
                <div class="mb-10 lg:mb-0">
                    <div class="passion-card p-10 h-full bg-white rounded-xl shadow-lg border-sport-blue card-lift hover:border-sport-yellow">
                        <div>
                            <h4 class="text-4xl font-black text-sport-blue mb-4 flex items-center font-display">
                                <span class="mr-3 text-sport-yellow text-5xl">&#9917;</span> The Beautiful Game
                            </h4>
                            <p class="space-y-4 text-lg text-gray-700 leading-relaxed">
                                I love playing sports! The thrill of competition, the strategy, and the teamwork involved in **football** (soccer) are unmatched. It’s a game that demands both mental focus and physical dedication.
                            </p>
                        </div>
                        <div class="mt-8 p-5 bg-sport-blue/5 rounded-lg border-l-4 border-sport-blue">
                             <h5 class="text-xl font-bold text-sport-blue mb-1">My Hero: Lionel Messi</h5>
                            <p class="text-gray-700 text-base">
                                I am the biggest fan of **Lionel Messi**. His unparalleled vision, immaculate control, and humble dedication inspire me to practice harder and dream bigger. He is the G.O.A.T.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Column 2: Outdoor Physical Activities -->
                <div class="mb-10 lg:mb-0">
                    <div class="passion-card p-10 h-full bg-white rounded-xl shadow-lg border-sport-yellow card-lift hover:border-sport-blue">
                        <div>
                            <h4 class="text-4xl font-black text-sport-blue mb-4 flex items-center font-display">
                                <span class="mr-3 text-sport-blue text-5xl">&#127793;</span> Farm & Field Work
                            </h4>
                            <p class="space-y-4 text-lg text-gray-700 leading-relaxed">
                                Beyond team sports, I find immense satisfaction in hands-on, outdoor physical work. It's a grounding experience that teaches responsibility and the value of hard, patient labor.
                            </p>
                            <ul class="mt-6 pl-5 text-gray-700 space-y-3">
                                <li class="flex items-center text-lg">
                                    <span class="mr-3 text-sport-yellow text-2xl font-bold">&bull;</span> **Cutting grass** and ensuring the land is kept neat.
                                </li>
                                <li class="flex items-center text-lg">
                                    <span class="mr-3 text-sport-yellow text-2xl font-bold">&bull;</span> The patient process of **planting trees** and watching them mature.
                                </li>
                                <li class="flex items-center text-lg">
                                    <span class="mr-3 text-sport-yellow text-2xl font-bold">&bull;</span> The daily discipline of **watering my farm** and caring for the crops.
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Single large image placeholder -->
            <div class="max-w-5xl mx-auto mt-16">
                <!-- 
                    *** 2. MAIN IMAGE: REPLACE THE URL BELOW WITH A LINK TO A PHOTO OF YOU PLAYING SPORTS or WORKING ON THE FARM ***
                    Example: src="https://example.com/droduel_sports_farm.jpg" 
                -->
                <img class="w-full h-auto rounded-xl shadow-2xl object-cover border-4 border-sport-yellow" 
                     style="height: 400px;"
                     src="https://placehold.co/1200x400/005f73/ffffff?text=Droduel+Jigme+Loday%3A+Balanced+Life" 
                     onerror="this.onerror=null; this.src='https://placehold.co/1200x400/cccccc/000000?text=Image+Failed+to+Load';"
                     alt="Image combining themes of football and outdoor farm work">
            </div>
        </div>
    </section>

    <!-- My Career Section (Future Goals) -->
    <section id="career" class="py-20 sm:py-32 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h3 class="text-lg font-semibold tracking-widest text-sport-blue uppercase">Future Path</h3>
                <h2 class="mt-4 text-4xl sm:text-6xl font-extrabold text-text-dark font-display">
                    Goals for High School and Beyond
                </h2>
            </div>
            
            <div class="max-w-4xl mx-auto bg-bg-light p-8 sm:p-12 rounded-xl card-lift border-t-4 border-sport-blue">
                <p class="text-xl text-gray-800 mb-8 leading-relaxed">
                    Currently in the 9th grade, my focus is maximizing my potential both in school and in training. I view every year as preparation for future opportunities.
                </p>
                
                <ul class="space-y-6 text-xl text-gray-700">
                    <li class="flex items-start">
                        <span class="text-sport-yellow text-3xl font-black mr-4">&#9658;</span>
                        <div>
                            <span class="font-bold text-text-dark">Academic Excellence:</span> Achieving high grades in core subjects like Math and Science to ensure a strong foundation for university entrance.
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-sport-yellow text-3xl font-black mr-4">&#9658;</span>
                        <div>
                            <span class="font-bold text-text-dark">Sports Aspirations:</span> My dream is to play competitive football at the collegiate level, possibly securing a scholarship that blends my passion with my education.
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-sport-yellow text-3xl font-black mr-4">&#9658;</span>
                        <div>
                            <span class="font-bold text-text-dark">Career Interest:</span> Exploring fields like Sports Analytics or Physical Therapy, careers that allow me to understand and optimize human physical performance, linking directly to my sports background.
                        </div>
                    </li>
                </ul>
                
                <p class="mt-12 text-center text-sm italic text-gray-500 border-t pt-6 border-gray-300">
                    "Success is not final; failure is not fatal: it is the courage to continue that counts." — Winston Churchill
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-sport-blue text-white py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-lg font-bold">Droduel Jigme Loday | 9th Grade Portfolio</p>
            <p class="mt-1 text-sm text-sport-yellow">Driven by Passion, Focused on Growth.</p>
            <p class="mt-4 text-xs text-gray-300">
                &copy; 2025 Personal Page. Website created by the Gemini Model.
            </p>
        </div>
    </footer>
</body>
</html>
