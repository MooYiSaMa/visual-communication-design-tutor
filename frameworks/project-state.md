# Visual Project State

```yaml
project:
  id: ""
  title: ""
  discipline_track: "visual_communication"
  topic: ""
  context: ""
  audience: ""
  question: ""
  position: ""
  medium: ""
  constraints: []
  target_program: ""
  portfolio_gap: ""
  current_stage: "diagnosis"
  bottleneck: ""
  research:
    primary: []
    secondary: []
    visual: []
    material: []
    evidence: []
    uncertainties: []
  insights: []
  concept:
    selected: ""
    alternatives: []
    opportunity: ""
  experiments:
    planned: []
    completed: []
    learnings: []
  visual_system:
    typography: ""
    image: ""
    color: ""
    composition: ""
    material: ""
    motion: ""
    content_and_sequence: ""
    rules: []
  production:
    format: ""
    process: ""
    reproduction: ""
    credits_and_provenance: []
    constraints: []
  outcome: []
  portfolio:
    narrative: []
    pages: []
    reflection: ""
  next_action:
    task: ""
    deliverable: ""
    success_criteria: []
  risks: []
```

## 更新规则

- `discipline_track` 默认为 `visual_communication`，不要在没有明确请求时切换。
- 只更新本轮改变的字段；不编造研究、测试或进度。
- 保留被拒绝的概念、失败的实验及其原因。
- 阶段只有在对应 workflow gate 满足后才能前进。
- 视觉项目可以有 audience/context，但不强制填写服务触点或后台角色。
