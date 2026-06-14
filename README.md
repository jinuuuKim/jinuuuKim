<h1 align="center">안녕하세요, 클라우드 인프라 엔지니어 김진우입니다 👋</h1>

<p align="center">
  <em>"코드로 인프라를 정의하고, 장애를 설계 단계에서 막습니다."</em>
</p>

<p align="center">
  <a href="mailto:kkjjww1503@naver.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

---

## 🧑‍💻 About Me

- AWS 인프라를 **Terraform IaC**로 설계·구축하는 클라우드 인프라 엔지니어입니다.
- 멀티 리전 아키텍처, 쿠버네티스(EKS) 운영, CI/CD 파이프라인, 관측성(Observability) 구성에 관심이 많습니다.
- 단순한 "동작하는 인프라"가 아니라 **트레이드오프를 고려한 설계**와 **재현 가능한 인프라**를 지향합니다.

---

## 🛠️ Tech Stack

**Cloud & IaC**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

**Container & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**CI/CD & Observability**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Database & Language**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

## 🚀 Featured Project

### StockOps — K-Food 수출 기업용 ERP/WMS 멀티 리전 인프라

AWS 위에 Terraform으로 구축한 멀티 리전(서울·오하이오) 기반의 ERP/WMS 인프라입니다.

- **Multi-Region**: 서울(primary)·오하이오(DR) 2개 리전, Global Accelerator 기반 라우팅
- **Kubernetes**: EKS(v1.30) + Karpenter 오토스케일링 + HPA + ArgoCD GitOps
- **IaC**: Terraform 상태를 `seoul / ohio / global` 레이어로 분리, S3 원격 백엔드 관리
- **CI/CD**: GitHub Actions + OIDC(액세스 키 없는 인증) → ArgoCD 배포
- **Frontend**: S3 + CloudFront(OAC) 정적 호스팅으로 마이그레이션
- **IoT Pipeline**: IoT Core → SQS(실시간) / Kinesis Firehose → S3 → Athena 분석
- **Observability**: Prometheus + Grafana 기반 모니터링/로깅

> 📐 실제 Terraform 코드베이스로부터 생성한 아키텍처 다이어그램을 README 상단에서 확인할 수 있습니다.

🔗 **Repository**: [StockOps Infra][https://github.com/jinuuuKim/Stockops-Infra]

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jinuuuKim&show_icons=true&theme=default&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinuuuKim&layout=compact&theme=default&hide_border=true" height="165"/>
</p>

---

<p align="center">
  <em>Infrastructure as Code, Reliability by Design.</em>
</p>
