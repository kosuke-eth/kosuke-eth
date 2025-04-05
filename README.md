<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>Kosuke's Profile</title>
  <style>
    /* 背景やフォント設定 */
    body {
      background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      margin: 0;
      padding: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    /* プロフィールカード */
    .profile-container {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 30px;
      max-width: 600px;
      width: 100%;
      text-align: center;
    }
    /* プロフィール画像 */
    .profile-image {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid #4CAF50;
      object-fit: cover;
      margin-bottom: 20px;
    }
    h1, h2 {
      color: #333;
      margin: 10px 0;
    }
    p {
      color: #555;
      line-height: 1.6;
    }
    ul {
      list-style: none;
      padding: 0;
      text-align: left;
      margin: 0 auto 20px;
      max-width: 500px;
    }
    li {
      margin-bottom: 10px;
    }
    /* スキルセクション */
    .skills img {
      margin: 0 5px;
      vertical-align: middle;
    }
    /* リンクのスタイル */
    a {
      text-decoration: none;
      color: #4CAF50;
    }
    a:hover {
      text-decoration: underline;
    }
    /* GIF画像 */
    .gif-container {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="profile-container">
    <img src="https://pbs.twimg.com/profile_images/1875384213622718464/TqT-Df8Y_400x400.jpg" alt="Kosuke's Photo" class="profile-image" />
    <h1>Hey there, I'm Kosuke! 👋</h1>
    <p>Welcome to my playful corner on GitHub! 🎉</p>
    
    <h2>🚀 About Me</h2>
    <ul>
      <li>🧑‍💻 I'm a Frontend Engineer passionate about crafting engaging digital experiences.</li>
      <li>🌱 Currently expanding my horizons into Backend development.</li>
      <li>💼 Proudly working at <a href="https://x.com/gustocoin" target="_blank">X - @gustocoin</a> where creativity meets tech.</li>
      <li>🎤 I also share my insights on talks at <a href="https://speakerdeck.com/aikosuke_gusto" target="_blank">Speakerdeck</a>.</li>
    </ul>
    
    <h2>⚡ Skills</h2>
    <div class="skills">
      <img src="https://skillicons.dev/icons?theme=dark&perline=7&i=html,css,js,ts,react,next,terraform,aws" alt="My Skills" />
    </div>
    
    <h2>📫 Connect with Me</h2>
    <p>📱 <a href="https://x.com/kosuke_eth" target="_blank">X - @kosuke_eth</a></p>
    
    <div class="gif-container">
      <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" alt="Playful GIF" width="200" />
    </div>
  </div>
</body>
</html>


