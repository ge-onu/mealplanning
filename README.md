# MealPlanning (fork)

더존비즈온 Cloud DX Academy 6기 최종 팀 프로젝트입니다.
식비 예산과 사용자 행동 데이터를 바탕으로 레시피·상품 추천과 AI 기능을 연결했습니다.
5인 팀으로 2026.06.29부터 2026.08.26까지 진행했고, 더존비즈온 최우수상을 받았습니다.

- 원본 저장소: [happyInit/food-budget-app](https://github.com/happyInit/food-budget-app)
- 라이브 데모: [app.mealbong.cloud](https://app.mealbong.cloud)
- 프로젝트 정리: [geonu.site/projects/mealplanning](https://geonu.site/projects/mealplanning/)

## 이 fork에서 내 역할

AI/ML을 맡았습니다.

- LLM 15종 비교 평가 기록을 정리했습니다.
- Guardrail 오탐 원인을 찾고 근거 범위 수정을 결정해, 동일 275건 기준 통과 건수를 166건에서 247건으로 늘렸습니다.
- 추천 이벤트의 session_id 전달 누락을 확인했습니다.

## 팀 범위

인프라(Docker → kubeadm 5노드 → AWS EKS → Lightsail, ArgoCD, Prometheus/Grafana)는 팀원이 구축했습니다.
이 README에서는 해당 범위를 제 기여로 적지 않았습니다.

## 참고

이 저장소는 원본 저장소의 개인 fork입니다.
원본보다 최신 상태가 아닐 수 있으니, 최신 코드는 원본 저장소를 확인해 주세요.
