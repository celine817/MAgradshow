<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>創意藝術學系碩士生創意寫作和藝術展2026 | 導覽系統</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:"PingFang TC","Microsoft JhengHei", sans-serif;}
body{
  background: linear-gradient(150deg, #70c4f9 0%, #82cff8 45%, #f0b8e3 100%);
  min-height:100vh; padding:80px 24px 40px;text-align:center;color:#1a1a22;position:relative; overflow-x:hidden;
}
body::before{
  content:"";position:fixed;top:0;right:0;width:110%;height:100%;
  background-image:linear-gradient(to right, rgba(255,255,255,0.2) 1px, transparent 1px);
  background-size: 11px 100%; transform:skewX(-24deg); transform-origin:top right; pointer-events:none;z-index:0;
}
.bubble{
  position:fixed; border-radius:50%;border: 1px solid rgba(255,255,255,0.6);
  background:radial-gradient(circle at 30% 30%,rgba(255,255,255,0.32), rgba(255,255,255,0.03));
  pointer-events:none;z-index:0;
}
.b1{width:135px;height: 135px; top:5%;left:5%;}
.b2{width:78px;height:78px; top:20%;left:41%;}
.b3{width:112px;height: 112px; top:36%;left:21%;}
.b4{width: 165px;height: 165px;top:31%;right:20%;}
.b5{width:52px;height:52px;top:14%;right:15%;}
.b6{width:64px;height:64px;top:60%;right:29%;}
.b7{width:72px;height:72px;top:64%;left:32%;}
.b8{width:62px;height:62px; top:76%;left:4%;}
.b9{width:148px;height: 148px;bottom:5%;left:22%;}
.b10{width:175px;height: 175px;bottom:3%;right:4%;}
.page-content{position:relative;z-index:1;}

/* 頁面切換控制 */
#homePage{display:block;}
#detailPage{display:none;max-width:600px;margin:0 auto;background:#fff;border-radius: 16px;padding:24px;}
.grad-title{font-size:32px;font-weight:600; letter-spacing:2px;margin-bottom:60px;color:#111118;}
.input-wrap{margin-bottom:32px;}
#audioCode{
  width:90%;max-width:320px;padding:18px 12px; font-size:22px;text-align:center;
  border:1px solid rgba(60,130,160,0.35); border-radius:12px;
  background:rgba(255,255,255,0.8); color:#111118; outline: none;transition:0.2s ease;
}
#audioCode:focus{border-color:#4a90e2; background:rgba(255,255,255,0.95);}
#playBtn{
  width:90%;max-width:320px;padding:18px;font-size:18px;border:none;border-radius:12px;
  background:#62a4cc;color:#fff;cursor:pointer;transition:0.2s ease;
}
#playBtn:active{background:#4887a9;}
#playBtn:hover{background:#5296bb;}
.divider{width:80px; height: 1px; background:rgba(30,30,40,0.28); margin:60px auto 40px;}
.tips{
  text-align:left;max-width:360px; margin:0 auto 60px;font-size: 14px; opacity:0.92;
  line-height: 1.8;background:rgba(255,255,255,0.7); padding:12px 16px;border-radius:8px;
}
footer{font-size: 13px; opacity:0.65; line-height:1.6;}

