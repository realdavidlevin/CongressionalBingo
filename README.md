🏛️ Judiciary Bingo: GOP Oversight Edition
A high-performance, single-file YouTube Playable designed to gamify the viewing experience of House Judiciary Committee hearings. This project focuses on the official @HouseJudiciaryGOP feed, providing a 40/60 split-screen layout for simultaneous watching and interaction.

🚀 Quick Start (Fixing Error 153)
Because this app uses the YouTube IFrame Player API, browsers require a valid origin. Opening the file directly (C:/Users/...) will cause a Video Configuration Error (153).

The Fix: Run a Local Server
VS Code: Install the Live Server extension. Right-click index.html → Open with Live Server.

Python: Open your terminal in the project folder and run:

Bash
python -m http.server 8000
Access: Open your browser to http://localhost:8000.

✨ Features
Integrated GOP Feed: Hardcoded to the official House Judiciary GOP oversight testimony (Special Counsel Jack Smith).

5x5 Traditional Grid: Includes a "Free Space" and 24 procedurally generated legal/procedural buzzwords.

YouTube Aesthetic: * Glowing Red Tiles: Toggles to a solid "YouTube Red" with a neon glow (No green checkmarks).

Particle Celebration: High-velocity "firewords" (confetti) burst upon completing a Bingo.

Responsive Split-Screen: Optimized for mobile Playables with a centered 16:9 player above the game board.

🛠️ Technical Stack
Frontend: HTML5, CSS3, Vanilla JavaScript.

APIs: * YouTube IFrame Player API (Video Control)

YouTube Playables SDK (Save/Load State ready)

Animations: Canvas API for physics-based particle effects.

📝 Word List Logic
To maintain high engagement, the buzzwords were curated from the Jack Smith testimony transcript, focusing on procedural highlights:

Rule of Law, Weaponization, Subpoena, Metadata, Executive Privilege, etc.

⚖️ License
This project is intended for educational use and as a boilerplate for YouTube Playables submissions.
