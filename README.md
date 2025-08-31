# Portfolio
Project Report
Creation of a Single Page Portfolio Website
Submitted by: Devesh Mokhariya

ABSTRACT
This report documents the conception, design, and development of a modern, single-page personal portfolio website. The primary goal of this project was to create a responsive, visually appealing, and professional online presence for showcasing personal skills, projects, and contact information. The website is built using fundamental web technologies, including HTML5 for the structure, Tailwind CSS for styling and responsiveness, and vanilla JavaScript for interactivity.
The final product is a seamless, single-page application that allows users to scroll through various sections, including an introduction (Hero), an "About Me" biography, a portfolio of projects, a list of technical skills, and a contact section. The design is clean and modern, featuring a dark theme that is popular in the tech industry. The website is fully responsive, ensuring a consistent and user-friendly experience across a wide range of devices, from desktop computers to mobile phones. Key interactive features include a mobile-friendly navigation menu and subtle UI effects that enhance user experience. This project serves as a practical demonstration of front-end web development capabilities.
OBJECTIVE
The principal objective of this project was to design and implement a single-page portfolio website that effectively functions as a digital resume and a showcase of technical abilities. The specific goals set forth at the beginning of the project are outlined below:
1.	To Establish a Professional Online Presence: To create a central, accessible location on the web where personal and professional information, such as skills and project work, can be presented to potential employers, collaborators, or clients.
2.	To Showcase Projects and Skills: To build dedicated sections that clearly and attractively display completed projects, complete with links to their repositories, and to list relevant technical skills in a concise format.
3.	To Achieve Full Responsiveness: To ensure the website provides an optimal viewing and interaction experience across various devices and screen sizes. The layout and content must fluidly adapt to desktops, tablets, and mobile phones without sacrificing usability or aesthetics.
4.	To Develop a Modern and Intuitive User Interface (UI): To design a clean, modern, and engaging user interface with a logical flow and intuitive navigation. The goal was to create a pleasant user experience (UX) that encourages visitors to explore the entire page.
5.	To Apply and Demonstrate Front-End Development Skills: To utilize core web technologies—HTML5, CSS3 (via Tailwind CSS), and JavaScript—to build a functional and polished web application from the ground up, thereby reinforcing and demonstrating proficiency in these areas.
6.	To Ensure Ease of Maintenance: To structure the code in a clean and organized manner, making it straightforward to update information, add new projects, or modify sections in the future.
INTRODUCTION
In the contemporary digital age, a personal portfolio website is an indispensable tool for any technology professional, especially for students and aspiring developers. It serves as a dynamic, interactive resume that goes far beyond a traditional paper document. It provides a platform to not only list skills and experience but to actively demonstrate them through project showcases, interactive elements, and thoughtful design. This project focuses on the creation of such a tool: a single-page portfolio website for Devesh Mokhariya.
A single-page website, also known as a one-page website, is one that presents all its content on a single HTML page. Navigation is typically handled through scrolling or by using links that jump to different sections of the page, rather than loading new pages. This approach offers a fluid, linear, and story-like user experience, guiding the visitor through a curated narrative. For a personal portfolio, this format is particularly effective as it allows for a concise and uninterrupted presentation of one's professional story.
The portfolio is structured into several distinct, logically ordered sections:
●	Header and Navigation: A fixed header at the top of the page provides consistent branding and easy navigation links that smoothly scroll the user to the corresponding section.
●	Hero Section: The initial view upon loading the site. It is designed to make a strong first impression, immediately introducing the individual and their primary professional identity with a bold heading and a brief, impactful statement.
●	About Me Section: This section offers a more detailed personal introduction, providing context about the individual's background, passion for technology, and current academic pursuits. It combines text with a personal photograph to create a more personal connection.
●	Projects Section: This is the core of the portfolio, where tangible work is displayed. Each project is presented in a "card" format, featuring an image, a title, a brief description, and a direct link to the project's source code on GitHub.
●	Skills Section: A visually scannable list of key technical skills and technologies that the individual is proficient in. This gives visitors a quick overview of technical capabilities.
●	Contact Section: The final call-to-action, encouraging visitors to get in touch. It includes a direct email link and icons linking to professional profiles like GitHub.
The design philosophy adopted for this website is one of modern minimalism, utilizing a dark theme with cyan accents. This choice is not only aesthetically pleasing but also reduces eye strain and is a popular trend within the developer community. The entire website is built from scratch, emphasizing a hands-on approach to front-end development.
METHODOLOGY
The development of the single-page portfolio website was executed through a structured, step-by-step process, utilizing a specific set of tools and technologies chosen for their efficiency and modern standards.
Tools and Technologies Used
1.	HTML5 (HyperText Markup Language 5): The foundation of the website. HTML5 was used to structure the content semantically. Elements like <header>, <main>, <section>, <nav>, and <footer> were employed to define the different parts of the page, which improves accessibility and SEO.
2.	Tailwind CSS v3: A utility-first CSS framework used for all styling and layout. Instead of writing custom CSS files, Tailwind provides low-level utility classes that can be composed to build any design directly in the markup.
○	Advantages: This approach enables rapid UI development, ensures design consistency, and makes responsiveness intuitive to implement using breakpoint prefixes (e.g., md:flex, lg:grid-cols-3). It keeps the HTML and styling co-located, simplifying the development process. The website was linked to the Tailwind CDN for ease of use.
3.	JavaScript (ES6): Used to add interactivity and enhance the user experience. The JavaScript code is embedded directly within the HTML file in a <script> tag. Its role in this project includes:
○	Mobile Menu Toggle: Handling the logic to show and hide the navigation menu on smaller screens.
○	Dynamic Header Styling: Adding a shadow to the header when the user scrolls down the page, providing a visual cue that the header is detached from the top.
4.	Google Fonts: Used to import the "Inter" font family. This font was chosen for its excellent readability and clean, modern aesthetic, which aligns with the overall design of the portfolio.
5.	Visual Studio Code: The primary code editor used for writing and organizing the project files.
Step-by-Step Implementation
The construction of the website followed a logical, section-by-section progression.
Step 1: Initial Setup and Boilerplate
The project began by creating a single index.html file. A standard HTML5 boilerplate was set up, including the <!DOCTYPE html>, <html>, <head>, and <body> tags. The <meta> tags for character set (UTF-8) and viewport settings were included to ensure proper rendering and responsiveness.
Step 2: Linking Dependencies
Within the <head> section, links were added to the required external resources. A <script> tag was used to include Tailwind CSS from its CDN, and a <link> tag was used to import the "Inter" font from the Google Fonts library.
Step 3: Building the Header and Navigation
A <header> element was created with a dark background. It was made fixed to the top of the viewport. Using Flexbox utilities from Tailwind (flex, justify-between, items-center), the name/logo and navigation links were aligned. The navigation was initially hidden on small screens (hidden) and made visible on medium screens and up (md:flex). A hamburger menu button was added for mobile, which would be controlled by JavaScript.
Step 4: Creating the Sections
The <main> content area was divided into logical <section> elements, each with a unique ID (e.g., id="about") to enable smooth-scrolling navigation.
●	Hero Section: This section was styled to take up the full viewport height (min-h-screen) and center its content vertically and horizontally using Flexbox. A gradient text effect was created using Tailwind's background and text-clipping utilities.
●	About Me Section: A two-column layout was created using Flexbox (flex, md:flex-row). On mobile devices, the columns stack vertically (flex-col) by default.
●	Projects Section: A CSS Grid (grid) was used to display the project cards. The number of columns adjusts with the screen size: one column on mobile, two on medium screens (md:grid-cols-2), and three on large screens (lg:grid-cols-3), creating a fully responsive gallery. Each card featured a subtle hover effect (hover:-translate-y-2) to provide visual feedback.
●	Skills Section: A Flexbox container with the flex-wrap property was used to display the skill tags. This allows the tags to wrap onto the next line if they exceed the container width, which is ideal for varying screen sizes.
●	Contact Section: This was a simple, centered section with a final call-to-action button (mailto: link) and SVG icons for social media links.
Step 5: Implementing JavaScript Interactivity
A <script> tag was placed at the end of the <body>.
●	Mobile Menu: Constants were declared to hold references to the menu button and the mobile menu element using document.getElementById(). An event listener (addEventListener) was attached to the button. On 'click', it toggles a 'hidden' class on the menu element, controlling its visibility.
●	Header Shadow: An event listener was attached to the window object to detect 'scroll' events. Inside the callback function, an if statement checks if the vertical scroll position (window.scrollY) is greater than 10 pixels. If it is, shadow classes are added to the header's classList; otherwise, they are removed.
Step 6: Finalization and Footer
A simple <footer> was added at the end of the page with copyright information, separated by a top border to visually distinguish it from the main content. The final code was reviewed for consistency and clarity.
<div style="page-break-after: always;"></div>
CODE
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Devesh Mokhariya - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .section {
            scroll-margin-top: 64px; 
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">

    <header id="header" class="bg-gray-900/80 backdrop-blur-sm fixed top-0 left-0 right-0 z-50 transition-shadow duration-300">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-white">Devesh Mokhariya</a>
            <nav class="hidden md:flex space-x-8 items-center">
                <a href="#about" class="hover:text-cyan-400 transition-colors duration-300">About</a>
                <a href="#projects" class="hover:text-cyan-400 transition-colors duration-300">Projects</a>
                <a href="#skills" class="hover:text-cyan-400 transition-colors duration-300">Skills</a>
                <a href="#contact" class="bg-cyan-500 hover:bg-cyan-600 text-white font-semibold px-4 py-2 rounded-lg transition-colors duration-300">Contact</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-gray-300 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>

        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
            <a href="#about" class="block py-2 hover:text-cyan-400">About</a>
            <a href="#projects" class="block py-2 hover:text-cyan-400">Projects</a>
            <a href="#skills" class="block py-2 hover:text-cyan-400">Skills</a>
            <a href="#contact" class="block mt-2 bg-cyan-500 hover:bg-cyan-600 text-white font-semibold px-4 py-2 rounded-lg text-center">Contact</a>
        </div>
    </header>

    <main class="container mx-auto px-6 pt-24">

  
        <section id="hero" class="min-h-screen flex items-center justify-center text-center -mt-24">
            <div class="max-w-3xl">
                <h1 class="text-5xl md:text-7xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 pb-2">Devesh Mokhariya</h1>
                <p class="text-xl md:text-2xl mt-4 text-gray-400">Creative Web Developer Enthusiast</p>
                <p class="mt-6 text-lg text-gray-300">I build beautiful, responsive, and user-friendly web experiences. Turning complex problems into simple, elegant solutions is my passion.</p>
                <div class="mt-8 flex justify-center gap-4">
                    <a href="#projects" class="bg-cyan-500 hover:bg-cyan-600 text-white font-semibold px-6 py-3 rounded-lg transition-transform duration-300 transform hover:scale-105">View My Work</a>
                    <a href="mailto:your-email@example.com" class="bg-gray-700 hover:bg-gray-600 text-white font-semibold px-6 py-3 rounded-lg transition-transform duration-300 transform hover:scale-105">Get in Touch</a>
                </div>
            </div>
        </section>

        <section id="about" class="section py-20">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold">About Me</h2>
                <p class="text-lg text-gray-400 mt-2">A little bit about my journey</p>
            </div>
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/3">
                    <img src="https://i.postimg.cc/VLZmmcQB/Whats-App-Image-2025-08-29-at-13-53-15-da85b4c1.jpg" alt="Devesh Mokhariya" class="rounded-full shadow-lg mx-auto border-4 border-gray-700">
                </div>
                <div class="md:w-2/3">
                    <p class="text-lg mb-4 text-gray-300">
                       Hello! I'm Devesh, a passionate and aspiring web developer currently pursuing my engineering degree at VIT Bhopal Univarsity. I have a strong enthusiasm for creating dynamic and intuitive user interfaces and enjoy building beautiful, responsive, and user-friendly web experiences.
                    </p>
                    <p class="text-lg mb-4 text-gray-300">
                        I believe in writing clean, maintainable code and am always eager to learn new technologies to improve my craft.
                    </p>
                     <p class="text-lg text-gray-300">
                        When I'm not coding, you can find me exploring hiking trails, experimenting with new recipes, or contributing to open-source projects.
                    </p>
                </div>
            </div>
        </section>

        <section id="projects" class="section py-20">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold">My Projects</h2>
                <p class="text-lg text-gray-400 mt-2">A selection of my favorite work</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">

                <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg transform hover:-translate-y-2 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/1e293b/38bdf8?text=Face+Recognition" alt="Face Recognition System" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-2">Face Recognation System</h3>
                        <p class="text-gray-400 mb-4">A full-featured e-commerce site built with React, Redux, and Firebase for real-time data synchronization.</p>
                        <a href="https://github.com/deveshmokhariya/Face-Recognition-Based-Attendance-System-" target="_blank" rel="noopener noreferrer" class="text-cyan-400 hover:underline">View Project &rarr;</a>
                    </div>
                </div>

                <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg transform hover:-translate-y-2 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/1e293b/38bdf8?text=School+Management" alt="School Management" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-2">School Management</h3>
                        <p class="text-gray-400 mb-4">A sleek and intuitive task manager with drag-and-drop functionality, built using Vue.js and Tailwind CSS.</p>
                        <a href="https://github.com/deveshmokhariya/school-management" target="_blank" rel="noopener noreferrer" class="text-cyan-400 hover:underline">View Project &rarr;</a>
                    </div>
                </div>

                <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg transform hover:-translate-y-2 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/1e293b/38bdf8?text=Parking+Management" alt="Parking Management System" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold mb-2">Parking Management System</h3>
                        <p class="text-gray-400 mb-4">A modern and responsive personal portfolio template created with just HTML and Tailwind CSS.</p>
                        <a href="https://github.com/deveshmokhariya/parking-management-system" target="_blank" rel="noopener noreferrer" class="text-cyan-400 hover:underline">View Project &rarr;</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills" class="section py-20">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold">My Skills</h2>
                <p class="text-lg text-gray-400 mt-2">Technologies I work with</p>
            </div>
            <div class="max-w-4xl mx-auto">
                <div class="flex flex-wrap justify-center gap-4">
                   <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">HTML5</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">CSS</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">JavaScript</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">React</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">Node.js</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">SQL</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">Git & GitHub</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">Java</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">C++</span>
                    <span class="bg-gray-700 text-gray-200 px-4 py-2 rounded-full text-lg font-medium">Python</span>
                </div>
            </div>
        </section>

        <section id="contact" class="section py-20">
            <div class="text-center">
                <h2 class="text-4xl font-bold">Get In Touch</h2>
                <p class="text-lg text-gray-400 mt-2">I'm always open to discussing new projects or collaboration opportunities.</p>
                <a href="mailto:your-email@example.com" class="mt-8 inline-block bg-cyan-500 hover:bg-cyan-600 text-white font-bold text-xl px-8 py-4 rounded-lg transition-transform duration-300 transform hover:scale-105">
                    Say Hello
                </a>
                <div class="mt-12 flex justify-center space-x-6">
                    <a href="https://github.com/deveshmokhariya" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-cyan-400 transition-colors">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12c0 4.418 2.865 8.165 6.839 9.489.5.092.682-.217.682-.482 0-.237-.009-.868-.014-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.031-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.203 2.398.1 2.651.64.7 1.03 1.595 1.03 2.688 0 3.848-2.338 4.695-4.566 4.942.359.308.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.001 10.001 0 0022 12c0-5.523-4.477-10-10-10z" clip-rule="evenodd" /></svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-cyan-400 transition-colors">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm-1 15.69v-5.6h-1.92v2.41H7.83v-2.41H6V8.68h1.83V7.22c0-1.58.84-2.52 2.5-2.52h2.08v2.41h-1.24c-.45 0-.52.22-.52.52v1.05h1.82l-.24 2.41h-1.58v5.6h-2.5z"/></svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-cyan-400 transition-colors">
                       <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M22.23 5.63a2.35 2.35 0 0 0-1.66-1.66C18.95 3.5 12 3.5 12 3.5s-6.95 0-8.57.47a2.35 2.35 0 0 0-1.66 1.66C1.3 7.25 1.3 12 1.3 12s0 4.75.47 6.37a2.35 2.35 0 0 0 1.66 1.66c1.62.47 8.57.47 8.57.47s6.95 0 8.57-.47a2.35 2.35 0 0 0 1.66-1.66c.47-1.62.47-6.37.47-6.37s0-4.75-.47-6.37zM9.93 15.5v-7l6.53 3.5-6.53 3.5z"/></svg>
                    </a>
                </div>
            </div>
        </section>

    </main>

    <footer class="border-t border-gray-800 mt-20">
        <div class="container mx-auto px-6 py-6 text-center text-gray-500">
            <p>&copy; 2025 Devesh Mokhariya. All Rights Reserved.</p>
        </div>
    </footer>

    <script>

        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        const mobileNavLinks = document.querySelectorAll('#mobile-menu a');
        mobileNavLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        const header = document.getElementById('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 10) {
                header.classList.add('shadow-lg', 'shadow-gray-900/50');
            } else {
                header.classList.remove('shadow-lg', 'shadow-gray-900/50');
            }
        });
    </script>
