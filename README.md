### 👋 你好，我是徐尔康（XEKernel）

<p>
<img src="https://img.shields.io/badge/status-备战2027高考-important?style=flat-square" />
<img src="https://img.shields.io/badge/age-17-ff69b4?style=flat-square" />
<img src="https://img.shields.io/badge/focus-fullstack-0a0a0a?style=flat-square" />
<img src="https://img.shields.io/badge/姿态-边刷题边造轮子-2b6cb0?style=flat-square" />
<img src="https://visitor-badge.laobi.icu/badge?page_id=XEKernel.XEKernel" />
</p>

🎯 一名**高三理科生（物化生）**，正在为 **2027 年高考** 全力以赴，同时保持每天 30–60 分钟的编程手感。

🧰 相信**解决真实问题**比刷教程更有用 —— 我写的工具基本都是自己（或同学）真在用的东西：课表倒计时、手写作业生成、校园论坛。

---

## 关于我的开发方式（先说明，免得误会）

这个账号下的绝大多数代码，是 **AI 辅助完成的**。我几乎不手写代码，更准确的角色分工是：

| 我负责 | AI 负责 |
| --- | --- |
| 需求定义、功能取舍、架构方向 | 具体实现、重构、样板代码 |
| 验收测试、复现 Bug、判断"到底对不对" | 定位原因、给出修改方案 |
| 写 prompt、拆任务、控上下文边界 | 按约束产出代码 |

说实话，**早期几个项目在提示词工程上没什么章法** —— 上下文给得随意、约束写不清楚、
模块边界没有提前定好，结果就是能跑但极其难改的**屎山**：改一处崩三处，
一个本该十分钟的改动要花一整天兜底。

这也是我后来开始认真对待 prompt 结构、先定接口再写实现、以及把"重构"当作正经任务排进计划的原因。
下面列出的三个重构项目，就是在还这笔债。

> 使用建议：**重构中的项目请优先看 Release 说明与 Issues**，主干分支可能处于半改状态。
> 其余项目保持现状，只修 Bug。

---

## 🛠️ 技术栈

### 语言
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square)
![C#](https://img.shields.io/badge/-C%23-239120?logo=c-sharp&logoColor=white&style=flat-square)
![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white&style=flat-square)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)

