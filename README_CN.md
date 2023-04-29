## 任何 GPU 机器均可提供你的大型语言模型处理服务

如果你不想搭建web服务器，又很难让你的LLM服务器对外公开（比如vast.ai,autodl.com等）。


您可以拥有自己的 AI 网站链接只需两步：

1.注册您的机器：

websocket.WebSocketApp("wss://v.stylee.top:8883/ws_ai_server?system={你的服务器系统}&id={服务器id}" ...

您的服务器系统名称可以是任何字符串。如 abcdefg ...

您的服务器将使用 websocket 接受到类似 [OpenAI 的json数据](https://platform.openai.com/docs/api-reference/chat/create)。


```
{
  "model": "gpt-3.5-turbo",
  "messages": [{"role": "user", "content": "Hello!"}]
  ...
}
```

使用 websocket 逐字或逐句发送结果。

最后，发送消息“ALL-finished!” , 系统将结束当前聊天，并为下一个服务做好准备。


2.然后打开网址：
https://ai.zyinfo.pro/?AI_system={你的服务器系统}

玩得开心 ！


提示：

您可以无限制地注册服务器（更多机器）。 为大众服务！！



我们有插件服务并与我们的知识数据库连接。

由 https://ai.zyinfo.pro 提供支持
