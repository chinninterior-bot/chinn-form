<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>沁隱軟裝空間設計｜丈量表單</title>
<script src="https://static.line-scdn.net/liff/edge/2/sdk.js"></script>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: sans-serif; background: #f9f6f2; display: flex; align-items: center; justify-content: center; min-height: 100vh; }
  .card { background: white; border-radius: 16px; padding: 40px 28px; text-align: center; max-width: 340px; width: 90%; box-shadow: 0 4px 20px rgba(0,0,0,0.08); }
  .logo { width: 56px; height: 56px; background: #5c4a3a; border-radius: 14px; margin: 0 auto 16px; display: flex; align-items: center; justify-content: center; }
  .logo svg { width: 30px; height: 30px; fill: white; }
  h1 { color: #5c4a3a; font-size: 18px; margin-bottom: 8px; }
  p { color: #888; font-size: 13px; line-height: 1.6; margin-bottom: 20px; }
  .spinner { width: 36px; height: 36px; border: 3px solid #e0d6cc; border-top-color: #5c4a3a; border-radius: 50%; animation: spin 0.8s linear infinite; margin: 0 auto 16px; }
  @keyframes spin { to { transform: rotate(360deg); } }
  .status { font-size: 13px; color: #aaa; }
  .btn { display: block; width: 100%; padding: 14px; background: #5c4a3a; color: white; border: none; border-radius: 12px; font-size: 15px; font-weight: bold; cursor: pointer; text-decoration: none; margin-top: 16px; }
</style>
</head>
<body>
<div class="card">
  <div class="logo">
    <svg viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 3c1.66 0 3 1.34 3 3s-1.34 3-3 3-3-1.34-3-3 1.34-3 3-3zm0 14.2c-2.5 0-4.71-1.28-6-3.22.03-1.99 4-3.08 6-3.08 1.99 0 5.97 1.09 6 3.08-1.29 1.94-3.5 3.22-6 3.22z"/></svg>
  </div>
  <h1>沁隱軟裝空間設計</h1>
  <p>正在為您開啟丈量需求表單</p>
  <div class="spinner" id="spinner"></div>
  <div class="status" id="status">讀取中...</div>
  <a class="btn" id="manual-btn" style="display:none" href="#">手動開啟表單</a>
</div>
<script>
const LIFF_ID = "2009845899-8rQXLHR7";
const FORM_BASE = "https://docs.google.com/forms/d/e/1FAIpQLSc_gztTlaJ4HbCh-k2eOszoF0hBMkSfwX3pKKknw0YdIh6CIQ/viewform";
const ENTRY_USERID = "entry.1780545459";

function goToForm(userId) {
  const url = userId ? FORM_BASE + "?usp=pp_url&" + ENTRY_USERID + "=" + encodeURIComponent(userId) : FORM_BASE;
  document.getElementById("status").textContent = "開啟表單中...";
  document.getElementById("spinner").style.display = "none";
  const btn = document.getElementById("manual-btn");
  btn.href = url;
  btn.textContent = "點此開啟表單";
  btn.style.display = "block";
  setTimeout(function() { window.location.href = url; }, 500);
}

async function init() {
  try {
    document.getElementById("status").textContent = "連線 LINE 中...";
    await liff.init({ liffId: LIFF_ID });
    if (!liff.isInClient() && !liff.isLoggedIn()) {
      document.getElementById("status").textContent = "請先登入 LINE...";
      liff.login();
      return;
    }
    document.getElementById("status").textContent = "取得帳號資訊中...";
    const profile = await liff.getProfile();
    goToForm(profile.userId);
  } catch (err) {
    document.getElementById("spinner").style.display = "none";
    document.getElementById("status").textContent = "請在 LINE 中開啟";
    const btn = document.getElementById("manual-btn");
    btn.href = FORM_BASE;
    btn.textContent = "直接開啟表單";
    btn.style.display = "block";
  }
}
init();
</script>
</body>
</html>
