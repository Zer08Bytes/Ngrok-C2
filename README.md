# Ngrok-C2
Ngrok-C2

想要模拟外网真实环境，测试远控控制软件，但是无公网服务器且不想实名。
前提：
	不想买腾讯云、阿里云等云服务器或者无公网IP的服务器，想要在内网任何一台主机，做远程控制C2的服务端。
	想隐藏，防止溯源(不实名、换其他穿透软件等，思路差不多)
	想使用ngrok免费版且未绑定信用卡组件远控C2的，注意，如果是付费版的，可以开多个通道，相对简单，理论上适合所有远控。
	由于现在免费版(未绑定信用卡)ngrok的只允许使用一条http/https通道，不支持tcp等通道(所以TCP监听的C2未绑定信用卡的就不要折腾了)，且会强制把http转成https请求，导致http监听的时候，由于转成https，有些C2的客户端上线有问题。所以是否支持客户端上线，需要看自己的远控类型。
	当然，也适合运维或研发人员，无域名或公网服务器的时候，测试网站等CMS
	注意不是Sunny-Ngrok这个哈

B站视频演示：https://www.bilibili.com/video/BV1moYrzcEpz/?vd_source=229f70258c44853078f16a5decbc2fb0


<img width="1413" height="920" alt="图片" src="https://github.com/user-attachments/assets/3f21b3f5-120e-4a24-9b2f-163c1941a1ca" />



