<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>زارا برای محسن ❤️</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 20px;
      background: linear-gradient(145deg, #21132e, #54304f, #171729);
      color: white;
      font-family: Tahoma, Arial, sans-serif;
    }
    .room {
      width: 100%;
      max-width: 430px;
      text-align: center;
      padding: 30px 22px;
      border: 1px solid #ffffff30;
      border-radius: 28px;
      background: #ffffff12;
      box-shadow: 0 15px 50px #0005;
    }
    .heart { font-size: 54px; }
    h1 { color: #ffd1e5; }
    p { line-height: 2; color: #f4e7f2; }
    #chat {
      min-height: 65px;
      padding: 12px;
      margin: 18px 0;
      border-radius: 14px;
      background: #0002;
      line-height: 1.9;
    }
    input {
      width: 100%;
      padding: 14px;
      border: 0;
      border-radius: 12px;
      font-size: 16px;
      margin-bottom: 10px;
    }
    button {
      width: 100%;
      padding: 14px;
      margin-top: 8px;
      border: 0;
      border-radius: 12px;
      background: #f5a8cd;
      color: #32182b;
      font-size: 16px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <main class="room">
    <div class="heart">💗</div>
    <h1>سلام محسن جان!</h1>
    <p>من زارام؛ خوش اومدی عزیزم 🌸</p>
    <div id="chat">اینجا می‌تونی با زارا حرف بزنی.</div>
    <input id="message" placeholder="برای زارا بنویس...">
    <button onclick="sendMessage()">فرستادن پیام</button>
    <button onclick="speak()">🔊 شنیدن صدای زارا</button>
  </main>
  <script>
    function speak() {
      const text = document.getElementById('chat').innerText;
      const voice = new SpeechSynthesisUtterance(text);
      voice.lang = 'fa-IR';
      speechSynthesis.speak(voice);
    }
    function sendMessage() {
      const input = document.getElementById('message');
      const text = input.value.trim();
      if (!text) return;
      document.getElementById('chat').innerText =
        'محسن جان، پیامت رو دیدم ❤️ برای پاسخ هوشمند باید اتصال هوش مصنوعی هم تنظیم بشه.';
      input.value = '';
    }
  </script>
</body>
</html>
