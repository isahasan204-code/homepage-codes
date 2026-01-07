


  


Professional Home Services You Can Rely On  


<!-- ===== HOME HERO (FULL-WIDTH) ===== -->
<section class="ehs-hero">
  <div class="ehs-hero-bg" aria-hidden="true"></div>

  <div class="ehs-hero-overlay" aria-hidden="true"></div>

  <div class="ehs-hero-inner">
    <div class="ehs-hero-content">
      <h1>Professional Home Services You Can Rely On</h1>
      <p>Expert home services with years of experience.</p>

      <div class="ehs-hero-actions">
        <a class="ehs-btn ehs-btn-primary" href="tel:+15196972361">Call Us</a>
        <a class="ehs-btn ehs-btn-outline" href="/contact/">Contact Us</a>
      </div>
    </div>
  </div>
</section>

<style>
  .ehs-hero{
    position: relative;
    min-height: 78vh;
    display: grid;
    place-items: center;
    overflow: hidden;
  }

  /* Background image (professional house) */
  .ehs-hero-bg{
    position: absolute;
    inset: 0;
    background-image:
      url("https://plus.unsplash.com/premium_photo-1689609950071-af404daa58a0?q=80&w=687&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D");
    background-size: cover;
    background-position: center;
    transform: scale(1.02);
  }

  /* Dark overlay for readability */
  .ehs-hero-overlay{
    position: absolute;
    inset: 0;
    background:
      linear-gradient(90deg, rgba(0,0,0,0.70) 0%, rgba(0,0,0,0.35) 55%, rgba(0,0,0,0.15) 100%);
  }

  /* Content wrapper */
  .ehs-hero-inner{
    position: relative;
    width: 100%;
    max-width: 1100px;
    padding: 0 16px;
  }

  .ehs-hero-content{
    max-width: 680px;
    color: #fff;
    padding: 20px 0;
  }

  .ehs-hero-content h1{
    font-family: "Playfair Display", serif;
    font-size: 34px;
    line-height: 1.15;
    margin: 0 0 12px 0;
    letter-spacing: 0.2px;
  }

  .ehs-hero-content p{
    font-family: "Inter", system-ui, Arial, sans-serif;
    font-size: 16px;
    line-height: 1.6;
    margin: 0 0 18px 0;
    opacity: 0.92;
    max-width: 56ch;
  }

  .ehs-hero-actions{
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    align-items: center;
  }

  .ehs-btn{
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 12px 18px;
    border-radius: 999px;
    font-family: "Inter", system-ui, Arial, sans-serif;
    font-weight: 800;
    font-size: 14px;
    text-decoration: none;
    border: 1px solid transparent;
    transition: transform .15s ease, opacity .15s ease;
    white-space: nowrap;
  }

  .ehs-btn:hover{
    transform: translateY(-1px);
    opacity: 0.95;
  }

  .ehs-btn-primary{
    background: #c4784a;
    color: #1f140f;
    border-color: rgba(255,255,255,0.18);
  }

  .ehs-btn-outline{
    background: rgba(255,255,255,0.10);
    color: #fff;
    border-color: rgba(255,255,255,0.22);
    backdrop-filter: blur(6px);
  }

  /* Responsive */
  @media (min-width: 768px){
    .ehs-hero{ min-height: 82vh; }
    .ehs-hero-inner{ padding: 0 24px; }
    .ehs-hero-content h1{ font-size: 52px; }
    .ehs-hero-content p{ font-size: 17px; }
  }

  @media (max-width: 420px){
    .ehs-hero-content h1{ font-size: 30px; }
    .ehs-btn{ width: 100%; }
  }
</style>









Professional Home Services You Can Rely On


CSS CODE 



/* FORCE ALL HERO TEXT TO WHITE */
.ehs-hero-content h1,
.ehs-hero-content p {
  color: #ffffff;
}

/* Buttons text color */
.ehs-btn {
  color: #ffffff;
}

/* Primary button – keep background, make text white */
.ehs-btn-primary {
  background: #c4784a;
  color: #ffffff; /* changed to white */
}

