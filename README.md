# 나의 깊이 · My Depth

바닷속을 내려가며 유기상을 알아가는 인터랙티브 자기소개 웹과 기획 발표 자료입니다.

## 구성

- [기획 발표](presentation/index.html): 36장으로 구성된 HTML 슬라이드. 발표용 이미지를 함께 포함합니다.
- [발표 대본](presentation/speaker-notes.md): 슬라이드별 발표 대본. 발표 화면에는 대본 기능이 없습니다.
- [웹 프로토타입](prototype/index.html): 수면에서 4,000m 해저까지 탐색한 뒤 수면으로 돌아오는 Three.js 웹입니다.

## 실행

파일을 내려받아 `presentation/index.html` 또는 `prototype/index.html`을 브라우저로 열면 됩니다. 외부 글꼴과 Three.js를 CDN에서 불러오므로 인터넷 연결이 필요합니다. GitHub 파일 화면의 Raw 링크는 웹 실행 화면이 아닙니다.

로컬 서버로 열려면 저장소 폴더에서 다음 명령을 실행합니다.

```sh
python -m http.server 8000
```

발표는 `http://localhost:8000/presentation/`, 프로토타입은 `http://localhost:8000/prototype/`에서 확인합니다.

## 조작

- 발표: 좌우 방향키 또는 PageUp/PageDown, Home/End로 이동합니다. F 키 또는 전체화면 버튼으로 화면을 확대합니다.
- 프로토타입: 스크롤로 잠수하고, 마우스로 주변을 비춥니다. 주황색 물고기에 마우스를 올려 설명을 보고, 작업을 상징하는 물건과 해저의 병은 클릭합니다.

## 진행 상태

입수부터 해저, 수면 복귀까지 주요 동작이 코드에 반영돼 있습니다. 심해 감정과 편지, 취향 항목은 일부 예시이며, 모바일 조작과 기기별 성능은 추가 점검할 예정입니다.
