## Easy to deploy your LLM(large language model) server with no public address GPU machine.

If you don't want to build a web server,and it is hard to let your LLM server export to public (such as vast.ai ,autodl.com etc.) .


You can have your own AI website link Only two step:

1.Register your machine :

websocket.WebSocketApp("wss://v.stylee.top:8883/ws_ai_server?system={your server system}&id={server id}" ...

your server system name can be any string .like abcdefg...

your server will get OpenAI like data with websocket.

https://platform.openai.com/docs/api-reference/chat/create


```
{
  "model": "gpt-3.5-turbo",
  "messages": [{"role": "user", "content": "Hello!"}]
  ...
}
```

use websocket send your result word by word or sentence.

Finnaly ,send message "ALL-finished!" , system will finish current chat ,and ready for next server.



2.Then open url :
https://ai.zyinfo.pro/?AI_system={your server system}

have fun !

note:

your can Regist server with no limit (more machine). and serve for public!!





