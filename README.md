```
function loadScript(url, callback){
  var head = document.getElementsByTagName('head')[0];
  var script = document.createElement('script');
  script.type = 'text/javascript';script.src = url;
  script.onreadystatechange = callback;
  script.onload = callback;
  head.appendChild(script);
}

loadScript('https://raw.githack.com/DineUpGroup/demo/main/script.js', () => {})
```
[bookmark]("javascript:(function()%7Bfunction%20loadScript(url%2C%20callback)%7B%0A%20%20var%20head%20%3D%20document.getElementsByTagName('head')%5B0%5D%3B%0A%20%20var%20script%20%3D%20document.createElement('script')%3B%0A%20%20script.type%20%3D%20'text%2Fjavascript'%3Bscript.src%20%3D%20url%3B%0A%20%20script.onreadystatechange%20%3D%20callback%3B%0A%20%20script.onload%20%3D%20callback%3B%0A%20%20head.appendChild(script)%3B%0A%7D%0A%0AloadScript('https%3A%2F%2Fraw.githack.com%2FDineUpGroup%2Fdemo%2Fmain%2Fscript.js'%2C%20()%20%3D%3E%20%7B%7D)%7D)()%3B")
