> 🌐 本文档由 [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) 翻译,英文原版见原项目。

# 如何获取 [Amp](https://ampcode.com) 的系统提示词

1. 在 VSCode 中登录 Amp
2. 向 Amp 发送一条简短的查询
3. 按住 Alt(Windows)或 Option(macOS),同时点击工作区(workspace)按钮

![](./view-thread-yaml.png)

4. 点击 "View Thread YAML"(查看线程 YAML)

# 说明

Amp 所使用的系统提示词是针对 Sonnet 4.x 调优的,并把其他 LLM 以工具形式注册了进去(即 "the oracle",神谕模型)。如果你想要获取针对 `GPT-5` 调优的系统提示词,需要先在 VSCode 用户设置中加入以下配置,然后重新执行上面的步骤:

```json
{
    "amp.url": "https://ampcode.com/",
    "amp.gpt5": true
}
```
