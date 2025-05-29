
[<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Dark Chief's Personal Demo Web</title>
    <style>
      :root {
        --main-bg: #000;
        --glow-blue: #00f0ff;
        --highlight-yellow: #ffe600;
        --text-light: #ccc;
      }

      body {
        background-color: var(--main-bg);
        color: var(--highlight-yellow);
        font-family: "Segoe UI", sans-serif;
        margin: 0;
        padding: 0;
      }

      header {
        background: linear-gradient(to right, #000000, #002244);
        padding: 20px;
        box-shadow: 0 0 20px var(--glow-blue);
        text-align: center;
      }

      h1 {
        font-size: 2.5em;
        color: var(--glow-blue);
        text-shadow: 0 0 10px var(--glow-blue);
      }

      .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        padding: 40px 20px;
      }

      .art {
        border: 2px solid var(--glow-blue);
        border-radius: 10px;
        padding: 10px;
        background: #111;
        box-shadow: 0 0 10px var(--glow-blue);
        max-width: 300px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
      }

      .art:hover {
        transform: scale(1.05);
        box-shadow: 0 0 20px var(--highlight-yellow);
      }

      .art img {
        width: 100%;
        border-radius: 10px;
      }

      .art p {
        margin-top: 10px;
        color: var(--text-light);
      }

      .contact {
        background: #111;
        padding: 40px 20px;
        text-align: center;
      }

      .contact h2 {
        color: var(--highlight-yellow);
        margin-bottom: 20px;
      }

      .contact p {
        color: var(--text-light);
        margin: 5px 0;
      }

      footer {
        background: #000;
        padding: 20px;
        color: #666;
        font-size: 0.9em;
        text-align: center;
      }

      @media (max-width: 768px) {
        .gallery {
          flex-direction: column;
          align-items: center;
        }
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Dark Chief's Personal Demo Web</h1>
      <p>My Art. My Voice. My Vision.</p>
    </header>

    <section class="gallery">
      <div class="art">
        <img
          src="https://i.ibb.co/xtmczCm2/476456030-1742347439661439-5098049306525920239-n.jpg"
          alt="Art 1"
        />
        <p>"Spirit of the Sea" – 2024</p>
      </div>
      <div class="art">
        <img
          src="https://i.ibb.co/0VpFqgmG/476932132-1742698492959667-7952671067325428594-n.jpg"
          alt="Art 2"
        />
        <p>"Warrior's Flame" – 2025</p>
      </div>
      <div class="art">
        <img
          src="https://i.ibb.co/XZmcq8DT/476462686-1742337259662457-8661363216769551072-n.jpg"
          alt="Art 3"
        />
        <p>"Cyber God" – 2024</p>
      </div>
    </section>

    <section class="contact">
      <h2>Contact Me</h2>
      <p>Email: kolaoibilly2223@gmail.com</p>
      <p>
        Facebook: <a href="https://www.facebook.com/billy.kolaoi" 
        style="color: var(--glow-blue)"
        >@Billy_CK
      </p>
      <p>
        Instagram:
        <a
          href="https://www.instagram.com/darkchief_art"
          style="color: var(--glow-blue)"
          >@darkchief_art</a
        >
      </p>
    </section>

    <footer>&copy; 2025 Billy C kolaoi. All rights reserved.</footer>
  </body>
</html>
Uploading index.html…]()[/* Global Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

body {
  background-color: #0b0c10;
  color: #f0f0f0;
  line-height: 1.6;
  padding: 1rem;
}

/* Header */
header {
  text-align: center;
  padding: 2rem 1rem;
  background: linear-gradient(to right, #0f0c29, #302b63, #24243e);
  color: #00ccff;
  text-shadow: 0 0 10px #00ccff;
  border-bottom: 2px solid #00ccff;
}

header h1 {
  font-size: 2.5rem;
  letter-spacing: 2px;
}

/* Gallery Grid */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

/* Image Cards */
.artwork {
  background-color: #1f1f1f;
  border: 2px solid #333;
  padding: 1rem;
  border-radius: 12px;
  box-shadow: 0 0 10px #00000070;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.artwork:hover {
  transform: scale(1.03);
  box-shadow: 0 0 15px #00ccff;
}

.artwork img {
  width: 100%;
  border-radius: 8px;
  border: 1px solid #444;
}

/* Captions */
.artwork p {
  text-align: center;
  margin-top: 0.5rem;
  color: #ffdf00;
  font-weight: bold;
}

/* Footer / Contact */
footer {
  margin-top: 3rem;
  padding: 2rem 1rem;
  text-align: center;
  background: #101010;
  color: #aaa;
  border-top: 2px solid #00ccff;
}

footer a {
  color: #00ccff;
  text-decoration: none;
  transition: color 0.3s ease;
}

footer a:hover {
  color: #ffdf00;
}
Uploading styles.css…]()


