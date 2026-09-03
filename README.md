<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yatharth Richhariya - GitAscii Profile</title>
<style>
  * { box-sizing: border-box; }
  html, body {
    margin: 0;
    padding: 0;
    background: #000;
  }
  .profile {
    position: relative;
    width: min(100%, 800px);
    margin: 0 auto;
    line-height: 0;
  }
  .profile > img {
    display: block;
    width: 100%;
    height: auto;
  }

  /* Clickable areas over the ORIGINAL GitAscii social icons.
     Coordinates are based on your JSON:
     social-media widget: x=378, y=290, width=416, height=120.
  */
  .social-link {
    position: absolute;
    top: 300px;
    width: 95px;
    height: 95px;
    display: block;
    z-index: 10;
    background: transparent;
  }

  .github  { left: 435px; }
  .linkedin { left: 545px; }
  .email { left: 655px; }

  .social-link:focus {
    outline: 2px solid #79c0ff;
    outline-offset: 2px;
  }
</style>
</head>
<body>

<div class="profile">

  <!-- EXACT GitAscii-generated design -->
  <img
    src="https://gitascii.com/api/yatharthrichhariya?v=1788419744660"
    alt="Yatharth Richhariya GitAscii Profile"
  >

  <!-- Invisible clickable overlays -->
  <a
    class="social-link github"
    href="https://github.com/yatharthrichhariya"
    target="_blank"
    rel="noopener noreferrer"
    aria-label="GitHub"
    title="GitHub">
  </a>

  <a
    class="social-link linkedin"
    href="https://www.linkedin.com/in/yatharth-richhariya"
    target="_blank"
    rel="noopener noreferrer"
    aria-label="LinkedIn"
    title="LinkedIn">
  </a>

  <a
    class="social-link email"
    href="mailto:yatharthrichhariya@gmail.com"
    aria-label="Email"
    title="Email">
  </a>

</div>

</body>
</html>
