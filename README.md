# AiStarOpen

基于ChatGPT、DALL-E2的开源AI解决方案，包括用户登录、注册、分佣、邀请、权限控制、敏感词校验。

# Demo

https://aistar.cool/chat

# 系统架构

![img](https://cdn.nlark.com/yuque/0/2023/jpeg/22382235/1688304761155-41dd700b-3e32-4391-b0c3-4369bf4fbebd.jpeg)

# 技术栈

**前端：**

Nextjs、TailwindCss、Typescript、WebSocket、Zustand、ChakraUI



**后端：**

golang，go-chi框架、JWT鉴权、Redis、Mysql

# Features

- 用户注册、登录（邮箱、验证码）
- 用户邀请，分佣
- 敏感词校验
- 会员管理系统，完整的充值系统，免费次数设置、体验次数设置
- AI内置角色创建、管理
- 支持上下文聊天
- Key池轮询，自动屏蔽异常Key
- AI绘画（基于Dall-E2、Mj）
- 支持私有知识库（基于golang-langchain）
- 插件系统，包括（Web联网、语音合成和语音转文字）

# TODO

- 插件自主开发能力及文档
- 优雅的错误处理
- 支持黑白模式
- 支持微信支付
- 支持自建大预言模型
- ·······

# 交流

有任何问题或者是想交流的同行或老板欢迎加群~

![img](https://cdn.nlark.com/yuque/0/2023/jpeg/22382235/1688304493443-249ad62a-7ede-45dd-ad8a-bbbaca63da29.jpeg)

# Ref

https://github.com/futantan/OpenGpt

https://github.com/tmc/langchaingo

https://github.com/michaelthwan/searchGPT