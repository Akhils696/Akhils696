<style>
    .banner {
        width: 100%;
        max-width: 1200px;
        height: 400px;
        background: linear-gradient(135deg, #0a0a1a 0%, #1a1a2e 25%, #16213e 50%, #0f3460 75%, #1a1a2e 100%);
        position: relative;
        overflow: hidden;
        border-radius: 8px;
        margin: 0 auto;
    }
    
    /* Neural network lines */
    .neural-lines {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        opacity: 0.3;
    }
    
    .line {
        position: absolute;
        background: linear-gradient(90deg, transparent, #4cc9f0, #4361ee, #7209b7, transparent);
        height: 2px;
        border-radius: 1px;
        transform-origin: left center;
    }
    
    /* Circuit patterns */
    .circuits {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        opacity: 0.2;
    }
    
    .circuit {
        position: absolute;
        border: 1px solid #4361ee;
        border-radius: 4px;
    }
    
    /* Code snippets */
    .code-snippets {
        position: absolute;
        opacity: 0.4;
        color: #4cc9f0;
        font-family: 'Courier New', monospace;
        font-size: 12px;
    }
    
    /* Cloud icons */
    .clouds {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        opacity: 0.15;
    }
    
    .cloud {
        position: absolute;
        color: #7209b7;
        font-size: 24px;
    }
    
    /* Text content */
    .content {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-align: center;
        z-index: 10;
        width: 100%;
    }
    
    .name {
        color: #ffffff;
        font-size: 48px;
        font-weight: 600;
        margin-bottom: 15px;
        text-shadow: 0 0 20px rgba(76, 201, 240, 0.5);
        letter-spacing: 1px;
    }
    
    .title {
        color: #4cc9f0;
        font-size: 24px;
        font-weight: 300;
        letter-spacing: 1px;
        text-shadow: 0 0 10px rgba(67, 97, 238, 0.3);
    }
    
    /* Animated elements */
    @keyframes pulse {
        0% { opacity: 0.3; }
        50% { opacity: 0.6; }
        100% { opacity: 0.3; }
    }
    
    .neural-lines {
        animation: pulse 4s infinite;
    }
</style>

<div class="banner">
    <!-- Neural Network Lines -->
    <div class="neural-lines">
        <div class="line" style="top: 30%; left: 10%; width: 80%; transform: rotate(5deg);"></div>
        <div class="line" style="top: 40%; left: 5%; width: 90%; transform: rotate(-3deg);"></div>
        <div class="line" style="top: 50%; left: 15%; width: 70%; transform: rotate(2deg);"></div>
        <div class="line" style="top: 60%; left: 8%; width: 85%; transform: rotate(-1deg);"></div>
        <div class="line" style="top: 70%; left: 20%; width: 60%; transform: rotate(4deg);"></div>
    </div>
    
    <!-- Circuit Patterns -->
    <div class="circuits">
        <div class="circuit" style="top: 15%; left: 80%; width: 60px; height: 40px;"></div>
        <div class="circuit" style="top: 75%; left: 10%; width: 80px; height: 30px;"></div>
        <div class="circuit" style="top: 25%; left: 5%; width: 40px; height: 60px;"></div>
        <div class="circuit" style="top: 65%; left: 85%; width: 50px; height: 35px;"></div>
    </div>
    
    <!-- Code Snippets -->
    <div class="code-snippets" style="top: 20%; left: 70%;">def neural_net():</div>
    <div class="code-snippets" style="top: 25%; left: 72%;">&nbsp;&nbsp;return ai_model</div>
    <div class="code-snippets" style="top: 70%; left: 15%;">class Developer:</div>
    <div class="code-snippets" style="top: 75%; left: 17%;">&nbsp;&nbsp;pass</div>
    <div class="code-snippets" style="top: 45%; left: 5%;"># AI & Software</div>
    
    <!-- Cloud Icons -->
    <div class="clouds">
        <div class="cloud" style="top: 10%; left: 25%;">☁️</div>
        <div class="cloud" style="top: 80%; left: 75%;">☁️</div>
        <div class="cloud" style="top: 35%; left: 85%;">☁️</div>
        <div class="cloud" style="top: 60%; left: 5%;">☁️</div>
    </div>
    
    <!-- Main Content -->
    <div class="content">
        <div class="name">Akhil Senthil</div>
        <div class="title">AI Enthusiast | Software Developer | CSE Undergraduate</div>
    </div>
</div>

<div align="center">

<!-- Custom Badges -->
<img src="https://img.shields.io/badge/Artificial%20Intelligence-2563eb?style=for-the-badge&logo=deeplearning.ai&logoColor=white"/>
<img src="https://img.shields.io/badge/Software%20Engineering-7c3aed?style=for-the-badge&logo=codeforces&logoColor=white"/>
<img src="https://img.shields.io/badge/Embedded%20Systems-0891b2?style=for-the-badge&logo=arduino&logoColor=white"/>
<img src="https://img.shields.io/badge/Amrita%20University-059669?style=for-the-badge&logo=gradle&logoColor=white"/>

</div>

<!-- Custom Divider -->
<div style="height: 3px; background: linear-gradient(90deg, #2563eb, #7c3aed, #0891b2); border-radius: 2px; margin: 20px 0;"></div>

<!-- ABOUT + CURRENT WORK side by side -->
<table width="100%">
<tr>
<td width="55%" valign="top">

## 🎓 About Me

Pursuing Computer Science Engineering at Amrita Vishwa Vidyapeetham with a passion for creating intelligent systems. My work focuses on the intersection of **artificial intelligence**, **software development**, and **embedded systems**. I specialize in building practical solutions that bridge theoretical concepts with real-world applications.

</td>
<td width="45%" valign="top">

## 🔧 Currently Working On

**Smart IoT Systems**
Developing Arduino-based solutions with sensor integration for real-time monitoring and automation.

**Machine Learning Applications**
Creating AI models for pattern recognition and predictive analysis in computational problems.

</td>
</tr>
</table>

<!-- Custom Divider -->
<div style="height: 3px; background: linear-gradient(90deg, #2563eb, #7c3aed, #0891b2); border-radius: 2px; margin: 20px 0;"></div>

## 📁 Projects Showcase

<table width="100%">
<tr>
<th>Project</th>
<th>Description</th>
<th>Status</th>
<th>Technologies</th>
</tr>
<tr>
<td><b>📍 GPS Tracking System</b></td>
<td>Real-time location monitoring using Arduino with integrated sensor networks for precise tracking.</td>
<td><img src="https://img.shields.io/badge/Completed-10b981?style=flat-square&logo=checkmarx&logoColor=white"/></td>
<td>Arduino · C · GPS · Sensors</td>
</tr>
<tr>
<td><b>🧠 AI Algorithm Development</b></td>
<td>Machine learning models for computational problem solving and pattern recognition.</td>
<td><img src="https://img.shields.io/badge/In%20Progress-f59e0b?style=flat-square&logo=progress&logoColor=white"/></td>
<td>Python · Scikit-learn · Algorithms</td>
</tr>
<tr>
<td><b>📊 MATLAB Simulation Suite</b></td>
<td>Comprehensive mathematical modeling and simulation environment for algorithm validation.</td>
<td><img src="https://img.shields.io/badge/Completed-8b5cf6?style=flat-square&logo=matlab&logoColor=white"/></td>
<td>MATLAB · Simulation · Analysis</td>
</tr>
</table>

<!-- Custom Divider -->
<div style="height: 3px; background: linear-gradient(90deg, #2563eb, #7c3aed, #0891b2); border-radius: 2px; margin: 20px 0;"></div>

## 💻 Technical Skills

<div align="center">

<!-- Programming Languages -->
<h3>Programming Languages</h3>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
<img src="https://img.shields.io/badge/Embedded%20C-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>

<!-- Web Technologies -->
<h3>Web Development</h3>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>

<!-- Tools & Platforms -->
<h3>Tools & Platforms</h3>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>

</div>

<!-- Custom Divider -->
<div style="height: 3px; background: linear-gradient(90deg, #2563eb, #7c3aed, #0891b2); border-radius: 2px; margin: 20px 0;"></div>

## 📚 Learning Journey

<details>
<summary><b>📚 Current Studies & Interests</b></summary>
<br/>

| Area | Focus | Progress |
|------|-------|----------|
| **Machine Learning** | Neural networks and deep learning | 🟢 Active |
| **Embedded Systems** | IoT and microcontroller programming | 🟢 Active |
| **Data Structures** | Algorithms and optimization | 🟡 In Progress |
| **Web Development** | Full-stack application building | 🟢 Completed |

**Current Learning Goals:**
- Advanced AI algorithms and neural network architectures
- Real-time embedded system design
- Cloud computing and distributed systems
- Software architecture and design patterns

</details>

<!-- Custom Divider -->
<div style="height: 3px; background: linear-gradient(90deg, #2563eb, #7c3aed, #0891b2); border-radius: 2px; margin: 20px 0;"></div>

## 📊 GitHub Analytics

<div align="center">

<!-- GitHub Stats -->
<img height="170em" src="https://github-readme-stats.vercel.app/api?username=Akhils696&show_icons=true&theme=blue-green&hide_border=true&bg_color=0a192f&title_color=64ffda&icon_color=64ffda&text_color=8892b0&ring_color=64ffda&count_private=true&include_all_commits=true"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Akhils696&layout=compact&theme=blue-green&hide_border=true&bg_color=0a192f&title_color=64ffda&text_color=8892b0&langs_count=6"/>

</div>

<div align="center">
<!-- GitHub Streak -->
<img src="https://streak-stats.demolab.com?user=Akhils696&theme=blue-green&hide_border=true&background=0a192f&ring=64ffda&fire=64ffda&currStreakLabel=64ffda&sideLabels=64ffda&dates=8892b0"/>
</div>

<div align="center">
<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Akhils696&bg_color=0a192f&color=64ffda&line=64ffda&point=64ffda&area=true&area_color=112240&hide_border=true" width="100%"/>
</div>

<!-- Custom Divider -->
<div style="height: 3px; background: linear-gradient(90deg, #2563eb, #7c3aed, #0891b2); border-radius: 2px; margin: 20px 0;"></div>

## 🎯 Career Aspirations

```
🎯 Short-term Goals
├── Master AI algorithms and neural networks
├── Complete advanced embedded systems projects
└── Build a portfolio of practical applications

🚀 Mid-term Vision
├── Strong foundation in software architecture
├── Contribute to meaningful open-source projects
└── Gain industry experience through internships

🌟 Long-term Ambition
├── Career in AI-driven software engineering
├── Work on cutting-edge technology solutions
└── Make impactful contributions to the field
```

**Core Philosophy:** *Depth over breadth. Systems over trends. Build solutions that create real value.*

<!-- Custom Divider -->
<div style="height: 3px; background: linear-gradient(90deg, #2563eb, #7c3aed, #0891b2); border-radius: 2px; margin: 20px 0;"></div>

## 🤝 Let's Connect

<div align="center">

<!-- Social Media Badges -->
<a href="https://www.linkedin.com/in/akhil-senthil-430b6a317">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/Akhils696">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.hackerrank.com/akhilsenthil696">
  <img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=white"/>
</a>
<a href="https://leetcode.com/AKHIL_S_696">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/>
</a>
<a href="https://instagram.com/_akxil_s_">
  <img src="https://img.shields.io/badge/Instagram-E1306C?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

<br/><br/>

### 📧 Contact Information

| Platform | Handle |
|----------|--------|
| **📧 Email** | akhilsenthil696@gmail.com |
| **💼 LinkedIn** | linkedin.com/in/akhil-senthil-430b6a317 |
| **💻 GitHub** | github.com/Akhils696 |
| **🏆 HackerRank** | hackerrank.com/akhilsenthil696 |
| **📊 LeetCode** | leetcode.com/AKHIL_S_696 |
| **📸 Instagram** | @_akxil_s_ |

</div>

<div align="center" style="margin-top: 30px; padding: 20px; background: linear-gradient(135deg, #0a192f, #112240); border-radius: 15px;">

### 💡 Open to Collaborations
I'm always excited to work on interesting projects, discuss AI and software development concepts, and collaborate on innovative solutions. Feel free to reach out!

</div>