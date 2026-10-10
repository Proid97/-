# ScreenIPad

iPad 가로 분할 화면의 구성 예시로, 왼쪽 과목 사이드바와 오른쪽 학습자료 목록으로 이루어집니다.

## 구성
- 사이드바(`sidebar-width` 320pt, `surface-sidebar`): 앱 이름, 과목 세 개(과목색 점 + 이름 + 진도), “나” 그룹(내 기록, 오답 노트).
- 선택된 과목 행: `accent-soft` 바탕, 진도 숫자 `accent-ink`.
- 콘텐츠: 과목 제목(`title`), 과목색 진도 막대와 요약, SegmentedControl, LessonRow 목록.

## 규칙
- 콘텐츠 좌우 여백 `space-6`, 위 `space-8`. 본문을 열면 `content-max` 안에 둡니다.
- 사이드바 행은 44pt 이상. 과목색은 점에만 씁니다.
- 세로 방향에서는 사이드바를 오버레이로 바꿉니다.
- 하지 말 것: 사이드바와 탭 바를 동시에 표시, 세 열 이상 분할.
