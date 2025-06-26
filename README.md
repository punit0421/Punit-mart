# Punit-mart
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Punit Mart - Your One Stop Shop
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Montserrat', sans-serif;
    }
  </style>
 </head>
 <body class="bg-gray-50 text-gray-800">
  <!-- Header / Navbar -->
  <header class="bg-white shadow-md sticky top-0 z-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between h-16">
    <a class="text-2xl font-bold text-indigo-600" href="#">
     Punit Mart
    </a>
    <nav class="hidden md:flex space-x-8 font-semibold text-gray-700">
     <a class="hover:text-indigo-600 transition" href="#home">
      Home
     </a>
     <a class="hover:text-indigo-600 transition" href="#products">
      Products
     </a>
     <a class="hover:text-indigo-600 transition" href="#about">
      About Us
     </a>
     <a class="hover:text-indigo-600 transition" href="#contact">
      Contact
     </a>
    </nav>
    <div class="md:hidden">
     <button aria-label="Toggle menu" class="text-gray-700 focus:outline-none focus:ring-2 focus:ring-indigo-600" id="menu-btn">
      <i class="fas fa-bars fa-lg">
      </i>
     </button>
    </div>
   </div>
   <nav class="hidden md:hidden bg-white border-t border-gray-200" id="mobile-menu">
    <a class="block px-4 py-3 text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 font-semibold" href="#home">
     Home
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 font-semibold" href="#products">
     Products
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 font-semibold" href="#about">
     About Us
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 font-semibold" href="#contact">
     Contact
    </a>
   </nav>
  </header>
  <!-- Hero Section -->
  <section class="bg-indigo-600 text-white" id="home">
   <div class="max-w-7xl mx-auto px-6 py-20 flex flex-col-reverse md:flex-row items-center md:items-start md:space-x-12">
    <div class="md:w-1/2 text-center md:text-left">
     <h1 class="text-4xl sm:text-5xl font-extrabold mb-4 leading-tight">
      Welcome to Punit Mart
     </h1>
     <p class="text-lg sm:text-xl mb-8 max-w-md mx-auto md:mx-0">
      Your one-stop shop for quality products at unbeatable prices. Shop smart, shop easy, shop Punit Mart.
     </p>
     <a class="inline-block bg-white text-indigo-600 font-bold px-8 py-3 rounded shadow hover:bg-indigo-50 transition" href="#products">
      Shop Now
     </a>
    </div>
    <div class="md:w-1/2 mb-10 md:mb-0">
     <img alt="A colorful shopping cart filled with various products and happy customers shopping in a modern store" class="rounded-lg shadow-lg mx-auto" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/22687d84-9d56-467c-bcb3-fb504a7b3ec1.jpg" width="600"/>
    </div>
   </div>
  </section>
  <!-- Products Section -->
  <section class="max-w-7xl mx-auto px-6 py-16" id="products">
   <h2 class="text-3xl font-extrabold text-center text-gray-900 mb-12">
    Our Products
   </h2>
   <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A basket filled with fresh assorted fruits including apples, bananas, and grapes on a wooden table" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/755ab3fb-379d-4785-2165-71f1b8b70159.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Fresh Fruits Basket
     </h3>
     <p class="text-gray-600 flex-grow">
      A selection of fresh, juicy fruits perfect for your daily nutrition.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $15.99
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A wooden crate filled with fresh organic vegetables including carrots, tomatoes, and lettuce on a rustic background" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/c2065607-cfe0-4183-40db-859e46b06546.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Organic Vegetables Crate
     </h3>
     <p class="text-gray-600 flex-grow">
      Freshly harvested organic vegetables, perfect for healthy meals.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $22.50
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A pack of assorted snacks including chips, nuts, and cookies arranged on a white background" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/7b68f625-3f8b-44b6-e4d1-8e00f12b9464.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Assorted Snacks Pack
     </h3>
     <p class="text-gray-600 flex-grow">
      A variety pack of tasty snacks to satisfy your cravings anytime.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $12.75
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A bag of premium roasted coffee beans spilling onto a wooden surface with coffee cups nearby" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/a6488322-7cdd-4645-77a1-bcbc231333e7.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Premium Coffee Beans
     </h3>
     <p class="text-gray-600 flex-grow">
      Rich and aromatic coffee beans sourced from the best plantations.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $18.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A set of colorful handmade soaps with natural ingredients arranged on a wooden tray with flowers" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/c53665d8-c644-4e7b-9633-34212880ac44.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Handmade Soaps Set
     </h3>
     <p class="text-gray-600 flex-grow">
      Natural and fragrant handmade soaps for gentle skin care.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $25.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A collection of colorful eco-friendly reusable shopping bags hanging on hooks in a store" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/a0faa38e-359f-4aa5-47fc-a30fcc2e8d05.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Eco-Friendly Reusable Bags
     </h3>
     <p class="text-gray-600 flex-grow">
      Durable and stylish bags to reduce plastic waste while shopping.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $9.99
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="An elegant box of assorted gourmet chocolates with decorative ribbons on a dark background" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/5b70e2ff-23c2-46f4-b000-c413a063fa31.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Gourmet Chocolate Box
     </h3>
     <p class="text-gray-600 flex-grow">
      Delicious handcrafted chocolates perfect for gifting or indulgence.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $30.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A loaf of freshly baked bread with a crispy crust on a wooden cutting board with a knife" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/ca2fecb2-6335-4e05-c402-14e67dcaa93e.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Fresh Baked Bread
     </h3>
     <p class="text-gray-600 flex-grow">
      Warm and soft bread baked daily for your breakfast and meals.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $4.50
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A glass jar filled with golden natural honey with a wooden honey dipper on a rustic table" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/2fe97adc-bb26-4eba-c150-45a0482038d8.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Natural Honey Jar
     </h3>
     <p class="text-gray-600 flex-grow">
      Pure and natural honey harvested from organic beehives.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $14.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A collection of herbal tea bags with dried herbs and flowers arranged on a wooden table" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/f6a3bb64-a1d5-42b1-573f-f6390cb59392.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Herbal Tea Collection
     </h3>
     <p class="text-gray-600 flex-grow">
      Relaxing and aromatic herbal teas for your daily wellness.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $16.25
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A set of kitchen essentials including knives, cutting board, and utensils arranged neatly" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/7eeab1e3-e9c1-4122-8221-cda9a9ea5824.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Kitchen Essentials Set
     </h3>
     <p class="text-gray-600 flex-grow">
      Everything you need to equip your kitchen for cooking and baking.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $45.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A bundle of fitness gear including dumbbells, yoga mat, and water bottle on a gym floor" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/7fa19534-d76a-4fdd-9d0a-909381746334.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Fitness Gear Bundle
     </h3>
     <p class="text-gray-600 flex-grow">
      High-quality fitness equipment to keep you active and healthy.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $60.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A collection of smart home devices including smart speakers, lights, and thermostats on a modern table" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/a41fcf2e-e440-45a1-eb7c-90c9ffb57198.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Smart Home Devices
     </h3>
     <p class="text-gray-600 flex-grow">
      Innovative devices to make your home smarter and more efficient.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $120.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A colorful set of kids toys including blocks, cars, and stuffed animals on a play mat" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/91ccd456-d4d8-4e9a-1435-6660bee2656f.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Kids Toys Set
     </h3>
     <p class="text-gray-600 flex-grow">
      Safe and fun toys to keep your children entertained and learning.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $35.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A stationery kit with pens, notebooks, and markers arranged neatly on a desk" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/0cc612a0-0f87-4ab5-491a-97f74513a2b4.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Stationery Kit
     </h3>
     <p class="text-gray-600 flex-grow">
      Complete set of stationery essentials for school, office, or home use.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $20.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
    <div class="bg-white rounded-lg shadow hover:shadow-lg transition p-4 flex flex-col">
     <img alt="A collection of beauty care products including lotions, creams, and makeup brushes on a vanity" class="rounded-md mb-4 object-cover h-48 w-full" height="300" loading="lazy" src="https://storage.googleapis.com/a1aa/image/692587ed-97e4-478c-7e12-8989e9bef2af.jpg" width="400"/>
     <h3 class="text-lg font-semibold mb-2">
      Beauty Care Products
     </h3>
     <p class="text-gray-600 flex-grow">
      Premium beauty products to enhance your natural glow and confidence.
     </p>
     <div class="mt-4 font-bold text-indigo-600">
      $40.00
     </div>
     <button class="mt-4 bg-indigo-600 text-white py-2 rounded hover:bg-indigo-700 transition">
      Add to Cart
     </button>
    </div>
   </div>
  </section>
  <!-- About Us Section -->
  <section class="bg-white py-16" id="about">
   <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center md:space-x-12">
    <div class="md:w-1/2 mb-10 md:mb-0">
     <img alt="Friendly shop staff assisting happy customers in a modern retail store with bright lighting and organized shelves" class="rounded-lg shadow-lg mx-auto" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/fb5e3097-d76a-45c9-1ad3-6fe6271fdaef.jpg" width="600"/>
    </div>
    <div class="md:w-1/2">
     <h2 class="text-3xl font-extrabold mb-6 text-gray-900">
      About Punit Mart
     </h2>
     <p class="text-gray-700 mb-4 leading-relaxed">
      At Punit Mart, we are committed to providing our customers with the best shopping experience. Established with a passion for quality and affordability, we offer a wide range of products from fresh groceries to household essentials.
     </p>
     <p class="text-gray-700 mb-4 leading-relaxed">
      Our friendly staff and customer-first approach ensure that you find exactly what you need with ease and confidence. We believe in building lasting relationships with our community by delivering value and trust.
     </p>
     <p class="text-gray-700 leading-relaxed">
      Visit us today and discover why Punit Mart is the preferred choice for smart shoppers.
     </p>
    </div>
   </div>
  </section>
  <!-- Contact Section -->
  <section class="bg-indigo-600 text-white py-16" id="contact">
   <div class="max-w-7xl mx-auto px-6">
    <h2 class="text-3xl font-extrabold mb-8 text-center">
     Contact Us
    </h2>
    <div class="max-w-3xl mx-auto bg-indigo-700 rounded-lg p-8 shadow-lg">
     <form action="mailto:punitmart@gmail.com" class="space-y-6" enctype="text/plain" method="POST">
      <div>
       <label class="block mb-2 font-semibold" for="name">
        Name
       </label>
       <input class="w-full px-4 py-2 rounded text-gray-900 focus:outline-none focus:ring-2 focus:ring-indigo-400" id="name" name="name" placeholder="Your full name" required="" type="text"/>
      </div>
      <div>
       <label class="block mb-2 font-semibold" for="email">
        Email
       </label>
       <input class="w-full px-4 py-2 rounded text-gray-900 focus:outline-none focus:ring-2 focus:ring-indigo-400" id="email" name="email" placeholder="you@example.com" required="" type="email"/>
      </div>
      <div>
       <label class="block mb-2 font-semibold" for="message">
        Message
       </label>
       <textarea class="w-full px-4 py-2 rounded text-gray-900 focus:outline-none focus:ring-2 focus:ring-indigo-400" id="message" name="message" placeholder="Write your message here" required="" rows="4"></textarea>
      </div>
      <button class="w-full bg-white text-indigo-600 font-bold py-3 rounded hover:bg-indigo-50 transition" type="submit">
       Send Message
      </button>
     </form>
    </div>
    <div class="mt-10 text-center text-indigo-200">
     <p>
      Email us at:
      <a class="underline hover:text-white" href="mailto:punitmart@gmail.com">
       punitmart@gmail.com
      </a>
     </p>
     <p class="mt-2">
      Website:
      <a class="underline hover:text-white" href="mailto:punitmart@gmail.com">
       www.punitmart@gmail.com
      </a>
     </p>
    </div>
   </div>
  </section>
  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-8">
   <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center">
    <p class="text-sm">
     © 2024 Punit Mart. All rights reserved.
    </p>
    <div class="flex space-x-6 mt-4 md:mt-0">
     <a aria-label="Facebook" class="hover:text-white" href="https://facebook.com" rel="noopener" target="_blank">
      <i class="fab fa-facebook fa-lg">
      </i>
     </a>
     <a aria-label="Twitter" class="hover:text-white" href="https://twitter.com" rel="noopener" target="_blank">
      <i class="fab fa-twitter fa-lg">
      </i>
     </a>
     <a aria-label="Instagram" class="hover:text-white" href="https://instagram.com" rel="noopener" target="_blank">
      <i class="fab fa-instagram fa-lg">
      </i>
     </a>
     <a aria-label="LinkedIn" class="hover:text-white" href="https://linkedin.com" rel="noopener" target="_blank">
      <i class="fab fa-linkedin fa-lg">
      </i>
     </a>
    </div>
   </div>
  </footer>
  <script>
   const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');

    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
 </body>
</html>
