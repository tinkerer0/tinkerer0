# tinkerer0

**Research, code, and a few side quests.**  
연구와 코딩, 그리고 틈틈이 즐기는 다른 프로젝트들.

[English](README.md) · [공개 프로젝트 전체](docs/PROJECTS.md) · [게임과 실험](docs/GAMES.md)

## 대표 프로젝트

### [MemoPet](https://github.com/tinkerer0/MemoPet) · macOS

별도 메모 앱을 열지 않고 떠오른 생각이나 그림을 남기는 작은 애니메이션 노트입니다.

**살펴볼 부분:** 네이티브 창 상호작용, 글·그림을 함께 쓰는 메모, 로컬 노트 저장.  
**기술:** Swift · AppKit. **제공 형태:** 소스를 직접 빌드해 사용하며 macOS 13 이상이 필요합니다.

[빌드·사용법](https://github.com/tinkerer0/MemoPet#build-and-run) · [저장 테스트](https://github.com/tinkerer0/MemoPet/blob/main/Tests/MemoPetCoreTests/MemoNotebookStoreTests.swift)

### [DeskWidget](https://github.com/tinkerer0/DeskWidget) · Windows

로컬 이미지 폴더를 이동·크기 조절이 가능한 바탕화면 위젯으로 바꾸는 앱입니다.

**살펴볼 부분:** 이미지 입력 검사, 로컬 설정, 포함할 파일을 명시한 패키징.  
**기술:** Electron · JavaScript · C# 런처. **제공 형태:** 소스와 Windows 패키징 절차이며, 현재 서명된 실행 파일은 제공하지 않습니다.

[소스·개발 방법](https://github.com/tinkerer0/DeskWidget#개발) · [이미지 검사](https://github.com/tinkerer0/DeskWidget/blob/main/src/image-utils.js) · [배포 점검표](https://github.com/tinkerer0/DeskWidget/blob/main/docs/RELEASE_CHECKLIST.md)

### [evidence-gate](https://github.com/tinkerer0/evidence-gate) · 개발 작업 도구

작업 완료 주장과 이를 뒷받침하는 검사를 연결하기 위한 Claude Code 스킬과 감사 hook입니다.

**살펴볼 부분:** 선언한 규칙과 실제 강제하는 규칙의 구분, 오래된 근거와 위조 인용 검사.  
**기술:** Python · Claude Code hooks. **범위:** 규칙 기반 검사를 갖춘 작업 보조 도구이며 생성된 결과의 정확성을 보장하지 않습니다.

[설계](https://github.com/tinkerer0/evidence-gate/blob/main/docs/DESIGN_declare_enforce_split.md) · [감사 hook](https://github.com/tinkerer0/evidence-gate/blob/main/hooks/eg_audit.py) · [테스트](https://github.com/tinkerer0/evidence-gate/blob/main/tests/test_eg_audit.py)

### [mote](https://github.com/tinkerer0/mote_game) · 브라우저 게임

흡수·성장·정산·스킨 수집을 중심으로 한 작은 아케이드 프로토타입입니다.

**살펴볼 부분:** 단일 HTML로 이어지는 플레이 흐름, 코드로 생성하는 소리, 브라우저 로컬 저장.  
**기술:** Canvas 2D · JavaScript · Web Audio. **제공 형태:** 브라우저 프로토타입.

[플레이](https://tinkerer0.github.io/mote_game/) · [소스·조작법](https://github.com/tinkerer0/mote_game)

## 분야별 탐색

- **앱:** [MemoPet](https://github.com/tinkerer0/MemoPet), [DeskWidget](https://github.com/tinkerer0/DeskWidget), [DeskPin](https://github.com/tinkerer0/desk_pin)
- **AI를 활용한 개발:** [Orca 작업 분담 정책](https://github.com/tinkerer0/orca-autonomous-coordinator), [evidence-gate](https://github.com/tinkerer0/evidence-gate), [다른 작업 도구](docs/PROJECTS.md#개발-도구와-작업-지침)
- **게임:** [대표 게임·테마 변형·터미널 실험 목록](docs/GAMES.md)
- **시각화:** [AI Scientist Lab UI](https://github.com/tinkerer0/ai_scientist_lab_ui) — 실제 연구가 실행되지 않는 합성 화면 데모.

각 저장소에 실행 방법과 한계가 있습니다. 이 소개는 직접 살펴볼 수 있는 작업을 안내하며, 모든 프로젝트가 상용 배포되었거나 성능 평가를 마쳤다는 뜻은 아닙니다.

## 기여·피드백

제가 이런 분야를 접한 지 얼마 안 돼서 부족한 점이 많습니다. 고칠 점이나 알려주실 내용이 있다면 issue나 PR로 남겨주시면 너무 감사하겠습니다.

## 라이선스

[MIT](LICENSE)는 이 프로필의 문서에 적용합니다. 연결된 프로젝트는 각각의 라이선스를 따릅니다.
