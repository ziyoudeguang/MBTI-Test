MBTI 人格测试网站

代码由DeepSeek生成

一个功能完整的在线 MBTI 人格测试工具，基于迈尔斯-布里格斯类型指标（Myers-Briggs Type Indicator）理论，提供 93 道标准测试题，并包含人格百科、维度解析、情感相处指南等丰富扩展内容。

✨ 功能特点

93道标准测试题：基于 MBTI M 版本编制，题目顺序随机打乱，确保测试结果客观。

智能计时与结果：后台自动计时，测试完成后在结果页显示总用时。

完整的人格百科：16 种人格类型的详细介绍、核心特质、适合领域，支持按四大类筛选查看。

MBTI 四维详解：深入解析 E/I、S/N、T/F、J/P 四个维度，帮助用户理解人格分类基础。

情感相处指南：分析各类型在恋爱中的风格、最佳配对及情感需求，提供关系建议。

本地进度保存：刷新页面后测试进度自动恢复（包括已答题目、计时、题目顺序）。

全响应式设计：适配手机、平板、电脑，操作流畅。

多页面导航：统一导航栏，方便在测试、百科、维度、情感等模块间切换。

🗂️ 文件结构
text

项目根目录/

├── index.html              # 主页面（测试、百科、维度、情感首页）

├── encyclopedia.html       # 独立人格百科页

├── dimensions.html         # MBTI 四维详解页

├── relationship.html       # 情感相处指南页

├── css/

│   └── style.css           # 全局样式（被多个页面复用）

├── js/

│   └── questions.js        # 93 道测试题数据（var mbtiQuestions）

└── image/                  # 16 种人格类型的图片（命名如 ENFJ-typies.jpg）

🚀 使用方法

下载或克隆本仓库。

将 image 文件夹放入根目录，并确保包含 16 张对应人格类型的图片（文件名格式：类型-typies.jpg，例如 INTJ-typies.jpg）。

使用任意 HTTP 服务器打开 index.html（推荐使用 Live Server 等工具，避免本地文件跨域问题）。

开始测试：点击“开始测试” → 阅读须知 → 逐题作答 → 获得结果并查看详细分析。

🛠️ 技术栈

HTML5 + CSS3（Flexbox/Grid 布局）

原生 JavaScript（ES6）

LocalStorage（进度存储）

无第三方依赖，纯原生实现🤝 贡献


欢迎提交 Issue 或 Pull Request 改进功能、修复 bug 或优化文档。

📄 许可证
MIT License。可自由使用、修改、分发，但请保留原作者声明。

Enjoy your MBTI journey！ 🧠💡

当然这段文字也是让DeepSeek生成的[憋笑]
