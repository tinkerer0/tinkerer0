# tinkerer0

**Research, code, and a few side quests.**  
연구와 코딩, 그리고 틈틈이 즐기는 다른 프로젝트들.

[English](README.md) · [공개 프로젝트 전체](docs/PROJECTS.md) · [게임과 실험](docs/GAMES.md)

## 대표 프로젝트

### [MemoPet](https://github.com/tinkerer0/MemoPet) · macOS

글과 그림으로 메모하고 로컬에 저장하는 macOS 앱입니다.

Swift · AppKit. macOS 13 이상에서 소스를 빌드해 사용합니다.

[빌드·사용법](https://github.com/tinkerer0/MemoPet#build-and-run) · [저장 테스트](https://github.com/tinkerer0/MemoPet/blob/main/Tests/MemoPetCoreTests/MemoNotebookStoreTests.swift)

### [DeskWidget](https://github.com/tinkerer0/DeskWidget) · Windows

로컬 이미지를 이동·크기 조절이 가능한 Windows 바탕화면 위젯으로 표시합니다.

Electron · JavaScript · C# 런처. 소스와 패키징 방법을 제공하며, 서명된 실행 파일은 제공하지 않습니다.

[소스·개발 방법](https://github.com/tinkerer0/DeskWidget#개발) · [이미지 검사](https://github.com/tinkerer0/DeskWidget/blob/main/src/image-utils.js) · [배포 점검표](https://github.com/tinkerer0/DeskWidget/blob/main/docs/RELEASE_CHECKLIST.md)

### [evidence-gate](https://github.com/tinkerer0/evidence-gate) · 개발 작업 도구

작업 완료 보고에 확인 근거를 남기는 Claude Code 스킬입니다.

직접 호출해 사용합니다. Python 감사 hook 실험과 결과도 보관하며, 해당 hook은 채택하지 않았습니다.

[설계](https://github.com/tinkerer0/evidence-gate/blob/main/docs/DESIGN_declare_enforce_split.md) · [실험과 부정 결과](https://github.com/tinkerer0/evidence-gate/commit/80ebaa8) · [테스트](https://github.com/tinkerer0/evidence-gate/blob/main/tests/test_eg_audit.py)

### [mote](https://github.com/tinkerer0/mote_game) · 브라우저 게임

흡수·성장·정산·스킨 수집이 있는 브라우저 아케이드 프로토타입입니다.

JavaScript · Canvas 2D · Web Audio. 진행 상황은 브라우저에 저장합니다.

[플레이](https://tinkerer0.github.io/mote_game/) · [소스·조작법](https://github.com/tinkerer0/mote_game)

## 분야별 프로젝트

- **앱:** [MemoPet](https://github.com/tinkerer0/MemoPet), [DeskWidget](https://github.com/tinkerer0/DeskWidget), [DeskPin](https://github.com/tinkerer0/desk_pin)
- **AI를 활용한 개발:** [Orca 작업 분담 정책](https://github.com/tinkerer0/orca-autonomous-coordinator), [evidence-gate](https://github.com/tinkerer0/evidence-gate), [다른 작업 도구](docs/PROJECTS.md#개발-도구와-작업-지침)
- **게임:** [대표 게임·테마 변형·터미널 실험 목록](docs/GAMES.md)
- **시각화:** [AI Scientist Lab UI](https://github.com/tinkerer0/ai_scientist_lab_ui), 합성 결과를 보여주는 화면 데모입니다. 실제 연구는 실행하지 않습니다.

실행 방법과 진행 상태는 각 저장소에 정리했습니다.

## 기여·피드백

수정 제안은 issue나 PR로 남겨주세요.

## 라이선스

[MIT](LICENSE)는 이 프로필의 문서에 적용합니다. 연결된 프로젝트는 각각의 라이선스를 따릅니다.
