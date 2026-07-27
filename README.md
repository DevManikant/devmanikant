<!-- 1. BULLETPROOF GRADIENT HEADER (PURE HTML/SVG) -->
<!-- Uses the exact deep space blue (#123652) to vibrant purple (#7F23E1) gradient -->
<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 220" width="100%" height="220">
    <defs>
      <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#123652" />
        <stop offset="100%" stop-color="#7F23E1" />
      </linearGradient>
    </defs>
    <rect width="1200" height="220" fill="url(#headerGrad)" rx="15" />
    <text x="50%" y="45%" text-anchor="middle" fill="#FFFFFF" font-family="'Fira Code', 'Segoe UI', sans-serif" font-size="48" font-weight="bold">Manikant Sharma</text>
    <text x="50%" y="70%" text-anchor="middle" fill="#BD93F9" font-family="'Fira Code', 'Segoe UI', sans-serif" font-size="22">Systems &amp; Automation Engineer</text>
  </svg>
</div>

<br />

<!-- 2. DYNAMIC TYPING HEADER & SOCIALS -->
<div align="center">
  <a href="https://github.com/devmanikant">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=BD93F9&center=true&vCenter=true&width=650&lines=High-Precision+Sub-1ms+Automation;Python+%26+Playwright+Specialist;Cloud+Infrastructure+%26+AsyncIO;Systems+Integration+Architect" alt="Typing SVG" />
  </a>

  <br /><br />

  <!-- MINIMALIST FLAT BADGES -->
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/devmanikant)
  [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:your.email@example.com)
</div>

<br />

<!-- 3. GITHUB-HOSTED GLOWING NEON DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-db03d600-a473-11eb-812d-d005fe0e8286.gif" width="100%" />

<br />

<!-- 4. SIDE-BY-SIDE BIO & GUARANTEED 3D ANIMATION -->
<table>
  <tr>
    <td width="55%" valign="top">
      <h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" width="30"> About Me</h2>
      <p>I am a systems-focused engineer dedicated to building high-performance systems and precision automation data pipelines.</p>
      <ul>
        <li>🔭 <b>Specialization:</b> Asynchronous event loops, sub-millisecond execution triggers, and cloud-native infrastructure.</li>
        <li>💻 <b>Environments:</b> Linux (Ubuntu / Lubuntu), AWS EC2, Azure Functions, Docker.</li>
        <li>⚡ <b>Core Languages:</b> Python (AsyncIO), JavaScript, C++.</li>
      </ul>
    </td>
    <td width="45%" align="center" valign="middle">
      <!-- 100% RELIABLE GITHUB-ALLOWED MEDIA -->
      <img src="https://media.giphy.com/media/uV3mC1123o3E18X3dO/giphy.gif" width="100%" alt="Coding Animation" />
    </td>
  </tr>
</table>

<br />

<!-- NEON DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-db03d600-a473-11eb-812d-d005fe0e8286.gif" width="100%" />

<br />

<!-- 5. TECHNICAL ECOSYSTEM -->
<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="30"> Technical Ecosystem</h2>

| Category | Technologies |
| :--- | :--- |
| **Languages** | `Python (AsyncIO)` `JavaScript` `Java` `C++` `C#` `Dart` |
| **Automation & Vision** | `Playwright` `Selenium` `OpenCV` `BeautifulSoup` |
| **Cloud & DevOps** | `AWS (EC2)` `Azure Functions` `Docker` `Linux (Ubuntu/Lubuntu)` `Git` |
| **Backend & DB** | `Node.js` `FastAPI` `PostgreSQL` `MongoDB` `Redis` |

<br />

<!-- 6. FEATURED PROJECTS -->
<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Rocket.png" width="30"> Highlighted Projects</h2>

| Project | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| **High-Precision Automation Engine** | Sub-millisecond trigger script engineered for high-concurrency event interaction. | `Python` `Playwright` `AsyncIO` | ![Active](https://img.shields.io/badge/Status-Active-7F23E1?style=flat-square) |
| **Face Recognition System** | Computer vision-based automated attendance management system. | `Python` `OpenCV` `SQLite` | ![Completed](https://img.shields.io/badge/Status-Completed-blue?style=flat-square) |

<br />

---

<br />

<!-- 7. ARCHITECTURE DEEP DIVES -->
<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Magnifying%20Glass%20Tilted%20Right.png" width="30"> Architecture & Performance Notes</h2>

<details>
<summary>🔍 <b>Click to expand: High-Precision Automation Architecture ( &lt; 1ms Latency)</b></summary>

<br />

### Core Engineering Focus
The primary challenge is minimizing execution latency between an event trigger and the automation action.

* **Non-Blocking Execution:** Leverages Python's `asyncio` loop combined with `Playwright`'s asynchronous API.
* **Network Optimization:** Multi-region AWS deployments chosen for physical proximity to target sockets, minimizing handshake overhead.
* **Zero Overhead:** Streamlined Docker containers running on tuned Ubuntu Server instances.

```python
# Conceptual layout of asynchronous high-precision execution
import asyncio
import time

async def precision_trigger(event_data):
    start_time = time.time()
    
    # Asynchronous non-blocking action
    async with action_context() as action:
        result = await action.execute(event_data)
        
    end_time = time.time()
    # Target execution time: < 0.001 seconds
    print(f"Executed in: {end_time - start_time:.6f}s")
