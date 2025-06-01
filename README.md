<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Information Website - Mahin Rahman</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&family=Roboto+Slab&display=swap');

  body {
    margin: 0;
    background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
    font-family: 'Poppins', sans-serif;
    color: #222;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  .container {
    max-width: 960px;
    margin: 40px auto;
    background: rgba(255, 255, 255, 0.25);
    backdrop-filter: blur(12px);
    border-radius: 16px;
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    padding: 40px;
    display: grid;
    grid-template-columns: 1fr 2fr 2fr;
    gap: 30px;
  }

  header {
    grid-column: 1 / 4;
    text-align: center;
    font-family: 'Roboto Slab', serif;
    font-size: 3rem;
    font-weight: 700;
    color: #004d7a;
    margin-bottom: 10px;
    user-select: none;
  }

  .name {
    grid-column: 1 / 4;
    text-align: center;
    font-family: 'Roboto Slab', serif;
    font-size: 2.5rem;
    font-weight: 700;
    color: #0077b6;
    margin-bottom: 30px;
    user-select: text;
  }

  .social {
    display: flex;
    flex-direction: column;
    gap: 20px;
    justify-content: flex-start;
    align-items: center;
  }

  .social a {
    text-decoration: none;
    color: #0077b6;
    font-weight: 600;
    font-size: 1rem;
    display: flex;
    align-items: center;
    gap: 12px;
    transition: color 0.3s ease;
  }
  .social a:hover {
    color: #00b4d8;
  }

  .social svg {
    width: 28px;
    height: 28px;
    fill: #0077b6;
    transition: fill 0.3s ease;
  }

  .social a:hover svg {
    fill: #00b4d8;
  }

  .bio {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #222;
    border-left: 3px solid #0077b6;
    padding-left: 15px;
  }

  /* Responsive */
  @media (max-width: 768px) {
    .container {
      grid-template-columns: 1fr;
      padding: 20px;
    }
    header, .name {
      font-size: 2.2rem;
    }
    .bio {
      border-left: none;
      padding-left: 0;
    }
    .social {
      flex-direction: row;
      justify-content: center;
      gap: 15px;
      margin-bottom: 20px;
    }
    .social a {
      font-size: 0.9rem;
    }
  }
</style>
</head>
<body>

