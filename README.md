# PAPERREPO

這個 Repo 存放可公開的開發決策記憶文件，供 Claude Chat 透過 URL 讀取。

## 為什麼這個 Repo 存在

Claude Chat 無法讀取私人 Repo。
將重要的設計決策、架構演進過程記錄公開於此，
讓 Claude Chat 也能理解過去的決策背景，避免重蹈舊問題。

## 文件說明

### claude-skills/
- `PCM.md` — PCM 工作流程框架（版本總覽、模組分工）
- `PAPER.md` — PCM 3.0 設計哲學與演進過程
- `PAPER2.md` — SKILL_2.0 文件架構決策記錄

## 什麼不在這裡

以下文件屬於內部操作，不公開：
- `CLAUDE.md`（Session 指令）
- `guide.md`（開發工作流程細節）
- 所有 `.claude/skills/`（工具性 Skill，含業務邏輯）
