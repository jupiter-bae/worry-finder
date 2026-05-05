# 🌿 마음 숲 (worry-finder)

지금 무엇 때문에 힘든지 모르겠을 때, 5가지 질문으로 내 마음 들여다보기.

## 사용 방법

`index.html`을 브라우저에서 열기만 하면 됩니다. 별도 빌드 과정 없음.

또는 라이브 데모: https://jupiter-bae.github.io/worry-finder/

## 특징

- **5문항 구조화 질문지** — 감정 / 떠오르는 순간 / 영역 / 두려움 / 바라는 상태
- **규칙 기반 분석** — AI/외부 API 없이 답변 조합으로 마음의 풍경, 진짜 고민, 작은 한 걸음을 펼쳐줌
- **일기 저장** — LocalStorage에 최근 기록 보관 (서버 없음, 내 기기에만)
- **숲 감성 디자인** — 초록 톤 + 따뜻한 손글씨 폰트

## 기술 스택

- HTML / CSS / JavaScript (Vanilla)
- Google Fonts: Gowun Dodum, Gowun Batang, Nanum Pen Script, Gaegu, Caveat
- 단일 파일(`index.html`) — 인라인 CSS·JS

## 로컬에서 띄우기

```bash
python3 -m http.server 8765
# 또는
npx serve -l 3000 .
```
