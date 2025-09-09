<!doctype html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Adict Manlung | The Flock Storyteller</title>
  <meta name="description" content="Official website of Adict Manlung – rapper, songwriter, and street storyteller. Listen, watch, and book shows." />
  <meta property="og:title" content="Adict Manlung | The Flock Storyteller" />
  <meta property="og:description" content="Official website of Adict Manlung – rapper, songwriter, and street storyteller." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://files.catbox.moe/jok7xm.png" />
  <meta name="theme-color" content="#0a0a0a" />
  <link rel="icon" href="/favicon.ico" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              DEFAULT: '#22c55e',
              dim: '#16a34a'
            }
          }
        }
      }
    }
  </script>
</head>
<body class="bg-black text-white selection:bg-brand selection:text-black">
  <!-- NAV -->
  <header class="fixed inset-x-0 top-0 z-50 backdrop-blur bg-black/60 border-b border-white/5">
    <nav class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 flex items-center justify-between h-16">
      <a href="#home" class="font-bold tracking-wider text-white">ADICT <span class="text-brand">MANLUNG</span></a>
      
      <!-- Desktop Navigation -->
      <div class="hidden md:flex items-center gap-6 text-sm">
        <a href="#about" class="hover:text-brand">About</a>
        <a href="#music" class="hover:text-brand">Music</a>
        <a href="#projects" class="hover:text-brand">Projects</a>
        <a href="#contact" class="hover:text-brand">Contact</a>
      </div>
      
      <!-- Mobile Navigation Button -->
      <button class="md:hidden flex flex-col justify-center items-center w-8 h-8 space-y-1.5" aria-label="Toggle menu">
        <span class="block w-6 h-0.5 bg-white"></span>
        <span class="block w-6 h-0.5 bg-white"></span>
        <span class="block w-6 h-0.5 bg-white"></span>
      </button>
      
      <a href="#music" class="md:inline-flex hidden px-3 py-1.5 rounded-full bg-brand text-black font-semibold hover:bg-brand-dim transition">Listen</a>
    </nav>
    
    <!-- Mobile Menu (hidden by default) -->
    <div class="md:hidden hidden bg-black/95 border-t border-white/5 py-4 px-4">
      <div class="flex flex-col space-y-4 text-center">
        <a href="#about" class="py-2 hover:text-brand">About</a>
        <a href="#music" class="py-2 hover:text-brand">Music</a>
        <a href="#projects" class="py-2 hover:text-brand">Projects</a>
        <a href="#contact" class="py-2 hover:text-brand">Contact</a>
        <a href="#music" class="py-2 px-4 mx-auto rounded-full bg-brand text-black font-semibold hover:bg-brand-dim transition w-fit">Listen</a>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <section id="home" class="relative pt-28 md:pt-36 pb-16 md:pb-24 overflow-hidden">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 items-center gap-10">
      <div>
        <h1 class="text-4xl md:text-6xl font-extrabold leading-tight">Adict Manlung
          <span class="block text-brand">The Flock Storyteller</span>
        </h1>
        <p class="mt-4 text-lg text-white/80 max-w-xl">Rapper • Songwriter • Street Poet. Nairobi-bred narratives over hard drums and raw emotion.</p>
        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#music" class="px-5 py-3 rounded-xl bg-brand text-black font-semibold hover:bg-brand-dim transition">Listen Now</a>
          <a href="https://www.youtube.com/@12FlockTV" target="_blank" rel="noopener noreferrer" class="px-5 py-3 rounded-xl border border-white/20 hover:border-brand hover:text-brand transition">Watch on YouTube</a>
        </div>
      </div>
      <div class="relative">
        <img src="https://files.catbox.moe/jok7xm.png" alt="Adict Manlung portrait" class="w-full max-w-md mx-auto rounded-2xl shadow-2xl ring-1 ring-white/10" width="500" height="500" />
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-16 md:py-24 border-t border-white/5">
    <div class="mx-auto max-w-5xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-4xl font-bold">About <span class="text-brand">Adict Manlung</span></h2>
      <p class="mt-4 text-white/80 leading-relaxed">Kenyan rapper Adict Manlung (real name Marklin Ochieng) – the voice of the streets. Born in Migori, Sori Karungu, raised by a single dad after losing his mother, his music is a mirror of real life – the hustle, pain, and hope.</p>
      <p class="mt-4 text-white/80 leading-relaxed">With roots in hip hop, street poetry, and conscious rap, Adict Manlung blends raw truth with rhythmic fire. Every track tells a story: My Gee, Unfinished Business, Black African – pure street vibes that hit hard.</p>
      <p class="mt-4 text-white/80 leading-relaxed">This is more than music; it's survival, struggle, and strength in every verse. Subscribe for official videos, freestyles, and street anthems from the underdog who refuses to quit.</p>
      <div class="mt-6 flex flex-wrap gap-3">
        <a href="#contact" class="px-4 py-2 rounded-lg bg-white/10 hover:bg-white/15 border border-white/10">Book a Show</a>
        <a href="#music" class="px-4 py-2 rounded-lg bg-white/10 hover:bg-white/15 border border-white/10">Stream Music</a>
      </div>
    </div>
  </section>

  <!-- MUSIC -->
  <section id="music" class="py-16 md:py-24 bg-white/5">
    <div class="mx-auto max-w-6xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-4xl font-bold">Music & Platforms</h2>
      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <a href="https://music.apple.com/ke/artist/adict-manlung/1826572392" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Apple Music</a>
        <a href="https://open.spotify.com/artist/5lrdgGBgb8of6nOr5HF9kw?si=rZ3TKBw1S-KC_ph3E8fvlQ" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Spotify</a>
        <a href="https://boomplay.com/artists/113745914?srModel=COPYLINK&srList=WEB" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Boomplay</a>
        <a href="https://tiktok.com/@iamadictmanlung" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">TikTok</a>
        <a href="https://lnk.to/My-Gee" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Linkfire</a>
        <a href="https://music.amazon.co.uk/artists/B0FHZ4WD1Y/adict-manlung" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Amazon Music</a>
        <a href="https://soundcloud.com/adictmanlung" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">SoundCloud</a>
        <a href="https://audiomack.com/adict-manlung" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Audiomack</a>
        <a href="https://deezer.com/en/artist/336509591" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Deezer</a>
        <a href="https://mdundo.com/a/594950" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">Mdundo</a>
        <a href="https://whatsapp.com/channel/0029Vb5dNyaJUM2UXfk0EE3k" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-black/60 border border-white/10 hover:border-brand flex items-center justify-center">WhatsApp Channel</a>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="py-16 md:py-24">
    <div class="mx-auto max-w-6xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-4xl font-bold">Projects</h2>
      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <article class="group relative overflow-hidden rounded-2xl border border-white/10 bg-white/5">
          <a href="https://www.youtube.com/watch?v=SaZ-DMup5wg" target="_blank" rel="noopener noreferrer">
            <img src="https://img.youtube.com/vi/SaZ-DMup5wg/maxresdefault.jpg" alt="My Gee music video thumbnail" class="h-44 w-full object-cover transition-transform group-hover:scale-105" width="480" height="360" />
            <div class="p-4">
              <h3 class="font-semibold">My Gee</h3>
              <p class="mt-1 text-sm text-white/70">Official Music Video</p>
            </div>
          </a>
        </article>
        <article class="group relative overflow-hidden rounded-2xl border border-white/10 bg-white/5">
          <a href="https://www.youtube.com/watch?v=Fj8d02Ar-T4" target="_blank" rel="noopener noreferrer">
            <img src="https://img.youtube.com/vi/Fj8d02Ar-T4/maxresdefault.jpg" alt="Unfinished Business music video thumbnail" class="h-44 w-full object-cover transition-transform group-hover:scale-105" width="480" height="360" />
            <div class="p-4">
              <h3 class="font-semibold">Unfinished Business</h3>
              <p class="mt-1 text-sm text-white/70">Official Music Video</p>
            </div>
          </a>
        </article>
        <article class="group relative overflow-hidden rounded-2xl border border-white/10 bg-white/5">
          <a href="https://www.youtube.com/watch?v=unXx10NhdGs" target="_blank" rel="noopener noreferrer">
            <img src="https://img.youtube.com/vi/unXx10NhdGs/maxresdefault.jpg" alt="Black African music video thumbnail" class="h-44 w-full object-cover transition-transform group-hover:scale-105" width="480" height="360" />
            <div class="p-4">
              <h3 class="font-semibold">Black African</h3>
              <p class="mt-1 text-sm text-white/70">Official Music Video</p>
            </div>
          </a>
        </article>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-16 md:py-24 bg-white/5">
    <div class="mx-auto max-w-4xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-4xl font-bold">Contact & Booking</h2>
      <p class="mt-2 text-white/80">For bookings, features, press, and collaborations, reach out below.</p>
      <div class="mt-8 grid md:grid-cols-2 gap-6">
        <div class="space-y-3">
          <div class="p-4 rounded-2xl border border-white/10 bg-black/60">
            <div class="text-sm text-white/60">Email</div>
            <a href="mailto:contact@adictmanlung.com" class="font-semibold hover:text-brand">contact@adictmanlung.com</a>
          </div>
          <div class="p-4 rounded-2xl border border-white/10 bg-black/60">
            <div class="text-sm text-white/60">Instagram</div>
            <a href="https://instagram.com/iamadictmanlung" target="_blank" rel="noopener noreferrer" class="font-semibold hover:text-brand">@iamadictmanlung</a>
          </div>
          <div class="p-4 rounded-2xl border border-white/10 bg-black/60">
            <div class="text-sm text-white/60">Facebook</div>
            <a href="https://facebook.com/iamadictmanlung1" target="_blank" rel="noopener noreferrer" class="font-semibold hover:text-brand">facebook.com/iamadictmanlung1</a>
          </div>
          <div class="p-4 rounded-2xl border border-white/10 bg-black/60">
            <div class="text-sm text-white/60">More Streaming Links</div>
            <ul class="list-disc list-inside text-sm text-white/70 space-y-1">
              <li><a href="https://music.apple.com/ke/artist/adict-manlung/1826572392" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Apple Music</a></li>
              <li><a href="https://open.spotify.com/artist/5lrdgGBgb8of6nOr5HF9kw?si=rZ3TKBw1S-KC_ph3E8fvlQ" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Spotify</a></li>
              <li><a href="https://boomplay.com/artists/113745914?srModel=COPYLINK&srList=WEB" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Boomplay</a></li>
              <li><a href="https://tiktok.com/@iamadictmanlung" target="_blank" rel="noopener noreferrer" class="hover:text-brand">TikTok</a></li>
              <li><a href="https://lnk.to/My-Gee" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Linkfire</a></li>
              <li><a href="https://music.amazon.co.uk/artists/B0FHZ4WD1Y/adict-manlung" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Amazon Music</a></li>
              <li><a href="https://soundcloud.com/adictmanlung" target="_blank" rel="noopener noreferrer" class="hover:text-brand">SoundCloud</a></li>
              <li><a href="https://audiomack.com/adict-manlung" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Audiomack</a></li>
              <li><a href="https://deezer.com/en/artist/336509591" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Deezer</a></li>
              <li><a href="https://mdundo.com/a/594950" target="_blank" rel="noopener noreferrer" class="hover:text-brand">Mdundo</a></li>
              <li><a href="https://whatsapp.com/channel/0029Vb5dNyaJUM2UXfk0EE3k" target="_blank" rel="noopener noreferrer" class="hover:text-brand">WhatsApp Channel</a></li>
            </ul>
          </div>
        </div>

        <!-- Contact Form -->
        <form name="contact" method="POST" data-netlify="true" class="p-6 rounded-2xl border border-white/10 bg-black/60 space-y-4">
          <input type="hidden" name="form-name" value="contact" />
          <div>
            <label for="name" class="block text-sm text-white/70 mb-1">Name</label>
            <input id="name" name="name" required class="w-full px-4 py-2 rounded-lg bg-white/10 border border-white/10 focus:outline-none focus:ring-2 focus:ring-brand" />
          </div>
          <div>
            <label for="email" class="block text-sm text-white/70 mb-1">Email</label>
            <input id="email" type="email" name="email" required class="w-full px-4 py-2 rounded-lg bg-white/10 border border-white/10 focus:outline-none focus:ring-2 focus:ring-brand" />
          </div>
          <div>
            <label for="message" class="block text-sm text-white/70 mb-1">Message</label>
            <textarea id="message" name="message" rows="4" required class="w-full px-4 py-2 rounded-lg bg-white/10 border border-white/10 focus:outline-none focus:ring-2 focus:ring-brand"></textarea>
          </div>
          <button type="submit" class="w-full px-4 py-2 rounded-lg bg-brand text-black font-semibold hover:bg-brand-dim transition">Send</button>
        </form>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="border-t border-white/5">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-8 flex flex-col md:flex-row items-center justify-between gap-4">
      <p class="text-sm text-white/60">© 2025 Adict Manlung. All rights reserved.</p>
      <div class="flex items-center gap-4 text-sm text-white/60">
        <a href="#" class="hover:text-brand">Privacy</a>
        <span class="opacity-40">•</span>
        <a href="#" class="hover:text-brand">Terms</a>
      </div>
    </div>
  </footer>

  <!-- JavaScript for mobile menu toggle -->
  <script>
    document.addEventListener('DOMContentLoaded', function() {
      const menuButton = document.querySelector('button[aria-label="Toggle menu"]');
      const mobileMenu = document.querySelector('.md\\:hidden.hidden');
      
      menuButton.addEventListener('click', function() {
        mobileMenu.classList.toggle('hidden');
      });
    });
  </script>
</body>
</html>
