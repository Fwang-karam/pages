# CLAUDE.md

## 프로젝트 개요
GitHub Pages로 공개하는 정적 HTML 페이지 모음. 빌드 도구·패키지 없음 — 각 페이지는 HTML/CSS/JS가 한 파일에 들어 있는 단일 파일이다.

- `index.html` — 아기 코끼리 덤보 달리기 (러너 게임, Space/↑/터치로 점프)
- `carrot-game.html` — 고양이 당근 피하기 (←/→/터치로 이동)
- `dbinc_report.html` — DB Inc 실적 보고서 (Chart.js 4.4.1, cdnjs). 수치는 **예시 데이터**이며, 하단 `<script>`의 `revenue`/`op`/`net` 배열 등을 바꾸면 차트와 표가 함께 갱신된다.

## 저장소
- origin: https://github.com/Fwang-karam/pages (공개)
- 배포 주소: https://fwang-karam.github.io/pages/ (main 브랜치 루트에서 GitHub Pages)

## 작업 규칙
- 사용자와는 한국어로 소통한다.
- 새 페이지는 같은 방식의 단일 HTML 파일로 루트에 추가하고, README.md의 바로 가기 표에 링크를 추가한다.
- 모바일(터치)에서도 동작하도록 만든다.
- 외부 스크립트는 cdnjs 등에서 버전을 고정해 불러온다.
- 확인은 브라우저에서 파일을 직접 열어서 한다.
