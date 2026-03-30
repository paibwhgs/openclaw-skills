# OpenClaw Skills Collection

 3 个实用的 OpenClaw Skills，提升你的 Agent 能力！

---

## Skills 列表

### 1.  Memory Extraction

**自动记忆管理** - 从对话中提取知识，构建持久化记忆

**功能**：
- 自动识别用户信息、项目、技能、偏好等实体
- 提取实体间的关系（owns, uses, prefers 等）
- 将原子化事实写入知识图谱
- 支持长期记忆管理

**适合场景**：
- 需要记住用户偏好的 Agent
- 多轮对话记忆管理
- 个性化助手

**安装**：
```bash
clawhub install memory-extraction
```
### 2. Agent Sequential Thinking
**序列思考工具** - 复杂任务分解与逐步推理

**功能**：

将复杂问题分解为可管理的步骤
支持动态调整思考步骤数
提供分支探索能力
支持假设验证和修订
**适合场景**：

复杂问题分析
多步骤任务规划
需要深度推理的场景
安装：
```bash
clawhub install agent-sequential-thinking
```
###3. Adaptive Tool Filter
**智能工具过滤** - 减少 token 消耗，提升响应速度

**功能**：

根据用户意图智能筛选工具
减少不必要的工具加载
降低 token 消耗（~70%）
提升响应速度
**效果对比**：

模式	工具数量	Token 消耗	响应时间
无过滤	50+	~5000 tokens	较慢
有过滤	10-20	~1500 tokens	更快
安装：

```bash
clawhub install adaptive-tool-filter
```

**项目特点**
特点	说明
 基于学习	参考 MCP、LightAgent 等框架设计
安全可靠	无隐私风险，本地运行
开箱即用	一键安装，自动生效
文档完善	每个 Skill 都有详细使用说明
学习资源

**本项目基于以下开源项目学习**：

MCP Memory Server - 知识图谱记忆系统
MCP Sequential Thinking - 序列思考工具
LightAgent - 自适应工具机制

贡献
欢迎提交 Issue 和 Pull Request！

License
MIT-0 - Free to use, modify, and redistribute. No attribution required.

联系
GitHub: @paibwhgs
ClawHub: @paibwhgs
⭐ 如果对你有帮助，请给个 Star！
