<p align="center">
  <a href="https://skyjjgw.com"><img src="https://github.com/skyjjgw/skyjjgw/raw/af1cf8f17e9edae323be409ab6d8b76c38b7c354/assets/starry-banner.svg" alt="A lantern lights the night: a traveler ignites a torch, a spark rises to a star, and the entire starry sky comes to life. Visit skyjjgw.com." width="100%" /></a>
</p>

<p align="center">
  <img src="https://github.com/skyjjgw/skyjjgw/raw/af1cf8f17e9edae323be409ab6d8b76c38b7c354/assets/intro-typing.svg" width="560" alt="Hi, I'm SKYJJGW. Turning ideas into tools you can use." /><br />
  Software engineering undergraduate, learning through projects and turning ideas into useful tools.
</p>

<p align="center">
  <a href="https://skyjjgw.com"><b>Website ↗</b></a> &nbsp; / &nbsp;
  <a href="#selected-projects">Projects</a> &nbsp; / &nbsp;
  <a href="https://skymoni.com/creators">Community ↗</a> &nbsp; / &nbsp;
  <a href="https://github.com/skyjjgw/AI-practice-log">Build log ↗</a> &nbsp; / &nbsp;
  <a href="mailto:skyjjgw@gmail.com">Email</a>
</p>

<br />

<p align="center">
  <a href="https://skymoni.com/creators">
    <picture>
      <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/skymoni-cloud-invitation-mobile.svg" />
      <img src="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/skymoni-cloud-invitation.svg" width="100%" alt="Skymoni 云端邀请函：你的脑洞，这里有人接住。聊 AI、晒作品、交换新灵感。欢迎免费加入我们的社区，点击来社区坐坐。" />
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://skymoni.com/creators"><b>☁ 来社区坐坐 / Meet us in the clouds ↗</b></a><br />
  <sub>A little place for big ideas. Come as you are, create what you love.</sub>
</p>

<br />

## About me

