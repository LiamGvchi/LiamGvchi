# GC Skills

Small, opinionated Codex Skills for turning rough intent into executable instructions, quiet editorial images, and restrained motion direction.

一组克制、可复用的 Codex Skills：把模糊想法变成可执行任务，把主题变成静态视觉，再把真实图片转成图生视频动态 Prompt。

## Public Skills

| Skill | Start with / 输入 | Get / 输出 |
| --- | --- | --- |
| [**GC AI Speak Translator**](https://github.com/LiamGvchi/gc-ai-speak-translator)<br><code>gc-ai-speak-translator</code> | A rough request that another AI needs to understand.<br>需要交给另一个 AI、但还没说清楚的想法。 | A precise, copy-ready prompt or agent task brief.<br>可直接复制的 Prompt 或 Agent 任务说明。 |
| [**GC Minimal Zine Poster**](https://github.com/LiamGvchi/gc-minimal-zine-poster)<br><code>gc-minimal-zine-poster-v0-1</code> | A theme, sentence, object, mood, article idea, photo, or content brief.<br>主题、句子、物件、情绪、文章想法、照片或内容 Brief。 | A quiet minimal zine-style poster image, final image prompt, and variation direction.<br>极简 zine 风格海报图片、最终图片 Prompt 与变化方向。 |
| [**GC Still Image Motion Director**](https://github.com/LiamGvchi/gc-still-image-motion-director)<br><code>gc-still-image-motion-director</code> | A real still image that may become an image-to-video clip.<br>准备交给图生视频模型的真实静态图片。 | A `motion`, `micro-motion`, or `static` decision, stability locks, and a copy-ready image-to-video prompt.<br>动态判断、固定项和可复制的图生视频 Prompt。 |

## Choose the Right Skill

- **“I know what I mean, but I do not know how to say it to AI.”**  
  Use [GC AI Speak Translator](https://github.com/LiamGvchi/gc-ai-speak-translator).

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
gc-minimal-zine-poster-v0-1
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
gc-minimal-zine-poster-v0-1
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

Open a Skill repository above and follow its installation instructions. Each repository is public, independently maintained, and available under the MIT License.

进入对应 Skill 仓库，按照各自 README 的安装说明操作。三个项目均为独立公开仓库，并采用 MIT License。
