<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0f172a,50:1d4ed8,100:22c55e&text=Surya%20Pratap%20Singh&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=DevOps%20Engineer%20%7C%20AWS%20%7C%20Kubernetes%20%7C%20Terraform%20%7C%20CI%2FCD&descAlignY=60&descSize=18" alt="header banner" />

  <h1>Surya Pratap Singh</h1>
  <p><strong>DevOps Engineer focused on cloud infrastructure, automation, CI/CD, GitOps, and observability.</strong></p>
  <p>
    AWS Certified engineer building production-ready delivery platforms with Kubernetes, Terraform, Jenkins, GitHub Actions,
    Argo CD, Prometheus, and Grafana.
  </p>
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=24&duration=2600&pause=900&color=FFFFFF&center=true&vCenter=true&width=1100&lines=Building+reliable+cloud+platforms+and+CI%2FCD+systems;Automating+infrastructure+with+Terraform%2C+GitOps%2C+and+Kubernetes;Improving+delivery+speed%2C+security%2C+and+observability+for+modern+applications" alt="Typing intro" />
  </a>
</div>

---

## About Me

I build deployment platforms and cloud environments that help teams ship faster, safer, and with more confidence.
My work sits at the intersection of automation, infrastructure, release engineering, observability, and security.

I enjoy turning manual workflows into repeatable systems, whether that means provisioning AWS infrastructure with Terraform,
setting up GitOps-based Kubernetes deployments, hardening CI/CD pipelines with scanning gates, or creating dashboards and alerts
that make production easier to operate.

## Core Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,ansible,linux,bash,python,jenkins,githubactions,prometheus,grafana,postgres,git,react,ts&perline=8" alt="Skill icons" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Argo%20CD-GitOps-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="Argo CD" />
  <img src="https://img.shields.io/badge/SonarQube-Code%20Quality-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white" alt="SonarQube" />
  <img src="https://img.shields.io/badge/Trivy-Container%20Security-1904DA?style=flat-square&logo=aquasecurity&logoColor=white" alt="Trivy" />
  <img src="https://img.shields.io/badge/CloudWatch-AWS%20Monitoring-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white" alt="CloudWatch" />
  <img src="https://img.shields.io/badge/InfluxDB-Time%20Series-22ADF6?style=flat-square&logo=influxdb&logoColor=white" alt="InfluxDB" />
  <img src="https://img.shields.io/badge/Redis-Cache-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
</div>

## Certifications

<div align="center">
  <a href="https://www.credly.com/badges/b80728fb-0983-459f-a94f-361ba644340b/public_url">
    <img src="https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20Associate-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Certified Solutions Architect Associate" />
  </a>
  <img src="https://img.shields.io/badge/Focus-AWS%20%7C%20Kubernetes%20%7C%20Terraform-0f172a?style=for-the-badge" alt="AWS Kubernetes Terraform" />
  <img src="https://img.shields.io/badge/Strength-CI%2FCD%20%7C%20GitOps%20%7C%20Observability-1d4ed8?style=for-the-badge" alt="CI/CD GitOps Observability" />
</div>

## Featured Projects

| Project | What it does |
| --- | --- |
| [MultiCloud-Watchtower](https://github.com/surya-edict/MultiCloud-Watchtower) | A multi-cloud FinOps platform that pulls billing data from AWS, Azure, and GCP, normalizes the cost into a single view, stores the metrics in InfluxDB, and surfaces trends through Grafana dashboards. It also adds Redis-backed alert deduplication and Slack notifications so unusual spend can be caught early instead of after the bill arrives. |
| [Netflix-Clone-DevOps](https://github.com/surya-edict/Netflix-Clone-DevOps) | A Netflix-style streaming app built with React, TypeScript, Vite, Material UI, and TMDB integrations, then containerized with Docker and served through NGINX. The project is a full DevSecOps showcase with Jenkins pipelines, SonarQube and Trivy scans, OWASP dependency checks, Kubernetes deployment, and Prometheus/Grafana monitoring around the application lifecycle. |
| [Three-Tier-Inventory-Management-System-with-AIOps-Style-Alerts](https://github.com/surya-edict/Three-Tier-Inventory-Management-System-with-AIOps-Style-Alerts) | A production-style inventory management system with a React frontend, FastAPI backend, and PostgreSQL database designed to handle real order workflows safely. It is deployed on AWS using Terraform, EKS, ECR, GitHub Actions, and Argo CD, with Prometheus/Grafana alerting added to monitor API health, low-stock events, and operational reliability. |

### Architecture Cards

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>MultiCloud-Watchtower</h3>
      <p><strong>Architecture</strong><br/>Cloud Billing APIs -> Python Processing -> InfluxDB -> Grafana -> Slack Alerts</p>
      <p><strong>Core Idea</strong><br/>Gives teams one place to understand multi-cloud spend, detect cost anomalies, and act before costs drift further.</p>
      <p><strong>Ops Angle</strong><br/>FinOps automation, alert deduplication, metrics pipeline, and cost governance workflow.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Netflix-Clone-DevOps</h3>
      <p><strong>Architecture</strong><br/>React App -> Docker -> Jenkins CI -> Security Scans -> Kubernetes -> Prometheus/Grafana</p>
      <p><strong>Core Idea</strong><br/>Combines a polished user-facing app with a production-style DevSecOps delivery flow from build to monitoring.</p>
      <p><strong>Ops Angle</strong><br/>Secure CI/CD, container delivery, runtime observability, and release readiness checks.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Three-Tier Inventory System</h3>
      <p><strong>Architecture</strong><br/>React Frontend -> FastAPI Backend -> PostgreSQL -> GitHub Actions -> Argo CD -> AWS EKS</p>
      <p><strong>Core Idea</strong><br/>Shows how a real business workflow can be deployed as a secure, observable, cloud-native platform.</p>
      <p><strong>Ops Angle</strong><br/>Terraform provisioning, GitOps deployment, alerting, and reliability-focused application operations.</p>
    </td>
  </tr>
</table>

## GitHub Analytics

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=surya-edict&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="170" src="https://streak-stats.demolab.com?user=surya-edict&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</div>

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=surya-edict&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</div>

## Let's Connect

<div align="center">
  <a href="mailto:su123pratap@gmail.com"><img src="https://img.shields.io/badge/Email-su123pratap%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/surya-edict"><img src="https://img.shields.io/badge/LinkedIn-surya--edict-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/surya-edict"><img src="https://img.shields.io/badge/GitHub-surya--edict-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</div>

<div align="center">
  <sub>Open to DevOps Engineer, Platform Engineer, Cloud Engineer, and SRE opportunities.</sub>
</div>
