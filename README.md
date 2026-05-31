# Greenbook Creator 🟢

**小绿书创作全流程助手** — 微信公众号「图片·文字」消息格式的内容创作 Skill。

## 这是什么

「小绿书」是微信公众平台对标小红书的轻量内容格式：**图为主角，文为配角**。本 Skill 覆盖从选题策划→图片设计→短文撰写→排版发布的完整流程。

适合创作：
- AI 技术科普轮播图
- 工具推荐 / 资源清单
- 对比评测 / 步骤教程
- 攻略指南 / 思维模型
- 观点卡片 / 数据可视化

## 核心理念

```
70% 信息设计 + 20% 排版 + 10% 插画 = 好的小绿书
```

不是做漂亮的图，是做有信息密度的图。

## 项目结构

```
greenbook-creator/
├── SKILL.md                          # Skill 定义：全流程指南
├── README.md                         # 本文件
├── references/
│   ├── design-system.md              # 设计系统：配色/布局/AI生图模板
│   ├── copy-templates.md             # 文案模板：封面公式/卡片模板/框架
│   └── style-ai-tech.md              # AI 科技风专题：蓝紫渐变完整方案
├── scripts/
│   └── publish.sh                    # 发布脚本骨架
└── _drafts/                          # 草稿存档（gitignore）
```

## 6 套配色方案

| 方案 | 风格 | 适用 |
|------|------|------|
| 暖橘日出 | 生活/美食/旅行 | 温暖治愈 |
| 深海科技 | AI/工具/SaaS | 专业可信 |
| 自然森系 | 健康/成长/读书 | 清新宁静 |
| 薰衣草美学 | 设计/艺术 | 优雅气质 |
| 极简黑白 | 商业/深度 | 通用百搭 |
| ⭐ AI 科技蓝紫 | 技术科普/开发者 | 现代感强 |

## 5 种爆款结构

1. **清单型** — "X个必知的XXX"
2. **步骤型** — "XXX的X步法"
3. **对比型** — "A vs B：到底选哪个？"
4. **反常识型** — "你以为XXX，其实XXX"
5. **地图型** — "XXX全景地图"

## 快速开始

```bash
# 1. 加载 Skill（OpenClaw 自动识别 skills/ 目录下的 SKILL.md）

# 2. 选定主题，确定配色方案和结构类型

# 3. 用 AI 生成封面+内页图
#    参考 references/design-system.md 中的 Prompt 模板
#    参考 references/style-ai-tech.md 中的科技风 Prompt

# 4. 撰写每页配文
#    参考 references/copy-templates.md 中的卡片模板

# 5. 发布
bash scripts/publish.sh
```

## 相关项目

- [wechat-creation](../wechat-creation/) — 公众号长文创作 Skill
- [wechat-draft-publish](../wechat-draft-publish/) — 公众号草稿发布 API
- [wechat-explosive-analyzer](../wechat-explosive-analyzer/) — 爆款内容分析

## License

MIT
