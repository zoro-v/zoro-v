<!-- Profile hero: Matrix animated SVG + Glitch title -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 360" width="100%" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="bg" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#071014"/>
      <stop offset="100%" stop-color="#001017"/>
    </linearGradient>
    <style type="text/css"><![CDATA[
      .mono { font-family: "Fira Code", "Courier New", monospace; fill:#2af77f; font-weight:600; font-size:14px; }
      .title { font-family: "Fira Code", monospace; font-weight:800; font-size:48px; fill:#bffcff; }
      .subtitle { font-family: Inter, system-ui, sans-serif; fill:#9fb3c8; font-size:16px; }
      a { fill:#7ecbff; text-decoration:none; }
    ]]></style>
  </defs>
  <!-- background -->
  <rect width="100%" height="100%" fill="url(#bg)"/>
  <!-- matrix columns (a few columns, each animates down) -->
  <g opacity="0.95">
    <text x="40" y="-10" class="mono">ﾌ ﾐ ｶ ﾀ ﾅ ﾊ ﾏ ﾔ ﾗ ﾜ 0 1 1 0
      <animate attributeName="y" from="-20" to="380" dur="6s" begin="0s" repeatCount="indefinite" />
    </text>

  <text x="110" y="-50" class="mono">A 7 5 3 9 F 1 2 4
      <animate attributeName="y" from="-50" to="380" dur="5.6s" begin="0.5s" repeatCount="indefinite" />
    </text>

   <text x="190" y="-30" class="mono">0 9 8 5 4 3 2 1
      <animate attributeName="y" from="-30" to="380" dur="6.4s" begin="0.9s" repeatCount="indefinite" />
    </text>

  <text x="260" y="-20" class="mono">X R C 7 2 9 5 0
      <animate attributeName="y" from="-20" to="380" dur="5s" begin="0.3s" repeatCount="indefinite" />
    </text>
    <text x="340" y="-40" class="mono">シ カ タ ナ サ ハ マ ヤ
      <animate attributeName="y" from="-40" to="380" dur="5.8s" begin="0.8s" repeatCount="indefinite" />
    </text>
    <text x="420" y="-10" class="mono">8 1 6 4 2 0 7 3 9
      <animate attributeName="y" from="-10" to="380" dur="6.1s" begin="0.2s" repeatCount="indefinite" />
    </text>
    <text x="500" y="-30" class="mono">Z X C V B N M 1 2 3
      <animate attributeName="y" from="-30" to="380" dur="5.3s" begin="0.7s" repeatCount="indefinite" />
    </text>
    <text x="760" y="-10" class="mono">0 1 0 1 1 0 1 0 1 1
      <animate attributeName="y" from="-10" to="380" dur="5.9s" begin="0.4s" repeatCount="indefinite" />
    </text>
    <text x="860" y="-40" class="mono">シ ﾌ ﾐ ｶ ﾀ ﾅ ﾊ ﾏ ﾔ ﾗ
      <animate attributeName="y" from="-40" to="380" dur="6.2s" begin="1.0s" repeatCount="indefinite" />
    </text>
    <text x="960" y="-20" class="mono">3 6 9 0 2 5 7 8 4 1
      <animate attributeName="y" from="-20" to="380" dur="5.5s" begin="0.6s" repeatCount="indefinite" />
    </text>
  </g>
  <!-- center glitch title group -->
  <g transform="translate(600,165)" text-anchor="middle">
    <!-- cyan shadow -->
    <text class="title" x="-4" y="-2" fill="#3ad1ff" opacity="0.85" style="mix-blend-mode:screen">
      Ozone
      <animate attributeName="x" values="-4;2;-4" dur="2.2s" repeatCount="indefinite" />
    </text>
        <!-- red shadow -->
  <text class="title" x="4" y="2" fill="#ff4d79" opacity="0.85" style="mix-blend-mode:screen">
      Ozone
      <animate attributeName="x" values="4;-2;4" dur="2.2s" repeatCount="indefinite" />
    </text>
      <!-- main -->
  <text class="title" x="0" y="0" fill="#bffcff">Ozone</text>
      <!-- subtitle -->
  <text class="subtitle" x="0" y="46">Blothunter • BugBounty • Cybersecurity</text>
  </g>
</svg>

<!-- ===== Badges & typing effect ===== -->
<p align="center">
  <img src="https://img.shields.io/badge/OS-Kali%20Linux-informational?logo=kali-linux" alt="os" />
  <img src="https://img.shields.io/badge/Lang-Python-blue?logo=python" alt="python" />
  <img src="https://img.shields.io/badge/Focus-Bug%20Bounty-success" alt="bugbounty" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=7aa2ff&center=true&width=760&lines=Bug+Bounty+%7C+Web+Exploitation+%7C+Automation+in+Python" alt="typing" />
</p>

<!-- ===== Contacts ===== -->
<p align="center">
  <strong>Contact:</strong>
  &nbsp;•&nbsp;
  <a href="mailto:Ozone_6@hotmail.com">Email</a>
  &nbsp;•&nbsp;
  <a href="https://t.me/Ozone_su_bot" target="_blank">Telegram</a>
  &nbsp;•&nbsp;
  <a href="https://zoro-v.github.io/Ozone/" target="_blank">Website</a>
</p>

---

## 🔐 عني
باحث أمن سيبراني يركز على Recon، اكتشاف ثغرات، وبناء PoC & أتمتة بالـPython.

## 🧰 الأدوات
Recon (gau, subfinder) • ffuf • nuclei • Python (requests, asyncio)

## 📂 مشاريع مهمة
- **Ozone** — أداة تحليل JS وPoC generator  
- **Firebase_Waf_Bypass** — فحص نقاط الـidToken  
- **cloudflare_403_bypass** — حيل رؤوس HTTP لتجاوز 403
