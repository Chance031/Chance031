<div align="center">
  <img src="./terminal.svg" alt="terminal" width="100%"/>
</div>

<br/>

---

## What I Learned

> AI를 활용하되, 코드를 이해하고 판단하는 능력을 함께 키우는 방식으로 공부하고 있습니다.

### C++

- 클래스 설계 시 책임 분리 — Tetromino / Board / Game이 각자의 역할만 담당하도록 구조화
- `constexpr`, `static_cast`, `std::array`, `std::chrono` 등 현대 C++ 관용구 실전 적용
- Anonymous namespace로 내부 헬퍼 함수 격리, `m_` prefix 멤버 변수 명명 규칙 유지
- `uint8_t` vs `int` 타입 선택 기준 — 저장 범위와 메모리 효율을 고려한 판단
- `std::mt19937` + `std::shuffle`로 시드 기반 균등 랜덤 구현 (7-bag 시스템)

### 게임 로직

- SRS(Super Rotation System) Wall Kick — I피스와 일반 피스의 킥 테이블 분리 구현
- Lock Delay + MaxLockReset 설계 — 타이머와 카운터를 조합한 상태 관리
- T-Spin 감지 (3-corner rule) — 회전 직후 코너 점유 여부로 판별
- Ghost Piece — 현재 블록을 복사해 충돌 직전 위치까지 이동시키는 방식
- 게임 루프 설계 — 입력 / 업데이트 / 렌더링을 명확하게 분리하고 프레임 딜레이 제어

### 협업 / 개발 도구

- Conventional Commits 형식으로 커밋 메시지 작성 (`feat`, `fix`, `docs`, `chore`)
- GitHub Actions를 통한 README 자동화 경험
- draw.io로 게임 FSM, 플레이 루프, UML 설계 문서 작성
- AI(Claude, ChatGPT)를 코드 리뷰 도구로 활용 — 생성된 코드를 직접 검토하고 수정하는 방식

---

## Tech Stack

**Core**

[![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
[![Unreal_Engine](https://img.shields.io/badge/Unreal_Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white)](https://img.shields.io/badge/Unreal_Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white)

**Tools**

[![Visual_Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)](https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)
[![Rider](https://img.shields.io/badge/Rider-000000?style=flat-square&logo=rider&logoColor=white)](https://img.shields.io/badge/Rider-000000?style=flat-square&logo=rider&logoColor=white)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
[![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
[![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

**Experienced**

[![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## Projects

> 기본기를 다지며 직접 만들어가는 프로젝트들입니다.

| 프로젝트 | 설명 | 기술 | 상태 |
|---|---|---|---|
| Console Tetris | C++로 구현하는 콘솔 테트리스 | C++ | 진행중 |
| SFML Tetris | 콘솔 테트리스를 SFML로 리메이크 | C++, SFML | 예정 |

---

## GitHub Stats

## Contact

// still leveling up, one commit at a time
