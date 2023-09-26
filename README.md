# Public-bing-chatgpt-proxy
## 公用的bing/chatgpt接入点

# 不能用提issue，看见就会修，如果帮到了你，请给点一个⭐

## 最近在逐渐改为 xxx-xx.nothingnessvoid.top的域名格式 推荐使用已更改的，未更改的会在未来一周内更改

### OpenAI接入点如下 `暂时无法使用账号密码登录`

#### 网页端接入点

<br>`https://fakeopen-ca.nothingnessvoid.top/chatgpt/backend-api/`  **推荐使用，这个服务器配置好点**  
<br>`https://fakeopen-sgp.nothingnessvoid.top/chatgpt/backend-api/`  
<br>`https://fakeopen-us.nothingnessvoid.top/chatgpt/backend-api/`   
<br>`https://fakeopen-jp.nothingnessvoid.top/chatgpt/backend-api/`  
<br>`https://fakeopen-la.nothingnessvoid.top/chatgpt/backend-api/`  
#### API接入点  

`https://proxy.nvoid.games/proxy/https://api.openai.com/v1`  
<br>`https://proxy.nvoid.live/proxy/api.openai.com/v1`

直接复制，不要改东西

### Bing接入点如下

`wss://bing-sgp.nothingnessvoid.top/sydney/ChatHub` **已更改，请注意**

`wss://bing-sgp2.nothingnessvoid.top/sydney/ChatHub` **已正常可用**

`wss://bing-jp.nothingnessvoid.top/sydney/ChatHub`  

`wss://bing-us.nothingnessvoid.top/sydney/ChatHub`  

`wss://sgp.nvoid.live/sydney/ChatHub` 



## Bing接入时cookie一定要包含 `RwBf` 的值和 `KievRPSSecAuth` 的值


<br>**推荐先退出登录后再重新登录，然后再复制cookie进入配置文件，这样能用的概率大**


<br>如果出现报错，请先进入Bing官方页面，登录后进行对话，会弹出验证页面，**通过验证能正常聊天后再复制cookie**

![image](https://github.com/Nothingness-Void/Public-bing-chatgpt-proxy/assets/55913486/b70f24fe-26cd-423c-a903-e7a7ef722778)

![image](https://github.com/Nothingness-Void/Public-bing-chatgpt-proxy/assets/55913486/cc76f8f1-87b9-4725-9342-f6b5c6ea2a29)

**前半段为未更新cookie时的对话，后半段为更新cookie后的对话（其余配置均不变）。**




Bing接入点也可直接访问

`https://ai.nothingnessvoid.tech/`  
<br>`https://bing.nvoid.live/`

直接访问就是不用代理的Bing镜像站
效果如下
![image](https://github.com/Nothingness-Void/Public-bing-chatgpt-proxy/assets/55913486/a8593471-8346-4059-ab71-1c787fbe62e4)

```
Bing端搭建项目为：https://github.com/adams549659584/go-proxy-bingai

Openai端搭建项目为: https://github.com/dqzboy/ChatGPT-Proxy
```
当然也可以通过我库中的对应文件夹里面的docker-compose进行一键部署

[Bing](https://github.com/Nothingness-Void/Public-bing-chatgpt-proxy/blob/main/go-porxy-bingai/docker-compose.yml)  

[OpenAI](https://github.com/Nothingness-Void/Public-bing-chatgpt-proxy/blob/main/go-chatgpt-api/docker-compose.yml)
