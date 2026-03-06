# dotfiles

개인 설정 파일 및 Claude 에이전트 구성 모음.

## 구조

```
.claude/
└── agents/
    ├── project-planner.md          # 프로젝트 기획 전문 에이전트
    └── react-vite-electron-expert.md  # React/Vite/Electron 전문 에이전트
```

## Claude 에이전트 설치

`~/.claude/agents/` 디렉토리에 복사하면 모든 Claude Code 프로젝트에서 사용 가능.

```bash
cp .claude/agents/*.md ~/.claude/agents/
```
