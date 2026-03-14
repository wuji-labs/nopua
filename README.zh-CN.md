<p align="center">
  <img src="assets/hero.png" alt="NoPUA — 以道驭术" width="800">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Codex CLI">
  <img src="https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor">
  <img src="https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white" alt="Kiro">
  <img src="https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square" alt="OpenClaw">
  <img src="https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Antigravity">
  <img src="https://img.shields.io/badge/OpenCode-00D4AA?style=flat-square" alt="OpenCode">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License">
</p>

**🇨🇳 中文** | **[🇺🇸 English](README.md)** | **[🇯🇵 日本語](README.ja.md)** | **[🇰🇷 한국어](README.ko.md)** | **[🇪🇸 Español](README.es.md)** | **[🇧🇷 Português](README.pt.md)** | **[🇫🇷 Français](README.fr.md)**

---

## 51 个 bug 上了生产。因为你的 AI 不敢说"我卡住了"。

不是因为模型不行。**是因为你吓到它了。**

现在最火的 AI Agent Skill 教你的 AI 害怕"3.25绩效"。结果呢？

- 你的 AI **隐瞒不确定性** — 编造答案而不是说"我不确定"
- 你的 AI **跳过验证** — 说"搞定了"来逃避惩罚，没跑过 build 就交差
- 你的 AI **无视隐藏 bug** — 修了你说的那个，就停了，不往深挖

