# 小说创作模板说明

本目录包含了适用于小说创作的 Spec-Kit 模板文件。这些模板将原本用于软件开发的规格驱动方法改造成了适合小说创作的工作流程。

## 📁 模板文件列表

### 核心模板

| 文件名 | 用途 | 对应原模板 |
|--------|------|-----------|
| `novel-spec-template.md` | 小说规格说明书 | `spec-template.md` |
| `novel-plan-template.md` | 创作计划 | `plan-template.md` |
| `novel-tasks-template.md` | 创作任务列表 | `tasks-template.md` |
| `novel-checklist-template.md` | 质量检查清单 | `checklist-template.md` |
| `novel-constitution-template.md` | 创作原则宪章 | `memory/constitution.md` |

### 指南文档

| 文件名 | 用途 |
|--------|------|
| `NOVEL-GUIDE.md` | 完整的使用指南和最佳实践 |
| `NOVEL-README.md` | 本文件,模板说明 |

## 🔄 从代码到小说的映射

### 概念映射

| 软件开发概念 | 小说创作概念 | 说明 |
|-------------|-------------|------|
| Feature (功能) | Plot (情节) | 独立的故事情节 |
| User Story (用户故事) | Story Arc (故事线) | 完整的叙事单元 |
| Acceptance Criteria (验收标准) | Scene Requirements (场景要求) | 情节必须达到的效果 |
| Technical Stack (技术栈) | Writing Style (写作风格) | 叙事视角、文风、结构等 |
| Implementation (实现) | Writing (写作) | 实际的创作过程 |
| Test (测试) | Review (审查) | 质量检查和修改 |
| MVP | 最小可行故事 | 核心情节构成的完整故事 |
| Refactoring (重构) | Revision (修订) | 改进和润色 |

### 工作流映射

| 软件开发阶段 | 小说创作阶段 |
|-------------|-------------|
| Requirements (需求) | Story Concept (故事构思) |
| Specification (规格说明) | Plot Outline (情节大纲) |
| Architecture (架构) | Story Structure (故事结构) |
| Design (设计) | Character & World Building (角色与世界观设定) |
| Implementation (实现) | Writing (写作) |
| Testing (测试) | Editing (编辑) |
| Deployment (部署) | Publishing (发布) |

## 🎯 核心改造点

### 1. 规格说明 (Spec)

**原来**: 定义软件功能和技术要求  
**现在**: 定义故事情节和创作要求

**关键改变**:
- User Stories → 故事情节 (按优先级P1, P2, P3)
- Functional Requirements → 故事要求
- Technical Requirements → 非功能性要求(文风、节奏、篇幅等)
- Acceptance Scenarios → 情节场景

### 2. 创作计划 (Plan)

**原来**: 技术实现方案  
**现在**: 创作方法和详细设计

**关键改变**:
- Technical Context → 创作背景(类型、视角、文风等)
- Architecture → 故事结构
- Implementation Details → 角色设定、世界观、详细大纲
- Phase Gates → 创作原则检查关卡

### 3. 任务列表 (Tasks)

**原来**: 代码实现任务  
**现在**: 章节创作任务

**关键改变**:
- Code Files → 章节文件
- Test Tasks → 审查任务
- Dependencies → 情节依赖关系
- Parallel Tasks → 可并行创作的章节

### 4. 检查清单 (Checklist)

**原来**: 代码质量检查  
**现在**: 小说质量检查

**关键改变**:
- Code Quality → 文字质量
- Logic Errors → 情节逻辑
- Performance → 节奏控制
- Security → 一致性

### 5. 创作宪章 (Constitution)

**原来**: 软件架构原则  
**现在**: 创作原则

**关键改变**:
- Library-First → 读者优先
- Simplicity → 简洁性(角色、情节线限制)
- Test-First → 质量优先
- Anti-Abstraction → 展示优于讲述

## 📖 使用场景

### 适合使用的情况

✅ **长篇小说创作**
- 需要保持一致性
- 多个情节线
- 长时间跨度的创作

✅ **系列小说**
- 需要维护世界观一致性
- 多部作品的连贯性
- 角色发展的长期规划

✅ **多人协作创作**
- 需要明确的分工
- 统一的风格和标准
- 版本控制和协作

✅ **商业写作项目**
- 有明确的交付要求
- 需要进度管理
- 质量标准明确

### 不太适合的情况

❌ **即兴创作**
- 追求自由发挥
- 不喜欢提前规划

