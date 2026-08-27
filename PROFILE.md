# GC Skills

Small, opinionated Codex Skills for turning rough intent into executable instructions, preserving character identity in minimal doodles, creating quiet editorial images, and directing restrained motion.

一组克制、可复用的 Codex Skills：把模糊想法变成可执行任务，在极简手绘中保留角色身份，把主题变成静态视觉，再为真实图片编写克制的动态 Prompt。

## Public Skills

| Skill | Start with / 输入 | Get / 输出 |
| --- | --- | --- |
| [**GC AI Speak Translator**](https://github.com/LiamGvchi/gc-ai-speak-translator)<br><code>gc-ai-speak-translator</code> | A rough request that another AI needs to understand.<br>需要交给另一个 AI、但还没说清楚的想法。 | A precise, copy-ready prompt or agent task brief.<br>可直接复制的 Prompt 或 Agent 任务说明。 |
| [**GC Minimal IP Doodle**](https://github.com/LiamGvchi/gc-minimal-ip-doodle)<br><code>gc-minimal-ip-doodle</code> | A mascot, toy, animal, or IP-character reference that needs a consistent minimal redraw.<br>需要在极简重绘中保持身份一致的吉祥物、玩具、动物或 IP 角色参考图。 | Identity-preserving minimal doodle illustrations across genuinely distinct small scenes.<br>在真正不同的小场景中生成保持角色身份一致的极简手绘插画。 |
| [**GC Minimal Zine Poster v0.3.1**](https://github.com/LiamGvchi/gc-minimal-zine-poster)<br><code>gc-minimal-zine-poster-v0-3</code> | A theme, sentence, article idea, photo, content brief, or reference set.<br>主题、句子、文章想法、照片、内容 Brief 或参考图集。 | A generated poster and final image prompt, or an evidence-based reusable visual system when analysis is requested.<br>生成的海报与最终生图 Prompt；请求分析时，返回基于证据的可复用视觉系统。 |
| [**GC Still Image Motion Director**](https://github.com/LiamGvchi/gc-still-image-motion-director)<br><code>gc-still-image-motion-director</code> | A real still image that may become an image-to-video clip.<br>准备交给图生视频模型的真实静态图片。 | A `motion`, `micro-motion`, or `static` decision, stability locks, and a copy-ready image-to-video prompt.<br>动态判断、固定项和可复制的图生视频 Prompt。 |

## Choose the Right Skill

- **“I know what I mean, but I do not know how to say it to AI.”**  
  Use [GC AI Speak Translator](https://github.com/LiamGvchi/gc-ai-speak-translator).

- **“I have a character reference and want consistent minimal doodles across different scenes.”**
  Use [GC Minimal IP Doodle](https://github.com/LiamGvchi/gc-minimal-ip-doodle).

- **“I have a theme or brief and want a finished editorial poster.”**  
  Use [GC Minimal Zine Poster](https://github.com/LiamGvchi/gc-minimal-zine-poster).

- **“I already have an image and need to decide how it should move.”**  
  Use [GC Still Image Motion Director](https://github.com/LiamGvchi/gc-still-image-motion-director).

## Use Them Independently or Together

Each Skill is a standalone repository with its own URL, stars, installation entry, documentation, and issue tracker. They do not need to be installed or used as a bundle.

They can also form one optional workflow:

```text
rough human request
        ↓
gc-ai-speak-translator
        ↓
clear executable brief
        ↓
gc-minimal-zine-poster-v0-3
        ↓
poster image + final image prompt
        ↓
gc-still-image-motion-director
        ↓
motion decision + platform-ready image-to-video prompt
        ↓
image-to-video model
```

```text
模糊的人类需求
        ↓
gc-ai-speak-translator
        ↓
清晰、可执行的任务说明
        ↓
gc-minimal-zine-poster-v0-3
        ↓
海报图片 + 最终图片 Prompt
        ↓
gc-still-image-motion-director
        ↓
动态判断 + 可交给 Seedance 等模型的图生视频 Prompt
        ↓
图生视频模型
```

The Motion Director writes motion direction and prompts. It does not generate the final video by itself.

Motion Director 负责动态判断和 Prompt 编写，本身不直接生成最终视频。

## Shared Principles

- inspect the real input before making recommendations;
- preserve the user's intent instead of inventing context;
- make visual and execution decisions explicit;
- avoid generic effects and decorative prompt inflation;
- return outputs that can be copied into the next tool;
- state uncertainty and capability boundaries clearly.

## Install

Open a Skill repository above and follow its installation instructions. Each repository is public and independently maintained; check its own README for the current license.

进入对应 Skill 仓库，按照各自 README 的安装说明操作。四个项目均为独立公开仓库；当前许可证以各仓库说明为准。
