<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SnoozeCruise | Arrive Rested</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <style>
        .hero-bg {
            background-image: linear-gradient(135deg, rgba(15, 23, 42, 0.9) 0%, rgba(15, 23, 42, 0.5) 100%), url('REPLACE_WITH_YOUR_IMG_LINK.jpg');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-slate-950 text-white font-['Inter']">

    <nav class="p-6 flex justify-between max-w-6xl mx-auto items-center">
        <span class="font-bold text-xl tracking-widest text-blue-400">SNOOZECRUISE</span>
        <button class="bg-blue-600 px-5 py-2 rounded-full font-bold text-sm hover:bg-blue-500">Book Now</button>
    </nav>

    <section class="hero-bg px-6 py-28 text-center min-h-[60vh] flex flex-col justify-center items-center rounded-3xl mx-4 my-2 border border-slate-800">
        <h1 class="text-4xl md:text-6xl font-bold mb-4 tracking-tighter">Arrive Rested.<br><span class="text-blue-500">Not Stressed.</span></h1>
        <p class="text-gray-300 mb-8 max-w-xl mx-auto">The world's first autonomous nap pod service. Travel while you sleep in full comfort.</p>
        <div class="flex flex-col md:flex-row gap-4">
            <button class="bg-white text-slate-950 px-8 py-3 rounded-xl font-bold">Download App</button>
            <button class="border border-slate-700 px-8 py-3 rounded-xl font-bold bg-slate-900/50">View Fleet</button>
        </div>
    </section>

    <section class="px-6 py-20 bg-slate-900">
        <h2 class="text-3xl font-bold text-center mb-4 tracking-tight">Our Services</h2>
        <p class="text-center text-gray-500 mb-12">Select your level of rest. No traffic, no stress.</p>
        
        <div class="grid gap-6 max-w-4xl mx-auto md:grid-cols-2">
            
            <div class="bg-slate-800 p-8 rounded-3xl border border-slate-700">
                <h3 class="text-xl font-bold">The Power Nap</h3>
                <p class="text-3xl font-bold my-4">$15 <span class="text-sm font-normal text-gray-400">/ride</span></p>
                <ul class="text-gray-400 text-sm space-y-2 mb-8 list-inside list-disc">
                    <li>✓ 20-minute transit</li>
                    <li>✓ Noise cancellation</li>
                    <li>✓ Wake-up alarm</li>
                </ul>
                <button class="w-full bg-slate-950 border border-slate-700 py-3 rounded-xl font-bold hover:bg-slate-800">Select Plan</button>
            </div>

            <div class="bg-blue-600 p-8 rounded-3xl relative overflow-hidden border border-blue-400">
                <div class="absolute top-4 right-4 bg-white text-blue-600 text-xs font-bold px-2 py-1 rounded">POPULAR</div>
                <h3 class="text-xl font-bold">The Deep REM</h3>
                <p class="text-3xl font-bold my-4">$35 <span class="text-sm font-normal text-blue-200">/ride</span></p>
                <ul class="text-blue-100 text-sm space-y-2 mb-8 list-inside list-disc">
                    <li>✓ 60-minute scenic transit</li>
                    <li>✓ Luxury bedding kit</li>
                    <li>✓ Full cabin aromatherapy</li>
                </ul>
                <button class="w-full bg-white text-blue-600 py-3 rounded-xl font-bold hover:bg-slate-100">Select Plan</button>
            </div>

        </div>
    </section>

    <footer class="py-10 text-center text-gray-700 text-xs uppercase tracking-widest border-t border-slate-800">
        SnoozeCruise Corp &copy; 2026. Rest assured.
    </footer>

</body>
</html>
