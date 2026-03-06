

Chat
Code
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no"/>
  <title>ফাস্ট লোন</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      font-family: 'Noto Sans Bengali', 'Inter', sans-serif;
      background: #0e3a27;
      color: #ffffff;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0;
      overflow-x: hidden;
    }
    .phone-frame {
      width: 100%;
      max-width: 380px;
      height: 100vh;
      background: #0e3a27;
      position: relative;
      overflow: hidden;
    }
    .content {
      padding: 40px 24px 80px;
      text-align: center;
    }
    .logo-container { margin-bottom: 24px; }
    .logo {
      width: 90px;
      height: 90px;
      background: #f59e0b;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 60px;
      font-weight: bold;
      margin: 0 auto 12px;
      color: white;
      box-shadow: 0 4px 12px rgba(245,158,11,0.4);
    }
    h1 { font-size: 32px; font-weight: 700; margin-bottom: 8px; }
    .subtitle { font-size: 17px; opacity: 0.9; margin-bottom: 40px; }
    .card {
      background: rgba(255,255,255,0.06);
      border-radius: 24px;
      padding: 28px 20px;
      backdrop-filter: blur(12px);
      border: 1px solid rgba(255,255,255,0.08);
      margin-bottom: 32px;
    }
    .label {
      font-size: 15px;
      opacity: 0.85;
      margin-bottom: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
    }
    .live-badge {
      background: #10b981;
      color: white;
      font-size: 12px;
      padding: 4px 10px;
      border-radius: 20px;
      font-weight: 600;
    }
    .amount {
      font-size: 56px;
      font-weight: 800;
      margin: 16px 0 32px;
      letter-spacing: -1px;
    }
    .stats {
      display: flex;
      justify-content: space-between;
      margin-bottom: 40px;
    }
    .stat {
      flex: 1;
      text-align: center;
      padding: 12px;
      background: rgba(255,255,255,0.05);
      border-radius: 16px;
      margin: 0 8px;
    }
    .stat-label { font-size: 14px; opacity: 0.8; margin-bottom: 6px; }
    .stat-value { font-size: 20px; font-weight: 700; }
    .status { color: #34d399; }
    .button {
      font-size: 18px;
      font-weight: 700;
      padding: 18px 24px;
      border: none;
      border-radius: 50px;
      width: 100%;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      margin-bottom: 16px;
    }
    .apply-button {
      background: #10b981;
      color: white;
      box-shadow: 0 8px 24px rgba(16,185,129,0.35);
    }
    .apply-button:hover { background: #059669; }
    .withdraw-button {
      background: #f59e0b;
      color: #000;
      box-shadow: 0 8px 24px rgba(245,158,11,0.35);
    }
    .withdraw-button:hover { background: #d97706; }
  </style>
</head>
<body>


  <div class="phone-frame">
    <div class="content">
      <div class="logo-container">
        <div class="logo">৩</div>
        <h1>ফাস্ট লোন</h1>
        <p class="subtitle">আপনার স্বপ্ন পূরণের সঙ্গী</p>
      </div>


      <div class="card">
        <div class="label">
          <span>↗</span> মোট উপলব্ধ টাকা <span class="live-badge">লাইভ</span>
        </div>
        <div class="amount">৳৫০,০০০</div>


        <div class="stats">
          <div class="stat">
            <div class="stat-label">মুদ্রা</div>
            <div class="stat-value">BDT ৳</div>
          </div>
          <div class="stat">
            <div class="stat-label">স্ট্যাটাস</div>
            <div class="stat-value status">✔ সক্রিয়</div>
          </div>
        </div>


        <button class="button apply-button">
          লোনের জন্য আবেদন করুন →
        </button>


        <a href="withdrawal.html" class="button withdraw-button">
          উত্তোলন করুন →
        </a>
      </div>
    </div>
  </div>


</body>
</html>

