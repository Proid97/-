# SubjectCard

과목 하나를 대표하는 카드로, 상단 과목색 띠와 진도를 보여 주고 누르면 과목 화면으로 이동합니다.

## 사용하는 쪽이 정하는 것
- 과목(`anatomy` · `development` · `disorders`): 띠, 배지, 진도 색이 이에 따라 정해집니다.
- 과목 이름, 챕터 수 배지, 메타 한 줄(문항 수 또는 “다음: 3장 후두의 구조 · 10분”), 진도 퍼센트.

## 상태
- 기본, 눌림(배경 `surface-sidebar`, 150ms), 포커스(`focus-ring`, `radius-lg`를 따름).
- 시작 전(0%): 진도 막대 대신 “아직 시작 전이에요” 문구.

## 규칙
- 카드 바탕 `surface-card`, `radius-lg`, `shadow-card`. 상단 6px 띠는 `subject-*`.
- 배지는 `subject-*-soft` 바탕에 `subject-*-ink` 글자, 퍼센트는 `subject-*-ink` mono.
- 과목 이름과 본문은 `ink-primary`입니다. 과목색 글자는 배지와 퍼센트에만 씁니다.
- iPhone은 세로로 쌓고, iPad는 세 장을 한 줄에 놓습니다.
- 하지 말 것: 왼쪽 색 테두리, 카드 전체를 과목색으로 채우기, 이모지 아이콘.