/* Outline button – already white but forced */
.ehs-btn-outline {
  color: #ffffff;
  border-color: rgba(255,255,255,0.35);
}






















Serving Your Community



<section class="ehs-community">
  <div class="ehs-community-wrap">
    <div class="ehs-community-card">
      <h2>Serving Your Community</h2>

      <p>
        <strong>Elite Home Services</strong> proudly serves <strong>London, Ontario</strong> and surrounding communities,
        providing reliable and professional home improvement services to local homeowners. Our location allows us to respond
        efficiently and support our clients with dependable, high-quality workmanship.
      </p>

      <p>
        Whether you’re in London or nearby areas, our team is ready to help with a wide range of services, including flooring
        installation, wooden backyard fences, door installation, custom wall décor, wall repairs, fresh painting, and many
        small home improvement projects. We understand local homes, conditions, and expectations, and we tailor every job to
        deliver clean, durable, and well-finished results.
      </p>

      <div class="ehs-chips">
        <span>Flooring Installation</span>
        <span>Wooden Fences</span>
        <span>Door Installation</span>
        <span>Custom Wall Décor</span>
        <span>Wall Repairs</span>
        <span>Fresh Painting</span>
        <span>Small Home Projects</span>
      </div>

      <p class="ehs-community-note">
        At <strong>Elite Home Services</strong>, we are committed to serving our community with honesty, attention to detail,
        and work you can trust.
      </p>
    </div>
  </div>
</section>

<style>
  .ehs-community{
    padding: 44px 16px;
    font-family: Arial, sans-serif;
  }
  .ehs-community-wrap{
    max-width: 1000px;
    margin: 0 auto;
  }
  .ehs-community-card{
    border: 1px solid #e7e7e7;
    border-radius: 16px;
    padding: 22px;
    background: #fff;
  }
  .ehs-community-card h2{
    margin: 0 0 12px 0;
    font-size: 30px;
    line-height: 1.2;
  }
  .ehs-community-card p{
    margin: 0 0 14px 0;
    font-size: 15.5px;
    line-height: 1.75;
    opacity: 0.95;
  }
  .ehs-chips{
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 8px 0 16px 0;
  }
  .ehs-chips span{
    border: 1px solid #e7e7e7;
    background: #fff;
    padding: 8px 10px;
    border-radius: 999px;
    font-size: 13px;
    line-height: 1;
    opacity: 0.95;
  }
  .ehs-community-note{
    margin-top: 8px;
    padding-top: 14px;
    border-top: 1px solid #f0f0f0;
  }
  @media (max-width: 640px){
    .ehs-community-card h2{ font-size: 24px; }
    .ehs-community-card{ padding: 18px; }
  }
</style>













Our Professional Home Services


<section class="ehs-services">
  <div class="ehs-wrap">
    <h2>Our Professional Home Services</h2>
    <p class="ehs-sub">
      Elite Home Services provides clean, reliable home improvement solutions with attention to detail and professional finishing.
    </p>
    <div class="ehs-grid">
      <div class="ehs-card">
        <h3>Painting, Wall Repair &amp; Wood Finishing</h3>
        <p>
          Interior and exterior painting with clean, smooth results. We also provide wall putty, wall repairs,
          and surface corrections for a flawless finish.
        </p>
      </div>
      <div class="ehs-card">
        <h3>Flooring Installation &amp; Removal</h3>
        <p>
          Professional laminate and vinyl flooring installation with proper leveling, precise alignment, and clean finishing.
        </p>
      </div>
      <div class="ehs-card">
        <h3>Fence &amp; Gate Services</h3>
        <p>
          Residential fence and gate installation, repair, and removal — including backyard wooden fencing solutions.
        </p>
      </div>
      <div class="ehs-card">
        <h3>Custom Wall &amp; Room Décor</h3>
        <p>
          Modern TV back wall decoration with clean finishing and optional LED lighting.
        </p>
      </div>
      <div class="ehs-card">
        <h3>Laundry Room Improvement &amp; Organization</h3>
        <p>
          Functional and decorative laundry room upgrades, including shelving and custom solutions.
        </p>
      </div>
      <div class="ehs-card">
        <h3>Small Home Installations</h3>
        <p>
          TV mounting, shelf installation, and a variety of small home improvement services.
        </p>
      </div>
    </div>
    <div class="ehs-footer">
      <div class="ehs-badges">
        <span>On-time Work</span>
        <span>Clean Results</span>
        <span>Fair Pricing</span>
        <span>Customer Satisfaction</span>
      </div>
      <div class="ehs-cta">
        <a class="ehs-btn ehs-btn-white" href="/contact/">Request a Quote</a>
        <a class="ehs-btn ehs-btn-outline" href="mailto:contact@elitehomeservices.ca">Email Us</a>
      </div>
    </div>
  </div>
