# 🎮 Game-Based Learning (GBL) with Unity

Game-Based Learning (GBL) blends instructional design with the motivational power of gameplay to create experiences that are interactive, meaningful, and memorable. Unity—one of the most widely used real-time 3D engines—provides a flexible framework for developing educational simulations, training tools, virtual labs, and serious games across platforms. This repository outlines key concepts, development patterns, and best practices for building GBL applications using Unity.

Why Use GBL?
* https://www.universityxp.com/blog/2019/4/16/why-use-games-based-learning

---

## 🌟 What Is Game-Based Learning?

Game-Based Learning applies game mechanics, narrative, and interactive systems to support specific learning outcomes. Unlike simple gamification, GBL integrates learning objectives directly into the gameplay loop. Effective GBL experiences typically include:

* **Clear learning goals** aligned to curriculum, skills, or performance outcomes
* **Interactive systems** where players experiment, test ideas, and see consequences
* **Motivational game mechanics** such as feedback loops, challenges, progression, or rewards
* **Assessment mechanisms** that measure learner understanding through gameplay, not just quizzes
* **Engaging stories, environments, or characters** that contextualize learning tasks

Game-Based Learning (Explained in 3 Minutes)
* https://www.youtube.com/watch?app=desktop&v=bZvLjAacVJg

---

## 🛠️ Designing GBL Experiences in Unity

### 1. Define Learning Objectives

Start with the learning goals, not the game mechanics. Every interaction and system in your scene should map to a curriculum goal, job task, or skill. Document these goals early so designers, developers, and subject-matter experts stay aligned.

### 2. Prototype Core Gameplay

Use Unity’s **prefabs**, **physics**, and **UI tools** to quickly prototype interactions that reinforce learning—puzzles, simulations, decision-making scenarios, tool manipulation, or environment exploration. Keep prototypes lightweight until the gameplay loop is validated.

### 3. Build Learning-Driven Systems

Common GBL mechanics supported by Unity include:

* **Action-Based Learning:** hands-on tasks using physics and interaction systems
* **Scenario-Based Learning:** dialogue, branching narratives, decision trees
* **Simulation-Based Learning:** systems modeling with scripts and real-world constraints
* **Puzzle or Challenge Loops:** logic challenges tied to subject concepts
* **Immediate Feedback Systems:** audio, visual, or UI feedback based on learner actions

### 4. Integrate Assessment and Analytics

Add gameplay-driven assessment through:

* Tracking task completion and accuracy
* Logging decisions or problem-solving steps
* Measuring timing, efficiency, and interactions
* Exporting performance data (JSON, CSV, LMS-compatible formats)

Unity’s flexible scripting makes it easy to capture and export learning analytics.

### 5. Deploy Across Platforms

Unity supports WebGL, desktop, VR, AR, and mobile—allowing GBL apps to reach classrooms, training centers, and remote learners. Always optimize performance and UX for the target device.

Game-Based Learning: 11 Tips To Get It Right
* http://playxlpro.com/11-tips-to-get-game-based-learning-right/

---

## GBL Video Tutorial

Building a Educational Game in Unity 3D
* https://www.youtube.com/watch?app=desktop&v=ZuH2f0knvh8

Unity Learn Game Design Document
* https://learn.unity.com/tutorial/fill-out-a-game-design-document#64cd0e2dedbc2a798e423ccf

---

## 🎨 Rapid UI Prototyping with the Unity Asset Store

Prototyping UI in Unity is fast, flexible, and highly visual, especially when leveraging high-quality assets from the Unity Asset Store. Unity’s Asset Store offers thousands of UI-focused packages—icon sets, fonts, button packs, templates, layout frameworks, shaders, and UX-ready prefabs. These resources accelerate early-stage development by providing:

* **Ready-made UI elements** (buttons, panels, icons, HUDs, menus)
* **Professional visual styles** without needing custom art
* **Reduced prototype time** so teams can focus on functionality
* **Consistent styling systems** for rapid iteration and testing
* **Cross-platform assets** compatible with desktop, mobile, XR, and WebGL

Using these assets early helps teams validate UX flows quickly before committing to custom art or deeper design.

Prototyping UI - Asset Store Resources
* https://assetstore.unity.com/packages/tools/gui/lean-gui-72138
* https://assetstore.unity.com/packages/tools/gui/3d-modern-menu-ui-116144
* https://assetstore.unity.com/packages/2d/gui/pinky-ui-274048

Styling Unity UI Elementa:
* https://www.youtube.com/watch?v=IuuKUaZQiSU

UI Kit For Vision Pro OS
* https://assetstore.unity.com/packages/tools/gui/ui-kit-for-vision-pro-os-265406

---

## 🛠️ Workflow for Prototyping UI with Asset Store Packages

### 1. Identify UI Needs

Before browsing the Asset Store, define what you need to prototype:

* Menu screens (Main Menu, Pause Menu, Settings)
* HUD elements (health bars, inventory, objective markers)
* Icons and glyphs
* Layout templates (grids, responsive panels)
* Stylized or themed UI packs

