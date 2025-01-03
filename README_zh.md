# <p align="center">💻 AI 图片翻译🚀✨</p>

<p align="center">AI图片翻译快速识别图片中的文字，并用大语言模型翻译成对应的语言，适合文档扫描件、漫画等场景使用。</p>

<p align="center"><a href="https://302.ai/tools/pt/" target="blank"><img src="https://file.302.ai/gpt/imgs/github/20250102/72a57c4263944b73bf521830878ae39a.png" /></a></p >

<p align="center"><a href="README_zh.md">中文</a> | <a href="README.md">English</a> | <a href="README_ja.md">日本語</a></p>

![界面预览](docs/AI图片翻译.png)

来自[302.AI](https://302.ai)的[AI 图片翻译](https://302.ai/tools/pt/)的开源版本。你可以直接登录302.AI，零代码零配置使用在线版本。或者对本项目根据自己的需求进行修改，传入302.AI的API KEY，自行部署。


## 界面预览
AI快速识别图片中的文字，并翻译成对应的语言。
![界面预览](docs/图片翻译1.png)

## 项目特性
### 🛠️ 多语言转换
  在图片中提取文字并翻译成多种语言。无论是漫画、还是截图，都能快速实现多语言转换。
### ✍️ 智能识别
  智能识别文字区域和布局，确保翻译准确。
### 🖼️ 支持多种图片格式
  - PNG
  - JPG
  - JPEG
  - WEBP
### 📤 批量处理
  可同时处理多个图片文件，提高效率。
### 🌙 贴心暗色
  提供暗色模式，呵护您的用眼健康。
### 🌍 多语言支持
  - 中文界面
  - English Interface
  - 日本語インターフェース

通过AI 图片翻译,任何图片内容都可以正常查看! 🎉💻 让我们一起探索AI驱动的代码新世界吧! 🌟🚀

## 🚩 未来更新计划
- [ ] 模糊与低质量图片优化
- [ ] 提高对不同格式图片以及图片文件大小限制方面的兼容性
  
## 技术栈
- Next.js 14
- Tailwind CSS
- Shadcn UI
- Vecel AI SDK

## 开发&部署
1. 克隆项目 `git clone https://github.com/302ai/302_image_translation`
2. 安装依赖 `pnpm install`
3. 配置302的API KEY 参考.env.example
4. 运行项目 `pnpm dev`
5. 打包部署 `docker build -t coder-generator . && docker run -p 3000:3000 coder-generator`


## ✨ 302.AI介绍 ✨
[302.AI](https://302.ai)是一个面向企业的AI应用平台，按需付费，开箱即用，开源生态。✨
1. 🧠 集合了最新最全的AI能力和品牌，包括但不限于语言模型、图像模型、声音模型、视频模型。
2. 🚀 在基础模型上进行深度应用开发，我们开发真正的AI产品，而不是简单的对话机器人
3. 💰 零月费，所有功能按需付费，全面开放，做到真正的门槛低，上限高。
4. 🛠 功能强大的管理后台，面向团队和中小企业，一人管理，多人使用。
5. 🔗 所有AI能力均提供API接入，所有工具开源可自行定制（进行中）。
6. 💡 强大的开发团队，每周推出2-3个新应用，产品每日更新。有兴趣加入的开发者也欢迎联系我们
