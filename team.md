# 项目团队

| 团队   | 角色               | 姓名   | 职责                           | 备注       |
|--------|--------------------|--------|--------------------------------|------------|
| 前端   | Leader (Doc Manager) | 徐博阳 | 前端技术决策和文档管理         | CEO、CTO   |
| 前端   | Proto & Designer   | 周晓   | 原型设计和UI/UX                |            |
| 前端   | Proto & Designer   | 郑勤   | 原型设计和交互逻辑             |            |
| 前端   | Proto & Designer   | 赵乙茗 | 视觉设计和动效实现             |            |
| 前端   | Frontend Test      | 肖赟   | 前端测试和质量保证             |            |
| 前端   | API Manager        | 夏倍蓓 | 前后端接口规范和管理           | CPO        |
| 后端   | Leader (Doc Manager) | 何德鑫 | 后端架构和文档管理             |            |
| 后端   | Server Manager     | 金子龙 | 服务器部署和维护               |            |
| 后端   | Issue Manager      | 朱林威 | 问题跟踪和知识管理             | CKO        |
| 后端   | Backend Test       | 高愉淇 | 后端测试和性能优化             |            |

# 项目仓库目录结构

```
Team7/
├── docs/                # 项目文档 (何德鑫、徐博阳维护)
│   ├── design/          # 设计文档
│   ├── api/             # API接口文档
│   └── meeting-notes/   # 会议记录
└── scripts/             # 部署脚本 (金子龙维护)
```

# 项目主计划

## 第一阶段：产品讨论与原型设计 (3.24-4.21)
- 第1周 (3.24-3.30): 需求分析与产品定位 (夏倍蓓、徐博阳)
- 第2周 (3.31-4.6): 核心功能设计与技术选型 (何德鑫、徐博阳)
- 第3周 (4.7-4.13): 原型设计初稿 (周晓、郑勤、赵乙茗)
- 第4周 (4.14-4.21): 原型评审与定稿 (全体成员)

## 第二阶段：开发实现 (4.22-5.26)
- 第5周 (4.22-4.28): 
  - 前端: 项目初始化、基础框架搭建 (徐博阳、周晓)
  - 后端: 技术架构设计、数据库建模 (何德鑫、金子龙)
  
- 第6周 (4.29-5.5):
  - 前端: 核心组件开发、UI框架集成 (赵乙茗、郑勤)
  - 后端: 基础API开发、认证系统实现 (朱林威、高愉淇)

- 第7周 (5.6-5.12):
  - 前端: 主要页面开发、交互逻辑实现 (周晓、郑勤)
  - 后端: 业务逻辑开发、核心功能实现 (何德鑫、金子龙)

- 第8周 (5.13-5.19):
  - 前端: 页面联调、性能优化 (肖赟、徐博阳)
  - 后端: API完善、压力测试 (高愉淇、朱林威)
  - 接口对接: 前后端初步联调 (夏倍蓓、何德鑫)

- 第9周 (5.20-5.26):
  - 全面联调: 功能集成测试 (全体成员)
  - Bug修复: 重点问题解决 (肖赟、高愉淇)
  - 文档完善: API文档更新 (夏倍蓓、何德鑫)

## 第三阶段：测试与优化 (5.27-6.16)
- 第10周 (5.27-6.2): 功能测试 (肖赟、高愉淇)
- 第11周 (6.3-6.9): 性能优化与Bug修复 (全体成员)
- 第12周 (6.10-6.16): 用户验收测试 (夏倍蓓、徐博阳)

# 团队协同工作制度

1. **例会制度**:
   - 每周四下午16:30-17:30固定例会
   - 会议记录由当周轮值记录员负责
   - 紧急问题可临时召集核心成员会议

2. **代码管理**:
   - 采用Git PR工作流
   - 每个功能/修复单独分支
   - 必须经过至少1人Code Review才能合并
   - 主干分支保护，禁止直接push

3. **文档规范**:
   - 所有设计文档需在docs目录存档
   - API变更需及时更新接口文档
