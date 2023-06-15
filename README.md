
# 环境设置

为了设置您的环境以在此处运行代码，首先安装所有要求：
```shell
pip install -r requirements.txt
```
### openai_api_key设置
将模板example.env复制到.env,并在文件.env中适当地编辑变量。
```
OPENAI_API_KEY:你自己的openaikey
http_proxy/s：你自己的代理端口
```

#运行官方样例 example.py

得到结果

```shell
{
  "choices": [
    {
      "finish_reason": "stop",
      "index": 0,
      "message": {
        "content": "The current weather in Boston, MA is sunny and windy with a temperature of 72 degrees.",
        "role": "assistant"
      }
    }
  ],
  "created": 1686872177,
  "id": "chatcmpl-7RqnhDK7ZxjRCzRM3SbMRsx1PKQaM",
  "model": "gpt-3.5-turbo-0613",
  "object": "chat.completion",
  "usage": {
    "completion_tokens": 19,
    "prompt_tokens": 73,
    "total_tokens": 92
  }
}
```