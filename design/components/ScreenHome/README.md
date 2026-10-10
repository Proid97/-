# ScreenHome

iPhone 홈 화면의 구성 예시로, 날짜와 인사말, 오늘의 목표, 과목 카드 세 장, 하단 탭 바를 한 열에 쌓습니다.

## 구성
- 상단: 날짜(`callout`, `ink-secondary`)와 인사말(`display`).
- 오늘의 목표 카드: `surface-card` + `border-subtle`, 진도 막대는 `accent`(과목에 속하지 않는 목표이므로).
- “과목” 섹션 제목(`heading`)과 SubjectCard 세 장. 메타 줄에 이어서 볼 챕터를 씁니다.
- 하단 TabBar(홈 활성).

## 규칙
- 좌우 여백 `space-4`, 섹션 사이 `space-6`.
- 인사말은 짧은 한 줄로 씁니다. 이름이 없으면 날짜만 둡니다.
- 하지 말 것: 홈에 광고성 배너, 통계 카드 여러 장 나열, 과목 카드 가로 스크롤.
