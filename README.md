<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - MAVADO Tech Hub</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-900 text-white">
  <!-- Particle Background -->
  <div id="particles-js" class="absolute inset-0 z-0"></div>

  <!-- Navigation -->
  <nav class="bg-gray-800 p-4 fixed w-full top-0 z-10">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-2xl font-bold text-blue-400">MAVADO Tech Hub</a>
      <ul class="flex space-x-6">
        <li><a href="index.html" class="hover:text-blue-400">Home</a></li>
        <li><a href="about.html" class="hover:text-blue-400">About</a></li>
        <li><a href="code-library.html" class="hover:text-blue-400">Code Library</a></li>
        <li><a href="community.html" class="hover:text-blue-400">Community</a></li>
        <li><a href="contact.html" class="hover:text-blue-400">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="py-20 mt-16 relative z-10">
    <div class="container mx-auto text-center">
      <h1 class="text-5xl font-bold mb-4">Welcome to MAVADO Tech Hub</h1>
      <p class="text-xl mb-6">Discover, learn, and share cutting-edge tech code and resources.</p>
      <a href="code-library.html" class="bg-blue-400 text-gray-900 px-6 py-3 rounded-full hover:bg-blue-500">Explore Code Library</a>
    </div>
  </section>

  <script>
    particlesJS('particles-js', {
      particles: {
        number: { value: 80, density: { enable: true, value_area: 800 } },
        color: { value: '#00b7ff' },
        shape: {
          type: ['circle', 'triangle', 'polygon', 'star'],
          stroke: { width: 0, color: '#000000' },
          polygon: { nb_sides: 5 }
        },
        opacity: { value: 0.5, random: true },
        size: { value: 3, random: true },
        line_linked: {
          enable: true,
          distance: 150,
          color: '#00b7ff',
          opacity: 0.4,
          width: 1
        },
        move: {
          enable: true,
          speed: 6,
          direction: 'none',
          random: false,
          straight: false,
          out_mode: 'out',
          bounce: false
        }
      },
      interactivity: {
        detect_on: 'canvas',
        events: {
          onhover: { enable: true, mode: 'repulse' },
          onclick: { enable: true, mode: 'push' },
          resize: true
        }
      },
      retina_detect: true
    });
  </script>
  <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About - MAVADO Tech Hub</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-900 text-white">
  <!-- Navigation -->
  <nav class="bg-gray-800 p-4 fixed w-full top-0 z-10">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-2xl font-bold text-blue-400">MAVADO Tech Hub</a>
      <ul class="flex space-x-6">
        <li><a href="index.html" class="hover:text-blue-400">Home</a></li>
        <li><a href="about.html" class="hover:text-blue-400">About</a></li>
        <li><a href="code-library.html" class="hover:text-blue-400">Code Library</a></li>
        <li><a href="community.html" class="hover:text-blue-400">Community</a></li>
        <li><a href="contact.html" class="hover:text-blue-400">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- About Section -->
  <section class="py-20 mt-16">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-8">About Us</h2>
      <p class="text-lg text-center max-w-2xl mx-auto">
        MAVADO Tech Hub is a vibrant community for developers and tech enthusiasts. We provide high-quality code snippets, tutorials, and resources to help you build innovative tech solutions.
      </p>
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Code Library - MAVADO Tech Hub</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism-dark.min.css">
  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-900 text-white">
  <!-- Navigation -->
  <nav class="bg-gray-800 p-4 fixed w-full top-0 z-10">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-2xl font-bold text-blue-400">MAVADO Tech Hub</a>
      <ul class="flex space-x-6">
        <li><a href="index.html" class="hover:text-blue-400">Home</a></li>
        <li><a href="about.html" class="hover:text-blue-400">About</a></li>
        <li><a href="code-library.html" class="hover:text-blue-400">Code Library</a></li>
        <li><a href="community.html" class="hover:text-blue-400">Community</a></li>
        <li><a href="contact.html" class="hover:text-blue-400">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Particle Background -->
  <div id="particles-js" class="absolute inset-0 z-0"></div>

  <!-- Code Library Section -->
  <section class="py-20 mt-16 relative z-10">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-8">Code Library</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="bg-gray-800 p-6 rounded-lg">
          <h3 class="text-2xl font-bold mb-4">Python: Simple API Request</h3>
          <pre><code class="language-python">
