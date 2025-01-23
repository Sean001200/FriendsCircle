# FriendsCircle
Social Media
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Facebook-Like Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="search-bar">
      <input type="text" placeholder="Search">
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#messages">Messages</a>
    </nav>
  </header>
  <main>
    <section class="profile">
      <div class="profile-pic"></div>
      <div class="profile-info">
        <h2>Profile Name</h2>
        <p>@username</p>
        <p>Birthday</p>
        <div class="tabs">
          <a href="#about">About</a>
          <a href="#contact">Contact</a>
        </div>
      </div>
    </section>
    <section class="content">
      <div class="post-type">
        <button>Photo</button>
        <button>Video</button>
      </div>
      <div class="post-box">
        <textarea placeholder="Write your post..."></textarea>
        <button class="post-btn">Post</button>
      </div>
      <div class="post-actions">
        <button>Like</button>
        <button>Comment</button>
        <button>Share</button>
      </div>
    </section>
    <aside class="sidebar">
      <div class="friends">
        <h3>Friends</h3>
        <ul>
          <li><input type="checkbox"> Friend 1</li>
          <li><input type="checkbox"> Friend 2</li>
        </ul>
      </div>
      <div class="following">
        <h3>Following</h3>
        <ul>
          <li><input type="checkbox"> User 1</li>
          <li><input type="checkbox"> User 2</li>
        </ul>
      </div>
      <div class="followers">
        <h3>Followers</h3>
        <ul>
          <li><input type="checkbox"> User A</li>
          <li><input type="checkbox"> User B</li>
        </ul>
      </div>
    </aside>
  </main>
</body>
</html>