A clear requirements list makes it easier to pick the right package.

### 2. Find High-Quality Asset Store Packages

Look for packages with:

* Good reviews and support
* Multiple resolution options (especially for mobile)
* Source PSD/PNG or vector files
* Prefab variants for Unity UI (uGUI)
* Documentation and examples

Popular categories include:

* **UI Kits**: Complete button, panel, and widget collections
* **Icon Packs**: Vector icons in flat, outline, or themed sets
* **Fonts & Text Packs**: TMP-compatible fonts
* **Shaders & Effects**: Gradient, blur, and animated UI materials
* **Full UI Templates**: Ready-built menus and screen flows

### 3. Import and Organize Assets

Keep your project maintainable by organizing UI packages in a consistent structure:

```
/Assets
  /UI
    /Art
    /Icons
    /Fonts
    /Prefabs
    /Materials
    /Themes
    /ThirdParty
```

Place Asset Store packages under **/ThirdParty** to differentiate them from in-house UI components.

### 4. Build UI Layouts with Prefabs

Most UI kits include prefab buttons, panels, sliders, or templates. Use these to rapidly assemble working screens:

* Drag prefabs into your Canvas hierarchy
* Adjust anchors and constraints for responsive design
* Combine layout groups (horizontal, vertical, grid)
* Use masks, background textures, or 9-slice images

This approach allows rapid iteration across platforms.

---

## 🎨 Styling UI in Unity

Styling is essential to ensuring UI is cohesive, legible, and visually appealing. Unity provides many tools that work seamlessly with Asset Store packs.

### 1. Use TextMeshPro for Typography

Always switch to **TextMeshPro (TMP)** for crisp, scalable text rendering. TMP allows:

* Font weights, outlines, shadows
* Auto-sizing
* Rich text formatting
* High-resolution SDF fonts

Integrate TMP-compatible fonts from the Asset Store for consistent text systems.

### 2. Build Theme Palettes

Define a project-wide UI style guide:

* **Primary / Secondary colors**
* **Neutral colors for surfaces**
* **Accent colors for interactivity**
* **Error / Warning / Success standards**

Create ScriptableObjects or Material presets for consistent reuse.

### 3. Customize Asset Store Elements

Even pre-made assets should be tailored:

* Adjust color palettes
* Update fonts to match your brand
* Replace icons to match your theme
* Use 9-slice sprites for scalable panels
* Swap to custom materials for a unified style

This ensures your UI doesn’t feel like a patchwork of third-party elements.

### 4. Add Animation & Feedback

UI should feel responsive and alive:

* Button hover and press animations
* Scale or color transitions
* UI fades for popups
* Animated progress bars
* Particle or shader-based highlights

Use Unity’s **Animation**, **Animator**, or **UI Toolkit transitions**.

### 5. Optimize for Performance

Especially for mobile/XR:

* Use atlased textures
* Minimize overdraw (avoid full-screen transparent panels)
* Limit realtime shadow or bloom effects on UI
* Keep canvases small and modular

---

# 🎮 Midterm Assignment: Game-Based Learning Prototypes in Unity

The Midterm assignment **develop a prototype Game-Based Learning (GBL) application using the Unity game engine**. The goal was to design an interactive experience that integrates learning objectives with gameplay mechanics, demonstrating how games can teach through action, problem-solving, and feedback loops.

Grading was calculated based on four criteria:

* Game Based Learning App Design / Approach
* Functioning Game Mechanic / Event Triggers
* Quality of UI / Environment presentation and polish
* Effective and varied utilization of Unity Asset Store 

After reviewing the submissions, the students explored a wide range of mechanics and genres type with many projects venturing into topics and concepts that we have not covered in class. The following summaries will help us compare approaches and identify best practices resources for further development.

---

## 🗂️ GBL Prototype Submission Summaries

### 🏙️ 1. City Builder / Resource Management Game

Players must **manage resources, allocate tasks, and balance constraints** over time. Learning outcomes often targeted **strategic decision-making**, **systems thinking**, and **prioritization skills**. Mechanics included building placement, resource harvesting, budget management, and time-based production.

Basics of city builder/resource management: 
* https://www.youtube.com/watch?v=n5EN2J2FxOQ
* https://gamedevacademy.org/unity-city-building-game-tutorial

---

### 🧭 2. First-Person Exploration 

Gameplay focused on **environmental storytelling, spatial navigation, and discovery**. Learning was embedded through exploring scenes, triggering information nodes, and interacting with objects. Common learning goals included **observation**, **interpretation**, and **contextual knowledge acquisition**.

FPS Microgame Template
* https://assetstore.unity.com/packages/templates/unity-learn-fps-microgame-urp-156015

Create a FPS Microgame in Unity
* https://www.youtube.com/watch?v=5W41yZ6JjI0

---

### 🏃‍♂️ 3. Endless Runner

Classic infinite movement loops where players avoid obstacles, collect items, or maintain rhythm. These prototypes often emphasized **reflex-based learning**, **pattern recognition**, or **reinforcement through repetition**. Endless runners are effective for practicing speed, focus, and timed decision-making.

