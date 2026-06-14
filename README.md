<!-- ===== 헤더 배너 (애니메이션) ===== -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2980,100:26d0ce&height=200&section=header&text=Jinwoo%20Kim&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Cloud%20Infrastructure%20Engineer&descSize=20&descAlignY=60"/>

<!-- ===== 타이핑 애니메이션 ===== -->
<p align="center">
  <a href="https://github.com/jinuuuKim">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=26D0CE&center=true&vCenter=true&width=600&lines=Infrastructure+as+Code+%E2%9A%99%EF%B8%8F;Multi-Region+Architecture+on+AWS+%E2%98%81%EF%B8%8F;Kubernetes+%26+GitOps+Enthusiast+%F0%9F%9A%A2;Reliability+by+Design+%F0%9F%9B%A1%EF%B8%8F" alt="Typing SVG" />
  </a>
</p>

<!-- ===== 방문자 수 / 연락처 ===== -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jinuuuKim&label=Profile%20views&color=26d0ce&style=flat-square" alt="profile views" />
  <a href="mailto:kkjjww1503@naver.com">
    <img src="https://img.shields.io/badge/Email-kkjjww1503@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white"/>
  </a>
</p>

---

## 🧑‍💻 About Me

```yaml
name: 김진우 (Jinwoo Kim)
role: Cloud Infrastructure Engineer
focus:
  - "AWS 인프라를 Terraform IaC로 설계·구축"
  - "멀티 리전 아키텍처 / EKS 운영 / GitOps"
  - "관측성(Observability) 및 CI/CD 자동화"
philosophy: "동작하는 인프라가 아니라, 트레이드오프를 설계한 인프라"
```

- ☁️ AWS 위에서 **재현 가능하고(reproducible) 장애에 강한** 인프라를 코드로 정의합니다.
- 🧩 단일 추천이 아닌 **트레이드오프 기반의 아키텍처 의사결정**을 지향합니다.
- 📈 꾸준함이 실력이라 믿으며, 매일 커밋으로 성장 중입니다.

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,terraform,kubernetes,docker,argocd,githubactions,grafana,prometheus,postgres,python,bash,linux&perline=6" />
</p>

<table align="center">
  <tr>
    <td align="center"><b>Cloud / IaC</b></td>
    <td>AWS &nbsp;·&nbsp; Terraform &nbsp;·&nbsp; Global Accelerator &nbsp;·&nbsp; Route53</td>
  </tr>
  <tr>
    <td align="center"><b>Container</b></td>
    <td>Kubernetes (EKS) &nbsp;·&nbsp; Docker &nbsp;·&nbsp; Helm &nbsp;·&nbsp; Karpenter</td>
  </tr>
  <tr>
    <td align="center"><b>CI/CD</b></td>
    <td>GitHub Actions (OIDC) &nbsp;·&nbsp; ArgoCD (GitOps)</td>
  </tr>
  <tr>
    <td align="center"><b>Observability</b></td>
    <td>Prometheus &nbsp;·&nbsp; Grafana</td>
  </tr>
  <tr>
    <td align="center"><b>Data / Lang</b></td>
    <td>PostgreSQL &nbsp;·&nbsp; Athena &nbsp;·&nbsp; Python &nbsp;·&nbsp; Bash</td>
  </tr>
</table>

---

## 🚀 Featured Project

<h3 align="center">
  <a href="https://github.com/jinuuuKim/Stockops-Infra">📦 StockOps — 멀티 리전 ERP/WMS 인프라</a>
</h3>

<p align="center">
  <i>K-Food 수출 기업 시나리오 기반의 AWS 멀티 리전 인프라 (Terraform IaC)</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white"/>
</p>

| 영역 | 구현 내용 |
|------|-----------|
| 🌏 **Multi-Region** | 서울(Primary) · 오하이오(DR) 2개 리전, Global Accelerator 라우팅 |
| 🚢 **Kubernetes** | EKS v1.30 + Karpenter 오토스케일링 + HPA + ArgoCD GitOps |
| 🧱 **IaC** | Terraform 상태를 `seoul / ohio / global` 레이어로 분리, S3 원격 백엔드 |
| 🔄 **CI/CD** | GitHub Actions + OIDC(키리스 인증) → ArgoCD 자동 배포 |
| 🌐 **Frontend** | S3 + CloudFront(OAC) 정적 호스팅 마이그레이션 |
| 📡 **IoT Pipeline** | IoT Core → SQS(실시간) / Kinesis Firehose → S3 → Athena 분석 |
| 📊 **Observability** | Prometheus + Grafana 모니터링/로깅 |

> 📐 실제 Terraform 코드베이스로부터 생성한 **아키텍처 다이어그램**을 레포 README에서 확인할 수 있습니다.

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=jinuuuKim&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinuuuKim&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=c%23" />
</p>

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:26d0ce,100:1a2980&height=120&section=footer&text=Infrastructure%20as%20Code,%20Reliability%20by%20Design&fontSize=16&fontColor=ffffff&fontAlignY=70"/>