</section>

<style>
  .ehs-services{
    padding: 48px 16px;
    background-color: #f9f9f9; /* Added a slight background to the section so the white button pops */
  }
  .ehs-wrap{
    max-width: 1100px;
    margin: 0 auto;
    font-family: Arial, sans-serif;
  }
  .ehs-wrap h2{
    margin: 0 0 10px 0;
    font-size: 30px;
    line-height: 1.2;
  }
  .ehs-sub{
    margin: 0 0 26px 0;
    font-size: 16px;
    line-height: 1.6;
    opacity: 0.9;
    max-width: 760px;
  }
  .ehs-grid{
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 16px;
  }
  .ehs-card{
    border: 1px solid #e6e6e6;
    border-radius: 14px;
    padding: 18px;
    background: #fff;
  }
  .ehs-card h3{
    margin: 0 0 10px 0;
    font-size: 18px;
    line-height: 1.3;
  }
  .ehs-card p{
    margin: 0;
    font-size: 14.5px;
    line-height: 1.65;
    opacity: 0.95;
  }
  .ehs-footer{
    margin-top: 20px;
    border-top: 1px solid #eee;
    padding-top: 18px;
    display: flex;
    gap: 16px;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  .ehs-badges{
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }
  .ehs-badges span{
    border: 1px solid #e6e6e6;
    padding: 8px 10px;
    border-radius: 999px;
    font-size: 13px;
    background: #fff;
  }
  .ehs-cta{
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
  }
  .ehs-btn{
    display: inline-block;
    padding: 10px 16px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: 700;
    font-size: 14px;
    transition: all 0.2s ease;
  }
  
  /* THE REQUESTED FIX */
  .ehs-btn-white {
    background: #ffffff; /* White background */
    color: #000000;      /* Black text for readability */
    border: 1px solid #e6e6e6; /* Border so it's visible */
  }

  .ehs-btn-outline{
    background: transparent;
    color: #111;
    border: 1px solid #111;
  }
  
  @media (max-width: 980px){
    .ehs-grid{ grid-template-columns: repeat(2, minmax(0, 1fr)); }
  }
  @media (max-width: 640px){
    .ehs-grid{ grid-template-columns: 1fr; }
    .ehs-wrap h2{ font-size: 24px; }
  }
</style>














about Our business



<section class="ehs-about">
  <div class="ehs-about-wrap">

    <div class="ehs-about-text">
      <h2>About Our Business</h2>

      <p>
        At <strong>Elite Home Services</strong>, we provide professional and dependable home improvement services across
        <strong>London, Ontario</strong> and surrounding areas. We focus on quality workmanship, clean results, and honest
        service on every project.
      </p>

      <p>
        Our services include flooring installation, wooden fence installation for backyards, door installation, and custom
        home décor such as TV wall designs and bedroom décor made to order. We also handle wall repairs and corrections,
        fresh interior painting, and a wide range of small home improvement and installation jobs.
      </p>

      <p>
        We take pride in delivering well-organized, on-time work with attention to detail, ensuring your home looks better,
        functions better, and feels refreshed. With <strong>Elite Home Services</strong>, you can count on reliable service,
        clear communication, and results you can trust.
      </p>
    </div>

    <div class="ehs-about-image">
      <img src="https://media.istockphoto.com/id/941972466/photo/manual-workers-making-construction-for-drywall.jpg?s=612x612&amp;w=0&amp;k=20&amp;c=07h_VZtzggt_MFlm9TiyHNtICzzslm42NeNz2pd783k=" alt="Elite Home Services Home Improvement">
    </div>

  </div>
</section>

<style>
  .ehs-about{
    padding: 44px 16px;
    font-family: Arial, sans-serif;
  }
  .ehs-about-wrap{
    max-width: 1000px;
    margin: 0 auto;
  }
  .ehs-about-text h2{
    margin: 0 0 14px 0;
    font-size: 30px;
    line-height: 1.2;
  }
  .ehs-about-text p{
    margin: 0 0 14px 0;
    font-size: 15.5px;
    line-height: 1.75;
    opacity: 0.95;
  }
  .ehs-about-image{
    margin-top: 22px;
    border-radius: 16px;
    overflow: hidden;
  }
  .ehs-about-image img{
    width: 100%;
    height: 340px;
    object-fit: cover;
    display: block;
  }

  @media (max-width: 640px){
    .ehs-about-text h2{ font-size: 24px; }
    .ehs-about-image img{ height: 220px; }
  }
</style>













(navigation page)

<section class="ehs-nav"> 

  <div class="ehs-nav-wrap"> 

    <a href="/" class="ehs-nav-card"> 

      <img src="https://images.unsplash.com/photo-1570129477492-45c003edd2be?q=80&w=2070&auto=format&fit=crop" alt="Home"> 

      <div class="ehs-nav-overlay"><span>🏠</span><h3>Home</h3></div> 

    </a> 

    <a href="/services/" class="ehs-nav-card"> 

      <img src="https://images.unsplash.com/photo-1676311396794-f14881e9daaa?q=80&w=2070&auto=format&fit=crop" alt="Services"> 

      <div class="ehs-nav-overlay"><span>🛠️</span><h3>Services</h3></div> 

    </a> 

    <a href="/projects/" class="ehs-nav-card"> 

      <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e" alt="Projects"> 

      <div class="ehs-nav-overlay"><span>📐</span><h3>Projects</h3></div> 

    </a> 

    <a href="/gallery/" class="ehs-nav-card"> 

      <img src="https://images.unsplash.com/photo-1505691938895-1758d7feb511" alt="Gallery"> 

      <div class="ehs-nav-overlay"><span>🖼️</span><h3>Gallery</h3></div> 

    </a> 

    <a href="/about/" class="ehs-nav-card"> 

      <img src="https://images.unsplash.com/photo-1571624436279-b272aff752b5?q=80&w=1172&auto=format&fit=crop" alt="About Us"> 

      <div class="ehs-nav-overlay"><span>ℹ️</span><h3>About Us</h3></div> 

    </a> 

    <a href="/contact/" class="ehs-nav-card"> 

      <img src="https://images.unsplash.com/photo-1534536281715-e28d76689b4d?q=80&w=2070&auto=format&fit=crop" alt="Contact"> 

      <div class="ehs-nav-overlay"><span>📞</span><h3>Contact</h3></div> 

    </a> 

    <a href="/faqs/" class="ehs-nav-card"> 

      <img src="https://images.unsplash.com/photo-1652077859695-de2851a95620?q=80&w=880&auto=format&fit=crop" alt="FAQs"> 

      <div class="ehs-nav-overlay"><span>❓</span><h3>FAQs</h3></div> 

    </a> 

    <a href="/customer-reviews/" class="ehs-nav-card"> 

      <img src="https://media.istockphoto.com/id/2218536266/photo/customer-review-satisfaction-feedback-survey-concept-user-give-rating-to-service-experience.jpg?s=612x612&w=0&k=20&c=iLm37Ds4y7BJthzZ6CkDBia20G15HTUdkYCgpsex-vE=" alt="Customer Reviews"> 

      <div class="ehs-nav-overlay"><span>⭐</span><h3>Customer Reviews</h3></div> 

    </a> 

  </div> 

</section> 

  

<style> 

  .ehs-nav{ padding: 44px 16px; font-family: Arial, sans-serif; } 

  .ehs-nav-wrap{ max-width: 1100px; margin: 0 auto; display: grid; grid-template-columns: repeat(2, 1fr); gap: 16px; } 

  .ehs-nav-card{ position: relative; height: 220px; border-radius: 16px; overflow: hidden; text-decoration: none; } 

  .ehs-nav-card img{ width: 100%; height: 100%; object-fit: cover; display: block; } 

  .ehs-nav-overlay{ position: absolute; inset: 0; background: rgba(0,0,0,0.45); color: #fff; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 6px; text-align: center; } 

  .ehs-nav-overlay span{ font-size: 28px; } 

  .ehs-nav-overlay h3{ margin: 0; font-size: 20px; font-weight: 700; } 

  .ehs-nav-card:hover .ehs-nav-overlay{ background: rgba(0,0,0,0.6); } 

  @media (max-width: 700px){ .ehs-nav-wrap{ grid-template-columns: 1fr; } } 

</style>













(Photo Gallery - 18 Photos)


<section class="ehs-gallery"> 

  <div class="ehs-gallery-wrap"> 

    <h2>Photo Gallery</h2> 

    <p class="ehs-gallery-intro">Take a look at our portfolio to see the precision and care we bring to every project.</p> 

    <div class="ehs-gallery-grid" id="ehsGalleryGrid"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/1200x/30/52/5d/30525dad8f1b4da0ed38c44ed999d458.jpg" alt="Photo 1"> 

<img class="ehs-thumb" src="https://i.pinimg.com/736x/ca/b3/23/cab323a621c0469982f4f2c448ff737a.jpg" alt="Photo 19">

<img class="ehs-thumb" src="https://i.pinimg.com/1200x/eb/4a/68/eb4a68d6f83b033d70bc01a4bf792a98.jpg" alt="Photo 20">

<img class="ehs-thumb" src="https://i.pinimg.com/736x/49/2e/a6/492ea68084095a27c9a6110198ed6fef.jpg" alt="Photo 21">

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/02/b9/c5/02b9c5ca5ec6c5bc2fa994185f33d536.jpg" alt="Photo 2"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/42/28/c5/4228c55f45c598e441713bf4b4202780.jpg" alt="Photo 3"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/6b/5a/e8/6b5ae8ddbe509e39d43e20b9abb3d044.jpg" alt="Photo 4"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/55/fb/7b/55fb7bf83dd92fc0e43fbaa1a6795ac3.jpg" alt="Photo 5"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/3d/3d/ef/3d3defd93e239c0447efef6095d0863d.jpg" alt="Photo 6"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/0a/27/42/0a27424c216871b6e2273e35462cf876.jpg" alt="Photo 7"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/1200x/71/a7/e5/71a7e5c9efab13548b5da13c20329e08.jpg" alt="Photo 8"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/1200x/df/e6/c0/dfe6c01f83fe30a21cb4fd207605a76a.jpg" alt="Photo 9"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/1200x/1d/95/35/1d953551c9dc8eba7806a1bc2efb3bc5.jpg" alt="Photo 10"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/ec/4f/2c/ec4f2c0506e1227df1deaa6f51872719.jpg" alt="Photo 11"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/1200x/04/d1/cd/04d1cde7775cbd265826384451a535fd.jpg" alt="Photo 12"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/28/3b/d9/283bd9483aef910b00b482f729420f23.jpg" alt="Photo 13"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/1200x/85/d1/7a/85d17a275962c9628107f3b35b93e850.jpg" alt="Photo 14"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/fd/17/21/fd172103fa8b8c1ba840ab5818e3ae9a.jpg" alt="Photo 15"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/53/f7/45/53f745ec8be773bca7b1d9d0047c5bbc.jpg" alt="Photo 16"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/736x/83/a7/47/83a747cc100509318ac5eaf80fb1399d.jpg" alt="Photo 17"> 

      <img class="ehs-thumb" src="https://i.pinimg.com/1200x/57/5d/e1/575de1eed160baf017bc6bd84ae6e1e8.jpg" alt="Photo 18"> 

    </div> 

  </div> 

</section> 

  

<div class="ehs-lightbox" id="ehsLightbox"> 

  <button class="ehs-lb-close" id="ehsLbClose">✕</button> 

  <button class="ehs-lb-arrow ehs-lb-prev" id="ehsLbPrev">‹</button> 

  <figure class="ehs-lb-figure"><img id="ehsLbImg" src=""></figure> 

  <button class="ehs-lb-arrow ehs-lb-next" id="ehsLbNext">›</button> 

  <div class="ehs-lb-counter" id="ehsLbCounter"></div> 

</div> 

  

<style> 

  .ehs-gallery{ padding: 48px 16px; font-family: Arial, sans-serif; color: #222; } 

  .ehs-gallery-wrap{ max-width: 1100px; margin: 0 auto; } 

  .ehs-gallery h2{ margin: 0 0 10px; font-size: 30px; } 

  .ehs-gallery-intro{ margin: 0 0 22px; font-size: 16px; line-height: 1.7; } 

  .ehs-gallery-grid{ display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; } 

  .ehs-thumb{ width: 100%; height: 160px; object-fit: cover; border-radius: 12px; cursor: pointer; border: 1px solid #eee; transition: transform .2s ease; } 

  .ehs-thumb:hover{ transform: scale(1.02); } 

  .ehs-lightbox{ position: fixed; inset: 0; background: rgba(0,0,0,.82); display: none; align-items: center; justify-content: center; z-index: 99999; padding: 16px; } 

  .ehs-lightbox.is-open{ display: flex; } 

  .ehs-lb-figure img{ max-width: 100%; max-height: 80vh; border-radius: 14px; box-shadow: 0 8px 30px rgba(0,0,0,.35); } 

  .ehs-lb-close, .ehs-lb-arrow{ position: absolute; background: rgba(255,255,255,.15); color: #fff; border: 0; cursor: pointer; border-radius: 999px; display: flex; align-items: center; justify-content: center; } 

  .ehs-lb-close{ top: 14px; right: 14px; width: 44px; height: 44px; font-size: 22px; } 

  .ehs-lb-arrow{ top: 50%; transform: translateY(-50%); width: 54px; height: 54px; font-size: 38px; } 

  .ehs-lb-prev{ left: 14px; } .ehs-lb-next{ right: 14px; } 

  .ehs-lb-counter{ position: absolute; bottom: 14px; left: 50%; transform: translateX(-50%); color: #fff; background: rgba(255,255,255,.12); padding: 6px 10px; border-radius: 999px; font-size: 14px; } 

</style> 

  

<script> 

(function(){ 

  const grid = document.getElementById('ehsGalleryGrid'); 

  const thumbs = Array.from(grid.querySelectorAll('.ehs-thumb')); 

  const lb = document.getElementById('ehsLightbox'); 

  const lbImg = document.getElementById('ehsLbImg'); 

  const lbCounter = document.getElementById('ehsLbCounter'); 

  let index = 0; 

  function openLightbox(i){ index = i; lb.classList.add('is-open'); render(); } 

  function render(){ 

    lbImg.src = thumbs[index].src; 

    lbCounter.textContent = (index + 1) + ' / ' + thumbs.length; 

  } 

  thumbs.forEach((img, i) => img.onclick = () => openLightbox(i)); 

  document.getElementById('ehsLbClose').onclick = () => lb.classList.remove('is-open'); 

  document.getElementById('ehsLbPrev').onclick = () => { index = (index - 1 + thumbs.length) % thumbs.length; render(); }; 

  document.getElementById('ehsLbNext').onclick = () => { index = (index + 1) % thumbs.length; render(); }; 

  lb.onclick = (e) => { if(e.target === lb) lb.classList.remove('is-open'); }; 

})(); 

</script>











 (25 Reviews) 


 <section class="ehs-reviews"> 

  <div class="ehs-reviews-wrap"> 

    <h2>Our Reviews</h2> 

    <p class="ehs-reviews-intro">Our customers appreciate the quality of our work, our attention to detail, and our commitment to clean, professional finishing. From the first consultation to the final result, we focus on delivering reliable service, clear communication, and results that homeowners can feel confident about. Their feedback reflects the care we put into every project, no matter the size.</p> 

    <div class="ehs-reviews-grid" id="ehsReviewsGrid"> 

      <div class="ehs-review"><strong>Michael Carter</strong><div class="ehs-stars">★★★★★</div><p>Great work on our laminate flooring. Clean cuts and finished on time.</p></div> 

      <div class="ehs-review"><strong>Sarah Mitchell</strong><div class="ehs-stars">★★★★★</div><p>They repaired our walls and repainted the living room. Perfect finish.</p></div> 

      <div class="ehs-review"><strong>Daniel Thompson</strong><div class="ehs-stars">★★★★★</div><p>Hired for a backyard wooden fence. Solid build, straight lines.</p></div> 

      <div class="ehs-review"><strong>Emily Johnson</strong><div class="ehs-stars">★★★★★</div><p>Professional and honest. Clean edges and no mess left behind.</p></div> 

      <div class="ehs-review"><strong>Jason Walker</strong><div class="ehs-stars">★★★★★</div><p>Door installation was done perfectly. Attention to detail is great.</p></div> 

      <div class="ehs-review"><strong>Olivia Parker</strong><div class="ehs-stars">★★★★★</div><p>Removed old flooring and installed vinyl. Fast and clean.</p></div> 

      <div class="ehs-review"><strong>Andrew Lewis</strong><div class="ehs-stars">★★★★★</div><p>TV wall décor came out amazing with clean finishing.</p></div> 

      <div class="ehs-review"><strong>Hannah Reed</strong><div class="ehs-stars">★★★★★</div><p>Interior painting and wall repairs. Very respectful team.</p></div> 

      <div class="ehs-review"><strong>David Brooks</strong><div class="ehs-stars">★★★★★</div><p>Wood staining on our stairs looks beautiful. No streaks.</p></div> 

      <div class="ehs-review"><strong>Sophia Adams</strong><div class="ehs-stars">★★★★★</div><p>Upgraded our laundry room with better storage. Great ideas.</p></div> 

  

      <div class="ehs-review ehs-hidden"><strong>Ryan Collins</strong><div class="ehs-stars">★★★★★</div><p>Exterior paint looks durable and even. Sharp results.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Natalie Bennett</strong><div class="ehs-stars">★★★★★</div><p>Very reliable service. Finished the job as promised.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Kevin Rogers</strong><div class="ehs-stars">★★★★★</div><p>Installed new baseboards. Everything looks clean.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Grace Phillips</strong><div class="ehs-stars">★★★★★</div><p>Corrected uneven wall areas and repainted perfectly.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Justin Evans</strong><div class="ehs-stars">★★★★★</div><p>Fence repair and gate adjustment done properly.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Chloe Murphy</strong><div class="ehs-stars">★★★★★</div><p>Helped mount our TV and install shelves. Secure work.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Brandon Scott</strong><div class="ehs-stars">★★★★★</div><p>Vinyl flooring installation was excellent. No gaps.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Megan Turner</strong><div class="ehs-stars">★★★★★</div><p>Painted our hallway and fixed cracks. Perfect results.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Ethan Howard</strong><div class="ehs-stars">★★★★★</div><p>Custom bedroom décor turned out beautiful.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Lily Cooper</strong><div class="ehs-stars">★★★★★</div><p>On-time work and exceeded our expectations.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Noah Bailey</strong><div class="ehs-stars">★★★★★</div><p>Installed a new door and did finishing. Aligned perfectly.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Ava Richardson</strong><div class="ehs-stars">★★★★★</div><p>Smooth walls, clean corners, and no paint splatter.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Logan Price</strong><div class="ehs-stars">★★★★★</div><p>Backyard fence installation was strong and looks fantastic.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Zoe Watson</strong><div class="ehs-stars">★★★★★</div><p>Updated laundry room. Great workmanship.</p></div> 

      <div class="ehs-review ehs-hidden"><strong>Tyler King</strong><div class="ehs-stars">★★★★★</div><p>Small home improvements done right. Respectful team.</p></div> 

 <div class="ehs-review ehs-hidden"><strong>Nabush Alwadi</strong><div class="ehs-stars">★★★★★</div><p>Exterior paint looks durable and even. Sharp results.</p></div> 

<div class="ehs-review"><strong>Mohammed Alhassan</strong><div class="ehs-stars">★★★★★</div><p>Door installation was done perfectly. Attention to detail is great.</p></div>

    </div> 

    <div class="ehs-reviews-actions"> 

      <button class="ehs-more-btn" id="ehsToggleReviews">See more</button> 

    </div> 

  </div> 

</section> 

  

<style> 

  .ehs-reviews{ padding: 48px 16px; font-family: Arial, sans-serif; } 

  .ehs-reviews-wrap{ max-width: 1100px; margin: 0 auto; } 

  .ehs-reviews-grid{ display: grid; grid-template-columns: 1fr 1fr; gap: 14px; } 

  .ehs-review{ background: #fbf9f6; border: 1px solid #e5ddd3; border-radius: 14px; padding: 16px; } 

  .ehs-stars{ color: #f4b400; font-size: 16px; margin: 5px 0; } 

  .ehs-hidden{ display: none; } 

  .ehs-reviews-actions{ margin-top: 16px; display: flex; justify-content: center; } 

  .ehs-more-btn{ padding: 10px 18px; border-radius: 12px; border: 0; background: #222; color: #fff; font-weight: 800; cursor: pointer; } 

  @media (max-width: 768px){ .ehs-reviews-grid{ grid-template-columns: 1fr; } } 

</style> 

  

<script> 

(function(){ 

  const btn = document.getElementById('ehsToggleReviews'); 

  const hidden = document.querySelectorAll('.ehs-review.ehs-hidden'); 

  let expanded = false; 

  btn.onclick = () => { 

    expanded = !expanded; 

    hidden.forEach(el => el.style.display = expanded ? 'block' : 'none'); 

    btn.textContent = expanded ? 'See less' : 'See more'; 

  }; 

})(); 

</script>












(Why Choose Us) 


<section class="ehs-why">  

  

  <div class="ehs-why-wrap">  

  

    <div class="ehs-why-grid">  

  

      <div class="ehs-why-img">  

  

        <img src="https://media.istockphoto.com/id/2190057704/photo/man-painting-living-room-wall-during-apartment-renovation.jpg?s=612x612&w=0&k=20&c=YdjDxlzP_PRNjX_yERTALgepZALghon-9H4PUF52ygw=" alt="Quality Work">  

  

      </div>  

  

      <div class="ehs-why-text">  

  

        <h2>Why Choose Us</h2>  

  

        <p>We focus on clean workmanship, reliability, and attention to every detail.</p>  

  

        <ul class="ehs-why-list">  

  

          <li><strong>✅ Professional Finishing:</strong> We prepare every surface properly and finish each job with attention to detail, ensuring a clean, refined, and long-lasting outcome. 

.</li>  

  

          <li><strong>✅ Diverse Services:</strong> Our services cover multiple areas of home improvement, allowing you to handle different projects with one reliable team. This ensures consistent quality and a smoother experience. 

</li>  

  

          <li><strong>✅ On-Time Delivery:</strong> We value your time and organize our work to stay on schedule. From start to finish, we aim for smooth progress and timely completion on every project. 

.</li>  

  

          <li><strong>✅ Fair Pricing:</strong>We provide clear and upfront pricing so you know exactly what to expect before the work begins. Our quotes are straightforward, fair, and based on the scope of your project. 

.</li>  

  

        </ul>  

  

      </div>  

  

    </div>  

  

  </div>  

  

</section>  

  

   

  

<style>  

  

  .ehs-why { padding: 60px 16px; }  

  

  .ehs-why-wrap { max-width: 1100px; margin: 0 auto; }  

  

  .ehs-why-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; align-items: center; }  

  

  .ehs-why-img img { width: 100%; border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }  

  

  .ehs-why-text h2 { font-size: 32px; margin-bottom: 15px; }  

  

  .ehs-why-list { list-style: none; padding: 0; }  

  

  .ehs-why-list li { padding: 12px; background: #f9f9f9; margin-bottom: 10px; border-radius: 8px; border-left: 4px solid #222; }  

  

  @media (max-width: 850px) { .ehs-why-grid { grid-template-columns: 1fr; text-align: center; } }  

  

</style>





