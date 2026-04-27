# 멋쟁이사자차럼 운영진 웹사이트 인프라 설계

## 목표

- Helm Chart를 통해 편하게 배포하는 것을 목표로 한다.
- 온프레미스 k8s 환경에서 배포하고 HPA로 자동 스케일 아웃을 구현한다.
- nginx Ingress Controller로 외부 트래픽을 라우팅 한다.

## 기술 스택

- Kubernetes : v1.29.15
- Helm
- HPA + Metrics Server

