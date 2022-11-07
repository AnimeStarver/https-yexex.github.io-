
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Home</title>
  <link rel="icon" type="image/png" href="favicon.png" />
  <link href="new.css" rel="stylesheet" type="text/css" />
  <link href="snackbar.css" rel="stylesheet" type="text/css" />
  <script src="https://kit.fontawesome.com/8df7d40c3b.js" crossorigin="anonymous"></script>
</head>

<body>
   <!-- Navigation Bar -->
  <nav class="bar" id="nav">
    <!-- Site Header -->
    <h2 id="header"><a class="yex">Yex</a>'s Games</h2>
    <!-- Navigation Bar Toggle -->
    <a class="updown" id="updown" onclick="b=!b; xd()"><i id='ud' class="fa fa-fw fa-angle-double-up"></i></a>
    <a class="active"><i class="fa fa-fw fa-home"></i></a>
    <a href="about.html" data-tippy-content="About"><i class="fa fa-fw fa-info-circle"></i></a>
    <a href="games.html" data-tippy-content="Games"><i class="fa fa-fw fa-gamepad"></i></a>
    <!-- Options Dropdown -->
    <div class="has-dropdown"> 
      <button id="settings" data-tippy-content="Settings"><i class="fa fa-fw fa-gear"></i></button>
      <ul class="dropdown">
        <li class="dropdown-item">
          <a onclick="theme('red', this)" href="#">Red</a>
        </li>
        <li class="dropdown-item">
          <a onclick="theme('rgb(50, 150, 255)', this)" href="#" class="active">Blue</a>
        </li>
        <li class="dropdown-item">
          <a onclick="theme('limegreen', this)" href="#">Green</a>
        </li>
        <li class="dropdown-item">
          <input type="color" id="thmclr"> 
          <a href="#" data-custom onclick="theme('white', this, true)">Custom</a>
        </li>
      </ul>
    </div>
    <a href="bookmarklets.html" data-tippy-content="Bookmarklets"><i class="fa fa-fw fa-bookmark"></i></a>
    <a href="chat.html" data-tippy-content="Chat"><i class="fa fa-fw fa-wechat"></i></a>
    <a href="https://discord.gg/V49EfgSWgr" data-tippy-content="Discord"><i class="fab fa-discord"></i></a>
    <a href="ide.html" data-tippy-content="IDE"><i class="fa fa-fw fa-code"></i></a>
  </nav>
  <!-- Loader -->
  <div class="loader">
    <div class="loader-logo">
      <img src="favicon.png" class="loader-logo-image"></img>
      <h1 class="loader-logo-title"> Yex </h1>
    </div>
    <div class="loader-bar"></div>
  </div>
  <div class="loaded-overlay"></div>
  <!-- Page Contents -->
  <h1 id='htitle'>Welcome!</h1>
  <p> This website is brought to you by <a class="lumi">Luminous Technologies</a>, visit the <i class="fa fa-fw fa-info-circle"></i> page for info about us <br>and our main dev, <a class="yex">Yex</a>. Games are on the <i class="fa fa-fw fa-gamepad"></i> page, and all should work and be unblocked.<br>Visit the <i class="fa fa-fw fa-bookmark"></i> page for bookmarklets, they modify the page you are on.<br>This page is in development and is recieving constant updates.<br> Open <i class="fa fa-fw fa-wechat"></i> or the <i class="fab fa-discord"></i> (disc server) to speak with other users. 
  <br> Contact us via <i class="fab fa-discord"></i> or <i class="fa fa-fw fa-wechat"></i> to request games/give feedback.</p>
  <!-- Scripts -->
  <script src="popper.js"></script>
  <script src="tippy.js"></script>
  <script src="snackbar.js"></script>
  <script src="updown.js"></script>
</body>
</html>
