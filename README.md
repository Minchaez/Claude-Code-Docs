# claude-code-docs

Claude Code 공식 문서를 전부 통과해 내 것으로 만드는 학습 공간.

**왜 이렇게 하는가:** 래퍼 도구나 써드파티 추상화를 좇기 전에, 네이티브로 뭘 할 수 있는지 먼저 아는 사람이 되기 위해. 문서 전 페이지를 한 번씩 통과하는 것이 이 레포의 일이다.

> **다음에 뭘 읽을지 모르겠다면:** "다음 배울 내용 알려줘" 또는 `/next`

---

## 진도 현황

**[→ COVERAGE.md](COVERAGE.md)** — 전 페이지 진도표. 상태를 여기서 확인하고 갱신한다.

### 상태 정의

| 기호 | 의미 |
|-----|-----|
| ⬜ | 미착수 |
| 📖 | 읽음 |
| 🔧 | 확인함 — 실제로 실행해서 검증했다 |
| 🧠 | 소화함 — 경계를 설명할 수 있고 남에게 말할 수 있다 |
| ⛔ | 보류 — 이유를 한 줄 적는다 |

---

## 디렉토리 역할

| 디렉토리 | 역할 |
|---------|-----|
| `COVERAGE.md` | 전 페이지 진도표. 이 레포의 중심 |
| `notes/` | 페이지 단위 노트. 예상과 실제의 차이, 기능 간 경계, 남은 질문만 적는다 |
| `index/by-need.md` | 노트에서 파생된 역색인. 요구사항 → 기능 매핑 |
| `index/glossary.md` | 공식 용어를 내 언어로 다시 쓴 것 |
| `labs/` | 손으로 확인하는 미니 프로젝트. 버려도 되는 것 |
| `configs/` | 학습 중 만든 재사용 가능한 설정 자산 |
| `log/` | 월별 학습 로그. 주 1회 whats-new 확인 후 3줄 |

---

## 문서를 읽는 순서 (4개 레이어)

레이어를 건너뛰지 않는다. 이전 레이어에 📖 이상이 되지 않은 페이지가 있으면 그것부터.

### Layer 0 — 세계관
`how-claude-code-works` · `features-overview` · `glossary`

### Layer 1 — 기반
`claude-directory` · `memory` · `context-window` · `permission-modes` · `sessions` · `best-practices` · `debug-your-config`

### Layer 2 — 확장 지점
`skills` · `hooks-guide` · `sub-agents` · `mcp` · `plugins`

### Layer 3 — 자동화·병렬
`headless` · `worktrees` · `agent-view` · `workflows` · `agent-teams` · `scheduled-tasks` · `cross-session-messaging`

> **Reference 그룹**은 통독하지 않는다. 필요할 때 검색해서 찾는다.
