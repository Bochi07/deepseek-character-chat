# DeepSeek Chat - AI 聊天助手

仿 DeepSeek 网页版的本地聊天工具，纯浏览器运行，数据存储在本地。

![界面预览](images/screenshot.png)

---

## 功能特点

- 支持 DeepSeek-V3、R1、V4 Flash、V4 Pro 等多个模型
- 无限个独立对话，每个对话可单独配置
- 角色扮演：内置 8 种预设，支持自定义 System Prompt
- 自定义头像（用户和 AI 均可设置）
- 流式打字输出，体验流畅
- 本地存储，无需后端服务器

---

## 快速开始

1. 浏览器打开 `index.html`
2. 选择模型，填入你的 API Key
3. 开始聊天

---

## 数据存储说明

所有数据存储在浏览器的 `localStorage` 中，包括：
- 对话历史
- API Key
- 角色设定

按 `F12` → `Application` → `Local Storage` 可查看或手动清除数据。

---

## 常见自定义修改

| 修改目标 | 操作方法 |
| :--- | :--- |
| 修改默认模型 | 调整 `<option selected>` 和 `appSettings.defaultModel` |
| 修改上下文轮数 | 调整 `CONTEXT_ROUNDS` 变量 |
| 清除所有数据 | 清除浏览器缓存或删除 localStorage 对应键 |

---

## 注意事项

> ⚠️ API Key 以明文形式存储在本地，请勿在公共或他人电脑上使用。
