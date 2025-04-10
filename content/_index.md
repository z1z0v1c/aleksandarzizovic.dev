---
weight: 2
layout: hextra-home
---
<style>
  .tech-scroll {
    overflow: hidden;
    width: 77%;
    max-width: 100vw;
  }

  .tech-scroll-track {
    display: flex;
    gap: 2rem;
    animation: scroll-left 60s linear infinite;
  }

  @keyframes scroll-left {
    0% {
      transform: translateX(0%);
    }
    100% {
      transform: translateX(-50%);
    }
  }

  .tech-scroll-track img {
    height: 100px;
  }

  .tech-scroll-track:hover {
    animation-play-state: paused;
  }

  .experience-container {
    width: 800px;
    max-width: 900px;
    margin: 0 auto;
    text-align: center;
  }

  .experience-entry {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 15px;
    margin-bottom: 20px;
    padding: 15px;
    border-radius: 8px;
    background-color: #1a1a1a;
    border: 1px solid #444;
    justify-content: space-between;
    gap: 10px;
    display: flex;
    justify-content: space-between;
    gap: 10px;
    width: 100%;
  }

  .experience-entry h3, .experience-entry h4, .experience-entry p {
    margin: 0;
  }

  .role {
    color: #fff;
    font-size: 1.1rem;
    font-weight: bold;
  }

  .company {
    color: #ccc;
    font-size: 1rem;
  }

  .date {
    color: #aaa;
    font-style: italic;
    font-size: 0.9rem;
  }

  .divider {
    width: 50%;
    margin: 15px auto;
    border: 0;
    border-top: 1px solid #444;
  }

  /* Mobile Responsiveness */
  @media (max-width: 768px) {
    .experience-entry {
      flex-direction: column;
      text-align: left;
    }

    .divider {
      width: 80%;
    }
  }

  .experience-entry > * {
    flex: 1;
  }

  .experience-entry h3 {
    text-align: left;
  }

  .experience-entry span.company {
    text-align: center;
  }

  .experience-entry span.date {
    text-align: right;
  }
</style>

<div class="hx:flex hx:gap-4 hx:flex-col hx:items-center hx:justify-center hx:max-w-screen-xl hx:mx-auto hx:pt-12 hx:px-4">

  <!-- Profile Image -->
  <img src="/images/profile-photo.jpg" alt="Profile Photo" style="width: 250px; height: auto; border-radius: 50%; margin-bottom: 1rem;" />

  <!-- Small Description -->
  <div class="hx:mt-4 hx:text-center hx:mb-6">
    {{< hextra/hero-subtitle >}}
      Hi, I’m Aleksandar - a Backend Developer based in Belgrade, Serbia.
      Passionate about clean code, distributed systems, and solving real-world challenges.
    {{< /hextra/hero-subtitle >}}
  </div>

  <!-- Headline -->
  {{< hextra/hero-headline >}}
  Let’s build something great together!
  {{< /hextra/hero-headline >}}

  <!-- Divider -->
  <hr class="hx:border-gray-701 hx:my-36" />
  <hr class="hx:border-gray-701 hx:my-12" />
  <hr class="hx:border-gray-701 hx:my-12" />

  <!-- Stack Icons -->
  <div class="tech-scroll">
    <div class="tech-scroll-track">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" title="C#" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go" title="Go" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="SQL" title="SQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" title="Linux" />
      <!-- Duplicate icons to make the loop seamless -->
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" title="C#" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go" title="Go" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="SQL" title="SQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" title="Linux" />
    </div>
  </div>
  
  <!-- Divider -->
  <hr class="hx:border-gray-701 hx:my-12" />
  <hr class="hx:border-gray-701 hx:my-12" />
  <hr class="hx:border-gray-701 hx:my-12" />

  <!-- Work history -->
  <div class="experience-container">
    <!-- Experience Entry 1 -->
    <div class="experience-entry">
      <h3 class="role">Backend Developer</h3>
      <span class="company">Fincore Ltd</span>
      <span class="date">December 2023 – July 2024</span>
    </div>
    <hr class="divider">
    <!-- Experience Entry 2 -->
    <div class="experience-entry">
      <h3 class="role">Software Developer</h3>
      <span class="company">Trace One</span>
      <span class="date">May 2022 – December 2023</span>
    </div>
    <hr class="divider">
    <!-- Experience Entry 3 -->
    <div class="experience-entry">
      <h3 class="role">Junior Software Developer</h3>
      <span class="company">OtaCo Engineering</span>
      <span class="date">November 2019 – May 2022</span>
    </div>
    <hr class="divider">
    <!-- Experience Entry 4 -->
    <div class="experience-entry">
      <h3 class="role">Web Development Intern</h3>
      <span class="company">msg global solutions</span>
      <span class="date">August 2019 – September 2019</span>
    </div>
    <hr class="divider">
    <!-- Experience Entry 5 -->
    <div class="experience-entry">
      <h3 class="role">Software QA Intern</h3>
      <span class="company">Endava</span>
      <span class="date">October 2018 – November 2018</span>
    </div>
  </div>

  <!-- Divider -->
  <hr class="hx:border-gray-701 hx:my-12" />
  <hr class="hx:border-gray-701 hx:my-12" />
  <hr class="hx:border-gray-701 hx:my-12" />

  <!-- Buttons -->
  <div class="hx:flex hx:flex-wrap hx:gap-4 hx:justify-center hx:mb-12">
    {{< hextra/hero-button text="More About Me" link="about" >}}
    {{< hextra/hero-button text="My Projects" link="projects" >}}
    {{< hextra/hero-button text="Get In Touch" link="contact" >}}
  </div>
</div>
<script>
  // Optional JavaScript to adjust animation duration based on actual content width
  window.addEventListener('load', function() {
    const ticker = document.querySelector('.tech-scroll-track');
    const tickerWidth = ticker.offsetWidth;
    const containerWidth = document.querySelector('.carousel-container').offsetWidth;
    // Adjust animation duration based on content width for consistent speed
    const speed = 20; // seconds for one complete cycle
    const ratio = tickerWidth / containerWidth;
    ticker.style.animationDuration = (speed * ratio / 2) + 's';
  });
</script>
