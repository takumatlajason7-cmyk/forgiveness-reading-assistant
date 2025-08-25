# 宽恕就是爱 - AI智能阅读助手

> 基于先进AI技术的智能阅读分析工具，专注于心灵成长类书籍的深度理解与感悟生成

## 🌟 项目简介

这是一个创新的AI阅读助手应用，专门为《宽恕就是爱》等心灵成长书籍设计。通过集成先进的大语言模型API，为用户提供个性化的阅读分析、深度感悟和实用的生活应用指导。

### ✨ 核心特色

- **🤖 AI深度分析**：集成智谱GLM-4、通义千问等先进AI模型
- **📖 智能章节管理**：自动识别章节结构，追踪阅读进度
- **💡 个性化感悟**：生成符合个人成长需求的深度分析
- **📱 短视频文案**：自动生成适合社交媒体的内容
- **📝 个人笔记系统**：支持为每章添加个人思考
- **📊 阅读统计**：可视化进度跟踪和习惯养成
- **🔄 数据导出**：支持进度和感悟的多格式导出

## 🚀 在线体验

**网站地址：** [https://你的用户名.github.io/forgiveness-reading-assistant](https://你的用户名.github.io/forgiveness-reading-assistant)

## 📱 功能特性

### 🎯 AI分析能力
- **核心观点提取**：识别每章的关键思想和哲学洞察
- **个人成长指导**：提供具体的自我提升建议
- **生活实践应用**：转化理论知识为可操作的生活方法
- **情感共鸣分析**：帮助读者产生深层的情感连接

### 📚 阅读管理
- **多格式支持**：TXT文件上传和内容解析
- **进度可视化**：直观的阅读进度条和统计数据
- **智能提醒**：支持自动阅读模式和习惯养成
- **历史记录**：完整的阅读历程追踪

### 🛠 技术实现
- **前端框架**：原生HTML5 + CSS3 + ES6+
- **AI集成**：支持多种大语言模型API
- **数据存储**：浏览器本地存储，保护用户隐私
- **响应式设计**：完美适配桌面和移动设备

## 🔧 快速开始

### 方法一：直接使用（推荐）
1. 访问在线版本：[项目地址](https://你的用户名.github.io/forgiveness-reading-assistant)
2. 点击"使用《宽恕就是爱》示例"开始体验
3. 配置AI API密钥获得完整功能

### 方法二：本地部署
```bash
# 1. 克隆项目
git clone https://github.com/你的用户名/forgiveness-reading-assistant.git

# 2. 进入项目目录
cd forgiveness-reading-assistant

# 3. 直接打开index.html文件
# 或者使用简单的HTTP服务器
python -m http.server 8000
# 访问 http://localhost:8000
```

## ⚙️ API配置

### 推荐：智谱GLM-4
1. 访问 [智谱AI开放平台](https://open.bigmodel.cn)
2. 注册账号并完成实名认证
3. 创建API密钥
4. 在应用中配置密钥即可使用

### 成本说明
- **智谱GLM-4**：0.1元/万tokens，日常使用成本约3-5元/月
- **通义千问**：类似价格，阿里云生态
- **OpenAI GPT**：价格较高，适合专业用户

## 📖 使用指南

### 基础使用流程
1. **配置API**：输入您的AI API密钥
2. **导入书籍**：上传TXT文件或使用示例书籍
3. **开始阅读**：点击章节开始阅读之旅
4. **AI分析**：点击"生成AI深度感悟"获得分析
5. **记录笔记**：添加个人思考和感悟
6. **导出分享**：导出进度或分享感悟到社交媒体

### 高级功能
- **批量操作**：一键标记所有章节为已读
- **自动阅读**：定时自动切换章节
- **数据导出**：JSON格式的进度数据和Markdown格式的感悟合集
- **键盘快捷键**：左右箭头切换章节，Ctrl+G生成分析，Ctrl+S保存笔记

## 🎨 界面预览

### 桌面版
- 现代化的渐变设计风格
- 直观的卡片式章节布局
- 丰富的数据可视化

### 移动版
- 完美的触屏适配
- 简洁的操作界面
- 流畅的交互体验

## 🔍 技术架构

### 前端技术栈
- **HTML5**：语义化结构和现代标准
- **CSS3**：渐变、动画和响应式设计
- **JavaScript ES6+**：模块化代码和异步处理
- **本地存储**：LocalStorage数据持久化

### AI集成方案
```javascript
// 支持多种AI API
const supportedAPIs = {
  zhipu: 'https://open.bigmodel.cn/api/paas/v4/chat/completions',
  qianwen: 'https://dashscope.aliyuncs.com/api/v1/services/aigc/text-generation/generation',
  openai: 'https://api.openai.com/v1/chat/completions'
};
```

### 数据结构设计
```javascript
// 阅读进度数据结构
{
  chapterIndex: {
    date: "2024-01-01T12:00:00.000Z",
    insight: {
      content: "AI分析内容",
      timestamp: "2024-01-01T12:00:00.000Z"
    }
  }
}
```

## 🛡️ 隐私保护

- **本地优先**：所有数据存储在用户本地浏览器
- **API安全**：支持自定义API端点，保护密钥安全
- **无服务器**：纯前端应用，无后端数据收集
- **开源透明**：完整代码公开，可审查安全性

## 🚦 开发计划

### 已完成 ✅
- [x] 基础阅读功能
- [x] AI分析集成
- [x] 进度管理系统
- [x] 数据导出功能
- [x] 响应式设计
- [x] 多API支持

### 开发中 🚧
- [ ] 更多书籍格式支持（PDF、EPUB）
- [ ] 社区分享功能
- [ ] 阅读习惯分析
- [ ] 个性化推荐系统

### 计划中 📋
- [ ] 移动端原生应用
- [ ] 云端数据同步
- [ ] 多语言支持
- [ ] 语音阅读功能

## 🤝 贡献指南

欢迎各种形式的贡献！

### 如何贡献
1. Fork 本项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 贡献类型
- 🐛 Bug修复
- ✨ 新功能开发
- 📚 文档完善
- 🎨 界面优化
- 🌐 翻译工作

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

## 👨‍💻 作者信息

**开发者**：[你的名字]
- 📧 邮箱：your.email@example.com
- 🐙 GitHub：[@你的用户名](https://github.com/你的用户名)
- 💼 LinkedIn：[你的LinkedIn](https://linkedin.com/in/你的账号)

## 🌟 Star History

如果这个项目对您有帮助，请给个