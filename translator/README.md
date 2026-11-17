# 간단 텍스트 번역기

브라우저에서 동작하는 한 페이지짜리 텍스트 번역기입니다.

## 기능
- 16개 언어 지원(원문 언어 자동 감지 포함)
- 원문/번역 언어 바꾸기(⇄)
- 문체 선택: 기본 / 격식체 / 구어체
- 실시간 결과 표시, 복사·중지·지우기
- Ctrl/⌘ + Enter로 번역

## 주의
번역은 claude.ai 아티팩트 런타임의 `sample` 기능(`claude.use("sample")`)으로 Claude를 호출합니다.
따라서 `index.html`을 GitHub Pages 등 claude.ai 밖에서 열면 화면은 보이지만 번역은 동작하지 않습니다.
외부에서 쓰려면 번역 API(예: Claude API, Papago, DeepL 등) 호출 코드로 바꿔야 합니다.
