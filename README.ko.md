# XIYO

[English](README.md)

AI와 함께하는 작업을 반복 가능하고, 검토 가능하며, 신뢰하기 쉽게 만드는 로컬 우선 도구를 개발합니다.

현재는 macOS용 에이전트 연동 도구와 SvelteKit 아키텍처 도구에 집중합니다. 처음 발견한 사람이 설치부터 정상 동작 확인까지 짧은 경로로 도달하는 것을 중요하게 생각합니다.

## 먼저 볼 프로젝트

| 프로젝트 | 해결하는 일 | 플랫폼 | 단계 |
| --- | --- | --- | --- |
| [XIYO Plugins](https://github.com/XIYO/plugins) | Codex·Claude Code에 Apple Calendar와 메시지 분석 도구 설치 | macOS | Preview |
| [svelte-arch](https://github.com/XIYO/svelte-arch) | 사람과 AI 에이전트가 같은 SvelteKit 구조를 따르도록 주입형 킷과 자동 감사 제공 | SvelteKit | Preview |

### XIYO Plugins

GitHub에서 공개 마켓플레이스를 바로 추가할 수 있습니다.

```bash
codex plugin marketplace add XIYO/plugins
codex plugin add apple-calendar@xiyo
codex plugin add message-pipeline@xiyo
```

설치한 스킬을 불러오려면 새 Codex 작업을 시작합니다. Claude Code 설치법과 플랫폼 선행 조건은 [플러그인 마켓플레이스](https://github.com/XIYO/plugins)에 정리합니다.

### svelte-arch

SvelteKit용 아키텍처 표준이자 프로젝트 주입 킷입니다. 기억에 의존하는 대신 사람과 코딩 에이전트가 같은 배치 규칙, 프로젝트 매니페스트, 실행 가능한 감사를 사용하게 합니다.

[아키텍처와 설치 안내 보기](https://github.com/XIYO/svelte-arch)

## 만드는 기준

- **로컬 우선 경계** — 문서화된 동작으로 선택한 내용을 보내는 경우가 아니면 개인 원본 데이터는 사용자 기기에 둡니다.
- **검토 가능한 동작** — CLI, 스키마, 계약을 통해 채팅 화면 밖에서도 에이전트 동작을 확인할 수 있게 합니다.
- **복구 가능한 흐름** — 멱등 작업, 명시적 상태, 진단 명령으로 중단된 작업을 안전하게 재개합니다.
- **에이전트 친화 저장소** — 설치, 첫 사용, 검증, 보안 경계, 기여 경로를 제품 기능처럼 관리합니다.

## 프로젝트 단계

- **Preview** — 지금 사용할 수 있지만 안정 버전 전까지 인터페이스나 설치 경로가 달라질 수 있습니다.
- **Experimental** — 평가 목적으로 공개하며 일부 연동이나 수동 설정이 빠져 있을 수 있습니다.
- **Archived** — 참고를 위해 보존하지만 더 이상 적극적으로 지원하지 않습니다.

## 연락처

- 웹사이트: [xiyo.dev](https://xiyo.dev)
- 이메일: [bunny@xiyo.dev](mailto:bunny@xiyo.dev)
- 보안 제보: 문제가 있는 저장소의 `SECURITY.md` 정책을 따릅니다.
