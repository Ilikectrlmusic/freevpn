## VPN原理：

> 每个箭头表示一次数据传输

**正常通信**：  
你访问 baidu，向百度服务器发送数据 &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp; GFW，认为没问题，放行 &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp; 百度服务器 &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp;（一般 GFW 不会检测返回的数据）→ 你看见百度网站

**访问不了外网**：  
你访问 google &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp; GFW，发现你在向谷歌服务器发送数据，阻止。没有下一步了，你的浏览器显示无法访问

**用 VPN 可以访问外网**：  
你访问 google，设备上的 VPN 软件将“访问 google”的请求发送到国外代理服务器而不是谷歌服务器 &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp; GFW 以为你在访问正常网站，放行 &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp;  
国外代理服务器收到“访问 google”的请求并自己访问 google &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp; 正常通信 &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp;  
代理服务器收到谷歌网站内容，并发送给你 &nbsp;&nbsp;&nbsp;&nbsp;→&nbsp;&nbsp;&nbsp;&nbsp; 你看见谷歌网站

👉 [点击观看视频讲解](https://www.youtube.com/watch?v=ZT-q6mJ-e3g)
