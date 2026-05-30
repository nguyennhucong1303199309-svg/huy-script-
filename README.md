<!DOCTYPE html><html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Script Thông Tin Player</title><style>
body{
margin:0;
background:#0d0d0d;
font-family:Arial,sans-serif;
color:white;
}

.header{
text-align:center;
padding:20px;
font-size:32px;
font-weight:bold;
color:#00ffaa;
}

.box{
width:90%;
max-width:1000px;
margin:auto;
background:#151515;
padding:15px;
border-radius:15px;
border:2px solid #00ffaa;
}

textarea{
width:100%;
height:500px;
background:#0a0a0a;
color:white;
border:none;
outline:none;
resize:none;
font-size:14px;
}

button{
width:100%;
margin-top:10px;
padding:15px;
font-size:20px;
font-weight:bold;
background:#00ffaa;
border:none;
border-radius:10px;
cursor:pointer;
}

button:hover{
opacity:0.9;
}
</style></head><body><div class="header">
SCRIPT THÔNG TIN PLAYER
</div><div class="box"><textarea id="script">
-- DÁN TOÀN BỘ SCRIPT THÔNG TIN PLAYER VÀO ĐÂY
</textarea><button onclick="copyScript()">
📋 SAO CHÉP SCRIPT
</button></div><script>
function copyScript(){
const text=document.getElementById("script");
navigator.clipboard.writeText(text.value);
alert("Đã sao chép script!");
}
</script></body>
</html># huy-script-
nơi sao chép script của huy script 
