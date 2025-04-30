# my-html-site
PORTIFOLIO
<html>
 <head>
  <title>
   Cassandra Mysterious Files
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
  </style>
 </head>
 <body class="bg-black text-white min-h-screen flex flex-col items-center justify-center">
  <!-- Page 1: Account Creation Page -->
  <div class="w-full max-w-md p-8 bg-black text-center" id="account-creation">
   <h1 class="text-4xl font-bold mb-8">
    CASSANDRA MYSTERIOUS FILES
   </h1>
   <h2 class="text-2xl mb-6">
    Create Your Account
   </h2>
   <form class="space-y-4" id="account-form">
    <input class="w-full p-2 rounded bg-gray-800 text-white" placeholder="Name" required="" type="text"/>
    <select class="w-full p-2 rounded bg-gray-800 text-white" required="">
     <option disabled="" selected="" value="">
      Service
     </option>
     <option value="KGB">
      KGB
     </option>
     <option value="FBI">
      FBI
     </option>
    </select>
    <button class="w-full p-2 bg-blue-600 rounded text-white font-bold" type="submit">
     Submit
    </button>
   </form>
   <p class="mt-4 hidden" id="notification">
    You are now discovering the truth!
   </p>
  </div>
  <!-- Page 2: Topic Selection Page -->
  <div class="hidden w-full max-w-md p-8 bg-blue-600 text-center" id="topic-selection">
   <h1 class="text-4xl font-bold mb-8">
    CASSANDRA MYSTERIOUS FILES
   </h1>
   <h2 class="text-2xl mb-6">
    Select Your Topic
   </h2>
   <div class="space-y-4">
    <button class="w-full p-2 bg-blue-800 rounded text-white font-bold" onclick="showPage('top-secret')">
     Top Secret
    </button>
    <button class="w-full p-2 bg-blue-800 rounded text-white font-bold" onclick="showPage('unsolved')">
     Unsolved
    </button>
    <button class="w-full p-2 bg-blue-800 rounded text-white font-bold" onclick="showPage('african-myths')">
     African Scary Myths
    </button>
    <button class="w-full p-2 bg-blue-800 rounded text-white font-bold" onclick="showPage('strange-stories')">
     Strange Stories
    </button>
    <button class="w-full p-2 bg-blue-800 rounded text-white font-bold" onclick="showPage('extraterrestrial')">
     Extraterrestrial
    </button>
   </div>
  </div>
  <!-- Topic Pages -->
  <div class="hidden w-full max-w-3xl p-8 bg-white text-black" id="top-secret">
   <h1 class="text-4xl font-bold mb-8">
    CASSANDRA MYSTERIOUS FILES
   </h1>
