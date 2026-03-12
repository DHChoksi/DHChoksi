<!-- Dhruvi H. Choksi | Game & VR Portfolio -->
<h1 align="center">Dhruvi H. Choksi</h1>
<h3 align="center"><i>Game Development | Extended Reality | Software Engineering</i></h3>

<p align="center">
  <img src="https://img.shields.io/badge/VR%20Development-Immersive-blueviolet?style=flat-square&logo=unity" />
  <img src="https://img.shields.io/badge/Game%20Design-Unity%20%26%20Unreal-informational?style=flat-square&logo=unrealengine" />
  <img src="https://img.shields.io/badge/Software%20Engineering-Multidisciplinary-critical?style=flat-square&logo=github" />
</p>

---

## About Me

I am a **Gameplay Engineer**, **Technical Game Designer**, and **XR Developer** with hands-on experience building interactive gameplay systems and immersive XR applications using **Unity and Unreal Engine** across PC, mobile, and VR platforms. Specialized in **C# gameplay programming, XR interactions, AI-driven mechanics, multiplayer systems, and performance optimization**, with a strong QA foundation that enables early identification of gameplay issues and delivery of stable, production-ready builds. Experienced in collaborating with cross-functional teams (engineering, design, research, and QA) to develop scalable systems for enterprise XR training, research-driven VR gameplay, and real-time interactive simulations.


---

> "Designing experiences is more than code, it's about bringing imagination to life."

---

## Education

**California State Polytechnic University, Pomona**  
Master of Science in Computer Science (2023 – 2025)

**Atmiya Institute of Technology and Science, India**  
Bachelor of Engineering in Information Technology (2016 – 2020)

---

## Graduate Thesis (VR Research)

### **Evaluating Motion Sickness Factors in VR: The Role of Navigation, Interaction, and Environmental Effects**  
*Master’s Thesis — California State Polytechnic University, Pomona (2025)*

