# 간단 텍스트 번역기

브라우저에서 동작하는 한 페이지짜리 텍스트 번역기입니다.

바로 사용하기: https://one333-dot.github.io/261117_timer/translator/

## 기능
- 16개 언어 지원(원문 언어 자동 감지 포함)
- 원문/번역 언어 바꾸기(⇄)
- 실시간 결과 표시, 복사·중지·지우기
- Ctrl/⌘ + Enter로 번역

## 번역 엔진
- 일반 웹(GitHub Pages 등): [MyMemory 무료 번역 API](https://mymemory.translated.net/doc/spec.php)를 사용합니다. 가입이나 API 키가 필요 없으며, 익명 무료 사용량은 하루 5,000자입니다([사용 한도](https://mymemory.translated.net/doc/usagelimits.php)). 입력한 텍스트는 MyMemory 서버로 전송됩니다.
- claude.ai 아티팩트 안에서 열면: Claude가 번역하며, 문체(기본/격식체/구어체) 선택을 쓸 수 있습니다.

기계 번역이므로 중요한 문서는 사람이 한 번 더 확인하세요.
