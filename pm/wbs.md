# WBS

프로젝트: Kyrgyz ICT Education Center Design & Author Supervision
기준 문서:
- `pm/project-execution-plan.md`
- `analysis/scope-deliverables-summary.md`
- `analysis/qualification-compliance-summary.md`

## WBS 운영 메모
- 본 WBS는 수주 직후 v0.1 기준 초안이다.
- 실제 계약 확정본, 착수회의 결과, 발주처 승인체계에 따라 세부 일정과 owner는 조정될 수 있다.
- 특히 현지 적격 파트너 구조와 bilingual deliverable 요구 수준은 세부 work package에 큰 영향을 줄 수 있다.

| WBS ID | Work Package | Owner | Start | End | Dependency | Status | Notes |
|--------|--------------|-------|-------|-----|------------|--------|-------|
| 1.0 | Project initiation & alignment | PM | T0 | T0+2w | - | pending | 착수 정렬 단계 |
| 1.1 | Contract / RFP / proposal alignment review | PM | T0 | T0+3d | - | pending | 계약범위, 제안서, RFP 정합성 확인 |
| 1.2 | Execution plan v0.1 finalize | PM | T0 | T0+1w | 1.1 | pending | 수행계획서 확정 |
| 1.3 | Partner role / license structure alignment | PM / Partner Lead | T0 | T0+1w | 1.1 | pending | local design license 및 역할 경계 확인 |
| 1.4 | Kickoff meeting preparation & execution | PM | T0+1w | T0+2w | 1.2, 1.3 | pending | 착수회의 자료/회의록 |
| 1.5 | Reporting / communication setup | PM | T0+1w | T0+2w | 1.2 | pending | 회의체, 보고주기, 기록체계 설정 |
| 2.0 | Design planning & survey preparation | Technical Lead / PM | T0+2w | T0+6w | 1.4 | pending | 설계 준비 단계 |
| 2.1 | Site investigation / survey planning | Technical Lead | T0+2w | T0+4w | 1.4 | pending | 현장조사/기초자료 계획 |
| 2.2 | Base data collection / constraints review | Technical Lead / Local Partner | T0+2w | T0+4w | 1.4 | pending | 부지/법규/행정 조건 정리 |
| 2.3 | Design Implementation Plan submission | PM / Technical Lead | T0+3w | T0+6w | 1.2, 2.1, 2.2 | pending | 계약상 초기 핵심 산출물 |
| 3.0 | Preliminary / schematic design | Technical Lead | T0+1m | T0+3m | 2.3 | pending | 초기 설계 단계 |
| 3.1 | Concept / layout option development | Technical Lead | T0+1m | T0+2m | 2.3 | pending | layout/masterplan 옵션 |
| 3.2 | Preliminary design package | Technical Lead | T0+2m | T0+3m | 3.1 | pending | 초기 설계 패키지 |
| 3.3 | KOICA/client review response (preliminary) | PM / Technical Lead | T0+3m | T0+3m+2w | 3.2 | pending | 리뷰 의견 반영 |
| 4.0 | Design development (SD/DD/CD) | Technical Lead | T0+3m | T0+9m | 3.3 | pending | 본 설계 단계 |
| 4.1 | Schematic Design (SD) | Technical Lead | T0+3m | T0+5m | 3.3 | pending | SD 산출물 |
| 4.2 | Design Development (DD) | Technical Lead | T0+5m | T0+7m | 4.1 | pending | DD 산출물 |
| 4.3 | Construction Documents (CD) | Technical Lead | T0+7m | T0+9m | 4.2 | pending | CD 산출물 |
| 4.4 | Drawings / specs / BoQ / calculations package | Technical Lead / QA | T0+6m | T0+9m | 4.2 | pending | 발주용 설계문서 패키지 |
| 4.5 | Bilingual review (EN/RU) | QA / Translation support | T0+7m | T0+9m | 4.3, 4.4 | pending | 영어/러시아어 제출 대응 |
| 4.6 | KOICA/client review response (design phase) | PM / Technical Lead | T0+8m | T0+9m | 4.3, 4.4 | pending | 승인 대응 |
| 5.0 | Tender support / contractor selection support | PM / Technical Lead | T0+9m | T0+12m | 4.6 | pending | 입찰지원 단계 |
| 5.1 | Tender document finalization | Technical Lead / QA | T0+9m | T0+10m | 4.6 | pending | 최종 발주 문서 |
| 5.2 | Addenda / bidder query response support | PM / Technical Lead | T0+10m | T0+11m | 5.1 | pending | 질의응답/정정 대응 |
| 5.3 | Bidder document / unit price review support | Technical Lead | T0+10m | T0+11m | 5.1 | pending | 평가 지원 성격 |
| 5.4 | Contractor selection support closure | PM | T0+11m | T0+12m | 5.2, 5.3 | pending | contractor 선정 지원 마무리 |
| 6.0 | Author’s supervision | Technical Lead / PM | T0+12m | T0+27m | 5.4 | pending | 시공단계 기술행정 지원 |
| 6.1 | Supervision plan setup | PM / Technical Lead | T0+12m | T0+13m | 5.4 | pending | 시공지원 운영 기준 |
| 6.2 | Weekly inspection / issue tracking | Technical Lead | T0+13m | T0+27m | 6.1 | pending | 주간 현장/이슈 대응 |
| 6.3 | Monthly progress reporting | PM | T0+13m | T0+27m | 6.1 | pending | 월간 보고 |
| 6.4 | Design clarification / change review | Technical Lead | T0+13m | T0+27m | 6.1 | pending | 설계변경/질의 대응 |
| 7.0 | Project management & governance | PM | T0 | T0+27m | - | in progress | 전 기간 공통 |
| 7.1 | Schedule control | PM | T0 | T0+27m | 1.2 | in progress | 마일스톤/지연 관리 |
| 7.2 | Risk / issue management | PM | T0 | T0+27m | 1.2 | in progress | risk-issue-log 연계 |
| 7.3 | Decision logging | PM | T0 | T0+27m | 1.2 | in progress | decision-log 연계 |
| 7.4 | Communication management | PM | T0 | T0+27m | 1.5 | in progress | communication-log 연계 |
| 7.5 | Quality gate management | PM / QA | T0 | T0+27m | 1.2 | in progress | 제출 전 품질 게이트 |
| 8.0 | Close-out & final reporting | PM / Technical Lead | T0+27m | T0+28m | 6.4 | pending | 종료 단계 |
| 8.1 | Final completion report | PM / Technical Lead | T0+27m | T0+28m | 6.4 | pending | 최종보고 |
| 8.2 | Deliverable archive & handoff | PM / Document Lead | T0+27m | T0+28m | 8.1 | pending | 산출물 정리/인계 |
| 8.3 | Lessons learned / closure note | PM | T0+28m | T0+28m | 8.2 | pending | 종료 회고 |

## Immediate next slicing
수주 직후 실제로는 아래 work package를 먼저 상세화해야 한다.
- 1.1 Contract / RFP / proposal alignment review
- 1.2 Execution plan v0.1 finalize
- 1.3 Partner role / license structure alignment
- 1.5 Reporting / communication setup
- 2.3 Design Implementation Plan submission
