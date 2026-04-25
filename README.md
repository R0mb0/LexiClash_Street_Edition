<div align="center">
<h1>🏙️ LexiClash: Street Edition 🔠</h1>

[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)

<p>
A high-stakes, fast-paced word puzzle game inspired by classic British game shows. Features "Frizzy Rules" with hidden letter values, strategic point spending for extra letters, and a vibrant, responsive UI. Supports up to 10 players with full state persistence. Perfect for parties and competitive nerds! 🔥
</p>

<h2><a href="[https://r0mb0.github.io/LexiClash_Street_Edition/]">👉 Click here to play the game! 👈</a></h2>

</div>

Image :)

<hr>

<h2>🚀 Features</h2>
<ul>
<li><strong>Interactive Game Board</strong>: A dynamic grid of letters with designated points. Click to flip cards, select letters, and build your winning word.</li>
<li><strong>Smart Correction Dock</strong>: A sleek, sticky glassmorphism panel anchored at the bottom of the screen. It validates your typed words in real-time against the available letters on the board, calculating the estimated score on the fly!</li>
<li><strong>Bilingual Support</strong>: Built-in localization! Seamlessly switch between English and Italian interfaces with a single tap.</li>
<li><strong>Local Save System</strong>: Interrupted game? No problem. The state of the game (players, scores, and remaining letters) is automatically saved in your browser's <code>localStorage</code>.</li>
<li><strong>Confetti & Animations</strong>: Fluid CSS animations for card flipping, UI transitions, and a custom HTML5 canvas confetti celebration when a player scores!</li>
<li><strong>Dark/Light Theme Ready</strong>: Automatically adapts to your system's color scheme with a beautiful neon-accented street aesthetic.</li>
<li><strong>100% Client-Side</strong>: Built with pure HTML, CSS, and Vanilla JavaScript. No servers, no backend, total privacy.</li>
</ul>

<h2>🛠️ How it works</h2>
<ol>
<li><strong>Game Initialization:</strong> The app loads the dictionary and initializes the letter board based on language settings. It checks <code>localStorage</code> to resume a previous session if available.</li>
<li><strong>The Turn Loop:</strong> Players tap letters on the virtual board to select them. The app dynamically tracks which letters are active and calculates the potential score.</li>
<li><strong>Real-time Validation:</strong> When using the "Correction" phase, the smart dock listens to every keystroke (<code>input</code> event), instantly checking if the typed characters match the available <code>state.board.letters</code>, preventing cheating and showing live score estimations.</li>
<li><strong>Dynamic UI Rendering:</strong> The entire interface is rendered dynamically via JavaScript template literals, ensuring the DOM is always perfectly synced with the game state without needing page reloads.</li>
</ol>

<h2>🏆 What makes it special?</h2>
<ul>
<li><strong>App-Like Experience</strong>: Designed specifically to feel like a native mobile app. The combination of fixed docks, scrollable areas, and touch-friendly buttons creates a flawless mobile experience.</li>
<li><strong>Elegant Layout Engineering</strong>: Solves complex UI challenges (like keeping the correction panel fixed without hiding the game board) using advanced CSS techniques like <code>position: sticky</code>, responsive padding, and Flexbox.</li>
</ul>

<h2>💡 Why use this project?</h2>
<ul>
<li><strong>For Game Nights</strong>: The perfect companion for offline evenings with friends. Just open it on a tablet or a laptop, place it in the middle of the table, and start playing!</li>
</ul>

<h2>⚡ Getting Started</h2>

<h3>Online</h3>
<p>Simply open the <a href="[https://r0mb0.github.io/LexiClash_Street_Edition/]">Live Demo link</a> on any device and start clashing!</p>

<h3>Local Installation</h3>
<p>Want to run it locally or customize the rules/letters?</p>
<ol>
<li><strong>Clone this repository</strong> or download the source code ZIP.</li>
<li>Double-click <code>index.html</code> to open it in your favorite browser.</li>
<li>Play around with the <code>config.js</code> or the dictionary arrays to add your own custom letters or rules!</li>
</ol>

<br>

<div align="center">
  <h3>Dedicated with love to Lucia ❤️</h3>
</div>

<br>

<a href="https://github.com/R0mb0/Crafted_with_AI">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAILight.svg">
<img alt="Crafted with AI" src="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDefault.svg">
</picture>
</a>
