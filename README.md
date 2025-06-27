# MLLM Chat

## 简介
我希望开发一个轻量级本地可以启动使用的多模态MLLM对话助手，具体需求见下面backlog，请逐一完成，可以细化和优化backlog的内容。

## Backlog
- [ ] 1. 基于本地的ollama接口调用MLLM，使用gemma3n:e4b模型，具体信息参考 [doc/gemma.md](doc/gemma.md)
- [ ] 2. 支持文本对话，支持图片、视频、音频数据的上传和对话
- [ ] 3. 使用uv或pnpm管理项目，使用bootstrap.sh启动项目
- [ ] 4. 针对test目录的 test_image.png, test_video.mp4, test_audio.mp3 进行测试
- [ ] 5. 使用openai兼容接口进行ollama的调用，配置代理和no_proxy，创建.env存储endpoint, api key，model， 代理和no_proxy,ssl certificate默认设置为否。
- [ ] 6.
