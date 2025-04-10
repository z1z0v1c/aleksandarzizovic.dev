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
    animation: scroll-right 60s linear infinite;
  }
</style>
<div class="hx:flex hx:gap-4 hx:flex-col hx:items-center hx:justify-center hx:max-w-screen-xl hx:mx-auto hx:pt-12 hx:px-4">
  <!-- Profile Image -->
  <img src="/images/profile-photo.jpg" alt="Profile Photo" style="width: 250px; height: auto; border-radius: 50%; margin-bottom: 1rem;" />
  <!-- Subtitle -->
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
  <hr class="hx:border-gray-701 hx:my-12" />
  <hr class="hx:border-gray-701 hx:my-12" />
  <hr class="hx:border-gray-701 hx:my-12" />
  <!-- Stack Icons -->
  <div class="tech-scroll">
    <div class="tech-scroll-track">
      <!-- Duplicate icons to make the loop seamless -->
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" title="C#" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go" title="Go" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="SQL" title="SQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" title="Linux" />
      <!-- Repeat for seamless scroll -->
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
  <!-- Experience -->
  <div class="experience-container" style="max-width: 700px; margin: 0 auto; text-align: center;">
    <!-- Experience Entry 1 -->
    <div class="experience-entry" style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 10px; margin-bottom: 5px;">
      <h3 style="margin: 0; color: #333;">Backend Developer</h3>
      <span style="color: #666;">|</span>
      <h4 style="margin: 0; font-weight: normal; color: #555;">Fincore Ltd</h4>
      <span style="color: #666;">|</span>
      <p style="margin: 0; font-style: italic; color: #777;">December 2023 - July 2024</p>
    </div>
    <!-- Border -->
    <hr style="width: 50%; margin: 15px auto; border: 0; border-top: 1px solid #ddd;">
    <!-- Experience Entry 2 - inline format -->
    <div class="experience-entry" style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 10px; margin-bottom: 5px;">
      <h3 style="margin: 0; color: #333;">Software Developer</h3>
      <span style="color: #666;">|</span>
      <h4 style="margin: 0; font-weight: normal; color: #555;">Trace One</h4>
      <span style="color: #666;">|</span>
      <p style="margin: 0; font-style: italic; color: #777;">May 2022 - December 2023</p>
    </div>
    <!-- Border -->
    <hr style="width: 50%; margin: 15px auto; border: 0; border-top: 1px solid #ddd;">
    <!-- Experience Entry 3 -->
    <div class="experience-entry" style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 10px; margin-bottom: 5px;">
      <h3 style="margin: 0; color: #333;">Junior Software Developer</h3>
      <span style="color: #666;">|</span>
      <h4 style="margin: 0; font-weight: normal; color: #555;">OtaCo Engineering</h4>
      <span style="color: #666;">|</span>
      <p style="margin: 0; font-style: italic; color: #777;">November 2019 - May 2022</p>
    </div>
    <!-- Border -->
    <hr style="width: 50%; margin: 15px auto; border: 0; border-top: 1px solid #ddd;">
    <!-- Experience Entry 4 -->
    <div class="experience-entry" style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 10px; margin-bottom: 5px;">
      <h3 style="margin: 0; color: #333;">Web Development Intern</h3>
      <span style="color: #666;">|</span>
      <h4 style="margin: 0; font-weight: normal; color: #555;">msg global solutions</h4>
      <span style="color: #666;">|</span>
      <p style="margin: 0; font-style: italic; color: #777;">August 2019 - September 2019</p>
    </div>
    <!-- Border -->
    <hr style="width: 50%; margin: 15px auto; border: 0; border-top: 1px solid #ddd;">
    <!-- Experience Entry 5 -->
    <div class="experience-entry" style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 10px; margin-bottom: 5px;">
      <h3 style="margin: 0; color: #333;">Software Quality Assurance Intern</h3>
      <span style="color: #666;">|</span>
      <h4 style="margin: 0; font-weight: normal; color: #555;">Endava</h4>
      <span style="color: #666;">|</span>
      <p style="margin: 0; font-style: italic; color: #777;">October 2018 - November 2018</p>
    </div>
  </div>
  <!-- Divider -->
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
