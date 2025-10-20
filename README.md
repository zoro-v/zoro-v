<!-- ===== Profile header: Animated Matrix SVG + Glitch name ===== -->
<!-- حجم العرض سيتكيّف داخل البروفايل -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 240" width="100%" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="bg" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#071027"/>
      <stop offset="100%" stop-color="#00121a"/>
    </linearGradient>
    <style type="text/css"><![CDATA[
      .title { font: bold 40px "Fira Code", monospace; fill: #a6f3ff; }
      .small { font: 14px "Inter", system-ui; fill: #9aa7bf; }
    ]]></style>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" fill="url(#bg)"/>

  <!-- matrix columns: repeating characters that animate down -->
  <!-- we create several columns; each has a single <text> with animate for y -->
  <!-- columns spacing 40px, randomize durations & delays for natural look -->
  <!-- column 1 -->
  <text x="40" y="-10" font-family="monospace" font-size="16" fill="#2ee08a" opacity="0.9">
    0 1 1 0 1 0 1 0 1
    <animate attributeName="y" from="-20" to="300" dur="4s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- column 2 -->
  <text x="80" y="-40" font-family="monospace" font-size="16" fill="#18b46b" opacity="0.85">
    A 7 5 3 9 F 1 2 4
    <animate attributeName="y" from="-40" to="300" dur="5s" begin="0.6s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.5;1;0.5" dur="5s" repeatCount="indefinite"/>
  </text>

  <!-- column 3 -->
  <text x="120" y="-20" font-family="monospace" font-size="16" fill="#2ee08a" opacity="0.9">
    シ カ タ ナ サ ハ マ
    <animate attributeName="y" from="-20" to="300" dur="4.6s" begin="0.2s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4.6s" repeatCount="indefinite"/>
  </text>

  <!-- repeat a few columns (you can add more) -->
  <text x="200" y="-10" font-family="monospace" font-size="16" fill="#15d68a" opacity="0.8">
    0 9 8 5 4 3 2 1
    <animate attributeName="y" from="-10" to="300" dur="5.3s" begin="0.3s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.5;1;0.5" dur="5.3s" repeatCount="indefinite"/>
  </text>

  <text x="320" y="-30" font-family="monospace" font-size="16" fill="#20a4ff" opacity="0.8">
    X R C 7 2 9 5 0
    <animate attributeName="y" from="-30" to="300" dur="4.2s" begin="0.9s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.5;1;0.5" dur="4.2s" repeatCount="indefinite"/>
  </text>

  <!-- Center glitch title (two colored layers with blink) -->
  <g transform="translate(600,110)">
    <text class="title" text-anchor="middle" data-text="Zoro" >
      Zoro
      <animate attributeName="opacity" values="1;0.6;1" dur="2.2s" repeatCount="indefinite"/>
    </text>

    <!-- red shadow -->
    <text class="title" text-anchor="middle" x="3" y="0" fill="#ff4d79" opacity="0.85" style="mix-blend-mode:screen">
      Zoro
      <animate attributeName="x" values="3; -2; 3" dur="2.2s" repeatCount="indefinite"/>
    </text>

    <!-- cyan shadow -->
    <text class="title" text-anchor="middle" x="-3" y="0" fill="#3ad1ff" opacity="0.85" style="mix-blend-mode:screen">
      Zoro
      <animate attributeName="x" values="-3; 2; -3" dur="2.2s" repeatCount="indefinite"/>
    </text>

    <!-- subtitle -->
    <text class="small" y="38" text-anchor="middle">Cybersecurity Researcher • Bug Bounty • Recon</text>
  </g>
</svg>

<!-- ===== Badges & typing effect (remote typing SVG service) ===== -->
<p align="center">
  <img src="https://img.shields.io/badge/OS-Kali%20Linux-informational?logo=kali-linux" alt="OS" />
  <img src="https://img.shields.io/badge/Lang-Python-blue?logo=python" alt="python" />
  <img src="https://img.shields.io/badge/Focus-Bug%20Bounty-success" alt="bug bounty" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=900&color=7aa2ff&center=true&width=700&lines=Recon+%2F+OSINT;Exploit+PoC;Automation+in+Python" alt="typing" />
</p>

<!-- ===== Links & contact ===== -->
<p align="center">
  <a href="https://zoro-v.github.io/Ozone/" target="_blank">🌐 Website</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/zoro-v" target="_blank">🐙 GitHub</a>
  &nbsp;•&nbsp;
  <a href="mailto:Ozone_6@hotmail.com.com">✉️ Email</a>
</p>

---

## 🔐 عني
باحث أمن سيبراني يركز على Web Apps، تحليل JavaScript/Next.js، استخراج أسرار/Endpoints، وإنشاء PoC منظم.

## 🧰 التقنيات
linux , windows , ios

## 📂 المشاريع المختارة
- **Ozone** — JS analyzer & PoC generator  
- **Firebase_Waf_Bypass** — token endpoint testing  
- **cloudflare_403_bypass** — header tricks


