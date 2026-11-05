<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%">
    <defs>
      <!-- Vibrant Gradients for the transparent boxes -->
      <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#FF007F" />
        <stop offset="100%" stop-color="#FFB100" />
      </linearGradient>
      <linearGradient id="grad2" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00F0FF" />
        <stop offset="100%" stop-color="#0055FF" />
      </linearGradient>
      <linearGradient id="grad3" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#39FF14" />
        <stop offset="100%" stop-color="#00FFAA" />
      </linearGradient>

      <!-- Glow effect for the boxes -->
      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="4" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>

      <!-- The Mask that reveals the text -->
      <mask id="revealMask">
        <rect width="100%" height="100%" fill="black" />
        <g transform="skewX(-25)">
          <rect x="-300" y="-20" width="100" height="240" fill="white">
            <animate attributeName="x" from="-300" to="1000" dur="4s" repeatCount="indefinite" />
          </rect>
          <rect x="-300" y="-20" width="200" height="240" fill="white">
            <animate attributeName="x" from="-300" to="1000" dur="4s" repeatCount="indefinite" begin="0.15s" />
          </rect>
          <rect x="-300" y="-20" width="80" height="240" fill="white">
            <animate attributeName="x" from="-300" to="1000" dur="4s" repeatCount="indefinite" begin="0.3s" />
          </rect>
        </g>
      </mask>
    </defs>

    <!-- Dark Background -->
    <rect width="800" height="200" fill="#0D1117" />

    <!-- Dimmed Base Text (shows when boxes are not passing) -->
    <text x="400" y="115" font-family="'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-weight="900" font-size="60" fill="#FFFFFF" fill-opacity="0.1" text-anchor="middle">Hi 👋, I'm Bertrand</text>

    <!-- Bright Revealed Text (only shows inside the mask) -->
    <text x="400" y="115" font-family="'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-weight="900" font-size="60" fill="#FFFFFF" text-anchor="middle" mask="url(#revealMask)">Hi 👋, I'm Bertrand</text>

    <!-- The Oblique Transparent Colorful Boxes -->
    <g transform="skewX(-25)" filter="url(#glow)">
      <!-- Box 1 -->
      <rect x="-300" y="-20" width="100" height="240" fill="transparent" stroke="url(#grad1)" stroke-width="4" rx="8">
        <animate attributeName="x" from="-300" to="1000" dur="4s" repeatCount="indefinite" />
      </rect>
      <!-- Box 2 -->
      <rect x="-300" y="-20" width="200" height="240" fill="transparent" stroke="url(#grad2)" stroke-width="4" rx="8">
        <animate attributeName="x" from="-300" to="1000" dur="4s" repeatCount="indefinite" begin="0.15s" />
      </rect>
      <!-- Box 3 -->
      <rect x="-300" y="-20" width="80" height="240" fill="transparent" stroke="url(#grad3)" stroke-width="4" rx="8">
        <animate attributeName="x" from="-300" to="1000" dur="4s" repeatCount="indefinite" begin="0.3s" />
      </rect>
    </g>
  </svg>

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=39FF14&center=true&vCenter=true&width=600&lines=Full-Stack+Web+Developer;Ready+for+a+new+project;Building+Menos+🚀" alt="Typing SVG" />
  </a>
</div>

<br>

## 👨‍💻 About Me

- 🔭 I’m currently building **Menos** (a high-end SaaS for social media automation).
- 🏘️ I recently built the community platform **[KAMBA Forum](https://kambaforum.netlify.app/)**.
- 🍿 I'm working on **[AGASOBANUYE KINAFLIX](https://kinaflix-fawn.vercel.app/)** for movie lovers.
- 🧠 I'm developing the educational platform **[Deep Learn](https://deeplearn.vercel.app/)**.
- 💬 Ask me about **Web Development, React, and UI/UX Design**.
- 📫 How to reach me: **mkbertrand123@gmail.com**

<br>

## 🚀 Projects & Creations

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ Menos <em>(In Progress)</em></h3>
      <p>A premium, dark-mode SaaS tool that automates social media posting to Facebook and Instagram. Built with React, Vercel, and Supabase.</p>
      <img src="https://img.shields.io/badge/Status-Building_🚧-39FF14?style=flat-square&logoColor=black" alt="Status">
    </td>
    <td width="50%" valign="top">
      <h3>🏘️ KAMBA Forum</h3>
      <p>A dedicated community platform designed to connect and engage users. Live and active.</p>
      <a href="https://kambaforum.netlify.app/"><img src="https://img.shields.io/badge/View_Live-000000?style=flat-square&logo=netlify&logoColor=white" alt="Live"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🍿 Kinaflix</h3>
      <p>A modern streaming and movie discovery platform tailored for viewers looking for the best content.</p>
      <a href="https://kinaflix-fawn.vercel.app/"><img src="https://img.shields.io/badge/View_Live-000000?style=flat-square&logo=vercel&logoColor=white" alt="Live"></a>
    </td>
    <td width="50%" valign="top">
      <h3>🧠 Deep Learn</h3>
      <p>An interactive educational platform aimed at making complex topics easier to digest.</p>
      <a href="https://deeplearn.vercel.app/"><img src="https://img.shields.io/badge/View_Live-000000?style=flat-square&logo=vercel&logoColor=white" alt="Live"></a>
    </td>
  </tr>
</table>

<br>

## 🛠️ Languages & Tools

<div align="center">
  
  **Frontend & Design** <br>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />

  **Backend & Databases** <br>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  
  **Other Tools** <br>
  <img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white" />
  <img src="https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white" />

</div>

<br>

## 🌐 Connect with Me

<div align="center">
  <a href="https://twitter.com/mwizerwabe34779" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
  <a href="https://linkedin.com/in/mwizerwa-k-bertrand-1a7b8233a" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://instagram.com/b3_rtrand" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://www.youtube.com/@btemOfficial" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
</div>

<br>

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=mkb-nel&theme=radical&no-frame=true&no-bg=true&margin-w=15" alt="Trophies" />
  <br><br>
  <img src="https://github-readme-stats.vercel.app/api?username=mkb-nel&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=39FF14&icon_color=39FF14" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mkb-nel&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=39FF14" width="48%" />
</div>

<br>

## 💖 Support My Work

<div align="center">
  <a href="https://ko-fi.com/mkbertrand">
    <img src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" height="45" alt="Buy Me a Coffee at ko-fi.com" />
  </a>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,20,24&height=120&section=footer" width="100%" />
</div>