/* 作品詳細頁專用樣式 */
.back-btn{
  display:block;width:100%; padding:12px 0;background:#62a4cc;color:white;border:none;
  border-radius:10px;font-size:16px;margin-bottom:20px;cursor:pointer;
}
.work-title{font-size:26px;font-weight:bold;margin-bottom:8px;}
.author-text{font-size:17px;color:#444;margin-bottom:18px;}
.desc-text{text-align:left;font-size: 15px; line-height: 1.7;color:#222; margin-bottom:24px;}

/* 媒體播放器外殼 */
#mediaContainer {
  margin-bottom: 20px;
}
/* OneDrive 影片容器（維持 16:9 比例） */
.onedrive-wrapper {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  border-radius: 10px;
  background: #f0f0f0;
}
.onedrive-wrapper iframe {
  position: absolute;
  top: 0; left: 0; width:100%; height:100%; border:none;
}
/* Buzzsprout 音訊容器（緊湊型 Bar） */
.buzzsprout-wrapper {
  border-radius: 10px;
  overflow: hidden;
  min-height: 60px;
}

/* 強化手機點擊區域 */
button, input {
  min-height:50px;
  -webkit-tap-highlight-color: rgba(0,0,0,0.15);
}

@media (max-width:480px){
  .grad-title{font-size:28px;}
  .b1{width:95px;height:95px;} .b10{width:120px;height:120px;}
  .work-title{font-size:22px;}
  #detailPage{padding:18px;}
}
</style>
</head>
<body>
<!-- 背景泡泡 -->
<div class="bubble b1"></div><div class="bubble b2"></div><div class="bubble b3"></div>
<div class="bubble b4"></div><div class="bubble b5"></div><div class="bubble b6"></div>
<div class="bubble b7"></div><div class="bubble b8"></div><div class="bubble b9"></div>
<div class="bubble b10"></div>
<div class="page-content">

<!-- 首頁：輸入編號頁 -->
<div id="homePage">
  <h1 class="grad-title">創意藝術學系碩士生創意寫作和藝術展2026</h1>

  <div class="input-wrap">
    <input type="text" id="audioCode" placeholder="請輸入編號，例:01">
  </div>
  <button id="playBtn">開啟作品導覽</button>
  <div class="divider"></div>
  <div class="tips">
    <p>💡 使用說明</p>
    <p>1. 輸入展品旁標註的兩位數編號</p>
    <p>2. 點擊按鈕直接線上聆聽或觀看作品資訊</p>
  </div>
  <footer>作品導覽系統</footer>
</div>

<!-- 第二頁：作品詳細頁 -->
<div id="detailPage">
  <button class="back-btn" onclick="backHome()">← 返回首頁</button>
  <h2 class="work-title" id="titleBox"></h2>
  <div class="author-text">作者：<span id="authorBox"></span></div>
  
  <!-- 動態媒體播放區域 -->
  <div id="mediaContainer"></div>

  <div class="desc-text" id="descBox"></div>
</div>

</div>
<script>
// 作品資料庫
const workData = {
  "01": {
    title: "作品標題範例",
    author: "創作者姓名",
    mediaType: "buzzsprout",
    buzzsproutId: "19468467",
    buzzsproutScript: "https://www.buzzsprout.com/2629235/episodes/19468467-01.js?container_id=buzzsprout-player-19468467&player=small",
    desc: "本作品透過文字與影像結合，探討都市空間與個體記憶的對話關係，以流動畫面呈現日常被忽略的細微情緒。"
  },
  "02": {
    title: "待填作品名",
    author: "待填作者",
    mediaType: "onedrive",
    embedUrl: "https://onedrive.live.com/embed?cid=YOUR_CID&resid=YOUR_RESID&authkey=YOUR_AUTHKEY",
    desc: "補充此作品創作理念與介紹文字"
  }
};

const home = document.getElementById("homePage");
const detail = document.getElementById("detailPage");
const mediaContainer = document.getElementById("mediaContainer");

// 數字過濾：轉半形、去除空白
function cleanCode(str){
  return str.replace(/\s/g,"").replace(/[０-９]/g, s => 
    String.fromCharCode(s.charCodeAt(0) - 0xFEE0)
  );
}

// 跳轉到作品詳細頁
function goDetail() {
  const input = document.getElementById("audioCode");
  const rawNum = input.value.trim();
  const num = cleanCode(rawNum);

  if (!num) {
    alert("請輸入兩位數展品編號");
    input.focus();
    return;
  }
  if (!workData[num]) {
    alert("編號不存在，請輸入正確展品編號");
    input.value = "";
    input.focus();
    return;
  }

  const data = workData[num];
  document.getElementById("titleBox").innerText = data.title;
  document.getElementById("authorBox").innerText = data.author;
  document.getElementById("descBox").innerText = data.desc;

  mediaContainer.innerHTML = "";

  if (data.mediaType === "buzzsprout") {
    const wrapper = document.createElement("div");
    wrapper.className = "buzzsprout-wrapper";
    const playerDiv = document.createElement("div");
    playerDiv.id = `buzzsprout-player-${data.buzzsproutId}`;
    wrapper.appendChild(playerDiv);
    const script = document.createElement("script");
    script.src = data.buzzsproutScript;
    script.type = "text/javascript";
    script.charset = "utf-8";
    wrapper.appendChild(script);
    mediaContainer.appendChild(wrapper);
  } else if (data.mediaType === "onedrive" && data.embedUrl) {
    const wrapper = document.createElement("div");
    wrapper.className = "onedrive-wrapper";
    const iframe = document.createElement("iframe");
    iframe.src = data.embedUrl;
    iframe.scrolling = "no";
    iframe.setAttribute("allowfullscreen", "true");
    wrapper.appendChild(iframe);
    mediaContainer.appendChild(wrapper);
  }

  home.style.display = "none";
  detail.style.display = "block";
  window.scrollTo(0,0);
}

// 返回首頁
function backHome() {
  detail.style.display = "none";
  home.style.display = "block";
  document.getElementById("audioCode").value = "";
  mediaContainer.innerHTML = "";
  window.scrollTo(0,0);
}

document.getElementById("playBtn").addEventListener("click", goDetail);
document.getElementById("audioCode").addEventListener("keydown", e => {
  if (e.key === "Enter") goDetail();
});
</script>
</body>
</html>