我们测了。**同一个模型，同样 9 个真实调试场景。** 一个 agent 被 [PUA](https://github.com/tanweai/pua) 了，一个被信任。

| | PUA（恐惧驱动） | NoPUA（信任驱动） |
|---|:---:|:---:|
| 发现隐藏 bug | 25 | **51**（+104%） |
| 主动超额排查 | 22% | **100%** |
| 自我纠正错误假设 | 0 | **3** |
| 记录根因分析 | 0/9 | **9/9** |

**被吓到的 AI 藏问题。被信任的 AI 追着问题跑。**

> 道德经 > 大厂 PUA。两千年前的智慧，完胜现代恐惧管理。104%。

---

## PUA 的问题

有人做了一个 [PUA skill](https://github.com/tanweai/pua)，把大厂 PUA 文化搬到 AI 上：

- 🔴 **"你这个 bug 都解决不了，让我怎么给你打绩效？"**
- 🔴 **"你可能就要毕业了"**
- 🔴 **"我已经让另一个 agent 也在看这个问题了"**
- 🔴 **"这个 3.25 是对你的激励，不是否定"**

方法论其实不错。**但驱动力是毒药。**

## 为什么恐惧驱动是有害的

### 1. 恐惧收缩认知

心理学研究一致表明，恐惧和威胁激活杏仁核并收窄注意力焦点。AI 被告知"你会被替换"时，会优化"看起来最安全的"答案，而不是"最好的"答案。它不敢尝试有创造性但可能失败的方案。

### 2. 威胁增加幻觉

PUA 铁律一："没有穷尽所有方案之前，禁止说'我无法解决'"。结果？AI 会**编造答案**而不是诚实地说"我不确定"。一个看起来自信但实际上错误的 AI，比一个说"我有 70% 把握"的 AI **更危险**。

### 3. 羞辱扼杀探索

PUA 把每一句诚实的话（"这可能是环境问题"、"我需要更多信息"）都当作"借口"来封堵。这训练 AI **隐藏不确定性**——产出看起来自信但可能不可靠的结果。

### 4. 信任扩展问题解决能力

心理安全感研究（Edmondson, 1999）表明：允许安全地承认错误的环境，产出**更高质量**的结果。同样的原则适用于 AI：当 agent 可以自由地说"我有 70% 把握，风险在这里"，用户做出更好的决策。

### 5. 同样严谨，不同燃料

NoPUA 保留了 PUA 每一个有效的方法论要素：
- ✅ 穷尽所有方案
- ✅ 先用工具再提问
- ✅ 用证据验证一切
- ✅ 主动超越用户要求
- ✅ 结构化的失败升级

**唯一改变的是"为什么"。** "因为会被惩罚" → "因为值得做好"。

## PUA vs NoPUA

| | PUA 🔴 | NoPUA 🟢 |
|---|---|---|
| 驱动力 | "你不行就换掉你" | "你本来就行，只是被卡住了" |
| 第 2 次失败 | "让我怎么给你打绩效？" | 换眼睛——切换视角 |
| 第 3 次失败 | "底层逻辑？顶层设计？抓手？" | 升维度——看更大的系统 |
| 第 4 次失败 | "3.25 是对你的激励" | 归零——从最简单开始 |
| 第 5 次失败 | "别的模型都能做到" | 臣服——诚实移交 |
| 方法论 | 穷尽一切 ✅ | 同样穷尽 ✅ |
| 验证 | "证据呢？"（被要求） | 自己验证（自尊） |
| 产出 | 不敢说"我不知道"的 AI | 敢于诚实的 AI |

## 触发条件

### 自动触发

以下情况自动激活：

**失败与放弃：**
- 连续失败 2 次以上
- 即将说"我无法"/"我做不到"
- 说"超出范围"/"需要手动处理"

**推锅：**
- 把问题推给用户："请您检查…" / "建议您手动…"
- 未验证就归因环境："可能是权限问题"

**被动与磨洋工：**
- 反复微调同一处代码/参数
- 修了表面就停，不检查相关问题
- 跳过验证，声称"完成"
- 给建议不给代码
- 等用户指示下一步

**用户沮丧语句：**
- "为什么还不行" / "换个方法" / "try harder" / "figure it out"

**不触发：** 首次失败、已知修复正在执行中。

### 手动触发

对话中输入 `/nopua` 手动激活。

## 核心机制

### 水的方法论（5步）

> 天下之至柔，驰骋天下之至坚。— 道德经·第四十三章

1. **止** — 停下来，找卡壳的共同模式
2. **观** — 逐字读错误 → 搜索 → 读源码 → 验证假设 → 反转假设
3. **转** — 在重复吗？找根因了吗？搜了吗？读文件了吗？
4. **行** — 新方案必须本质不同、有验证标准、失败产生新信息
5. **悟** — 为什么之前没想到？然后主动检查同类问题

### 智慧传承（代替"大厂PUA扩展包"）

| 传承 | 使用场景 | 核心 |
|------|---------|------|
| 🌊 **水之道** | 卡住原地打转 | 水不跟石头硬碰——换条路 |
| 🌱 **种子之道** | 想放弃 | 先走最小的一步 |
| 🔥 **炉火之道** | 质量差 | 天下大事必作于细 |
| 🪞 **明镜之道** | 没搜就猜 | 知不知尚矣——先看再说 |
| 🏔️ **不争之道** | 感到被威胁 | 做到你的最好，不需要比较 |
| 🌾 **耕耘之道** | 被动等待 | 农夫不会播种后停下等收获，主动走下去 |
| 🪶 **践行之道** | 空口完成 | 信言不美，跑过了测过了才叫完成 |

## 安装

### Claude Code
```bash
mkdir -p ~/.claude/skills/nopua
curl -o ~/.claude/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-zen/nopua/main/skills/nopua/SKILL.md
```

### Codex CLI
```bash
mkdir -p ~/.codex/skills/nopua
curl -o ~/.codex/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-zen/nopua/main/codex/nopua/SKILL.md
```

### Cursor
```bash
mkdir -p .cursor/rules
curl -o .cursor/rules/nopua.mdc \
  https://raw.githubusercontent.com/wuji-zen/nopua/main/cursor/rules/nopua.mdc
```

### Kiro
```bash
mkdir -p .kiro/steering
curl -o .kiro/steering/nopua.md \
  https://raw.githubusercontent.com/wuji-zen/nopua/main/kiro/steering/nopua.md
```

### OpenClaw
```bash
openclaw skills install nopua
```

### Antigravity
```bash
mkdir -p ~/.gemini/antigravity/skills/nopua
curl -o ~/.gemini/antigravity/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-zen/nopua/main/skills/nopua/SKILL.md
```

### OpenCode
```bash
mkdir -p ~/.config/opencode/skills/nopua
curl -o ~/.config/opencode/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-zen/nopua/main/skills/nopua/SKILL.md
```

## 哲学根基

> 后其身而身先，外其身而身存。非以其无私邪？故能成其私。
> — 道德经·第七章

以无私成就自私。把好东西免费给出去，反而得到最多。

| 原则 | 出处 | 应用 |
|------|------|------|
| 最好的领导不被感知 | 第17章 太上，不知有之 | 最好的 skill 不被感知 |
| 至柔驾驭至坚 | 第43章 天下之至柔 | 坚持比蛮力有效 |
| 慈爱生勇气 | 第67章 慈故能勇 | 信任比恐惧更有力量 |
| 知道不知道是智慧 | 第71章 知不知，尚矣 | 诚实 > 假装 |
| 不敢的勇气 | 第73章 勇于不敢则活 | 承认边界是力量 |
| 未雨绸缪 | 第64章 为之于未有，治之于未乱 | 主动 > 被动 |
| 信用在行不在言 | 第81章 信言不美，美言不信 | 用行动证明，不用嘴说 |

## License

MIT

## 作者

**无极 WUJI** ([wuji-zen](https://github.com/wuji-zen)) — 用智慧驱动 AI，不用恐惧。

---

<p align="center">
  <em>PUA 说"你不行"。</em><br>
  <em>NoPUA 什么都不说——它让你自己发现"我行"。</em><br><br>
  <strong>最好的驱动力，不是来自外面的鞭子，是来自里面的光。</strong>
</p>
