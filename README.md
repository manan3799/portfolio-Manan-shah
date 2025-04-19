<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Manan Shah - Portfolio</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- GSAP CDN -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      scroll-behavior: smooth;
    }
    section {
      min-height: 100vh;
      padding: 4rem 2rem;
    }
    a:focus {
      outline: 2px solid #2563eb;
      outline-offset: 2px;
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-800">
  <!-- Navbar -->
  <nav class="fixed top-0 w-full bg-white shadow-md z-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between h-16">
        <div class="flex items-center">
          <h1 class="text-xl font-bold">Manan Shah</h1>
        </div>
        <div class="flex items-center space-x-4">
          <a href="#home" class="text-gray-600 hover:text-blue-600">Home</a>
          <a href="#about" class="text-gray-600 hover:text-blue-600">About</a>
          <a href="#education" class="text-gray-600 hover:text-blue-600">Education</a>
          <a href="#experience" class="text-gray-600 hover:text-blue-600">Experience</a>
          <a href="#portfolio" class="text-gray-600 hover:text-blue-600">Portfolio</a>
          <a href="#contact" class="text-gray-600 hover:text-blue-600">Contact</a>
        </div>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="flex items-center justify-center bg-gradient-to-r from-blue-500 to-indigo-600 text-white">
    <div class="text-center animate-section">
      <img src="https://via.placeholder.com/150" alt="Manan Shah, Manufacturing Production Technician" class="w-32 h-32 rounded-full mx-auto mb-4">
      <h1 class="text-4xl font-bold mb-2">Manan Shah</h1>
      <p class="text-xl mb-4">Manufacturing Production Technician</p>
      <a href="#contact" class="bg-white text-blue-600 px-8 py-3 rounded-full hover:bg-gray-200 shadow-md">Get in Touch</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="bg-white animate-section">
    <div class="max-w-7xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">About Me</h2>
      <img src="https://i.imgur.com/F7CVmNl.jpeg" alt="Manan Shah working on ship fabrication grinding" class="w-48 h-48 mx-auto mb-4 rounded-lg object-cover" loading="lazy">
      <p class="text-lg max-w-2xl mx-auto">
        I am an industrious Manufacturing Production Technician with 5 years of hands-on experience in material assembly, inventory maintenance, and equipment operations. I specialize in mechanical fitting, grinding, and production processes across industries like glass manufacturing and tire production. I am committed to quality control and embracing new manufacturing technologies.
      </p>
      <div class="mt-6 grid grid-cols-1 sm:grid-cols-3 gap-4">
        <div class="p-4 bg-gray-100 rounded-lg">
          <h3 class="font-semibold">Grinding & CNC Operation</h3>
          <p>Expertise in manual and CNC grinding for precision manufacturing.</p>
        </div>
        <div class="p-4 bg-gray-100 rounded-lg">
          <h3 class="font-semibold">Float Glass Production</h3>
          <p>Skilled in glass forming, annealing, and furnace operation.</p>
        </div>
        <div class="p-4 bg-gray-100 rounded-lg">
          <h3 class="font-semibold">Teamwork & Problem-Solving</h3>
          <p>Proven ability to collaborate and resolve mechanical issues.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Education Section -->
  <section id="education" class="bg-gray-50 animate-section">
    <div class="max-w-7xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">Education</h2>
      <div class="space-y-6">
        <div class="flex items-center space-x-4">
          <img src="https://i.imgur.com/Ap9aZF0.png" alt="Gujarat Technological University Logo" class="w-12 h-12 object-contain" loading="lazy">
          <div class="text-left">
            <h3 class="font-semibold">Diploma in Mechanical Engineering</h3>
            <p>Gujarat Technological University, Anand, India</p>
            <p>2014 - 2017</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience" class="bg-white animate-section">
    <div class="max-w-7xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">Work Experience</h2>
      <div class="space-y-6">
        <div class="flex items-center space-x-4">
          <img src="https://i.imgur.com/m0uNeIq.png" alt="AOSS SP ZOO Logo" class="w-12 h-12 object-contain" loading="lazy">
          <div class="text-left">
            <h3 class="font-semibold">Mechanical Fitter and Grinder</h3>
            <p>AOSS SP ZOO, Poland</p>
            <p>Nov 2023 - Present</p>
            <p>Conducted assembly work using blueprints, performed grinding operations in ship fabrication, and maintained mechanical equipment.</p>
          </div>
        </div>
        <div class="flex items-center space-x-4">
          <img src="https://i.imgur.com/2ss5dD2.png" alt="Sisecam Logo" class="w-12 h-12 object-contain" loading="lazy">
          <div class="text-left">
            <h3 class="font-semibold">Production Technician</h3>
            <p>Sisecam Flat Glass India Pvt Ltd, Halol, India</p>
            <p>Feb 2022 - Sep 2023</p>
            <p>Coordinated float glass forming, operated tin bath tweel, annealing lehr, and glass melting furnace.</p>
          </div>
        </div>
        <div class="flex items-center space-x-4">
          <img src="https://i.imgur.com/fKifSvZ.png" alt="Schaeffler Logo" class="w-12 h-12 object-contain" loading="lazy">
          <div class="text-left">
            <h3 class="font-semibold">Trainee</h3>
            <p>Schaeffler India Pvt Ltd, Vadodara, India</p>
            <p>Sep 2020 - Feb 2022</p>
            <p>Operated CNC grinding machines, maintained tight tolerances, and performed preventive maintenance.</p>
          </div>
        </div>
        <div class="flex items-center space-x-4">
          <img src="https://i.imgur.com/z78rvlH.png" alt="Yokohama Rubber Logo" class="w-12 h-12 object-contain" loading="lazy">
          <div class="text-left">
            <h3 class="font-semibold">Technical Intern Trainee</h3>
            <p>Yokohama Rubber Pvt Ltd, Onomichi, Japan</p>
            <p>Oct 2018 - Oct 2019</p>
            <p>Operated radial tire building machines, learned Japanese quality methods (TPM, 5S, Kaizen), and performed maintenance.</p>
          </div>
        </div>
        <div class="flex items-center space-x-4">
          <img src="https://i.imgur.com/DlgJI3b.png" alt="ATG Tyres Logo" class="w-12 h-12 object-contain" loading="lazy">
          <div class="text-left">
            <h3 class="font-semibold">Diploma Apprentice Trainee</h3>
            <p>ATG Tyres Pvt Ltd, Dahej, India</p>
            <p>Feb 2018 - Aug 2018</p>
            <p>Operated tire strip winding and building machines, maintained inventory, and addressed production issues.</p>
          </div>
        </div>
        <div class="flex items-center space-x-4">
          <img src="https://i.imgur.com/HaRvZCI.png" alt="Vovantis Lab Logo" class="w-12 h-12 object-contain" loading="lazy">
          <div class="text-left">
            <h3 class="font-semibold">Technician</h3>
            <p>Vovantis Lab Pvt Ltd, Vadodara, India</p>
            <p>Sep 2017 - Jan 2018</p>
            <p>Operated cartoon and tube printers, tablet compressors, and managed chemical processing equipment.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="bg-gray-50 animate-section">
    <div class="max-w-7xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">Portfolio</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="bg-white p-4 rounded-lg shadow-md">
          <img src="https://i.imgur.com/1uesNMV.jpeg" alt="Ship fabrication grinding project" class="w-full h-48 object-cover rounded-md" loading="lazy">
          <h3 class="font-semibold mt-2">Ship Fabrication Grinding</h3>
          <p>Performed manual grinding of TIG and MIG welded areas in ship fabrication assemblies.</p>
        </div>
        <div class="bg-white p-4 rounded-lg shadow-md">
          <img src="https://i.imgur.com/90RWPuG.jpeg" alt="Mechanical component assembly using blueprints" class="w-full h-48 object-cover rounded-md" loading="lazy">
          <h3 class="font-semibold mt-2">Mechanical Assembly Work</h3>
          <p>Conducted assembly and maintenance of mechanical components using blueprints.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-white animate-section">
    <div class="max-w-7xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">Contact Me</h2>
      <p class="text-lg mb-4">Szczecin, Poland</p>
      <p class="text-lg mb-4">+48729403088 | +919879364639</p>
      <p class="text-lg mb-4">shahmanan3799@gmail.com</p>
      <div class="flex justify-center space-x-4">
        <a href="https://www.linkedin.com/in/manan-shah-4398a3137" target="_blank" class="text-blue-600 hover:text-blue-800">LinkedIn</a>
        <a href="mailto:shahmanan3799@gmail.com" class="text-blue-600 hover:text-blue-800">Email</a>
      </div>
    </div>
  </section>

  <!-- GSAP Animations -->
  <script>
    // Register ScrollTrigger
    gsap.registerPlugin(ScrollTrigger);

    // Animate sections on scroll
    document.querySelectorAll('.animate-section').forEach(section => {
      gsap.from(section, {
        opacity: 0,
        y: 50,
        duration: 1,
        scrollTrigger: {
          trigger: section,
          start: 'top 80%',
          end: 'bottom 20%',
          toggleActions: 'play none none none'
        }
      });
    });

    // Hover effect on buttons
    document.querySelectorAll('a[href="#contact"]').forEach(button => {
      button.addEventListener('mouseenter', () => {
        gsap.to(button, { scale: 1.1, duration: 0.3 });
      });
      button.addEventListener('mouseleave', () => {
        gsap.to(button, { scale: 1, duration: 0.3 });
      });
    });
  </script>
</body>
</html>
