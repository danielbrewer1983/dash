<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>BREWER HOME</title>
    <style>
      body {
        background-color: red;
        color: black;
        font-family: Arial, sans-serif;
        text-transform: uppercase;
        font-size: 28px;
        margin: 0;
        padding: 20px;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
      }

      a {
        background-color: #007BFF;
        color: black;
        padding: 12px 20px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        border-radius: 8px;
        transition: background-color 0.3s ease, color 0.3s ease;
        margin: 10px auto;
        font-weight: bold;
        font-size: 22px;
      }

      a:hover {
        background-color: #0056b3;
        color: #ffffff;
      }

      .dropdown {
        position: relative;
        display: flex;
        justify-content: center;
        margin: 15px auto;
      }

      .dropdown-content {
        display: none;
        position: absolute;
        background-color: #007BFF;
        min-width: 180px;
        box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.2);
        z-index: 1;
        border-radius: 8px;
        overflow: hidden;
        left: 50%;
        transform: translateX(-50%);
      }

      .dropdown-content a {
        padding: 12px 16px;
        display: block;
        text-align: center;
        font-weight: bold;
        font-size: 22px;
        color: black;
      }

      .dropdown-content a:hover {
        background-color: #0056b3;
        color: white;
      }

      .dropdown:hover .dropdown-content {
        display: block;
      }

      .dropbtn {
        font-size: 22px;
        background-color: #007BFF;
        color: black;
        padding: 12px 20px;
        border: none;
        cursor: pointer;
        border-radius: 8px;
      }

      .toggle {
        margin: 20px 0;
        text-align: center;
      }

      .toggle button {
        font-size: 22px;
        background-color: #007BFF;
        color: black;
        padding: 12px 20px;
        border: none;
        border-radius: 8px;
        cursor: pointer;
      }

      .toggle-links {
        display: none;
        flex-direction: column;
        margin-top: 10px;
      }

      .toggle-links a {
        margin: 8px auto;
      }

      img {
        max-width: 100%;
        height: auto;
        margin: 20px 0;
      }

      hr {
        border: 1px solid #000;
        width: 80%;
        margin: 20px auto;
      }
    </style>
    <script>
      function togglePearls() {
        const links = document.getElementById("pearlsLinks");
        links.style.display = links.style.display === "flex" ? "none" : "flex";
      }
    </script>
  </head>
  <body>
    <h1>Brewer Home</h1>

    <a href="https://forms.clickup.com/9010099348/f/8cgpd4m-4334/R8YMECKX2IE17KGOL2" target="_blank">To Do Form</a><br />
    <a href="https://app.clickup.com/9010099348/v/b/li/901407160371" target="_blank">To Do Board</a><br />
    <a href="https://auspicious-somber-espadrille.glitch.me/" target="_blank">Comms Menu</a><br />
    <a href="https://sharing.clickup.com/9010099348/wb/h/8cgpd4m-4534/f514495276aefe9" target="_blank">Goals Whiteboard</a><br />

    <div class="dropdown">
      <button class="dropbtn">Drops</button>
      <div class="dropdown-content">
        <a href="https://www.facebook.com" target="_blank">Facebook</a>
        <a href="https://www.instagram.com" target="_blank">Instagram</a>
        <a href="https://www.x.com" target="_blank">X.com</a>
      </div>
    </div>

    <div class="dropdown">
      <button class="dropbtn">Top AI Podcasts</button>
      <div class="dropdown-content">
        <a href="https://lexfridman.com/podcast/" target="_blank">Lex Fridman Podcast</a>
        <a href="https://www.latent.space/podcast" target="_blank">Latent Space</a>
        <a href="https://openai.com/blog/the-gpt-review" target="_blank">The GPT Review</a>
        <a href="https://www.vox.com/ai-podcast" target="_blank">The AI Alignment Problem</a>
        <a href="https://www.talkpython.fm/episodes/show/456/artificial-intelligence" target="_blank">Talk Python: AI Series</a>
      </div>
    </div>

    <div class="toggle">
      <button onclick="togglePearls()">PEARLS</button>
      <div class="toggle-links" id="pearlsLinks">
        <a href="https://pearlkingdom.carrd.co/" target="_blank">PEARL KINGDOM</a>
        <a href="https://doc.clickup.com/9010099348/p/h/8cgpd4m-814/59a51b47df8286e/8cgpd4m-1154" target="_blank">Square Links</a>
      </div>
    </div>

    <hr />

    <img src="https://cdn.glitch.global/bdd4ea00-86d0-4858-a8d0-3df5a092bbe9/7f82c1d1b08d357690e08fcb560528c6-rainbow-colorful-doodle%20(1).webp?v=1735450159552" alt="Rainbow Colorful Doodle" />

    <a href="https://forms.clickup.com/9010099348/f/8cgpd4m-4514/P81ICTLZCK8QEY9XGY" target="_blank">How Many Words?</a><br />
    <a href="https://forms.clickup.com/9010099348/f/8cgpd4m-4194/NSZ2H0IEUX4LE82I9P" target="_blank">BIGTASK FORM</a><br />
    <a href="https://app.clickup.com/9010099348/v/b/6-901407232103-2" target="_blank">Chore Deep Dive</a><br />
    <a href="https://chatgpt.com/" target="_blank">AI</a><br />

    <a href="https://www.jotform.com/app/230813754753156" target="_blank">Brewer App</a><br />
    <p>Tools to make tools<br />By having a centralized system<br />to manage tasks, appointments, and notes,<br />you can focus on what truly matters.</p>

    <a href="https://marred-elderly-hell.glitch.me" target="_blank">URL Tools</a><br />
    <a href="https://agate-discovered-nation.glitch.me/" target="_blank">Moose Dropdown</a><br />
    <a href="https://app.clickup.com/9010099348/v/dc/8cgpd4m-1834" target="_blank">Hack Beta</a><br />
    <a href="https://oldmoose.mailchimpsites.com/blank" target="_blank">Hack 2.0</a><br />
    <a href="https://dull-lydian-plot.glitch.me" target="_blank">Glitch Edit</a><br />

    <a href="https://app.clickup.com/9010099348/v/f/90144037193/90100437332" target="_blank">Personal Upgrades Brave Book</a><br />
    <a href="https://app.clickup.com/9010099348/v/f/90140367281/90100437332" target="_blank">Productivity Hacks ClickUp Folder</a><br />

    <img src="https://t9010099348.p.clickup-attachments.com/t9010099348/e73f012e-1336-4f24-89e7-0458864f4d1f/find_15643652.png?view=open" alt="Find Image" />

    <a href="https://forms.clickup.com/9010099348/f/8cgpd4m-3854/HRHX9TI76MANW8RRRA" target="_blank">500 Word Writing Prompt 4 Ai</a><br />
    <a href="https://app.clickup.com/9010099348/v/gr/8cgpd4m-3954" target="_blank">500 Words Table</a><br />
    <a href="https://app.clickup.com/9010099348/v/li/901407165238" target="_blank">500!</a><br />
    <a href="https://app.clickup.com/9010099348/v/f/90144058018/90140141544" target="_blank">Keenmind Folder</a><br />
  </body>
</html>
