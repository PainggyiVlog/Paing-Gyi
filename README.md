<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Painggyi Vlog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }
    .container {
      max-width: 1200px;
      margin: 20px auto;
      padding: 0 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-content {
      padding: 20px;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Painggyi Vlog</h1>
    <p>Welcome to my personal vlog!</p>
  </header>

  <div class="container">
    <h2>Latest Posts</h2>
    <div class="grid">
      <div class="card">
        <img src="post1.jpg" alt="Post 1">
        <div class="card-content">
          <h3>Post Title 1</h3>
          <p>This is a short description of the post.</p>
          <a href="post1.html">Read More</a>
        </div>
      </div>
      <div class="card">
        <img src="post2.jpg" alt="Post 2">
        <div class="card-content">
          <h3>Post Title 2</h3>
          <p>This is a short description of the post.</p>
          <a href="post2.html">Read More</a>
        </div>
      </div>
    </div>
  </div>

  <footer>
    <p>&copy; 2023 Painggyi Vlog. All rights reserved.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me - Painggyi Vlog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }
    .container {
      max-width: 800px;
      margin: 20px auto;
      padding: 0 20px;
    }
    .profile-img {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      margin: 20px auto;
      display: block;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>About Me</h1>
  </header>

  <div class="container">
    <img src="profile.jpg" alt="Profile Picture" class="profile-img">
    <h2>ပိုင်သက်စိုး</h2>
    <p>Hello! I'm Paing Thet Soe, a passionate vlogger sharing my life experiences and stories. Follow me on my journey!</p>
  </div>

  <footer>
    <p>&copy; 2023 Painggyi Vlog. All rights reserved.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Painggyi Vlog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }
    .container {
      max-width: 800px;
      margin: 20px auto;
      padding: 0 20px;
    }
    form {
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #333;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .social-links {
      margin-top: 20px;
    }
    .social-links a {
      margin-right: 10px;
      text-decoration: none;
      color: #333;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Contact Me</h1>
  </header>

  <div class="container">
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Send Message</button>
    </form>

    <div class="social-links">
      <h2>Follow Me:</h2>
      <a href="https://www.facebook.com/yourprofile" target="_blank">Facebook</a>
      <a href="https://www.tiktok.com/@yourprofile" target="_blank">TikTok</a>
      <a href="mailto:paingthetsoe37931@gmail.com">Email</a>
    </div>
  </div>

  <footer>
    <p>&copy; 2023 Painggyi Vlog. All rights reserved.</p>
  </footer>
</body>
</html>
