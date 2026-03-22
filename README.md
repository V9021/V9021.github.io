<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Admiral's Landing</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <!-- HEADER -->
    <header class="navbar">
      <div class="logo">Admiral's Landing</div>

      <nav>
        <a href="our_story.html" target="_self">Farragut's Story</a>
        <a href="our_mission.html">Our Mission</a>
        <a href="local_events.html">Local Events</a>
        <a href="other_activities.html">Other Activities</a>
        <a href="community_forum.html">Community Forum</a>
        <a href="#">References</a>
        <a href="sign_up.html">Sign Up</a>
      </nav>
    </header>
    <!-- HERO -->
    <section class="hero">
      <h1>Attractions, Museums, and More!</h1>
      <p>
        For those with other interests
      </p>
    </section>
    <style>
    body {
      font-family: Arial, sans-serif;
    }

    .features {
      display: flex;
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: #f4f4f4;
      padding: 30px;
      border-radius: 10px;
      cursor: pointer;
      width: 150px;
      text-align: center;
      transition: 0.3s;
    }

    .card:hover {
      background: #ddd;
    }

    /* Popup styles */
    .popup {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.6);
    }

    .popup-content {
      background: white;
      padding: 20px;
      margin: 15% auto;
      width: 300px;
      border-radius: 10px;
      text-align: center;
      position: relative;
    }

    .close {
      position: absolute;
      right: 10px;
      top: 5px;
      font-size: 24px;
      cursor: pointer;
    }
  </style>
    <!-- FEATURES -->
    <section class="features">
      <div class="card" data-popup="popup1">
        <h3>Anchor Park</h3>
      </div>
      <div class="card" data-popup="popup2">
        <h3>Campbell Station Inn</h3>
      </div>
      <div class="card" data-popup="popup3">
        <h3>Farragut History Walk</h3>
      </div>
      <div class="card" data-popup="popup4">
        <h3>McFee Splash Pad</h3>
      </div>
    </section>
    <section class="features">
      <div class="card" data-popup="popup5">
        <h3>Founders Park at Campbell Station</h3>
      </div>
      <div class="card" data-popup="popup6">
        <h3>Willow Creek Golf Club</h3>
      </div>
      <div class="card" data-popup="popup7">
        <h3>Farragut Museum</h3>
      </div>
      <div class="card" data-popup="popup8">
        <h3>Cool Sports</h3>
      </div>
    </section>
    <section class="features">
      <div class="card" data-popup="popup9">
        <h3>Admiral Farragut Plaza</h3>
      </div>
      <div class="card" data-popup="popup10">
        <h3>Pleasant Forest Cemetery</h3>
      </div>
      <div class="card" data-popup="popup11">
        <h3>Topgold Knoxville</h3>
      </div>
      <div class="card" data-popup="popup12">
        <h3>Civil War Trails Historical Marker</h3>
      </div>
    </section>
    <section class="features">
      <div class="card" data-popup="popup13">
        <h3><a href="">Mayor Bob Leanard Park</a></h3>
      </div>
      <div class="card" data-popup="popup14">
        <h3><a href="">Farragut Folklore Museum</a></h3>
      </div>
      <div class="card" data-popup="popup15">
        <h3><a href="">Fort Sanders</a></h3>
      </div>
    </section>
    <div class="popup" id="popup1">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p></p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup2">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Campbell Station Innk</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup3">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2></h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup4">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup5">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup6">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup7">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup8">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup9">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup10">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup11">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup12">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup13">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup16">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup15">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Anchor Park</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <section class="hero">
      <h1>Dining</h1>
      <p>
        The best places to eat!
      </p>
    </section>
    <section class="features">
      <div class="card" data-popup="popup16">
        <h3>35 North</h3>
      </div>
      <div class="card" data-popup="popup17">
        <h3>Buttermilk Sky Pie</h3>
      </div>
      <div class="card" data-popup="popup18">
        <h3>Yamato Ramen House</h3>
      </div>
      <div class="card" data-popup="popup19">
        <h3>Tupelo Honey</h3>
      </div>
    </section>
    <section class="features">
      <div class="card" data-popup="popup20">
        <h3>Summer Moon Coffee</h3>
      </div>
      <div class="card" data-popup="popup21">
        <h3>Pin Thai</h3>
      </div>
      <div class="card" data-popup="popup22">
        <h3>Parlor Doughnuts</h3>
      </div>
      <div class="card" data-popup="popup23">
        <h3>First Watch</h3>
      </div>
    </section>
    <div class="popup" id="popup16">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>35 North</h2>
        <p></p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup17">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Buttermilk Sky Pie</h2>
        <p></p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup18">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Yamato Ramen House</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup19">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Tupelo Honey</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup20">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Summer Moon Coffee</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup21">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Pin Thai</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup22">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>Parlor Doughnuts</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>
    <div class="popup" id="popup23">
      <div class="popup-content">
        <span class="close">&times;</span>
        <h2>First Watch</h2>
        <p>Learn more about this park:</p>
        <a href="https://www.townoffarragut.org/784/Farragut-Parks" target="_blank">
          Visit Page For More Information
        </a>
      </div>
    </div>

  <script>
  const cards = document.querySelectorAll(".card");
  const popups = document.querySelectorAll(".popup");
  const closes = document.querySelectorAll(".close");

  // Open popup
  cards.forEach(card => {
    card.addEventListener("click", () => {
      const popupId = card.getAttribute("data-popup");
      document.getElementById(popupId).style.display = "block";
    });
  });

  // Close popup (X button)
  closes.forEach(btn => {
    btn.addEventListener("click", () => {
      btn.closest(".popup").style.display = "none";
    });
  });

  // Close when clicking outside content
  window.addEventListener("click", (e) => {
    popups.forEach(popup => {
      if (e.target === popup) {
        popup.style.display = "none";
      }
    });
  });
</script>
  </body>
</html>