</body>
</html>



RESULTS & OUTPUT
The project successfully resulted in a functional, responsive, and visually appealing single-page portfolio website. The final output matches the initial design goals. Below are screenshots demonstrating the website's appearance and functionality on different screen sizes.


 

  

 

CONCLUSION
The "Single Page Portfolio Website" project was successfully completed, meeting all the objectives outlined at the start. The final product is a modern, fully responsive, and professional portfolio that effectively showcases the skills and projects of Devesh Mokhariya.
Through this project, practical experience was gained in several key areas of front-end web development. The use of HTML5 for semantic structure, Tailwind CSS for rapid and responsive design, and JavaScript for user interactivity provided a holistic development experience. The choice of a single-page architecture proved to be highly effective for creating a streamlined and engaging user journey, ideal for a personal portfolio.
The methodology of building the site section by section ensured an organized workflow and allowed for focused development on each component's functionality and styling. The final website performs well across all major devices, providing a consistent and intuitive experience for all users.
Future Enhancements:
While the current version of the website is complete and functional, there are several potential improvements that could be implemented in the future:
●	Contact Form: Integrating a functional contact form using a backend service like Netlify Forms or a third-party API to allow visitors to send messages directly from the site.
●	Animations and Transitions: Adding more subtle animations (e.g., on-scroll fade-in effects for sections) to further enhance the user experience.
●	Content Management System (CMS): Integrating a headless CMS (like Sanity or Strapi) to manage project and skill data, making it easier to update content without touching the code.
In conclusion, this project serves as a strong foundational piece for a professional online presence and a testament to the practical application of modern front-end development techniques.
