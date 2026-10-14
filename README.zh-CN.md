# Tried and True AI

[English](README.md) | 中文

我是非技术背景，这里收录的都是我在用 AI 做项目的过程中**实际用过、确实有帮助**的公开资源。AI 资讯多到刷不完，我的原则是少而精：只跟真正在做东西的人，看完就去动手，不让刷信息占掉做事的时间。

清单会持续更新，欢迎 Star 关注，也欢迎在 [Issues](https://github.com/zlgan-spec/tried-and-true-ai/issues) 推荐你觉得好的资源。

## 目录

- [值得关注的人](#值得关注的人)
- [搞懂 AI](#搞懂-ai)
- [Skill 与工具](#skill-与工具)
- [社区](#社区)
- [网页设计灵感](#网页设计灵感)
- [网页组件与动效](#网页组件与动效)

## 值得关注的人

- [Andrej Karpathy](https://x.com/karpathy) - OpenAI 创始成员、前特斯拉 AI 负责人，"vibe coding"这个词就是他在 X 上提的。他很会把大模型讲给普通人听，YouTube 上的 Deep Dive into LLMs like ChatGPT 适合入门
- [Matt Pocock](https://github.com/mattpocock) - TypeScript 名师，现在专注 AI 编程教学。他的 [skills](https://github.com/mattpocock/skills) 虽然写给工程师，但做项目的思路对非研发很有参考价值
- [Zara Zhang](https://github.com/zarazhangrui) - 非技术背景的 AI 玩家，代表作 [frontend-slides](https://github.com/zarazhangrui/frontend-slides)（让 AI 做网页 PPT）；另有 [codebase-to-course](https://github.com/zarazhangrui/codebase-to-course)，能把代码仓库变成给非技术同学看的互动课程。小红书也有更新
- [卡兹克 khazix-skills](https://github.com/KKKKhazix/khazix-skills) - 公众号「数字生命卡兹克」作者开源的 skill 合集。追 AI 最新动态看他的公众号

## 搞懂 AI

- [Dictionary of AI Coding](https://github.com/mattpocock/dictionary-of-ai-coding) - 用大白话解释 AI 编程黑话，我会反复翻
- [VibeHub](https://vibe-hub.org/) - 图解 vibe coding 常用术语，前后端、Git、AI 都有。每个词从"你会怎么说"讲到"它叫什么"，比如鼠标移上去按钮变色，叫 Hover。非研发没必要从 0 系统学技术，但关键的词得认识，我有空就翻几个补补盲区。另有一页「AI 味」清单，列了紫色发光、emoji 当图标这类 AI 页面的通病
- [深入理解 AI Agent](https://github.com/bojieli/ai-agent-book) ⭐ 强烈推荐 - 李博杰的开源书，含全文和 PDF。很多时候我们不知道自己不知道什么，先懂 agent 的原理，才能更好地用 AI

## Skill 与工具

- [skills.sh](https://www.skills.sh/) - 热门 agent skill 目录。我会定期逛逛，下载后改成自己的版本，比从 0 写一个 skill 快
- [ponytail](https://github.com/DietrichGebert/ponytail) - 让 AI 用更少的代码做出更好的效果，少写代码就少出错
- [taste-skill](https://github.com/Leonxlnx/taste-skill) - 给 AI 装上"审美"，别再生成千篇一律的模板页面
- [Supabase](https://supabase.com/) - vibe coding 常用的省心后端平台，数据、用户、登录这些都能做。有免费额度
- [pptx2html-turbo](https://github.com/brnyxx/pptx2html-turbo) - 把旧 PPT 转成 HTML。HTML 对 AI 更友好，转完就能让 AI 接着改。有在线版
- 克隆网页二选一：
  - [claude-skill-web-clone](https://github.com/Jane-xiaoer/claude-skill-web-clone) - 方法论型，先读网页真实源码再复刻，不靠 AI 瞎猜
  - [ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) - 模板型，一条命令开始克隆

## 社区

- [WaytoAGI](https://waytoagi.feishu.cn/wiki/QPe5w5g7UisbEkkow8XcDmOpn8e) - 很活跃的中文 AI 社区，资料多但质量参差。适合让 AI 帮你检索推荐，或者有空上去逛逛

## 网页设计灵感

AI 给的是互联网的平均值，能及格，但容易千篇一律、带 AI 味。想做出有自己风格的东西，得靠你的审美来挑、来定方向。审美是可以练的，多看好东西就会慢慢长出来。下面是我常看的，也常直接丢给 AI 当参考。

PRD 定下来、开始做视觉时，我的顺序是：先看整体风格 → 拆页面结构 → 记录可落地细节 → 进入 Vibe Coding。

**找灵感**

- [Dribbble](https://dribbble.com/) - 视觉设计大全，我常直接贴链接让 AI 参考
- [Awwwards](https://www.awwwards.com/) - 获奖网站合集
- [Land-book](https://land-book.com/) - 落地页设计合集
- [SaaS Landing Page](https://saaslandingpage.com/) - 专门收 SaaS 落地页
- [Supahero](https://supahero.io/) - 网站首屏设计合集
- [Curated](https://curated.design/) - 高质量官网合集，可按风格和行业筛选，点进去就是真实在线的网站

**拿来即用**

- [v0 Templates](https://v0.app/templates) - 各种网页模板
- [MotionSites](https://motionsites.ai/) - 现成的网页 prompt，复制给 AI 就能做出动效站

**我当范本的网站**

- [Anthropic - Path to Hope](https://www.anthropic.com/path-to-hope) - 官方站，照着学不容易出错
- [Notion](https://www.notion.com/) - 黑白为主、大字标题、手绘小人插画，用产品截图当主视觉。想做简洁不花哨的产品首页，照它学

## 网页组件与动效

- [React Bits](https://reactbits.dev/) - 200+ 现成的动效组件，带代码，像搭积木一样组合
- [Aceternity UI](https://ui.aceternity.com/) - 不只有单个组件，还有能直接拼成页面的区块
- [Magic UI](https://magicui.design/) - 动效很克制。静态页面做完、要加动效时丢给 AI 参考，建议只用在首次进入、关键操作和状态变化上
- [oriform](https://www.oriform.art/) - 前端动效展厅，数量不多但质量很高，一键复制
- [Codrops](https://tympanus.net/codrops/) - 网页交互灵感库，每个案例都讲思路、附源码。适合学思路，不建议一键全部照搬
- [sticker-forge](https://github.com/CatsJuice/sticker-forge) - 能撕的贴纸效果，我超级喜欢，自己也用上了
- [Rough Notation](https://roughnotation.com/) - 手绘下划线、圈注动效。光靠口头描述，AI 很难做出不生硬的效果，用它就行
- [Voxel Icon](https://voxel-icon.vercel.app/) - 3D 立体像素图标，附带一个能生成同款图标的 skill

## 许可

内容采用 [CC BY 4.0](LICENSE) 许可，转载请注明出处。
