# bejubaansewatrustngo.com
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bejubaan Seva Trust - Every Paw Deserves Love</title>

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600;700&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    :root{--brand:#fb923c;--brand-dark:#f97316}
    body{font-family:'Open Sans',sans-serif;background:#fffaf0}
    h1,h2,h3{font-family:'Poppins',sans-serif}

    /* Hero animation */
    .hero-bg{background-image:linear-gradient(0deg, rgba(0,0,0,0.45), rgba(0,0,0,0.25)), url('http://127.0.0.1:5500/Gemini_Generated_Image_im6ibuim6ibuim6i.png');background-size:cover;background-position:center}

    /* Simple lightbox modal */
    .modal-backdrop{background:rgba(0,0,0,0.6)}

    /* Floating WhatsApp */
    .whatsapp-float{position:fixed;right:18px;bottom:18px;z-index:60}

    /* Smooth scroll */
    html{scroll-behavior:smooth}

    /* Small tweaks */
    .btn-brand{background:var(--brand);color:white}
    .btn-brand:hover{background:var(--brand-dark)}

    /* Sticky header shadow on scroll (toggled by JS) */
    .scrolled{box-shadow:0 6px 18px rgba(0,0,0,0.15)}

    /* Gallery hover */
    .gallery-img{transition:transform .25s ease, box-shadow .25s ease}
    .gallery-img:hover{transform:scale(1.03);box-shadow:0 10px 30px rgba(0,0,0,0.2)}

    /* Responsive hero text */
    @media (max-width:640px){.hero-title{font-size:1.25rem}}
  </style>
</head>
<body class="antialiased text-gray-800">

  <!-- Header -->
  <header id="siteHeader" class="fixed w-full top-0 left-0 z-50 bg-white/90 backdrop-blur">
    <div class="max-w-6xl mx-auto flex items-center justify-between px-4 py-3">
      <a href="#home" class="flex items-center gap-3">
        <img src="logo_dog-removebg-preview.png" alt="logo" class="w-12 h-12 rounded-full object-cover border-2 border-orange-400">
        <div>
          <div class="text-sm text-gray-600">Bejubaan</div>
          <div class="text-lg font-bold">Seva Trust</div>
        </div>
      </a>

      <!-- Desktop nav -->
      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a href="#home" class="hover:text-orange-500">Home</a>
        <a href="#about" class="hover:text-orange-500">About</a>
        <a href="#volunteer" class="hover:text-orange-500">Volunteer</a>
        <a href="#donate" class="hover:text-orange-500">Donate</a>
        <a href="#gallery" class="hover:text-orange-500">Gallery</a>
        <a href="#contact" class="hover:text-orange-500">Contact</a>
        <a href="https://forms.gle/hjYZnn6HGtC7F7xSA" target="_blank" class="ml-2 px-4 py-2 rounded-full btn-brand text-xs">Register</a>
      </nav>

      <!-- Mobile menu button -->
      <button id="mobileBtn" class="md:hidden text-2xl">☰</button>
    </div>

    <!-- Mobile menu -->
    <div id="mobileMenu" class="hidden md:hidden bg-white/95 border-t">
      <div class="flex flex-col px-6 py-4 gap-2 text-sm">
        <a href="#home" class="py-2">Home</a>
        <a href="#about" class="py-2">About</a>
        <a href="#volunteer" class="py-2">Volunteer</a>
        <a href="#donate" class="py-2">Donate</a>
        <a href="#gallery" class="py-2">Gallery</a>
        <a href="#contact" class="py-2">Contact</a>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <main class="pt-20">
    <section id="home" class="hero-bg h-[520px] md:h-[640px] flex items-center">
      <div class="max-w-6xl mx-auto w-full px-6">
        <div class="bg-black/45 p-6 md:p-12 rounded-lg text-white max-w-3xl">
          <h1 class="hero-title text-2xl md:text-4xl font-bold leading-tight">Be Their Hope, Be Their Voice — Join Bejubaan Seva Trust</h1>
          <p class="mt-4 text-sm md:text-lg">Love. Feed. Protect. Repeat. We rescue, treat and rehabilitate stray dogs and find loving homes for them.</p>

          <div class="mt-6 flex flex-wrap gap-3">
            <a href="#volunteer" class="px-4 py-2 rounded-lg btn-brand">Volunteer Now</a>
            <a href="#donate" class="px-4 py-2 rounded-lg bg-white text-orange-600 font-semibold">Donate Today</a>
            <a href="#gallery" class="px-4 py-2 rounded-lg bg-white/20 border border-white/30">See Gallery</a>
          </div>

          <div class="mt-6 grid grid-cols-2 sm:grid-cols-3 gap-4 text-center">
            <div><div class="text-xl font-bold">20+</div><div class="text-xs">Active Volunteers</div></div>
            <div><div class="text-xl font-bold">30+</div><div class="text-xs">Dogs Fed Monthly</div></div>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="py-16 bg-white">
      <div class="max-w-6xl mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-8 items-center">
          <div>
            <h2 class="text-3xl font-bold text-orange-600 mb-4">About Bejubaan Seva Trust</h2>
            <p class="text-lg leading-relaxed mb-4">Bejubaan Seva Trust is a community-driven NGO working for the welfare of street dogs. We rescue injured animals, provide medical care, arrange adoptions, and run community feeding programs.</p>
            <ul class="space-y-2 text-sm text-gray-600">
              <li>• Community feeding programs</li>
            </ul>

            <div class="mt-6 flex gap-3">
              <a href="#volunteer" class="btn-brand px-4 py-2 rounded">Join as Volunteer</a>
              <a href="#donate" class="px-4 py-2 rounded border border-orange-200">Donate</a>
            </div>
          </div>

          <div class="rounded-lg overflow-hidden shadow">
            <img src="Gemini_Generated_Image_im6ibuim6ibuim6i.png" alt="about" class="w-full h-72 object-cover">
          </div>
        </div>
      </div>
    </section>
      <!-- Volunteer Modal -->
     <section id="volunteer" class="py-16 bg-orange-50">
         <div class="max-w-4xl mx-auto px-6 text-center">
           <h2 class="text-2xl font-bold mb-4">Become a Volunteer</h2>
            <p class="mb-6 text-gray-700">Fill out our official Volunteer Google Form.</p>

           <a href="https://forms.gle/hjYZnn6HGtC7F7xSA"
             class="btn-brand px-5 py-3 rounded-lg text-lg"
             target="_blank">
      Open Volunteer Form
    </a>
  </div>
     </section>

    <!-- DONATE -->
     <section id="donate" class="py-16 bg-white">
      <h3 class="text-xl font-bold mb-3"><center>Scan & Pay (UPI)</center></h3>

      <img src="WhatsApp Image 2025-11-07 at 14.07.44_9c84c79d.jpg" 
           alt="QR code"
           class="mx-auto w-60 h-60 rounded shadow">

      <p class="mt-4 text-gray-700 text-sm">
        <center> Works on PhonePe, Google Pay, Paytm & all UPI apps.</center>
       
      </p>
    </div>

  </div>
</section>

    <!-- GALLERY -->
    <section id="gallery" class="py-16 bg-orange-50">
      <div class="max-w-6xl mx-auto px-6">
        <h2 class="text-3xl font-bold text-center text-orange-600 mb-8">Gallery</h2>
        <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4">
          <img src="IMG-20251121-WA0004 dog.jpg" alt="g1" class="gallery-img rounded shadow cursor-pointer" data-full="https://via.placeholder.com/1200x900?text=Rescue+1">
          <img src="MixCollage-21-Nov-2025-07-53-PM-643.jpg" alt="g2" class="gallery-img rounded shadow cursor-pointer" data-full="https://via.placeholder.com/1200x900?text=Rescue+2">
         <!----<img src="http://via.placeholder.com/800x600?text=Adoption" alt="g3" class="gallery-img rounded shadow cursor-pointer" data-full="https://via.placeholder.com/1200x900?text=Adoption">
          <img src="https://via.placeholder.com/800x600?text=Volunteer+Moments" alt="g4" class="gallery-img rounded shadow cursor-pointer" data-full="https://via.placeholder.com/1200x900?text=Volunteer+Moments">
          <img src="https://via.placeholder.com/800x600?text=Feeding+Drive" alt="g5" class="gallery-img rounded shadow cursor-pointer" data-full="https://via.placeholder.com/1200x900?text=Feeding+Drive">
          <img src="https://via.placeholder.com/800x600?text=Before+After" alt="g6" class="gallery-img rounded shadow cursor-pointer" data-full="https://via.placeholder.com/1200x900?text=Before+After">-->
        </div>
      </div>

      <!-- Lightbox Modal -->
      <div id="lightbox" class="hidden fixed inset-0 z-50 flex items-center justify-center">
        <div class="absolute inset-0 modal-backdrop"></div>
        <div class="relative max-w-4xl w-full p-4 z-60">
          <img id="lightboxImg" src="" class="w-full rounded shadow max-h-[80vh] object-contain">
          <button id="closeLightbox" class="absolute top-2 right-2 bg-white/80 rounded-full p-2">✕</button>
        </div>
      </div>

    </section>

    <!-- CONTACT -->
    <section id="contact" class="py-16 bg-white">
      <div class="max-w-6xl mx-auto px-6">
        <h2 class="text-3xl font-bold text-center text-orange-600 mb-6">Contact Us</h2>
        <div class="grid md:grid-cols-2 gap-8">
          <div class="space-y-2">
            <p><strong>Email:</strong> bejubaansewat@gmail.com</p>
            <p><strong>Phone / WhatsApp:</strong> +91-7291955060</p>
            <p><strong>Address:</strong> (Add your city/local address here)</p>
            <div class="mt-4">
              <a href="https://www.instagram.com/bejubaansewa/#" target="_blank"
   style="display:inline-flex; align-items:center; gap:10px; 
          padding:10px 18px; background:#E1306C; color:white; 
          border-radius:10px; text-decoration:none; font-size:18px;">
   <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" 
        width="25" alt="Instagram">
   Instagram
</a>
<a href="https://www.facebook.com/Bejubaansewa/#" target="_blank"
   style="display:inline-flex; align-items:center; gap:10px; 
          padding:10px 18px; background:#1877F2; color:white; 
          border-radius:10px; text-decoration:none; font-size:18px;">
   <img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Facebook_icon.svg" 
        width="25" alt="Facebook">
   Facebook
</a>

            <!---- <a href="https://www.youtube.com/@" target="_blank"
   style="display:inline-flex; align-items:center; gap:10px; 
          padding:10px 18px; background:#FF0000; color:white; 
          border-radius:10px; text-decoration:none; font-size:18px;">
   <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" 
        width="30" alt="YouTube">
   YouTube
</a>-->

            </div>
          </div>

          <form id="contactForm" class="bg-orange-50 p-6 rounded-lg">
            <input name="name" placeholder="Name" class="w-full p-2 mb-3 rounded border" required>
            <input name="email" placeholder="Email" class="w-full p-2 mb-3 rounded border" required>
            <textarea name="message" placeholder="Message" class="w-full p-2 mb-3 rounded border" rows="4" required></textarea>
            <button type="submit" class="w-full btn-brand py-2 rounded">Send Message</button>
            <p id="contactMsg" class="text-sm mt-3 text-green-600 hidden">Message sent. We'll contact you soon.</p>
          </form>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-orange-500 text-white py-6">
      <div class="max-w-6xl mx-auto px-6 text-center">
        <p>Follow us: Instagram | Facebook | YouTube</p>
        <p class="mt-2 text-sm">&copy; 2025 Bejubaan Seva Trust. Made with ❤️</p>
      </div>
    </footer>

  </main>

  <!-- Floating WhatsApp -->
  <a href="https://wa.me/917291955060?text=Hi%20Bejubaan%20Sewa%20Trust" target="_blank" class="whatsapp-float">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="whatsapp" class="w-14 h-14 rounded-full shadow-lg">
  </a>

  <!-- Scripts -->
  <script>
    // Mobile menu toggle
    const mobileBtn = document.getElementById('mobileBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    mobileBtn.addEventListener('click', ()=> mobileMenu.classList.toggle('hidden'));

    // Sticky header shadow on scroll
    const header = document.getElementById('siteHeader');
    window.addEventListener('scroll', ()=>{
      if(window.scrollY > 20) header.classList.add('scrolled'); else header.classList.remove('scrolled');
    });

    // Volunteer modal
    const volModal = document.getElementById('volModal');
    document.getElementById('openVolunteer').addEventListener('click', ()=> volModal.classList.remove('hidden'));
    document.getElementById('closeVolunteer').addEventListener('click', ()=> volModal.classList.add('hidden'));

    // Volunteer form submit (demo -> replace with Apps Script URL to save to Google Sheets)
    document.getElementById('volForm').addEventListener('submit', function(e){
      e.preventDefault();
      // Example: POST to a Google Apps Script URL (replace below)
      const scriptURL = 'GOOGLE_APPS_SCRIPT_URL'; // <-- replace with your Apps Script Web App URL
      const formData = new FormData(this);

      if(scriptURL === 'GOOGLE_APPS_SCRIPT_URL'){
        // Demo success
        this.reset();
        document.getElementById('volMsg').classList.remove('hidden');
        setTimeout(()=>{ document.getElementById('volMsg').classList.add('hidden'); volModal.classList.add('hidden'); }, 2200);
        return;
      }

      fetch(scriptURL, { method: 'POST', body: formData })
        .then(res=>res.json())
        .then(()=>{
          document.getElementById('volMsg').classList.remove('hidden');
          this.reset();
          setTimeout(()=>{ document.getElementById('volMsg').classList.add('hidden'); volModal.classList.add('hidden'); }, 2200);
        })
        .catch(()=>{
          alert('Submission failed. You can use the Google Form link instead.');
        });
    });

    // Gallery lightbox
    const galleryImgs = document.querySelectorAll('.gallery-img');
    const lightbox = document.getElementById('lightbox');
    const lightboxImg = document.getElementById('lightboxImg');
    const closeLightbox = document.getElementById('closeLightbox');

    galleryImgs.forEach(img => {
      img.addEventListener('click', ()=>{
        lightboxImg.src = img.dataset.full || img.src;
        lightbox.classList.remove('hidden');
      });
    });
    closeLightbox.addEventListener('click', ()=> lightbox.classList.add('hidden'));
    lightbox.addEventListener('click', (e)=>{ if(e.target === lightbox) lightbox.classList.add('hidden') });

    // Contact form demo
    document.getElementById('contactForm').addEventListener('submit', function(e){
      e.preventDefault();
      // Implement backend or Apps Script to handle contact messages; demo success below
      this.reset();
      document.getElementById('contactMsg').classList.remove('hidden');
      setTimeout(()=> document.getElementById('contactMsg').classList.add('hidden'), 2500);
    });

    // Razorpay demo integration (front-end only) - for real implement server order creation
    function openRazorpay(amount){
      if(!amount) amount = 500;
      // For production, generate order on server and use key_id + order_id
      const options = {
        "key": "rzp_test_YOUR_KEY", // <-- replace with your Razorpay key
        "amount": amount * 100,
        "currency": "INR",
        "name": "Bejubaan Seva Trust",
        "description": "Donation",
        "handler": function (response){
          alert('Thank you for donating! Payment ID: ' + response.razorpay_payment_id);
        },
        "prefill": {"name":"", "email":"", "contact":""},
        "theme": {"color":"#fb923c"}
      };

      // Load Razorpay script then open
      const rzpScript = document.createElement('script');
      rzpScript.src = 'https://checkout.razorpay.com/v1/checkout.js';
      rzpScript.onload = ()=>{ const rzp = new Razorpay(options); rzp.open(); };
      document.body.appendChild(rzpScript);
    }

    // Expose for buttons
    window.openRazorpay = openRazorpay;
  </script>
</body>
</html>
