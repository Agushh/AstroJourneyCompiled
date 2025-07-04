<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Astro Journey – 2D Sandbox Adventure</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
        Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
      line-height: 1.6;
      margin: 20px;
      background-color: #1a1a1a;
      color: #eee;
    }
    h1, h2, h3 {
      color: #f0a500;
    }
    hr {
      border: 0;
      height: 1px;
      background: #444;
      margin: 30px 0;
    }
    a {
      color: #f0a500;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    img {
      max-width: 100%;
      height: auto;
      margin: 10px 0;
      border-radius: 6px;
      box-shadow: 0 0 8px rgba(240, 165, 0, 0.7);
    }
    pre {
      background: #222;
      padding: 15px;
      border-radius: 6px;
      overflow-x: auto;
    }
    code {
      font-family: monospace;
      background: #333;
      padding: 2px 5px;
      border-radius: 4px;
    }
    ul {
      list-style-type: none;
      padding-left: 0;
    }
    ul li {
      margin-bottom: 8px;
      padding-left: 1.5em;
      position: relative;
    }
    ul li::before {
      content: "🌟";
      position: absolute;
      left: 0;
    }
    section {
      margin-bottom: 40px;
    }
  </style>
</head>
<body>
  <h1>🌌 Astro Journey – 2D Sandbox Adventure</h1>

  <p><strong>Astro Journey</strong> is a 2D space survival sandbox game, developed independently as a professional practice project at Technical School No. 3 <em>Domingo Faustino Sarmiento</em>.<br />
  Created with <strong>Unity</strong> and <strong>C#</strong>, featuring retro <strong>pixel art</strong> style graphics.</p>

  <hr />

  <section>
    <h2>🧭 Overview</h2>
    <p>Astro Journey blends exploration, construction, and destruction mechanics within a procedurally generated universe. Inspired by games like <strong>Minecraft</strong>, <strong>Terraria</strong>, and <strong>Starbound</strong>, this project aims to deliver a free-form gameplay experience focused on player interaction and progression.</p>
    <p>The game is currently in <strong>Alpha</strong> stage, developed by a single student, making it an ambitious project that will keep evolving.</p>
  </section>

  <section>
    <h2>🚀 How to Run</h2>
    <p>After downloading the <code>.zip</code> containing all versions, select the desired version and run the executable named <code>AstroJourney.exe</code>.<br />
    For versions 1.1.3 and later, first extract the <code>.rar</code> file and then run the executable.</p>
  </section>

  <section>
    <h2>🛠️ Development Status</h2>
    <ul>
      <li>Procedural terrain generation using fractal noise, creating smooth and diverse landscapes with long highlands and lowlands for a lively world.</li>
      <li>Procedural cave generation combining noise layers to control cave quantity and shapes (still subject to improvement).</li>
      <li>Procedural texture generation using shaders with Voronoi algorithms to enrich block textures and avoid monotony. RuleTiles enable dynamic block connection.</li>
      <li>Dynamic lightmaps generated via custom shaders that overlay lighting effects per tile to add depth and graphical richness.</li>
      <li>Player mechanics featuring basic movement (left, right, jump) with animations and mouse directional facing.</li>
      <li>Block building and destruction system.</li>
      <li>Dynamic lighting.</li>
      <li>Local memory save/load system.</li>
      <li>Animated UI menus.</li>
      <li>Functional inventory and hotbar.</li>
      <li>Toggle between static and dynamic textures.</li>
      <li>Pause menu with control guide.</li>
    </ul>
  </section>

  <section>
    <h2>🔨 Technologies Used</h2>
    <ul>
      <li>Game engine: <strong>Unity (C#)</strong></li>
      <li>Graphics editor: <strong>Aseprite</strong></li>
      <li>IDE: <strong>Visual Studio 2022</strong></li>
      <li>Version control: <strong>GitHub &amp; GitHub Desktop</strong></li>
    </ul>
  </section>

  <section>
    <h2>🎥 Demo Video (Version 1.1.3)</h2>
    <p>Watch a short gameplay demonstration of version 1.1.3 here:<br />
    <a href="https://youtu.be/K2AWMYYg9is" target="_blank" rel="noopener noreferrer">https://youtu.be/K2AWMYYg9is</a></p>
  </section>

  <section>
    <h2>👨‍💻 Author</h2>
    <p><strong>Agustín Zalazar</strong><br />
    📧 <a href="mailto:agustinzalazar9@gmail.com">agustinzalazar9@gmail.com</a><br />
    🔗 <a href="https://github.com/Agushh/AstroJourneyCompiled/" target="_blank" rel="noopener noreferrer">Game Repository</a></p>
  </section>

  <section>
    <h2>🖼️ Visual References</h2>

    <h3>Procedural Terrain Example:</h3>
    <img src="https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/b7d18ce1-7b3c-4b0d-b85d-1f4733aad749" alt="Procedural Terrain" />

    <h3>Procedural Caves Example:</h3>
    <img src="https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/d976385c-ecdf-44bd-994d-48fdf391d8dd" alt="Procedural Caves" />

    <h3>Procedural Shader Textures:</h3>
    <img src="https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/0e965fd7-4e9b-4bc0-9669-63f36336482d" alt="Shader Textures" />

    <h3>RuleTiles Dynamic Block Connection:</h3>
    <img src="https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/665170d9-3461-4470-87f7-e7153b7e7210" alt="RuleTiles" />

    <h3>Dynamic Lightmap Shader:</h3>
    <img src="https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/1d52171c-556f-44bd-88ca-e4740959b552" alt="Lightmap" />

    <h3>Player Character Mechanics:</h3>
    <img src="https://github.com/Agushh/AstroJourneyCompiled/assets/67559610/b1be75d5-e968-405b-9242-ed92742dfba3" alt="Player Mechanics" />
  </section>
</body>
</html>
