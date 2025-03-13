<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTFOLIO</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-amber-600 h-screen">
    <div>
    <nav class="bg-black h-16 text-white flex items-center justify-center relative px-6">
        <h1 class="absolute left-16 text-lg font-bold">Jassika</h1>
        <ul class="flex space-x-6">
            <li><a href="#home" class="hover:text-gray-400">Home</a></li>
            <li><a href="#Education" class="hover:text-gray-400">Education</a></li>
            <li><a href="#projects" class="hover:text-gray-400">Projects</a></li>
            <li><a href="#about" class="hover:text-gray-400">About</a></li>
        </ul>
        <a href="#contact" class="bg-white text-black px-4 py-2 rounded-md font-semibold hover:bg-gray-300 transition absolute right-16">
            Contact Me
        </a>
    </nav>
    <div class="flex">
    <div class="text-black font-bold text-4xl px-20 py-32">
        <h1>Hi</h1>
        <div class ="flex space-x-4 ">
        <h1>I'm </h1>
        <h1 class="text-fuchsia-900"> Jassika</h1>
    </div>
    <div>
    <h1>a Frontend Devloper</h1>
    <h6 class="text-sm mr-96">I am Jassika, a 2nd-year B.Tech IT student with a passion for software development and technology. I enjoy building innovative projects, exploring new programming languages, and enhancing my problem-solving skills. Always eager to learn and grow in the field of IT! 🚀</h6>
</div>
<div class=" -mt-60 w-full px-6">
    <img src="mypic.jpg" alt="Jassika" class="w-1/4 h-1/4 rounded-full object-cover float-right ml-6">
    
    </div>
</div>

<a href="#contact" class="bg-black text-white my-96 mx-16 px-4 py-2 rounded-md font-semibold hover:bg-gray-300 transition absolute left-16">
    Hire me
</a>
<a href="#experience" class="bg-black text-white my-96 mx-48 px-4 py-2 rounded-md font-semibold hover:bg-gray-300 transition absolute left-16">
    Experience
</a>
</div>
<div class="bg-blue-950 h-screen">
    <div class="justify-center pt-16 pl-12 items-center">
        <img src="mypic.jpg" alt="Jassika" class="w-1/4 h-1/4 rounded-full border-amber-600 border-8 object-cover float-left ml-6">
    </div>
    <section class="p-6 w-1/2 ml-auto space-y-11">
        <h2 class="text-2xl text-amber-600 font-bold mb-4">Education</h2>
    
        <div class="mb-4">
            <h3 class="text-lg text-cyan-400 font-semibold">B.Tech in Information Technology</h3>
            <p class="text-sm text-cyan-100">Lovely Professional University, Jalandhar Punjab</p>
            <p class="text-sm text-cyan-100">2023 - 2027 (Expected)</p>
        </div>
    
        <div>
            <h3 class="text-lg text-cyan-400 font-semibold">Higher Secondary Education (Class 12)</h3>
            <p class="text-sm text-cyan-100">Baluni Public school, sikandra agra</p>
            <p class="text-sm text-cyan-100">Year of Completion: 2023</p>
        </div>

        <div>
            <h3 class="text-lg text-cyan-400 font-semibold">Secondary Education (Class 10)</h3>
            <p class="text-sm text-cyan-100">Ganesh Ram Nagar Saraswati Balika Vidhya Mandir, Balkeshwar Agra</p>
            <p class="text-sm text-cyan-100">Year of Completion: 2021</p>
        </div>
    </section>
    
</div>
<div class="bg-amber-600">]
    <section class="p-6 max-w-lg mx-auto bg-white shadow-lg rounded-2xl">
        <h2 class="text-2xl font-bold text-center mb-4">Contact Me</h2>
        
        <form action="#" method="POST" class="space-y-4">
            <div>
                <label class="block text-gray-700 font-medium mb-1">Your Name</label>
                <input type="text" placeholder="Enter your name" 
                    class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-400 focus:border-blue-400 outline-none">
            </div>
    
            <div>
                <label class="block text-gray-700 font-medium mb-1">Email Address</label>
                <input type="email" placeholder="Enter your email" 
                    class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-400 focus:border-blue-400 outline-none">
            </div>
    
            <div>
                <label class="block text-gray-700 font-medium mb-1">Message</label>
                <textarea placeholder="Write your message..." rows="4"
                    class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-400 focus:border-blue-400 outline-none"></textarea>
            </div>
    
            <button type="submit" 
                class="w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700 transition duration-300">
                Send Message
            </button>
        </form>
    </section>
    
</div>
   
</body>
</html>