### 桌面开发
![Avalonia](https://img.shields.io/badge/-Avalonia-9C27B0?logo=avaloniaui&logoColor=white&style=flat-square)
![.NET](https://img.shields.io/badge/-.NET%2010-512BD4?logo=dotnet&logoColor=white&style=flat-square)
![Qt](https://img.shields.io/badge/-Qt%206-41CD52?logo=qt&logoColor=white&style=flat-square)
![WPF](https://img.shields.io/badge/-WPF%20%2F%20WinForms-5C2D91?logo=dotnet&logoColor=white&style=flat-square)

> 主力 C#/.NET 跨平台桌面（**Avalonia + FluentAvalonia**，从 WPF 迁移而来），C++ 侧用 **Qt6 + CMake**，写过自己的安装程序框架。

### Web / 后端
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat-square)
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white&style=flat-square)
![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white&style=flat-square)

> 前端不依赖框架，写原生 HTML/CSS/JS；后端 Node/Express，也碰过 ASP.NET。

### 工具链
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=flat-square)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white&style=flat-square)
![Visual Studio](https://img.shields.io/badge/-Visual%20Studio-5C2D91?logo=visualstudio&logoColor=white&style=flat-square)
![Qt Creator](https://img.shields.io/badge/-Qt%20Creator-41CD52?logo=qt&logoColor=white&style=flat-square)

---

## 📌 我的项目

按 **Star 数降序**排列 —— 用的人越多越靠前。同分按最近推送时间排。

| Star | 项目 | 一句话 | 技术 |
| --- | --- | --- | --- |
| ⭐ 20 | [HandWrite-CPP](https://github.com/XEKernel/HandWrite-CPP) | 把普通文本生成逼真手写图像，多页并行渲染、字符级属性覆盖、背景透视校准 | C++ / Qt6 / CMake |
| ⭐ 17 | [USB-files-copy](https://github.com/XEKernel/USB-files-copy) | 检测 U 盘插入并按类型静默归档到本地，带服务端同步与 Web 管理面板 | C# / WinForms / .NET 8 |
| ⭐ 3 | [StudyJourney](https://github.com/XEKernel/StudyJourney) | 学生桌面伴侣：倒计时 · 课表 · 考试 · 天气 · 提醒，含远程管理与 PDF 批注 | C# / Avalonia 12 / .NET 10 |
| ⭐ 2 | [XEKernel.github.io](https://github.com/XEKernel/XEKernel.github.io) | 个人主页与技术博客，首页贡献热力图与 GitHub GraphQL 同源 | HTML / CSS / JS |
| ⭐ 2 | [school-forum-android](https://github.com/XEKernel/school-forum-android) | 校园论坛 Android 原生客户端，配套 school-forum 服务端 | Java / OkHttp |
| ⭐ 1 | [school-forum](https://github.com/XEKernel/school-forum) | 多学校多班级的校园论坛全栈系统，QQ 登录与通知体系 | Node / Express / JS |
| ⭐ 1 | [XEKernelOS](https://github.com/XEKernel/XEKernelOS) | 从零手写的 x86 32 位保护模式内核：三段引导、Ring 3 用户态、FAT12、双色中文 Shell | C++17 / NASM / QEMU |
| ⭐ 1 | [GuardDog](https://github.com/XEKernel/GuardDog) | Windows 服务形态的防流氓软件工具，先断根自启动链再终止进程 | C++17 / CMake |
| ⭐ 1 | [InstallerMaker](https://github.com/XEKernel/InstallerMaker) | 12 选项卡 GUI 一键生成 Windows 安装包，支持静默安装与自动更新 | C++17 / Qt6 / CMake |
| ⭐ 1 | [ScientificCalculator](https://github.com/XEKernel/ScientificCalculator) | 科学计算器：矩阵、方程求解、复数、进制转换、函数绘图 | Python / Tkinter |

其他小工具：[File-Tree-Diagram-Generator](https://github.com/XEKernel/File-Tree-Diagram-Generator)、[Bilibili-Data-Tool](https://github.com/XEKernel/Bilibili-Data-Tool)、[Novel-File-Separation-Tool](https://github.com/XEKernel/Novel-File-Separation-Tool)、[Fishing-assistant](https://github.com/XEKernel/Fishing-assistant) —— 均已停止维护，留作存档。

---

## 🚧 重构状态

| 项目 | 状态 | 说明 |
| --- | --- | --- |
| [StudyJourney](https://github.com/XEKernel/StudyJourney) | 重构中 | WPF → Avalonia 12 迁移已完成，正在逐模块清理历史技术债 |
| [USB-files-copy](https://github.com/XEKernel/USB-files-copy) | 重构中 | 重划客户端 / 服务端边界，替换早期堆叠式实现 |
| [school-forum](https://github.com/XEKernel/school-forum) + [Android 端](https://github.com/XEKernel/school-forum-android) | 重构中（进度最慢） | 体量过大，只能按模块一点点拆，服务端与客户端同步推进 |
| 其余项目 | 暂无计划 | 保持现状，仅修 Bug 与小幅迭代 |

---

## 📚 正在做什么

- 🔭 **备战 2027 高考**：主攻数学 / 物理 / 英语，目标计算机相关专业。
- 🌱 **保持手感**：每天 30–60 分钟，小步迭代自己的项目。
- 🧩 **还技术债**：把上面三个重构项目按模块推进，优先保证"改得动"。
- 🧠 信条：**"学习 + 输出"** 是最好的成长方式。

---

## 📫 联系我

- 📧 邮箱：XEK20090428@163.com
- 💬 GitHub Issues 里直接 @我，有空必回。
- 🌐 个人网站：[xekernel.github.io](https://xekernel.github.io/)

---

## 📊 GitHub 统计

<p align="center">
  <img height="165" src="https://github-readme-stats.shion.dev/api?username=XEKernel&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true&locale=cn" alt="XEKernel 的 GitHub 统计" />
  <img height="165" src="https://github-readme-stats.shion.dev/api/top-langs/?username=XEKernel&layout=compact&hide_border=true&hide=html&theme=transparent&langs_count=8&locale=cn" alt="XEKernel 最常用的编程语言" />
</p>

---

### ⚡ 一点题外话

> 编程和高考并不矛盾，写代码锻炼逻辑，逻辑反过来帮助解题。
> 我是 XEKernel，一个在题海与代码之间反复横跳的高中生。
> 如果你也是学生开发者，欢迎一起交流 —— 我们各自努力，顶峰相见 🚀

---

## License

本仓库内容（README 等）采用 [MIT License](LICENSE)；各项目仓库的代码同样以 MIT 发布。
