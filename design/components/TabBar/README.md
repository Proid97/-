# TabBar

iPhone 화면 하단의 고정 탭 바로, 홈 · 학습 · 모의고사 · 내 기록 네 곳으로 이동합니다.

## 사용하는 쪽이 정하는 것
- 현재 탭(`aria-current`). 탭 구성과 순서는 고정입니다.
- 선택 사항: 내 기록 탭의 새 항목 표시.

## 상태
- 활성: 아이콘과 라벨 `accent-ink`, 라벨 600.
- 비활성: `ink-secondary`.

## 규칙
- 높이 `tabbar-height`(49pt) + 홈 인디케이터 안전 영역(34pt). 바탕 `surface-elevated`, 위쪽 `border-subtle` 선.
- 아이콘은 SF Symbols `house`, `book`, `doc.text`, `chart.bar`, 26pt, 선 1.5px. 라벨은 늘 함께 보여 줍니다.
- 모의고사 진행 중에는 탭 바를 숨겨 실수로 시험을 벗어나지 않게 합니다.
- iPad 가로 화면에서는 탭 바 대신 과목 사이드바를 씁니다.
- 하지 말 것: 탭 다섯 개 이상, 라벨 없는 아이콘, 과목색으로 활성 표시.
