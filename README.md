# Randal

Frontend engineer (React, TypeScript) in Qingdao, China. I build plugins for [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness), an open-source agent harness.

Open **[dsh-auth-gate](https://github.com/TecFancy/dsh-auth-gate)** first: a login door for a public instance that ships without one. **[dsh-lingualab](https://github.com/TecFancy/dsh-lingualab)** is the other thing I build — a listening lab, not a gap in the harness.

[npm](https://www.npmjs.com/~smpower)

**[dsh-auth-gate](https://github.com/TecFancy/dsh-auth-gate)** — a login door for a public instance

`dsh` ships without authentication, so anyone holding the URL can drive your agent and spend your tokens. This puts a door in front of it: password or shared-token sign-in, optional TOTP, passkeys, session cookies, rate limiting, and a CLI for user management.

`dsh plugin --profile web add dsh-auth-gate`

<img src="https://raw.githubusercontent.com/TecFancy/dsh-auth-gate/main/docs/demo/login-page.png" width="640" alt="The dsh-auth-gate sign-in page">

**[dsh-lingualab](https://github.com/TecFancy/dsh-lingualab)** — a listening lab for the media already in your workspace

Turn audio or video with subtitles into sentence-level listening practice, with looping, shadowing, recording, and notes written back to disk where the agent can read them.

`dsh plugin --profile web add dsh-lingualab`

<img src="https://raw.githubusercontent.com/TecFancy/dsh-lingualab/main/docs/assets/practice-light.webp" width="640" alt="The LinguaLab practice view: one sentence on the stage, the subtitle list beside it">

**[dsh-deeptutor](https://github.com/TecFancy/dsh-deeptutor)** — a bridge to DeepTutor

Connects dsh to DeepTutor, so a session can explain a topic step by step, quiz you, plan a learning path, search your own knowledge bases, and archive the answer as an HTML study page — without leaving the conversation. Also works from Claude Code.

`dsh plugin --profile web add dsh-deeptutor`

`dsh` is in developer preview and breaks compatibility on purpose. These follow it: version ranges checked against each release, mount points tracked, and CI on every pull request.

Also: **[posh-mocha](https://github.com/TecFancy/posh-mocha)**, a PowerShell and Windows Terminal kit.

Community work, not affiliated with DeepSeek.

<details>
<summary>中文简介</summary>

前端开发工程师，React 和 TypeScript 为主。今年下半年开始给 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)（简称 dsh）写插件。dsh 是一个开源的 agent harness，安装后即可作为编码助手使用，插件系统是它的骨架。

我做的几个插件里，最值得先看的是 **[dsh-auth-gate](https://github.com/TecFancy/dsh-auth-gate)**。dsh 本身没有登录功能，把实例开到公网上，谁拿到地址谁就能用你的 agent、消耗你的 token。这个插件就是给 dsh 装一道门：密码或共享令牌登录、TOTP、Passkey、限流，还带一个管理用户的命令行。

**[dsh-lingualab](https://github.com/TecFancy/dsh-lingualab)** 是另一回事，不算「dsh 缺的东西」。它是我自己想用的一个精听面板：把工作区里的音频和字幕拖进去，就能一句一句练，变速、循环、跟读、录音都有；听到好的句子可以收藏，笔记直接写回磁盘，agent 也能读。

还有一个 **[dsh-deeptutor](https://github.com/TecFancy/dsh-deeptutor)**，把 DeepTutor 接进对话里。想弄懂一个概念、想让人出几道题考自己、想规划一条学习路线，都不用离开当前会话。

三个都是一行命令装。

</details>
