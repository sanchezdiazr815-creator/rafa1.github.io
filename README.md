<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NFC</title>
</head>

<body style="margin:0; display:flex; justify-content:center; align-items:center; height:100vh; background:black; color:white; font-family:sans-serif;">

<h1 id="count" style="font-size:100px;">0</h1>

<script>
fetch('https://api.countapi.xyz/hit/rafa123/gorra')
.then(res => res.json())
.then(res => {
document.getElementById('count').innerText = res.value;
});
</script>

</body>
</html>
