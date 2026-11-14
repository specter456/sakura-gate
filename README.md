# Sakura Gate · 桜の門
### An Interactive Physics-Based Pearl Poem Curtain

Welcome to my interactive web project! This is a fully coded, physics-based simulation of a traditional Japanese *Noren* (curtain) made of pearls and poetry, hanging in the gate of a magical cherry blossom castle. 

## 🎬 The Inspiration
This project was inspired by a reference video I found of a hanging cloth of letters that reacted to mouse movements. I wanted to recreate that exact magical, sparkling aesthetic, but build it entirely from scratch using raw code—no drag-and-drop website builders. 

## ✨ Features
- **Verlet Integration Physics:** The curtain isn't just an image; it's made of hundreds of individual "beads" connected by invisible threads, reacting to gravity, wind, and mouse interaction in real-time.
- **Custom Web Audio Engine:** A procedurally generated, soothing Japanese *Furin* (wind chime) sound that triggers when you brush past the pearls.
- **Atmospheric Effects:** Falling Sakura petals, flying birds, twinkling gold/silver stars, and a dynamic ground shadow that sways with the curtain.
- **Custom "Atelier" UI:** Because aligning code to an AI-generated background is tricky, I built a custom control panel with sliders, keyboard nudging, and independent left/right slant controls to perfectly fit the curtain into the gate.
- **Persistent Memory:** Uses LocalStorage and IndexedDB to remember your exact alignment and settings every time you reopen the file.

## 🚧 The Journey & Hurdles Faced
Building this was a massive learning curve. Here are some of the challenges I overcame:

1. **The `.txt` Trap:** I started in Notepad and couldn't figure out why my code wasn't running. I learned the hard way that Windows hides file extensions, turning my `index.html` into `index.html.txt`. This pushed me to upgrade to **Visual Studio Code**, which was a game-changer.
2. **The Physics Problem:** Initially, the text looked like a rigid spreadsheet. I had to implement 2D Verlet physics with gravity and damping to make it swing like a real, heavy fabric curtain rather than a floating grid.
3. **The Audio Challenge:** Browsers block audio by default, and my early attempts sounded like a microwave beep or a crackling bubble. I had to learn the Web Audio API to layer sine waves, creating a pure, mathematical wind chime sound.
4. **The Alignment Struggle:** I used AI (Bing Image Creator) to generate the perfect Himeji Castle background, but the code-generated curtain wouldn't fit the gate. Instead of guessing numbers, I coded a real-time UI panel with arrow-key controls and a "Column Remover" to surgically trim and align the curtain to the roof's slant.

## 🛠️ Tech Stack
- **HTML5 Canvas** for rendering
- **Vanilla JavaScript** (No libraries or frameworks)
- **Web Audio API** for procedural sound
- **Verlet Integration** for physics simulation

## 🎓 Why I Built This
I am a Class 12 student from India with a deep passion for Computer Science, Robotics, and Japanese culture (currently preparing for the MEXT scholarship!). I wanted to build something that blends technical fundamentals (physics, audio synthesis) with artistic vision. This project proves that with enough iteration and curiosity, you can bring a magical vision to life purely through code.

---
*Built with persistence, a lot of trial and error, and a love for cherry blossoms.* 🌸