Endless Runner Template
* https://assetstore.unity.com/packages/templates/tutorials/endless-runner-sample-game-87901

Publish your first mobile runner game
* https://learn.unity.com/tutorial/publish-your-first-mobile-runner-game#63e9c88eedbc2a297b640566

---

### 🎮 4. Third-Person Character Exploration

Projects in this category involved **character-based movement**, environmental interaction, and light puzzle-solving. Students used third-person controllers to deliver learning through **interaction sequences**, **collectables**, and **narrative triggers**. These prototypes highlight learner agency and guided exploration.

Smooth Camera Third Person
* https://www.youtube.com/watch?v=o7O28SFGWS4

Character Controller
* https://www.youtube.com/playlist?list=PLBcfp6HMOJwzDcdCzoAx3jJKm7sIcBXJZ

---

### 🃏 5. Memory Match Card Game

Familiar classs concentration game focused on **cognitive training**, pattern memory, and recall. Gameplay typically involved matching pairs or solving themed card sets tied to a learning domain (language, science, history, etc.). These prototypes reinforce **short-term and working memory** skills. Having worked on a few of these in the past, an effective learning feedback practice, after a successful match is a prompt that displays information related to the card content.

3D Memory Match:
* https://www.youtube.com/watch?v=Hhqfi2-NsNI

Asset Store Shsder Graph Edge
* https://assetstore.unity.com/packages/vfx/shaders/ui-shader-effects-edge-effects-291229

Shader Graph Tutorials:
* https://learn.unity.com/tutorial/introduction-to-shader-graph
* https://www.youtube.com/watch?v=TbZYoSu1w8Y
* https://www.youtube.com/watch?v=x1-3sZDjeyk

---

### 🕵️ 6. Stealth Game

Avoiding detection/contact from enemy patrol using player mechanics to find ways of escape . Learning was connected to **strategy**, **timing**, **risk assessment**, and **spatial problem-solving**. v

Stealth Game Tutorial
* https://learn.unity.com/course/3d-stealth-game-haunted-house

Animating Chicken Tutorial/Asset
* https://www.youtube.com/watch?v=dg9SZytofIE&t=261s
* https://assetstore.unity.com/packages/3d/characters/animals/birds/chicken-animated-173605

Pet Chase Game Mechanic Asset
* https://assetstore.unity.com/packages/templates/packs/pet-chase-game-template-170751

---

### 🏓 7. Ball-Toss Game

Physics-based prototypes involve throwing or launching objects to hit targets or complete challenges which introduces physics components and force-based mechanics.

3D Pathfinding:
* https://www.youtube.com/watch?v=mJu-zdZ9dyE

3D Animation System:
* https://learn.unity.com/course/introduction-to-3d-animation-systems/unit/working-with-assets/tutorial/2-1-animation-window-features-and-settings?version=2019.4#5f34730eedbc2a002195db74

---

### ⏱️ 8. Timed Item Collection Game

Gameplay revolved around collecting objects within a time limit. These prototypes support learning through **prioritization**, **navigation**, **speed**, and **task sequencing**. Students explored collectible spawning, timers, UI feedback, and reward loops.

Collect The Collectible
* https://learn.unity.com/pathway/unity-essentials/unit/programming-essentials/tutorial/collect-the-collectible

Build Open World:
* https://www.youtube.com/watch?v=WbZpj8WcjN0

Inventory Manager: 
* https://www.youtube.com/watch?v=AoD_F1fSFFg

---

### 📝 9. Quiz-Based Game

Multiple-choice quiz systems integrated with gameplay loops such as scoring, feedback, and progress tracking. These prototypes align strongly with **knowledge reinforcement**, **retrieval practice**, and **self-assessment**. Designs included question databases, UI panels, and correctness animations.

Quiz Toolkit Asset:
* https://assetstore.unity.com/packages/essentials/tutorial-projects/quizu-a-ui-toolkit-sample-268492

Make a Quiz Game with Multiple Choices in Unity:
* https://www.youtube.com/watch?v=G9QDFB2RQGA

Unity AR Quiz Game
* https://www.youtube.com/watch?v=svYMrgkczrw

---

### 🌐 10. Language Learning Game

Prototypes combine vocabulary, pronunciation, or grammar tasks with engaging mechanics like matching, selecting, or arranging items. Learning outcomes focused on **language acquisition**, **recognition**, and **repetition**. Several projects integrated audio clips, iconography, and contextual learning tasks.

Dialog System: https://gamedevbeginner.com/dialogue-systems-in-unity/
* https://assetstore.unity.com/packages/tools/game-toolkits/basiclanguage-dialogsystem-224467

Language Learning Game:
* https://www.youtube.com/watch?v=ql55ndPXSzE

TMP Effects:
* https://www.youtube.com/watch?v=oBkplJ8N_NY

Text Animator:
* https://assetstore.unity.com/packages/tools/gui/text-animator-for-unity-ui-toolkit-and-text-mesh-pro-341308

---
