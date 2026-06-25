<div align="center">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Sass" />
  <img src="https://img.shields.io/badge/Engine-Stockfish%20API-4B5263?style=for-the-badge&logo=data:image/png;base64..." alt="Stockfish API" />

  <br/><br/>

  <h1>Full-Stack Web Chess</h1>
  <pre>
   _  _ 
  ( \/ )
   \  / 
   /  \ 
  /____\
  [====]
  </pre>
  <p><em>A modern, feature-rich chess experience powered by Angular and the Stockfish Engine.</em></p>
</div>

<hr />

<h2>The Project</h2>
<p>Experience the classic game of chess seamlessly in your browser. This project is a fully realized chess application built to handle complex game logic, state management, and real-time AI integration. Whether challenging a friend locally or testing your skills against a world-class engine, the interface remains smooth, responsive, and intuitive.</p>
<p>A month of focused engineering went into crafting a reliable game state, polished move handling, and a clean UI using official Lichess assets.</p>

<hr />

<h2>Key Features</h2>
<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Dual Game Modes</strong></td>
      <td>Play locally against a friend (2-player) or battle the AI.</td>
    </tr>
    <tr>
      <td><strong>Stockfish AI Integration</strong></td>
      <td>Play against the computer with 5 adjustable difficulty levels powered by the Stockfish REST API (<code>stockfish.online</code>).</td>
    </tr>
    <tr>
      <td><strong>Comprehensive Game Logic</strong></td>
      <td>Accurately detects complex game states including Check, Checkmate, and Stalemate.</td>
    </tr>
    <tr>
      <td><strong>Move History Tracking</strong></td>
      <td>Real-time logging of match progress using standard algebraic notation (PGN style).</td>
    </tr>
    <tr>
      <td><strong>Interactive Board Controls</strong></td>
      <td>Includes a "Flip Board" mechanism for better viewing angles and active piece highlighting.</td>
    </tr>
    <tr>
      <td><strong>Polished UI & Audio</strong></td>
      <td>Sleek piece graphics sourced from the official <code>lichess-org</code> repository, paired with intuitive sound effects.</td>
    </tr>
  </tbody>
</table>

<hr />

<h2>Architecture & Tech Stack</h2>
<p>While standard chess games can be built in vanilla JS, this project utilizes a modern framework architecture to maintain strict typing and modular game logic.</p>
<ul>
  <li><strong>Frontend Framework:</strong> Angular</li>
  <li><strong>Language:</strong> TypeScript</li>
  <li><strong>Styling:</strong> SCSS / Custom Theming (<code>custom-theme.scss</code>)</li>
  <li><strong>Game Logic Engine:</strong> Custom TypeScript logic (<code>app/chess-logic/</code>)</li>
  <li><strong>AI Backend:</strong> External Stockfish REST API</li>
</ul>

<hr />

<h2>Directory Structure</h2>
<pre><code>
Chess-Game/
├── app/
│   ├── chess-logic/      # Core rules, state management, and move validation
│   ├── modules/          # Angular feature modules
│   ├── routes/           # Application routing
│   ├── app.component.* # Root component (HTML, SCSS, Spec, TS)
│   └── app.module.ts     # Main application module
├── assets/               # Lichess piece graphics and sound effects
├── styles.css            # Global styling
└── custom-theme.scss     # Application-specific UI themes
</code></pre>

<hr />

<h2>Setup & Installation</h2>
<p>To run this project locally, ensure you have <a href="https://nodejs.org/">Node.js</a> and the <a href="https://angular.io/cli">Angular CLI</a> installed.</p>

<p><strong>1. Clone the repository:</strong></p>
<pre><code>git clone https://github.com/Shahrukh-aidev/Chess-Game.git
cd Chess-Game/Chess-Game</code></pre>

<p><strong>2. Install dependencies:</strong></p>
<pre><code>npm install</code></pre>

<p><strong>3. Launch the development server:</strong></p>
<pre><code>ng serve</code></pre>

<p><strong>4. Play:</strong></p>
<p>Open your browser and navigate to <code>http://localhost:4200/</code>.</p>

<hr />

<h2>License</h2>
<pre><code>Apache License 2.0 — Free to use, modify, and distribute.</code></pre>
