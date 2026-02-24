# /review-evaluate — 검토 및 5기준 평가 (100점 품질 스코어)

콘텐츠를 **검토(Review)**하여 문제점을 파악하고, **평가(Evaluate)**하여 품질 점수를 부여하는 종합 시스템.

## Install

```bash
npx skills add SUNWOONGKYU/review-evaluate-core
```

## 2단계 프로세스

### 1단계: 검토 (Review)
- 문제점 및 개선사항 식별
- 구체적 수정 제안 제공
- 심각도 분류 (Critical / High / Medium / Low)

### 2단계: 평가 (Evaluate)
5가지 기준으로 품질 점수 산정 (각 20점 만점, 총 100점):

| 기준 | 설명 |
|------|------|
| 기술적 정확성 | Information correctness and currency |
| 가독성 | Ease of reading and understanding |
| 구조 및 구성 | Logical flow and systematic arrangement |
| 완성도 | Comprehensive coverage of the topic |
| 유용성 | Practical applicability and real-world value |

## 사용법

```
/review-evaluate <파일경로 또는 디렉토리>
```

## License

MIT