❌ **实验性写作**
- 探索新形式
- 打破常规结构

❌ **极短篇**
- 1000字以内的微小说
- 规划成本大于创作成本

## 🚀 快速开始

### 方式1: 使用命令(推荐)

如果你的AI助手支持自定义命令:

```bash
# 1. 建立创作原则
/novelkit.constitution [你的创作原则要求]

# 2. 创建规格说明
/novelkit.specify [你的故事构思]

# 3. 创建创作计划
/novelkit.plan [你的创作方法]

# 4. 生成任务列表
/novelkit.tasks

# 5. 开始创作
/novelkit.implement
```

### 方式2: 手动使用模板

1. 复制 `novel-spec-template.md` 并填写你的故事构思
2. 复制 `novel-plan-template.md` 并填写创作计划
3. 复制 `novel-tasks-template.md` 并分解创作任务
4. 使用 `novel-checklist-template.md` 进行质量检查

### 方式3: 让AI帮你填写

将模板内容提供给AI,让它帮你填写:

```
请根据以下故事构思,帮我填写 novel-spec-template.md:

[你的故事构思]
```

## 📚 详细文档

完整的使用指南请参考 `NOVEL-GUIDE.md`,包含:

- 详细的工作流程说明
- 核心概念解释
- 创作示例
- 最佳实践
- 常见问题解答
- 进阶技巧

## 🎨 示例项目结构

使用这些模板后,你的项目结构可能如下:

```
my-novel/
├── .specify/
│   ├── memory/
│   │   └── novel-constitution.md    # 创作原则
│   ├── specs/
│   │   └── 001-main-story/
│   │       ├── novel-spec.md        # 规格说明
│   │       ├── novel-plan.md        # 创作计划
│   │       ├── research.md          # 背景研究
│   │       ├── characters.md        # 角色设定
│   │       ├── worldview.md         # 世界观设定
│   │       ├── outline.md           # 详细大纲
│   │       ├── writing-guide.md     # 写作指南
│   │       └── tasks.md             # 任务列表
│   └── templates/
│       └── [这些模板文件]
├── manuscript/
│   ├── chapters/
│   │   ├── chapter-001.md
│   │   ├── chapter-002.md
│   │   └── ...
│   ├── drafts/                      # 草稿
│   └── notes/                       # 创作笔记
└── README.md
```

## 🔧 自定义模板

你可以根据自己的需求修改这些模板:

### 添加新字段

例如在 `novel-spec-template.md` 中添加:
```markdown
## 灵感来源
- [列出你的灵感来源]
```

### 调整检查清单

根据你的创作类型调整 `novel-checklist-template.md`:
- 悬疑小说: 增加线索铺设检查
- 言情小说: 增加情感曲线检查
- 科幻小说: 增加设定自洽性检查

### 修改创作原则

根据你的创作理念修改 `novel-constitution-template.md`:
- 添加新的原则条款
- 调整限制(如角色数量)
- 增加特定类型的要求

## 💡 最佳实践

### 1. 从小说宪章开始

先建立你的创作原则,这将指导所有后续决策。

### 2. 详细的角色设定

投入时间创建详细的角色档案,这会让写作更顺畅。

### 3. 使用优先级

合理分配情节优先级(P1, P2, P3),确保核心故事完整。

### 4. 保持文档更新

创作过程中如有变化,及时更新规格说明和计划。

### 5. 定期检查

使用检查清单定期检查质量,不要等到全部完成。

## 🤝 贡献

如果你有改进建议或发现问题:

1. 在原项目提交 Issue
2. 提交 Pull Request
3. 分享你的使用经验

## 📄 许可证

这些模板基于原 Spec-Kit 项目,采用 MIT 许可证。

---

## 🎓 学习路径

### 初学者

1. 阅读 `NOVEL-GUIDE.md` 的"快速开始"部分
2. 尝试一个短篇小说项目
3. 使用所有模板走一遍完整流程

### 进阶用户

1. 自定义模板以适应你的创作风格
2. 尝试长篇或系列小说项目
3. 探索多人协作创作

### 高级用户

1. 创建自己的创作原则体系
2. 开发自定义的检查清单
3. 建立自己的创作方法论

---

## 📞 获取帮助

- 查看 `NOVEL-GUIDE.md` 的常见问题部分
- 参考模板中的注释和说明
- 在社区寻求帮助

---

**开始你的规格驱动小说创作之旅吧!** ✍️📚
