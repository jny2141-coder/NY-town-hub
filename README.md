# NY Town

아이소메트릭 3D 마을 대시보드. 건물마다 생활 영역이 연결돼 있음.

| 건물 | 역할 |
|---|---|
| Home | 오늘의 브리핑 |
| KH Univ (평화의 전당) | 수업·학점·강의 자료·학교 메일·학교 행사 |
| Library | CPA 수험 기지 |
| Workplace | 쏭스터디랩 업무 |
| Archive (오디움 스타일) | 관심 분야 탐구 · 구마 겐고의 오디움처럼 알루미늄 파이프 외관 |
| Boutique / Pub / Bank / Broadcast / Gallery | 쇼핑·영어회화·주식·블로그·취미·관심분야 |
| Bistro / Izakaya / Hansik / Café | 레시피 키친 |

- `index.html` — 원본 Claude 아티팩트 페이지 (https://claude.ai/artifact/NNrys1ob83a1r4vusxtg3g)
- `artifact.json` — 아티팩트 런타임 capability 선언 (db, Gmail/Calendar/Drive/Notion 연동 등)

> Calendar·Gmail·DB 같은 기능은 `window.claude` 런타임에서만 동작해서, 그냥 브라우저로 열면 3D 마을만 보이고 연동 기능은 안 돼.
