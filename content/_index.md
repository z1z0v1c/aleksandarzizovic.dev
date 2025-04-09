---
weight: 2
layout: hextra-home
---

<div class="hx:flex hx:flex-col hx:items-center hx:justify-center hx:max-w-screen-xl hx:mx-auto hx:pt-12 hx:px-4">

  <!-- Profile Image -->
<img src="/images/A.png" alt="GitHub Profile Picture" style="width: 250px; height: auto; border-radius: 50%; margin-bottom: 1rem;" />

<!-- Headline -->
{{< hextra/hero-headline >}}
Let’s build something great together!
{{< /hextra/hero-headline >}}

  <!-- Subtitle -->
  <div class="hx:mt-4 hx:text-center hx:mb-6">
    {{< hextra/hero-subtitle >}}
      Hi, I’m Aleksandar - a Backend Developer based in Belgrade, Serbia.
      Passionate about clean code, distributed systems, and solving real-world challenges.
    {{< /hextra/hero-subtitle >}}
  </div>

  <div style="display: flex; justify-content: center; gap: 16px; align-items: center; margin: 1rem 0;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" height="32" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" title="C#" height="32" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go" title="Go" height="32" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="SQL" title="SQL" height="32" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" height="32" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" height="32" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" title="Linux" height="32" />
  </div>

  <!-- Buttons -->
  <div class="hx:flex hx:flex-wrap hx:gap-4 hx:justify-center hx:mb-12">
    {{< hextra/hero-button text="More About Me" link="about" >}}
    {{< hextra/hero-button text="Get In Touch" link="contact" >}}
  </div>

</div>

<!-- Divider -->
<hr class="hx:border-gray-700 hx:my-12" />

<!-- Explore Section -->
<div class="hx:max-w-screen-xl hx:mx-auto hx:px-4">

  <h2 class="hx:text-3xl hx:font-bold hx:underline hx:mb-6 hx:text-center">Explore</h2>

{{< cards class="hx:flex hx:justify-center hx:gap-6" >}}
{{< card link="projects" title="Projects" icon="folder-open" >}}
{{< card link="posts" title="Posts" icon="document-text" >}}
{{< /cards >}}

</div>
