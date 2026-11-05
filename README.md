# MealPlanning (fork)

더존비즈온 Cloud DX Academy 6기 최종 팀 프로젝트입니다.
식비 예산과 사용자 행동 데이터를 바탕으로 레시피·상품 추천과 AI 기능을 연결했습니다.
5인 팀으로 2026.06.29부터 2026.08.26까지 진행했고, 더존비즈온 최우수상을 받았습니다.

- 원본 저장소: [happyInit/food-budget-app](https://github.com/happyInit/food-budget-app)
- 라이브 데모: [app.mealbong.cloud](https://app.mealbong.cloud)
- 프로젝트 정리: [geonu.site/projects/mealplanning](https://geonu.site/projects/mealplanning/)

## 이 fork에서 내 역할

AI/ML을 맡아 핵심 AI 기능의 PoC·구현·트러블슈팅을 대부분 맡았습니다.

- 응답 검증 오탐 원인을 찾아 근거 범위 수정을 이끌었고, 같은 275건에서 통과가 166건에서 247건으로 늘었습니다.
- LLM 후보 15종을 누적 1,750건 평가 기록으로 비교했습니다.
- AI 기능 12종의 서버리스 전환을 판정하고, Lambda·SQS·SNS·S3·EventBridge Scheduler를 Terraform으로 작성했습니다.
- 추천 이벤트의 session_id 누락을 Frontend → API → Event Storage → Training Dataset 순서로 추적해 전달 경로를 고쳤습니다.

## 팀 범위

인프라(Docker → kubeadm 5노드 → AWS EKS → Lightsail, Argo CD, Prometheus/Grafana)는 도구 선택을 팀 회의에서 함께 정했고, 설치·운영은 인프라 담당 팀원이 맡았습니다.
이 README에서는 해당 범위를 제 기여로 적지 않았습니다.

## 참고

이 저장소는 원본 저장소의 개인 fork입니다.
원본보다 최신 상태가 아닐 수 있으니, 최신 코드는 원본 저장소를 확인해 주세요.