import requests

def get_user_data(user_id):
    response = requests.get(f"https://api.example.com/users/{user_id}")
    if response.status_code == 200:
        return response.json()
    return None
          </code></pre>
        </div>
        <div class="bg-gray-800 p-6 rounded-lg">
          <h3 class="text-2xl font-bold mb-4">JavaScript: Array Filter</h3>
          <pre><code class="language-javascript">
const numbers = [1, 2, 3, 4, 5, 6];
const evenNumbers = numbers.filter(num => num % 2 === 0);
console.log(evenNumbers); // [2, 4, 6]
          </code></pre>
        </div>
      </div>
    </div>
  </section>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-python.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/components/prism-javascript.min.js"></script>
  <script>
    particlesJS('particles-js', {
      particles: {
        number: { value: 80, density: { enable: true, value_area: 800 } },
        color: { value: '#00b7ff' },
        shape: {
          type: ['circle', 'triangle', 'polygon', 'star'],
          stroke: { width: 0, color: '#000000' },
          polygon: { nb_sides: 5 }
        },
        opacity: { value: 0.5, random: true },
        size: { value: 3, random: true },
        line_linked: {
          enable: true,
          distance: 150,
          color: '#00b7ff',
          opacity: 0.4,
          width: 1
        },
        move: {
          enable: true,
          speed: 6,
          direction: 'none',
          random: false,
          straight: false,
          out_mode: 'out',
          bounce: false
        }
      },
      interactivity: {
        detect_on: 'canvas',
        events: {
          onhover: { enable: true, mode: 'repulse' },
          onclick: { enable: true, mode: 'push' },
          resize: true
        }
      },
      retina_detect: true
    });
  </script>
  <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Community - MAVADO Tech Hub</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-900 text-white">
  <!-- Navigation -->
  <nav class="bg-gray-800 p-4 fixed w-full top-0 z-10">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-2xl font-bold text-blue-400">MAVADO Tech Hub</a>
      <ul class="flex space-x-6">
        <li><a href="index.html" class="hover:text-blue-400">Home</a></li>
        <li><a href="about.html" class="hover:text-blue-400">About</a></li>
        <li><a href="code-library.html" class="hover:text-blue-400">Code Library</a></li>
        <li><a href="community.html" class="hover:text-blue-400">Community</a></li>
        <li><a href="contact.html" class="hover:text-blue-400">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Community Section -->
  <section class="py-20 mt-16">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-8">Join Our Community</h2>
      <p class="text-lg text-center max-w-2xl mx-auto">
        Connect with developers, share your projects, and collaborate on innovative ideas. Join our forums and events to grow your skills.
      </p>
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - MAVADO Tech Hub</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-900 text-white">
  <!-- Navigation -->
  <nav class="bg-gray-800 p-4 fixed w-full top-0 z-10">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-2xl font-bold text-blue-400">MAVADO Tech Hub</a>
      <ul class="flex space-x-6">
        <li><a href="index.html" class="hover:text-blue-400">Home</a></li>
        <li><a href="about.html" class="hover:text-blue-400">About</a></li>
        <li><a href="code-library.html" class="hover:text-blue-400">Code Library</a></li>
        <li><a href="community.html" class="hover:text-blue-400">Community</a></li>
        <li><a href="contact.html" class="hover:text-blue-400">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Contact Section -->
  <section class="py-20 mt-16">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-8">Contact Us</h2>
      <div class="max-w-lg mx-auto">
        <p class="text-lg text-center mb-6">Have questions or want to collaborate? Reach out to us!</p>
        <p class="text-lg text-center">Email: contact@mavadotechhub.com</p>
        <p class="text-lg text-center">Phone: +1-555-987-6543</p>
      </div>
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html>
