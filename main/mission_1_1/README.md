# 본과정 미션 1-1 AI Agent에게 일 제대로 시키는 법 배우기

과업: 채용공고 붙이면 정해진 8칸으로 정리하기 (모델은 Gemini 4 Hydrogen)

## 문서 순서
1. `docs/model-comparison.md` 모델 3개 비교하고 고른 거
2. `docs/system-design.md` 페르소나, 프롬프트 v1 v2, 예시, 검증 전략, 환각 검증 판정
3. `docs/run-log.md` 작업 기록이랑 실제 대화 전문 (본 대화 20턴, v2 대화 10턴)
4. `docs/unresolved.md` 프롬프트 고쳐도 끝내 안 된 거 2개

## 실제로 한 순서
문서는 종류별로 나눠서 순서대로 안 읽어도 됨. 시간순은 `run-log.md` 맨 위 작업 기록에 있음

| 순서 | 한 일 | 적힌 곳 |
| --- | --- | --- |
| 1 | 모델 3개 비교 | model-comparison |
| 2 | 페르소나, 프롬프트 v1 | system-design 1~5번 |
| 3 | 검증 전략, 환각 질문 5개 (대화 전) | system-design 7번 |
| 4 | 실제 대화 20턴 | run-log 본 대화 |
| 5 | Zero-shot, Few-shot 비교 | system-design 6번 |
| 6 | Pass/Fail 판정 | system-design 8번 |
| 7 | v2 작성 | system-design 9번 |
| 8 | v2로 다시 대화 | run-log 아래쪽 |
| 9 | 안 되는 거 시도 | unresolved |
