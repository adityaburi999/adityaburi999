<!--
Directory suggestion:
  ./assets/banner.png
  ./assets/avatar.png
  ./assets/legalguard-cover.png
  ./assets/project-1.png
  ./assets/project-2.png
  ./assets/project-3.png

  ./assets/icons/github.svg
  ./assets/icons/x.svg
  ./assets/icons/discord.svg
  ./assets/icons/globe.svg
  ./assets/icons/mail.svg

Notes:
- Keep images optimized (≤ 150–300 KB) for fast loading.
- All links below use placeholders so the file contains no external URLs by default.
- Replace '#' with actual links when ready.
-->

<!-- Animated hero banner (pure inline SVG, no external requests) -->
<p align="center">
  <svg width="100%" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Aditya — Web Developer">
    <defs>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#7C3AED">
          <animate attributeName="stop-color" values="#7C3AED;#06B6D4;#22C55E;#F59E0B;#7C3AED" dur="12s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#06B6D4">
          <animate attributeName="stop-color" values="#06B6D4;#22C55E;#F59E0B;#7C3AED;#06B6D4" dur="12s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>

      <radialGradient id="glow" cx="50%" cy="50%" r="60%">
        <stop offset="0%" stop-color="#ffffff" stop-opacity="0.35"/>
        <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
      </radialGradient>

      <filter id="soft">
        <feGaussianBlur stdDeviation="8"/>
      </filter>
    </defs>

    <!-- Animated gradient background -->
    <rect width="1200" height="260" fill="url(#grad)"/>
    <!-- Soft moving glows -->
    <circle cx="200" cy="60" r="120" fill="url(#glow)" filter="url(#soft)">
      <animate attributeName="cx" values="200;1000;200" dur="18s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="60;200;60" dur="16s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1000" cy="200" r="140" fill="url(#glow)" filter="url(#soft)">
      <animate attributeName="cx" values="1000;180;1000" dur="20s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="200;80;200" dur="14s" repeatCount="indefinite"/>
    </circle>

    <!-- Headline -->
    <g>
      <text x="50%" y="46%" text-anchor="middle" fill="#0B1021" opacity="0.18" style="font: 900 64px/1.1 'Segoe UI', Inter, system-ui, -apple-system, sans-serif;">ADITYA</text>
      <text x="50%" y="46%" text-anchor="middle" fill="#FFFFFF" style="font: 900 64px/1.1 'Segoe UI', Inter, system-ui, -apple-system, sans-serif;">
        ADITYA
        <animate attributeName="letter-spacing" values="0;4;0" dur="8s" repeatCount="indefinite"/>
      </text>
    </g>

    <!-- Subheadline typing effect (stroke reveal) -->
    <g>
      <text x="50%" y="64%" text-anchor="middle" fill="none" stroke="#FFFFFF" stroke-width="1.2" style="font: 500 20px/1 'Segoe UI', Inter, system-ui, -apple-system, sans-serif; letter-spacing: 0.6px;">
        Web developer • Student builder • Shipping useful web experiences
        <animate attributeName="stroke-dasharray" values="0,800;800,0;0,800" dur="10s" repeatCount="indefinite"/>
      </text>
    </g>

    <!-- Scroll cue -->
    <g transform="translate(600, 225)">
      <rect x="-16" y="-6" rx="8" ry="8" width="32" height="22" fill="#ffffff22" stroke="#ffffff55"/>
      <circle r="3" fill="#fff">
        <animate attributeName="cy" values="-2;4;-2" dur="1.8s" repeatCount="indefinite"/>
      </circle>
    </g>
  </svg>
</p>

<!-- Avatar + name block -->
<p align="center">
  <img src="./assets/avatar.png" alt="Aditya avatar" width="96" height="96" style="border-radius: 50%; box-shadow: 0 6px 18px rgba(0,0,0,0.2);" />
</p>

<h1 align="center">Aditya</h1>
<p align="center">Web developer • Student builder • Minimalist deployments</p>

<!-- Social row (inline SVG icons, links left as '#') -->
<p align="center">
  <a href="#" title="Portfolio">
    <!-- Globe icon -->
    <svg width="18" height="18" viewBox="0 0 24 24" role="img" aria-label="Website" style="vertical-align: -3px;">
      <path fill="currentColor" d="M12 2a10 10 0 1 0 .001 20.001A10 10 0 0 0 12 2zm0 2c1.9 0 3.63.66 5 1.76C15.9 7.06 14.07 8 12 8s-3.9-.94-5-2.24A7.95 7.95 0 0 1 12 4zm0 16a7.95 7.95 0 0 1-5-1.76C8.1 16.94 9.93 16 12 16s3.9.94 5 2.24A7.95 7.95 0 0 1 12 20zm-7-8c0-.69.1-1.36.29-2h3.42A17.2 17.2 0 0 0 8 12c0 .69.05 1.36.14 2H5.29A7.97 7.97 0 0 1 5 12zm11.86-2h3.42c.18.64.29 1.31.29 2s-.1 1.36-.29 2h-3.42c.09-.64.14-1.31.14-2s-.05-1.36-.14-2zM10 12c0-.74.05-1.43.14-2h3.72c.09.57.14 1.26.14 2s-.05 1.43-.14 2H10.14A18.9 18.9 0 0 1 10 12z"/>
    </svg>
    <span>&nbsp;Portfolio</span>
  </a>
  &nbsp;•&nbsp;
  <a href="#" title="Email">
    <!-- Mail icon -->
    <svg width="18" height="18" viewBox="0 0 24 24" role="img" aria-label="Email" style="vertical-align: -3px;">
      <path fill="currentColor" d="M20 4H4a2 2 0 0 0-2 2v1.2l10 5.6 10-5.6V6a2 2 0 0 0-2-2zm0 5.4-8 4.4-8-4.4V18a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V9.4z"/>
    </svg>
    <span>&nbsp;Email</span>
  </a>
  &nbsp;•&nbsp;
  <a href="#" title="GitHub">
    <!-- GitHub icon -->
    <svg width="18" height="18" viewBox="0 0 24 24" role="img" aria-label="GitHub" style="vertical-align: -3px;">
      <path fill="currentColor" d="M12 2a10 10 0 0 0-3.16 19.49c.5.09.68-.22.68-.48v-1.68c-2.78.6-3.37-1.17-3.37-1.17-.45-1.15-1.11-1.45-1.11-1.45-.9-.62.07-.61.07-.61 1 .07 1.53 1.05 1.53 1.05.89 1.53 2.34 1.09 2.91.83.09-.64.35-1.09.63-1.34-2.22-.25-4.56-1.11-4.56-4.96 0-1.09.39-1.98 1.03-2.68-.1-.26-.45-1.3.1-2.7 0 0 .84-.27 2.75 1.02a9.5 9.5 0 0 1 5 0c1.91-1.29 2.75-1.02 2.75-1.02.55 1.4.2 2.44.1 2.7.64.7 1.03 1.59 1.03 2.68 0 3.86-2.34 4.71-4.57 4.96.36.31.68.92.68 1.86v2.75c0 .27.18.58.69.48A10 10 0 0 0 12 2z"/>
    </svg>
    <span>&nbsp;GitHub</span>
  </a>
  &nbsp;•&nbsp;
  <a href="#" title="X">
    <!-- X icon -->
    <svg width="18" height="18" viewBox="0 0 24 24" role="img" aria-label="X" style="vertical-align: -3px;">
      <path fill="currentColor" d="M17.37 3H20l-5.61 6.4L21.5 21h-6.11l-4.27-5.6L5.9 21H3.26l6.03-6.88L2.5 3h6.21l3.86 5.15L17.37 3zm-1.08 16h1.69L8.76 5h-1.7l9.23 14z"/>
    </svg>
    <span>&nbsp;X</span>
  </a>
  &nbsp;•&nbsp;
  <a href="#" title="Discord">
    <!-- Discord icon -->
    <svg width="18" height="18" viewBox="0 0 24 24" role="img" aria-label="Discord" style="vertical-align: -3px;">
      <path fill="currentColor" d="M20.3 4.37a18.4 18.4 0 0 0-4.62-1.42c-.2.37-.42.88-.58 1.27-1.68-.25-3.36-.25-5.04 0-.17-.4-.37-.9-.58-1.27a18.28 18.28 0 0 0-4.61 1.43C2.38 8.06 1.76 11.66 2 15.21a18.54 18.54 0 0 0 5.66 2.86c.46-.63.87-1.3 1.23-2.01- .68-.26-1.32-.6-1.92-1.02.16-.12.32-.25.48-.38 3.7 1.73 7.7 1.73 11.39 0 .16.13.32.26.48.39-.6.41-1.24.75-1.91 1 .36.71.77 1.39 1.23 2.02 2.06-.66 3.96-1.69 5.65-2.86.25-3.66-.37-7.26-2.59-10.84zM9.5 13.73c-.84 0-1.52-.77-1.52-1.72 0-.95.68-1.72 1.52-1.72.85 0 1.53.77 1.53 1.72 0 .95-.68 1.72-1.53 1.72zm5 0c-.85 0-1.53-.77-1.53-1.72 0-.95.68-1.72 1.53-1.72.84 0 1.52.77 1.52 1.72 0 .95-.68 1.72-1.52 1.72z"/>
    </svg>
    <span>&nbsp;Discord</span>
  </a>
</p>

---

<!-- About -->
### About me

- Student developer who learns by shipping real projects and iterating in public.  
- Passionate about code craft, clean architecture, and pragmatic outcomes.  
- Deployed and maintained production apps with a focus on reliability and fast feedback loops.  

<!-- Animated badges (pure HTML, CSS-style inline via attributes) -->
<p>
  <span style="display:inline-block;padding:8px 12px;border-radius:10px;background:linear-gradient(135deg,#7C3AED,#06B6D4);color:#fff;font:600 12px/1 Inter,system-ui;">React + Vite</span>
  <span style="display:inline-block;padding:8px 12px;border-radius:10px;background:linear-gradient(135deg,#22C55E,#0EA5E9);color:#fff;font:600 12px/1 Inter,system-ui;">Azure Web Apps</span>
  <span style="display:inline-block;padding:8px 12px;border-radius:10px;background:linear-gradient(135deg,#F59E0B,#EF4444);color:#fff;font:600 12px/1 Inter,system-ui;">TypeScript / JS</span>
  <span style="display:inline-block;padding:8px 12px;border-radius:10px;background:linear-gradient(135deg,#6B7280,#111827);color:#fff;font:600 12px/1 Inter,system-ui;">Git & CI</span>
</p>

<!-- Collapsible sections -->
<details open>
  <summary><b>Featured: LegalGuard</b></summary>

  <p align="left">
    <img src="./assets/legalguard-cover.png" alt="LegalGuard cover" width="100%" style="border-radius: 12px; box-shadow: 0 8px 24px rgba(0,0,0,0.15);" />
  </p>

  - Stack: React + Vite • Azure Web Apps  
  - Focus: reliability, clear DX, and simple, maintainable deployments  
  - Link: add your live URL here in plain text when ready  
</details>

<details>
  <summary><b>Projects</b></summary>

  <table>
    <tr>
      <td width="33%">
        <img src="./assets/project-1.png" alt="Project 1" width="100%" style="border-radius: 10px;" />
        <h4>Project One</h4>
        <p>Short description of problem, approach, and result.</p>
      </td>
      <td width="33%">
        <img src="./assets/project-2.png" alt="Project 2" width="100%" style="border-radius: 10px;" />
        <h4>Project Two</h4>
        <p>Short description with measurable outcome if possible.</p>
      </td>
      <td width="33%">
        <img src="./assets/project-3.png" alt="Project 3" width="100%" style="border-radius: 10px;" />
        <h4>Project Three</h4>
        <p>Short description highlighting performance/UX improvements.</p>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><b>Tech stack</b></summary>

  <p>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">React</span>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">Vite</span>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">TypeScript</span>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">JavaScript</span>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">HTML</span>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">CSS</span>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">Tailwind</span>
    <span style="display:inline-block;margin:6px;padding:10px 12px;border-radius:12px;background:#0B1021;color:#E5E7EB;font:600 12px/1 Inter;">Git</span>
  </p>
</details>

<details>
  <summary><b>Activity & fun</b></summary>

  <!-- Local placeholder images; add generated assets later if desired -->
  <p>
    <img src="./assets/stats.png" alt="Stats card" height="160" />
    <img src="./assets/streak.png" alt="Streak card" height="160" />
  </p>

  <!-- Animated wave separator -->
  <p align="center">
    <svg width="100%" height="80" viewBox="0 0 1200 120" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M0,0V46.29c47.29,22,103.74,29,158,17,70.36-15.4,136-57.87,206-73,53.68-11.68,109,3.39,161,21s100.68,38.72,157,43c86,6.49,172-17.61,258-35V0Z" opacity=".25" fill="#7C3AED"></path>
      <path d="M0,0V15.81C47.29,37.8,103.74,49.5,158,42.5c70.36-9.3,136-49,206-62,53.68-9.91,109,2.88,161,17.83S626.68,31.44,683,34c86,3.21,172-13.05,258-25.95V0Z" opacity=".5" fill="#06B6D4"></path>
      <path d="M0,0V5.63C47.29,25.29,103.74,36.06,158,32c70.36-5.08,136-40.47,206-51,53.68-7.72,109,2.24,161,13.83S626.68,12.11,683,14c86,1.29,172-7.78,258-15.62V0Z" fill="#22C55E"></path>
    </svg>
  </p>
</details>

---

<!-- Contact (plain text to avoid external links) -->
### Contact

- Email: adityaburi11[at]gmail[dot]com  
- Portfolio: legalguard[dot]me  
- Discord: add your numeric ID or username here  

<!-- Footer quote -->
> Code is a craft; progress comes from building, shipping, and iterating in public.

<!-- End -->
