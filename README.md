<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cajas con Imágenes</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        .box {
            transition: transform 0.2s;
        }
        .box:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-gray-100 p-10">

    <h1 class="text-3xl font-bold text-center mb-10">Lenguajes y Tecnologías</h1>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="box rounded-lg border border-gray-300 p-5 bg-white shadow-md cursor-pointer" onclick="alert('HTML')">
            <label class="font-semibold text-lg">HTML</label>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML" class="mt-2 w-full h-32 object-contain rounded-lg">
        </div>

        <div class="box rounded-lg border border-gray-300 p-5 bg-white shadow-md cursor-pointer" onclick="alert('CSS')">
            <label class="font-semibold text-lg">CSS</label>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/62/CSS3_logo_and_wordmark.svg" alt="CSS" class="mt-2 w-full h-32 object-contain rounded-lg">
        </div>

        <div class="box rounded-lg border border-gray-300 p-5 bg-white shadow-md cursor-pointer" onclick="alert('JavaScript')">
            <label class="font-semibold text-lg">JavaScript</label>
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/JavaScript_logo_2.svg" alt="JavaScript" class="mt-2 w-full h-32 object-contain rounded-lg">
        </div>

        <div class="box rounded-lg border border-gray-300 p-5 bg-white shadow-md cursor-pointer" onclick="alert('PHP')">
            <label class="font-semibold text-lg">PHP</label>
            <img src="https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg" alt="PHP" class="mt-2 w-full h-32 object-contain rounded-lg">
        </div>

        <div class="box rounded-lg border border-gray-300 p-5 bg-white shadow-md cursor-pointer" onclick="alert('Astro')">
            <label class="font-semibold text-lg">Astro</label>
            <img src="https://astro.build/assets/branding/astro-logo.svg" alt="Astro" class="mt-2 w-full h-32 object-contain rounded-lg">
        </div>

        <div class="box rounded-lg border border-gray-300 p-5 bg-white shadow-md cursor-pointer" onclick="alert('Tailwind CSS')">
            <label class="font-semibold text-lg">Tailwind CSS</label>
            <img src="https://tailwindcss.com/_next/image?url=%2Fimg%2Fsocial-preview.jpg&w=1920&q=75" alt="Tailwind CSS" class="mt-2 w-full h-32 object-contain rounded-lg">
        </div>

        <div class="box rounded-lg border border-gray-300 p-5 bg-white shadow-md cursor-pointer" onclick="alert('JavaScript')">
            <label class="font-semibold text-lg">JavaScript</label>
            <img src="https://upload.wikimedia.org/wikipedia/commons/9/9b/JavaScript-logo.svg" alt="JavaScript" class="mt-2 w-full h-32 object-contain rounded-lg">
        </div>
    </div>

    <script>
        // Aquí puedes agregar más interactividad si lo deseas
    </script>
</body>
</html>
