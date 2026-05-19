```markdown
# DeepSeek Chat - AI聊天助手

仿 DeepSeek 网页版的本地聊天工具，纯浏览器运行，数据存本地。

---

## 功能

- 支持 DeepSeek-V3、R1、V4 Flash、V4 Pro
- 无限个独立对话，每个可单独配置
- 角色扮演（8种预设 + 自定义 System Prompt）
- 用户和AI自定义头像
- 流式打字输出
- 本地存储，无需服务器

---

## 使用

1. 浏览器打开 `index.html`
2. 选择模型，输入 API Key
3. 开始聊天

---


## 数据存储

所有数据存 `localStorage`，包括对话历史、API Key、角色设定。

按 F12 → Application → Local Storage 可查看或删除。

---

## 常见修改

- **改默认模型**：修改 `<option selected>` 和 `appSettings.defaultModel`
- **改上下文轮数**：修改 `CONTEXT_ROUNDS` 变量
- **清数据**：清除浏览器缓存或删除 localStorage 对应键

---

## 注意

API Key 明文存本地，勿在公共电脑使用。
```
