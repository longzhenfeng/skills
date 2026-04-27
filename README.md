# 面向真实工程师的 Agent Skills

这是我日常用于真实工程工作的 agent skills，不是只追求“氛围编程”的那一套。

如果你想持续关注这些 skills 的更新，以及我后续新增的 skills，可以订阅我的 newsletter：

[订阅 Newsletter](https://www.aihero.dev/s/skills-newsletter)

## 规划与设计

这些 skills 适合在动手写代码之前，先把问题想清楚。

- **to-prd** — 把当前对话上下文整理成一份 PRD，并提交为 GitHub issue。不需要额外访谈，直接基于你们已经讨论过的内容进行归纳。

  ```
  npx skills@latest add longzhenfeng/skills/to-prd
  ```

- **to-issues** — 把任意计划、规格说明或 PRD 拆成可以被独立领取和推进的 GitHub issues，按垂直切片组织。

  ```
  npx skills@latest add longzhenfeng/skills/to-issues
  ```

- **grill-me** — 围绕一个计划或设计进行持续追问，直到决策树的每个分支都被澄清。

  ```
  npx skills@latest add longzhenfeng/skills/grill-me
  ```

- **design-an-interface** — 针对某个模块并行生成多套差异明显的接口设计方案。

  ```
  npx skills@latest add longzhenfeng/skills/design-an-interface
  ```

- **request-refactor-plan** — 通过与用户访谈，产出一个包含细粒度提交步骤的详细重构计划，并将其整理为 GitHub issue。

  ```
  npx skills@latest add longzhenfeng/skills/request-refactor-plan
  ```

## 开发

这些 skills 用来帮助你编写、重构和修复代码。

- **tdd** — 使用 red-green-refactor 循环进行测试驱动开发。无论是新功能还是 bug 修复，都按一个个垂直切片推进。

  ```
  npx skills@latest add longzhenfeng/skills/tdd
  ```

- **triage-issue** — 通过探索代码库调查 bug，找出根因，并整理出一份基于 TDD 的修复计划 GitHub issue。

  ```
  npx skills@latest add longzhenfeng/skills/triage-issue
  ```

- **improve-codebase-architecture** — 结合 `CONTEXT.md` 中的领域语言和 `docs/adr/` 中的设计决策，发现代码库里值得进一步深化和演进的架构机会。

  ```
  npx skills@latest add longzhenfeng/skills/improve-codebase-architecture
  ```

- **migrate-to-shoehorn** — 把测试文件中的 `as` 类型断言迁移到 `@total-typescript/shoehorn`。

  ```
  npx skills@latest add longzhenfeng/skills/migrate-to-shoehorn
  ```

- **scaffold-exercises** — 创建练习目录结构，包括章节、题目、解答和讲解内容。

  ```
  npx skills@latest add longzhenfeng/skills/scaffold-exercises
  ```

## 工具与环境配置

- **setup-pre-commit** — 配置 Husky pre-commit hooks，集成 lint-staged、Prettier、类型检查和测试。

  ```
  npx skills@latest add longzhenfeng/skills/setup-pre-commit
  ```

- **git-guardrails-claude-code** — 为 Claude Code 配置 hooks，在执行危险的 git 命令（如 `push`、`reset --hard`、`clean` 等）前进行拦截。

  ```
  npx skills@latest add longzhenfeng/skills/git-guardrails-claude-code
  ```

## 写作与知识管理

- **write-a-skill** — 按规范结构、渐进式信息展开和配套资源，创建新的 skill。

  ```
  npx skills@latest add longzhenfeng/skills/write-a-skill
  ```

- **edit-article** — 通过重构段落、提升表达清晰度和收紧措辞来润色文章。

  ```
  npx skills@latest add longzhenfeng/skills/edit-article
  ```

- **ubiquitous-language** — 从当前对话中提取一份 DDD 风格的通用语言术语表。

  ```
  npx skills@latest add longzhenfeng/skills/ubiquitous-language
  ```

- **obsidian-vault** — 在 Obsidian vault 中搜索、创建和管理笔记，支持 wikilinks 和索引笔记。

  ```
  npx skills@latest add longzhenfeng/skills/obsidian-vault
  ```