<div class="container">
  <header>Information Website</header>
  <div class="name">Mahin Rahman</div>

  <nav class="social" aria-label="Social media and contact links">
    <a href="mailto:mahinrahman13140@gmail.com" target="_blank" rel="noopener noreferrer" title="Email">
      <svg viewBox="0 0 24 24"><path d="M20 4H4a2 2 0 00-2 2v12a2 2 0 002 2h16a2 2 0 002-2V6a2 2 0 00-2-2zm0 2l-8 5-8-5h16zm0 12H4V8l8 5 8-5v10z"/></svg>
      Email
    </a>
    <a href="https://wa.me/01770756964" target="_blank" rel="noopener noreferrer" title="WhatsApp">
      <svg viewBox="0 0 24 24"><path d="M20.52 3.48a11.93 11.93 0 00-16.89 0A11.93 11.93 0 002 14.18c.1 1.3.5 2.56 1.19 3.7l-1.45 5.3 5.43-1.39a11.92 11.92 0 005.25 1.21 11.93 11.93 0 008.13-20.52zm-3.24 13.15c-.25.7-1.48 1.33-2.04 1.42-.54.1-1.02.14-1.54-.28-.5-.4-1.85-1.9-2.14-2.13-.28-.24-.5-.34-.5-.68 0-.33.09-.5.13-.54.04-.04.1-.1.16-.16.07-.07.1-.1.14-.16.04-.06.02-.1 0-.14-.02-.04-.54-1.28-.75-1.75-.2-.46-.4-.4-.55-.4-.14 0-.3 0-.46 0-.16 0-.42.06-.64.3-.22.24-.84.82-.84 2 .01 1.18.87 2.32.99 2.48.12.16 1.74 2.68 4.22 3.75 2.48 1.07 3.57.86 4.21.75.63-.11 2.02-.82 2.31-1.61.3-.8.3-1.49.21-1.61z"/></svg>
      WhatsApp
    </a>
    <a href="https://www.facebook.com/mahin.rahman.757258" target="_blank" rel="noopener noreferrer" title="Facebook Profile">
      <svg viewBox="0 0 24 24"><path d="M22 12a10 10 0 10-11.7 9.87v-6.99H8v-2.88h2.3V9.66c0-2.27 1.34-3.53 3.4-3.53.98 0 2 .18 2 .18v2.2h-1.12c-1.1 0-1.44.67-1.44 1.36v1.62h2.45l-.39 2.88h-2.06v6.99A10 10 0 0022 12z"/></svg>
      Facebook Profile
    </a>
    <a href="https://www.facebook.com/mahin0o" target="_blank" rel="noopener noreferrer" title="Facebook Page">
      <svg viewBox="0 0 24 24"><path d="M22 12a10 10 0 10-11.7 9.87v-6.99H8v-2.88h2.3V9.66c0-2.27 1.34-3.53 3.4-3.53.98 0 2 .18 2 .18v2.2h-1.12c-1.1 0-1.44.67-1.44 1.36v1.62h2.45l-.39 2.88h-2.06v6.99A10 10 0 0022 12z"/></svg>
      Facebook Page
    </a>
    <a href="https://www.instagram.com/mahin0o0" target="_blank" rel="noopener noreferrer" title="Instagram">
      <svg viewBox="0 0 24 24"><path d="M7.75 2h8.5A5.75 5.75 0 0122 7.75v8.5A5.75 5.75 0 0116.25 22h-8.5A5.75 5.75 0 012 16.25v-8.5A5.75 5.75 0 017.75 2zm0 1.5A4.25 4.25 0 003.5 7.75v8.5A4.25 4.25 0 007.75 20.5h8.5a4.25 4.25 0 004.25-4.25v-8.5A4.25 4.25 0 0016.25 3.5h-8.5zM12 7a5 5 0 110 10 5 5 0 010-10zm0 1.5a3.5 3.5 0 100 7 3.5 3.5 0 000-7zm4.88-.12a1.12 1.12 0 11-2.24 0 1.12 1.12 0 012.24 0z"/></svg>
      Instagram
    </a>
    <a href="https://www.tiktok.com/@mahin0o0" target="_blank" rel="noopener noreferrer" title="TikTok">
      <svg viewBox="0 0 24 24"><path d="M12 2v5a5 5 0 005 5h5v-4a7 7 0 01-7-7zM10 9a7 7 0 11-7 7v4h4a5 5 0 005-5V9z"/></svg>
      TikTok
    </a>
    <a href="https://www.threads.net/@mahin0o0" target="_blank" rel="noopener noreferrer" title="Threads">
      <svg viewBox="0 0 24 24"><path d="M12 2L2 12h3v7h14v-7h3L12 2z"/></svg>
      Threads
    </a>
    <a href="https://www.youtube.com/@Mahin.0o0" target="_blank" rel="noopener noreferrer" title="YouTube">
      <svg viewBox="0 0 24 24"><path d="M10 15l5-3-5-3v6zM21 6.5a3 3 0 00-3-3H6a3 3 0 00-3 3v11a3 3 0 003 3h12a3 3 0 003-3v-11z"/></svg>
      YouTube
    </a>
  </nav>

  <section class="bio" aria-label="Biography">
    <p>
      Mahin Rahman is a passionate Computer Science student currently studying at Headway Engineering Institute, Sylhet. Dedicated to mastering the latest technologies and developing innovative software solutions, he combines creativity with technical expertise. Mahin is active on multiple social platforms and eager to connect, collaborate, and grow his digital presence.
    </p>
  </section>
</div>

</body>
</html>