- Research-focused VR study analyzing **motion sickness, comfort, and immersion** across different **locomotion mechanics** (jet packing, web-swinging, free locomotion) and **interaction complexity**.
- Developed **two custom, space-themed, narrative-driven VR gameplay prototypes (Intergalactic Ranger) in Unity (URP) and evaluated them against a commercial VR benchmark (Swarm VR) using Meta Quest 3 / 3S.**
- Conducted a controlled user study with **33 participants**, applying **VRSQ and MSQ** metrics to derive **design guidelines for comfortable, immersive VR experiences**.
- Findings contribute to **best practices for VR gameplay, training simulations, and immersive system design**.
**[Download Full Thesis (PDF)](https://github.com/DHChoksi/AssetsForPortfolio/blob/main/Motion_Sickness_Master_Thesis__Final.pdf)**

---
## Experience

### Lead XR Consultant 
**Cal Poly Pomona** - Remote, CA | Jan 2026 – Present
- Leading R&D for an **AI/ML-based VR Smart Manufacturing project**, integrating predictive data models into immersive workspaces.
- Developing high-fidelity **VR flight simulators** for research and training, focusing on aerodynamic accuracy and control mapping.
- Investigating **VR Sickness (VIMS)** through a master's thesis, currently preparing for publication. The study establishes industry comfort standards by analyzing locomotion mechanics (jet-packing, web-swinging, free locomotion).

### Technical Game Designer  
**Elite Neuro** — Remote, CA | Jun 2025 – Jan 2026  
- **Developed and optimized interactive VR gameplay systems** in Unity using C#, focusing on performance, scalability, and immersive interaction design for cognitive training applications.  
- **Integrated and optimized 3D assets, lighting, and rendering pipelines**, improving runtime stability and visual clarity across multiple VR form factors.  
- **Collaborated with cross-functional teams** (engineers, designers, researchers) to prototype and iterate on XR modules, incorporating user feedback to improve interaction flow and usability.  
- **Authored technical documentation and UX guidelines**, reducing onboarding time for new contributors and ensuring consistency across XR builds.

### VR Research and Technology Intern  
**Delta Air Lines** — Atlanta, GA | Jan 2025 – May 2025  
- **Designed and developed two physics-based XR training simulations** in Unity (C#) used by **2,000+ operational staff**, supporting enterprise onboarding and safety training initiatives.  
- **Led pre-production planning, asset integration, and technical support**, ensuring XR applications met performance, usability, and learning objectives.  
- **Coordinated and executed large-scale XR simulation testing events** spanning **3 days and 200 participants**, collecting user feedback and driving data-informed design improvements.  
- **Managed and optimized LiDAR-based asset pipelines** using **Artec Leo, Artec Studio, and Blender**, maintaining version-controlled XR environments and UI systems.

### Project Manager & Level Designer  
**BooBoo Games** — Ahmedabad, India | Jul 2022 – Aug 2023  
- **Led end-to-end development of 10+ Unity and Unreal projects**, coordinating QA, development, and art teams to deliver on schedule across mobile, PC, and WebGL platforms.  
- **Designed and integrated gameplay mechanics, UI/UX systems, and multiplayer levels**, improving player engagement and retention metrics.  
- **Optimized physics and rendering systems** using Unity, C#, and OpenCV, ensuring technical accuracy while maintaining creative intent.

### Senior Game Developer  
**DesaniXR** — Remote, India | Dec 2021 – Mar 2022  
- **Developed and deployed multi-platform games and XR applications** using Unity and Unreal Engine, introducing new features and improving existing workflows.  
- **Built and integrated 3D environments, animations, and interaction systems**, collaborating closely with artists and animators to deliver polished, production-quality experiences.  
- **Mentored junior developers and interns**, improving code quality, performance awareness, and Unity best practices across the team.

### Game Developer & Quality Analyst  
**TimeLoop Technologies Pvt. Ltd.** — Remote, India | Nov 2020 – Dec 2021  
- **Designed, developed, tested, and debugged 2D and 3D games** for **PC, Android, iOS, and WebGL** using Unity and C# with object-oriented programming principles.  
- **Integrated analytics and telemetry systems** to track player behavior and retention, contributing to a **~20% improvement in user engagement**.  
- **Implemented in-app purchases (IAP) and ad monetization systems** (banner, rewarded ads), supporting scalable monetization strategies.  
- **Collaborated in Agile development cycles**, maintaining version control, QA documentation, and stable release pipelines.

---

## Projects

## Extended Reality (XR / VR / MR)

### MR Shared Experience & Spatial Colocation — *Unity | Networking & Shared Space* `In-Progress`*
**Tech:** Unity, Meta SDK, Photon Fusion 2, Shared Spatial Anchors
- Developed a robust **Custom Colocation Engine** (`ColocationManager`) to facilitate seamless local spatial synchronization between multiple headsets in a shared physical environment.
- Created a specialized **Alignment Architecture** using a custom `AlignmentManager` that utilizes mathematical logic to align the virtual `OVRCameraRig` with shared physical coordinates via spatial anchors.
- Implemented **Networking & Discovery Logic** using asynchronous tasks to manage session advertising and discovery, ensuring low-latency anchor loading across a distributed network.
- **Industry Application:** Designed for multi-user industrial training and collaborative digital twin inspection.
[Source Files](https://github.com/DHChoksi/MRSharedExp)

### Experimental Passthrough Body Tracking — *Unity | AI & Computer Vision* `In-Progress`*
**Tech:** Unity Sentis (ONNX), MediaPipe, Meta Passthrough API, OpenXR
- Built a **Real-Time Pose Estimation Pipeline** using **Unity Sentis** to execute MediaPipe ONNX models locally on the headset, eliminating the need for external cloud processing.
- Developed a **Spatial Visualization System** (`SkeletonVisualizer`) that maps 33 viewport joints to 3D world space using a custom raycast-based depth fallback system.
- Integrated **Sensor Fusion** techniques, combining raw passthrough camera feeds with spatial camera poses to generate 1:1 scale virtual skeletons within the user's physical environment.
- **Industry Application:** Focused on ergonomics analysis and hands-free gesture control for smart manufacturing.
[Source Files](https://github.com/DHChoksi/Body-Tracking-MR-Passthrough)

 ### Enterprise MR & VR Training Simulations — *Unity | XR Training Systems*  
- Designed and developed **two immersive VR and Mixed Reality (MR) training simulations prototypes** in Unity for operational staff, supporting real-world learning and onboarding use cases.  
- Implemented **passthrough-based MR experiences**, enabling users to safely interact with virtual training content while maintaining awareness of the physical environment.  
- Built interaction systems using **hand tracking, controller tracking, and gesture-based input**, supporting multiple XR interaction modes across devices with targeted platforms quest 3, 3s and Pro.  
- Integrated **physics-based interactions, spatial UI, and guided task flows** to reinforce procedural learning and skill retention.  
- Collaborated with **cross-functional teams** (educators, designers, engineers, and QA) to translate training requirements into **scalable, maintainable XR applications**.  
[Source Files](https://github.com/DHChoksi/VRFunBoomer)
  
### Intergalactic Ranger (IGR) — *Unity | VR Research Game*  
- Research-driven VR gameplay experience developed as part of a **graduate thesis**.  
- Implements **jetpack locomotion, web-swinging traversal, combat systems, environmental hazards (black holes), and zero-gravity navigation**.  
- Designed to study **VR comfort, immersion, and interaction complexity** through controlled gameplay mechanics.
[Watch Video](https://drive.google.com/file/d/1fEtRDZxa22noznYq27VQZPCWjQrUZMo8/view?usp=sharing) | 
[Watch Video](https://raw.githubusercontent.com/DHChoksi/Portfolio/main/Assets/underworld.mp4) | 
[Source Files](https://github.com/DHChoksi/IGR_Game.git) | 
[Prototype](https://github.com/DHChoksi/IGR_LocomotionPrototype)

### VR Fun Boomer — *Unity | VR Gameplay*  
- Experimental VR project focusing on **interactive mechanics and player feedback loops**.  
- Emphasizes **rapid prototyping** and VR interaction design.
[Source Files](https://github.com/DHChoksi/VRFunBoomer)

### Gorillazila — *Unity | Mixed Reality (MR)*  
- Mixed Reality experience combining **real-world spatial awareness with virtual gameplay elements**.  
- Explores **MR interaction, spatial anchoring, and immersive gameplay** blending physical and digital environments.
[Source Code](https://github.com/DHChoksi/Gorillazila)

### Floor Is Lava – Treasure Hunt — *Unity | MR Multiplayer*  
- Multiplayer MR experience featuring **environmental hazards, collaborative gameplay, and spatial navigation**.  
- Designed to test **player coordination and shared mixed-reality spaces**.
[Source Code](https://github.com/DHChoksi/FloorIsLavaTreasureHunt)

---

## 3D Games & AI Systems

### Maze Runner AI FPS — *Unity | 3D FPS with Custom AI*  
- First-person 3D maze shooter featuring **enemy AI without NavMesh**.  
- Implements **raycast-based vision, state machines, obstacle avoidance, and combat behavior**.  
- Focused on **AI perception, decision-making, and emergent navigation**.
[Source Code](https://github.com/DHChoksi/UnityTrainingAIBotGAme_MazeRunner) |
[Watch Video](https://drive.google.com/file/d/18SFYmhxIBSbnrn_kowhsLgylBWOFEGp1/view?usp=sharing) 

### Tic Tac Toe AI — *Unity | 3D AI Logic*  
- Built for a **foundation eligibility assessment** to demonstrate AI reasoning.  
- Features **rule-based strategic AI** (win, block, center, corners) without Minimax.  
- Highlights **clean game-state management and decision prioritization**.
[Source Code](https://github.com/DHChoksi/TicTacToe_AI)

### Underworld’s Downfall — *Unity | 3D Top-Down Shooter*  
- Procedural top-down shooter with **dynamic level generation, combat systems, and visual effects**.  
- Designed for **replayability and system-driven gameplay flow**.
[Watch Video](https://raw.githubusercontent.com/DHChoksi/Portfolio/main/Assets/under.mp4) | 
[Source Files](https://github.com/DHChoksi/Underworld_s_downfall)

---

## 2D Games (Unity/HTML)

### Baby Joy Joy – Musical Instruments — *Unity | 2D Educational Game*  
- Interactive 2D educational game designed to introduce **musical instruments** to young learners.  
- Emphasizes **audio-visual feedback**, touch-based interaction, and child-friendly UI/UX principles.
[App Listing](https://joy-joy-musical-instruments.updatestar.com/)

### Baby Joy Joy – Jack in the Box — *Unity | 2D Educational Game (iOS)*  
- iOS-based 2D educational game built in Unity, focused on **cause-and-effect learning** through playful interaction.  
- Designed for **engagement, repetition, and intuitive input** tailored to early learners.
[App Listing](https://joy-joy-jack-in-the-box-ios.soft112.com/)

### Match the Card — Unity | 2D Puzzle  
- Designed and implemented a memory card game with responsive UI and smooth animations.  
[Watch Video](https://raw.githubusercontent.com/DHChoksi/Portfolio/main/Assets/MatchCards.mp4) |
[Source Files](https://drive.google.com/file/d/1CSPq5i6pDNOYil6LtDMSkRA9MJsvaidP/view?usp=sharing)

### HTML Games — Racing Car | BrickBreaker  
- Created lightweight browser-based games using HTML, CSS, and JavaScript.  
[Source Files](https://github.com/DHChoksi/HTMLGames_Training)

---

## Unity Custom APIs & Systems

### Dynamic Audio Manager API — *Unity | Custom Audio System*  
- Modular audio management system supporting **BGM, SFX, UI SFX, pooling, and runtime control**.  
- Designed as a **reusable Unity API** with clean architecture and extensibility.
[Source Code](https://github.com/DHChoksi/DynamicAudioManager_API)

### Haptic Manager API — *Unity | XR Haptics System*  
- Platform-agnostic haptics framework with **ScriptableObject-driven haptic profiles**.  
- Supports **single-hand and dual-hand feedback** and is easily extensible to new XR devices.
[Source Code](https://github.com/DHChoksi/HapticManager_API)

---

## Other Projects

### Moodify (BeatFusion) — *Java | AI-Driven Music Application*  
- Java-based music application exploring **mood-aware audio processing and interaction**.  
- Focuses on syncing **user experience with dynamic audio behavior**.
[Source Files](https://github.com/DHChoksi/Moodify)

### Obesity Classification — Python | Machine Learning  
- Developed a classification model using biometric and behavioral data to predict obesity levels.  
[Source Files](https://github.com/DHChoksi/Portfolio/raw/main/Assets/ObeysityClassification-main.zip)

### Vallabhi Jewelers — MEAN Stack | Full Stack App  
- Built a responsive MEAN stack web app with real-time chat and video support for virtual consultations.  
[Source Files](https://drive.google.com/file/d/1mk20mi0vssU5rdc3f5SkQCWBS01sBB3g/view?usp=sharing)

---

## Tech Stack & Tools

### Programming Languages & Game Engines
<p>
  <img src="https://img.shields.io/badge/Unity_(C%23)-222C37?style=for-the-badge&logo=unity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Unreal_Engine-313131?style=for-the-badge&logo=unrealengine&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

---

### XR Platforms & Frameworks
<p>
  <img src="https://img.shields.io/badge/Unity_XR-000000?style=for-the-badge&logo=unity&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenXR-5C2D91?style=for-the-badge&logo=virtualreality&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebXR-FF6F00?style=for-the-badge&logo=googlechrome&logoColor=white"/>
  <img src="https://img.shields.io/badge/Meta_SDK-0467DF?style=for-the-badge&logo=meta&logoColor=white"/>
  <img src="https://img.shields.io/badge/Horizon_Worlds-0A66C2?style=for-the-badge&logo=meta&logoColor=white"/>
</p>

---

### Gameplay, AI & Systems
<p>
  <img src="https://img.shields.io/badge/Gameplay_Systems-4CAF50?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI_Logic_&_State_Machines-FF5722?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Multiplayer_(Photon)-795548?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Procedural_Content-9C27B0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Performance_Optimization-607D8B?style=for-the-badge"/>
</p>

---

### Tools, Pipelines & Asset Workflow
<p>
  <img src="https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white"/>
  <img src="https://img.shields.io/badge/Adobe_Creative_Suite-FF0000?style=for-the-badge&logo=adobe&logoColor=white"/>
  <img src="https://img.shields.io/badge/Artec_Leo_LiDAR-0052CC?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Artec_Studio-673AB7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
</p>

---

### Development, QA & Collaboration
<p>
  <img src="https://img.shields.io/badge/Git-EE4C2C?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Agile_Development-009688?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
  <img src="https://img.shields.io/badge/Trello-0079BF?style=for-the-badge&logo=trello&logoColor=white"/>
  <img src="https://img.shields.io/badge/QA_&_Debugging-3F51B5?style=for-the-badge"/>
</p>
---

## Skills

### Game Development & XR
- Gameplay systems design, AI-driven mechanics, XR interaction design  
- VR / AR / MR development, immersive simulation systems  
- Multiplayer fundamentals (Photon, Meta SDK), scalable gameplay architecture  

### Programming & Engines
- **Unity (C#)**, **Unreal Engine**, Object-Oriented Programming  
- Java, Python, JavaScript  
- OpenCV, performance optimization, rendering pipelines  

### XR Platforms & Frameworks
- Unity XR, OpenXR, WebXR  
- Meta SDK, Horizon Worlds  
- PC, Mobile, Standalone VR (Quest)

### Tools & Pipelines
- Blender, Adobe Creative Suite  
- Artec Leo LiDAR Scanner, Artec Studio  
- Version control (Git), asset pipeline management  
- Project management tools (Jira, Trello)

### Collaboration & Production
- Cross-functional team collaboration  
- Technical documentation & SOP creation  
- Research-driven prototyping and UX iteration  
- Agile development and QA workflows

---

## Contact & Links

**Email:** [dhchoksi.work1699@gmail.com](mailto:dhchoksi.work1699@gmail.com)  
**LinkedIn:** [linkedin.com/in/dhchoksi](https://www.linkedin.com/in/dhchoksi)  
**Resume:** [View Resume](https://docs.google.com/document/d/18h5sr3vMYYJeZB2gl_0Vna8HBhrN4Vm-F0o-W1PDjZY/edit?usp=sharing)

---

<p align="center">
  <strong>Thank you for visiting.</strong><br>
  Let's collaborate, innovate, and build immersive worlds together.
</p>