我是一名软件工程本科生，围绕 **AI 应用、开发者工具和交互体验**做项目。目前在维护 [Skymoni](https://skymoni.com/) 和它的创作者社区，也在把日常开发中遇到的问题做成独立工具。

我喜欢这样的改进：让思维导图可以离线分享，让 Android 模拟器留在工作区里，让插件出问题时仍然有入口恢复。这里记录这些工具从想法、原型到发布的过程，以及仍在继续的学习。

<p>
  <a href="https://skymoni.com/creators"><b>来社区交流 AI、工具与作品 ↗</b></a> &nbsp; · &nbsp;
  <a href="https://skyjjgw.com"><b>走进我的交互式作品馆 ↗</b></a>
</p>

<br />

## Selected projects

这些项目分别对应我正在维护的服务、已发布的工具，以及经过场景验证的原型。每个入口都能继续查看源码、使用方式或验证范围。

<table>
  <tr>
    <td width="50%" valign="top">
      <sub>01 &nbsp; / &nbsp; SERVICE &amp; COMMUNITY</sub>
      <h3><a href="https://skymoni.com/">Skymoni ↗</a></h3>
      <p><b>AI API 服务与创作者社区，持续迭代中。</b></p>
      <p>基于 New API 定制接口服务与管理界面，搭建创作者社区。围绕发帖、账号衔接、通知和邮件编辑等实际使用需求持续改进。</p>
      <p>当前前端、服务端和独立社区服务的对应源码可查，历史版本附下载与 SHA-256 校验。</p>
      <p><sub>持续维护 · New API 定制 · React / Go</sub></p>
      <p><a href="https://skymoni.com/creators">访问社区</a> &nbsp; · &nbsp; <a href="https://github.com/skyjjgw/skymoni-source">版本源码</a></p>
    </td>
    <td width="50%" valign="top">
      <sub>02 &nbsp; / &nbsp; EDGE AI &amp; ACCESSIBILITY</sub>
      <h3><a href="https://github.com/skyjjgw/visionbridge-aiot-accessibility">VisionBridge · 视桥 ↗</a></h3>
      <p><b>让盲道占用的发现、处理与复核形成闭环。</b></p>
      <p>边缘设备识别障碍并上报位置与证据；云端审核、地图派单，志愿者通过 App 处理任务并提交复核记录。</p>
      <p>已完成单边缘设备、单云节点与志愿者流程的原型验证，继续完善部署与可观测性。</p>
      <p><sub>可运行原型 · YOLO / FastAPI / React / Flutter</sub></p>
      <p><a href="https://github.com/skyjjgw/visionbridge-aiot-accessibility#已实现能力">实现范围</a> &nbsp; · &nbsp; <a href="https://github.com/skyjjgw/visionbridge-aiot-accessibility/blob/main/docs/DEVELOPMENT.md">开发指南</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub>03 &nbsp; / &nbsp; DEVELOPER EXPERIENCE</sub>
      <h3><a href="https://github.com/skyjjgw/dsh-plugin-android-preview">Android App Preview ↗</a></h3>
      <p><b>在 DSH 聊天侧栏里操作真实 Android 模拟器。</b></p>
      <p>支持点击、滑动和输入；Flutter 保存 Dart 后可热重载。APK、包名、Activity 与 monorepo 源码目录可配置，普通 Android APK 可关闭 Flutter 模式。</p>
      <p>v0.2.0 的 18 项测试通过三平台 CI，投屏与热重载链路已用 Windows 模拟器验证。</p>
      <p><sub>已发布 v0.2.0 · JavaScript / ADB / scrcpy / Flutter</sub></p>
      <p><a href="https://github.com/skyjjgw/dsh-plugin-android-preview/releases/tag/v0.2.0">安装与发行记录</a> &nbsp; · &nbsp; <a href="https://github.com/skyjjgw/dsh-plugin-android-preview/actions/runs/39592839411">查看 CI</a></p>
    </td>
    <td width="50%" valign="top">
      <sub>04 &nbsp; / &nbsp; LOCAL-FIRST TOOLS</sub>
      <h3><a href="https://github.com/skyjjgw/xmind-to-html">XMind → HTML ↗</a></h3>
      <p><b>把思维导图变成一份能直接分享的离线网页。</b></p>
      <p>将主题、备注、图片和多画布内容打包进单个 HTML，支持搜索、折叠、拖动与缩放。接收者用浏览器即可查看，无需安装 XMind。</p>
      <p>提供 Windows 程序和 Python CLI，已验证 XMind 8 XML、Zen 与 2026 JSON 格式样本。</p>
      <p><sub>已发布 v1.1.0 · Python / HTML / JavaScript</sub></p>
      <p><a href="https://github.com/skyjjgw/xmind-to-html/releases/tag/v1.1.0">下载发行版</a> &nbsp; · &nbsp; <a href="https://github.com/skyjjgw/xmind-to-html#已验证的兼容范围">兼容范围</a></p>
    </td>
  </tr>
</table>

### More from the workbench

| 项目 | 解决的具体问题 | 当前形态 |
| --- | --- | --- |
| [DSH Version Guard](https://github.com/skyjjgw/dsh-version-guard) | 保存插件与配置回退点；即使 DSH 无法启动，也能通过独立进程打开恢复入口。 | 插件 + 独立恢复工具 |
| [FlowForge](https://github.com/skyjjgw/flowforge-workflow-studio) | 录制浏览器操作、编辑流程图，再导出可独立运行的流程。基于 HumanJS 定制。 | 工作流工作台；已验证本地演示流程 |
| [Starry Museum](https://github.com/skyjjgw/starry-museum-portfolio) | 把项目和手记放进可交互画框，提供可修改、可静态部署的匿名作品集模板。 | MIT 模板 · [在线演示](https://skyjjgw.github.io/starry-museum-portfolio/) |

<details>
  <summary><b>Earlier projects &amp; learning experiments · 更多实践</b></summary>

  <ul>
    <li><a href="https://github.com/skyjjgw/enterprise-rag-knowledge-base">Enterprise RAG</a>：围绕文档解析、混合检索、重排序和 LangGraph 问答链路展开的学习项目。</li>
    <li><a href="https://github.com/skyjjgw/An-edge-cloud-collaborative-assistive-navigation-system-for-visually-impaired-users">Assistive Navigation</a>：云端、视觉识别与志愿者协作的早期实践。</li>
    <li><a href="https://github.com/skyjjgw/BookTranslator">BookTranslator</a>：书籍翻译、术语复用和中断后继续处理的探索。</li>
    <li><a href="https://github.com/skyjjgw/drip-browser-source">Drip Browser</a>：浏览器标签页、账号界面与桌面交互的源码快照。</li>
    <li><a href="https://github.com/skyjjgw/QuickNotes">QuickNotes</a>：Markdown 笔记与悬浮窗口的桌面应用实践。</li>
  </ul>
</details>

<br />

## My toolkit

技术选择跟着项目走：用 Python 和检索工具验证 AI 流程，用 Web、接口和移动端把能力接到可操作的界面上。最近的实践也涉及 React 与 Flutter；Java / Spring Boot 仍在继续学习。

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/toolkit-workbench-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/toolkit-workbench-mobile.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/toolkit-workbench-dark.svg" />
  <img src="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/toolkit-workbench.svg" width="100%" alt="My toolkit. AI and knowledge: LangChain, LangGraph, RAG, Elasticsearch, Dify, OCR / VLM. Build and ship: Python, TypeScript, Vue 3, FastAPI, SQLite, REST APIs, Electron, Git, Docker. Currently learning Java and Spring Boot." />
</picture>

<br />

## How I build

- **从实际卡点出发。** 文件不方便分享、开发时来回切窗口、插件故障后缺少恢复入口，都是项目的起点。
- **先跑通一个完整流程。** 从真实输入走到可操作的结果，再逐步补齐配置、异常处理和使用说明。
- **留下可核对的证据。** 用源码、发行包、测试和场景记录说明完成程度，并持续记录已知限制。

开发中我会使用 AI 编程工具辅助实现，也在练习需求拆解、代码阅读、问题定位和结果验证。这里既有持续维护的项目，也有学习中的原型；各自的状态写在仓库说明里。

[查看学习与实践记录 ↗](https://github.com/skyjjgw/AI-practice-log) &nbsp; · &nbsp; [在社区分享你的问题或作品 ↗](https://skymoni.com/creators)

<br />

## One contribution at a time

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/contribution-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/contribution-snake.svg" />
  <img width="100%" alt="A snake follows my GitHub contribution trail, eating the contribution squares along the way." src="https://raw.githubusercontent.com/skyjjgw/skyjjgw/main/assets/contribution-snake.svg" />
</picture>

<p align="center"><sub>Small steps. Useful things. A trail worth keeping.</sub></p>

<br />

<p align="center">
  <b>Stay curious. Make something useful.</b><br />
  <sub><a href="https://skyjjgw.com">skyjjgw.com</a> &nbsp; · &nbsp; <a href="https://skymoni.com/creators">skymoni community</a> &nbsp; · &nbsp; <a href="mailto:skyjjgw@gmail.com">say hello</a></sub>
</p>
