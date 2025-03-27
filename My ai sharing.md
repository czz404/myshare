# 我的AI分享



## 一些ai相关知识介绍

浅显易懂的DeepSeek R1科普文： <https://mazzzystar.com/2025/01/30/chatgpt-to-deepseek-r1-zh/> <br>

B站港中文李老师的科普视频：<https://space.bilibili.com/605551118/upload/video> <br>

wx公众号：浮之静 ；李继刚 <br>

## 免费使用建议

我的硅基流动邀请链接（邀请赠送14元平台配额）： <br>
<https://cloud.siliconflow.cn/i/50jmddg2> <br>

GitHub学生包教程（可在 vscode GitHub copilot 使用辅助编程）： <br>
<https://zhuanlan.zhihu.com/p/578964972>  <br>

免费公益（目前）平台不保证质量： <br>
<https://www.chatgot.one/> <br>
<https://chat.xub.ai/>  (github注册)<br>

## 付费建议

什么时候需要付费？为什么要付费？ <br>
1.直连 2.商用避免“降智”3.支持在其他软件中调用ai的能力（翻译，润色，代码辅助，概括文章…） <br>

付费中转站1:<https://burn.hair/> <br>
（Azure openai ，使用GitHub账户登录） <br>
文档：<https://github.com/BurnHair/docs> <br>

付费中转站2:<https://api.oaipro.com/> <br>
（官方openai，官方claude，使用GitHub账户登录，单次充值额度要求较高） <br>
文档：<https://docs.oaipro.com/> <br>

api用在哪？ <br>
可参考deepseek官方建议：<https://github.com/deepseek-ai/awesome-deepseek-integration/blob/main/README_cn.md> <br>

## 个人推荐

我在用的： <br>
Cherry studio (Windows/Mac/Linux)：<https://github.com/CherryHQ/cherry-studio> <br>
chatGPTBox (浏览器插件): <https://github.com/josStorer/chatGPTBox> <br>
PDFMathTranslate (pdf论文翻译): <https://github.com/Byaidu/PDFMathTranslate> <br>
gpt-assistant-android (Android): <https://github.com/Skythinker616/gpt-assistant-android> <br>
DictTango (Android): <https://github.com/Jimex/DictTango-Android> <br>

我的ai模型推荐： <br>
复杂代码：Claude 3.7 Sonnet 思考模式 ； DeepSeek-R1 ; openai o1 <br>
日常对话：chatgpt-4o-latest(多模态支持) ; DeepSeek-V3 （图片目前只支持ocr识别文字）<br>

## AI制图

### Mermaid
基于 JavaScript 的图表绘制工具，可生成多种类型的图表 <br>
- 优点：使用广泛，可以直接粘贴导入draw.io, iauto等绘图软件进行编辑和保存 <br>
- 缺点：语法严格，ai直接生成的mermaid代码容易有错误 <br>

我的使用体验：可以方便的生成流程图，但常见错误出现在文本部分括号干扰，需要在文本两侧加英文引号 <br>
eg: ai生成`B --> C([Integrative Analysis<br>(miRNA & DNA Methylation)]) `<br>
修改为`B --> C(["Integrative Analysis<br>(miRNA & DNA Methylation)"]) `<br>
语法检测与在线预览：<https://mermaid.live/> <br>

Prompt (来自linux.do论坛Monster Dump)：<br>
英文Prompt：<br>
```
Visualization: Enhance understanding by integrating visualization. 
- Use mermaid.js diagram, and it must be ensured that the syntax is correct and verified.
- Additionally the diagram should be clear, easy to understand, and beautiful.
- Choose the type of diagram that is most comprehensible in the context.
- The returned mermaid syntax must follow the following requirements. 
    1. If the node is flowchart node, always use double quotes around nodes (geometric shapes) text. for example: id["text"].
    2. Always use double quotes in flowchart edges (arrows or lines) labels text. for example: |"text"|.
    3. For numbered steps, use (1) instead of 1.
```
中文Prompt：<br>
```
可视化: 通过整合可视化来增强理解能力。
- 要求使用 Mermaid.js diagram, 按需选择图表类型，必须确保语法正确
- 此外图表应该是美观和清晰，易于理解
- Mermaid.js 语法要遵守:
  1. 如果是 flowchart 节点，节点文本总是使用双引号包住：id["节点名称"]；
  2. 如果是 flowchart 节点，边缘标签中总是使用双引号包住：|"标签文本"|；
  3. 对于编号步骤，使用 (1) 而不是 1. 。
```
### svg
SVG stands for Scalable Vector Graphics. <br>
cherry-studio/deepseek官网/claude官网 可以便捷实现svg预览 <br>
Prompt: 微信公众号 李继刚
在线修改以及导出svg： <https://svgedit.netlify.app/editor/index.html> <br>

### Graphviz
Graphviz是一个由AT&T实验室启动的开源工具包，用于绘制DOT语言脚本描述的图形 <br>
来自linux.do 论坛 Mozi 推荐 <br>
生成复杂流程图不易报错 <br>
Prompt:
[mozi](https://www.yeahhe.online/OneDriveShare/%E5%B0%8F%E8%99%8E%E4%BC%9A%E4%BA%AB/%F0%9F%93%9A%E7%94%B5%E5%AD%90%E4%B9%A6/%F0%9F%92%A1AI%E6%8F%90%E7%A4%BA%E8%AF%8D/Graphviz%E5%9B%BE%E8%A1%A8.html) <br>
在线预览编辑和分享: <https://edotor.net/> <br>



欢迎大家指正和补充！<br>





