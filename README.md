# 이도언 게임 다운로드

**[QA 포트폴리오](https://leedoeon.vercel.app/qa/index.html)**

Unity 없이 실행하는 Windows 64비트 게임 파일입니다. 소스 저장소의 비공개 설정은 유지하며, 이 저장소에는 실행 패키지와 실행 안내만 공개합니다.

## 다운로드

| 게임 | Windows 실행 파일 |
|---|---|
| 접힌 빛 — A Fold of Light | [ZIP 다운로드](https://github.com/lde0707/portfolio-game-builds/releases/tag/afoldoflight-2026-11-14) |
| 쓰레기 집게 소년 | [ZIP 다운로드](https://github.com/lde0707/portfolio-game-builds/releases/tag/trashboy-2026-11-14-r2) |
| FlyEditor | [ZIP 다운로드](https://github.com/lde0707/portfolio-game-builds/releases/tag/flyeditor-2026-11-14) |
| 데굴데굴 퍼즐 | [ZIP 다운로드](https://github.com/lde0707/portfolio-game-builds/releases/tag/deguldegul-2026-11-14) |
| Rushitadel | [ZIP 다운로드](https://github.com/lde0707/portfolio-game-builds/releases/tag/rushitadel-2026-11-14-r2) |
| StillDrawn | [ZIP 다운로드](https://github.com/lde0707/portfolio-game-builds/releases/tag/stilldrawn-2026-11-14) |
| 진주도둑들 | [STOVE 공식 출시 페이지](https://store.onstove.com/games/104688) |

## 실행 방법

1. 게임별 다운로드 페이지의 **게임이름-Windows-x64.zip**을 받습니다. `Source code`는 게임 파일이 아닙니다.
2. ZIP **전체**를 압축 해제합니다.
3. 폴더 안의 **EXE**를 실행합니다. Unity 설치는 필요 없습니다.

`Data` 폴더, `UnityPlayer.dll`과 나머지 동봉 파일을 함께 유지하세요. 모바일·macOS에서는 이 파일을 실행할 수 없습니다.
데굴데굴 퍼즐은 [itch.io 웹 플레이](https://lde0707.itch.io/degul-degul)도 제공합니다.

## 확인 범위

2026-11-14에 일곱 게임의 시작부터 주요 기능까지 실제 키보드·마우스 입력으로 플레이했습니다. 이동·퍼즐·전투·수집·보상·재실행 중 각 게임에서 확인한 경로를 기록했습니다.

- 쓰레기 집게 소년: Windows 그래픽 충돌 수정 후 채굴·수집·분리수거 보상 재검증
- Rushitadel: 화면 상단 이탈 수정 후 이동·반동 경계 재검증
- 진주도둑들: 메뉴 겹침·상점 잘림·전투 배경 배율 수정. 수정 실행 파일은 팀 비공개 저장소에 있으며 STOVE 판매 빌드는 별도입니다.

[게임별 실제 화면·확인 범위·수정 전후 기록](https://leedoeon.vercel.app/qa/reports/windows-playtest-2026-11-14.html)

전체 완주·모든 PC 환경·기존 저장 파일의 모든 호환성을 검증한 결과는 아닙니다. 각 릴리스의 `SHA256SUMS.txt`로 ZIP 무결성을 확인할 수 있습니다.
