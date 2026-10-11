<p align="center">
  <img src="image/terminal-intro.svg" width="100%" alt="$ kubectl get engineer jeon-insoo — Building reliable infrastructure & automating everything, with contributions to the CNCF ecosystem."/>
</p>

<p align="center">
  <a href="mailto:mumberrymountain@gmail.com"><img src="https://img.shields.io/badge/Email-161b22?style=for-the-badge&logo=gmail&logoColor=EA4335"/></a>
  <a href="https://mumberrymountain.github.io/jeon-resume-blog/"><img src="https://img.shields.io/badge/Blog-161b22?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<br>

## Skills

#### Container & Orchestration
<a href="https://www.docker.com"><img src="image/skills/docker.svg" width="88" height="94" alt="Docker"/></a><a href="https://kubernetes.io"><img src="image/skills/kubernetes.svg" width="88" height="94" alt="Kubernetes"/></a><a href="https://helm.sh"><img src="image/skills/helm.svg" width="88" height="94" alt="Helm"/></a><a href="https://kustomize.io"><img src="image/skills/kustomize.svg" width="88" height="94" alt="Kustomize"/></a><a href="https://istio.io"><img src="image/skills/istio.svg" width="88" height="94" alt="Istio"/></a>

#### CI/CD & GitOps
<a href="https://docs.gitlab.com/ee/ci/"><img src="image/skills/gitlab-ci.svg" width="88" height="94" alt="GitLab CI"/></a><a href="https://github.com/features/actions"><img src="image/skills/actions.svg" width="88" height="94" alt="Actions"/></a><a href="https://www.jenkins.io"><img src="image/skills/jenkins.svg" width="88" height="94" alt="Jenkins"/></a><a href="https://argo-cd.readthedocs.io"><img src="image/skills/argocd.svg" width="88" height="94" alt="ArgoCD"/></a>

#### Infrastructure as Code
<a href="https://developer.hashicorp.com/terraform"><img src="image/skills/terraform.svg" width="88" height="94" alt="Terraform"/></a><a href="https://www.ansible.com"><img src="image/skills/ansible.svg" width="88" height="94" alt="Ansible"/></a>

#### MLOps
<a href="https://mlflow.org"><img src="image/skills/mlflow.svg" width="88" height="94" alt="MLflow"/></a><a href="https://dvc.org"><img src="image/skills/dvc.svg" width="88" height="94" alt="DVC"/></a><a href="https://kserve.github.io/website/"><img src="image/skills/kserve.svg" width="88" height="94" alt="KServe"/></a><a href="https://www.kubeflow.org"><img src="image/skills/kubeflow.svg" width="88" height="94" alt="Kubeflow"/></a>

#### Monitoring & Observability
<a href="https://prometheus.io"><img src="image/skills/prometheus.svg" width="88" height="94" alt="Prometheus"/></a><a href="https://grafana.com"><img src="image/skills/grafana.svg" width="88" height="94" alt="Grafana"/></a><a href="https://grafana.com/oss/loki/"><img src="image/skills/loki.svg" width="88" height="94" alt="Loki"/></a><a href="https://grafana.com/oss/tempo/"><img src="image/skills/tempo.svg" width="88" height="94" alt="Tempo"/></a><a href="https://opentelemetry.io"><img src="image/skills/opentelemetry.svg" width="88" height="94" alt="OpenTelemetry"/></a><a href="https://github.com/HolmesGPT/holmesgpt"><img src="image/skills/holmesgpt.svg" width="88" height="94" alt="HolmesGPT"/></a>

#### Programming Languages
<a href="https://go.dev"><img src="image/skills/go.svg" width="88" height="94" alt="Go"/></a><a href="https://www.python.org"><img src="image/skills/python.svg" width="88" height="94" alt="Python"/></a><a href="https://www.gnu.org/software/bash/"><img src="image/skills/bash.svg" width="88" height="94" alt="Bash"/></a>

<br>

## Certifications

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://www.credly.com/badges/5f295cb0-30fd-44d4-a7c6-9eb4d97a992e/public_url"><img src="https://images.credly.com/size/340x340/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="80" alt="AWS Certified Solutions Architect - Associate"/></a><br>
      <sub>AWS Certified Solutions Architect - Associate</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://www.credly.com/badges/12f7e9d3-406e-45a1-addf-6d28fce3fb03/public_url"><img src="https://images.credly.com/size/340x340/images/6f614b71-3f2e-488e-8b29-71e90d4dbf80/blob" width="80" alt="HashiCorp Certified: Terraform Associate (004)"/></a><br>
      <sub>HashiCorp Certified: Terraform Associate (004)</sub>
    </td>
  </tr>
</table>

<br>

## Open Source Contributions

> Merged fixes in **Prometheus · node_exporter · OpenTofu · Helm** and more

#### Major Contributions

| 프로젝트 | 기여 내용 | PR |
|---|---|---|
| <img src="image/org-opentofu.png" width="20"/> [opentofu](https://github.com/opentofu/opentofu) | `tofu init -backend=false` 실행 시 암호화된 로컬 state 파일을 불필요하게 읽고 복호화를 시도하는 현상 수정 | [![#4077](https://img.shields.io/github/pulls/detail/state/opentofu/opentofu/4077)](https://github.com/opentofu/opentofu/pull/4077) |
| <img src="image/org-prometheus.png" width="20"/> [prometheus](https://github.com/prometheus/prometheus) | `tracing.client_type: http`와 `insecure: true` 함께 사용시 프로메테우스 실행할 때 에러나는 현상 수정 | [![#18454](https://img.shields.io/badge/backported-v3.11.1-6f42c1)](https://github.com/prometheus/prometheus/pull/18469) |
| <img src="image/org-prometheus.png" width="20"/> [node_exporter](https://github.com/prometheus/node_exporter) | `--collector.diskstats.device-include` 단독 사용 시 device-exclude 기본값과의 충돌로 패닉이 발생하는 현상 수정 | [![#3603](https://img.shields.io/github/pulls/detail/state/prometheus/node_exporter/3603)](https://github.com/prometheus/node_exporter/pull/3603) |
| <img src="image/org-dhatim.png" width="20"/> [fastexcel](https://github.com/dhatim/fastexcel) | `fastexcel-reader`가 엑셀 파일의 1904 날짜 체계를 정상적으로 인식하지 못하는 현상 수정 | [![#527](https://img.shields.io/github/pulls/detail/state/dhatim/fastexcel/527)](https://github.com/dhatim/fastexcel/pull/527) |
<!--
| <img src="https://github.com/olifolkerd.png" width="20"/> [tabulator](https://github.com/olifolkerd/tabulator) | 테이블을 임시적으로 DOM에서 제거한 상태에서 행을 추가하고 다시 렌더링할 때 행 추가 상태가 반영되지 않는 현상 수정 | [![#4756](https://img.shields.io/github/pulls/detail/state/olifolkerd/tabulator/4756)](https://github.com/olifolkerd/tabulator/pull/4756) |
| <img src="https://github.com/pqina.png" width="20"/> [filepond](https://github.com/pqina/filepond) | 데이터가 많아 스크롤이 생기는 환경에서 드래그 앤 드랍 소팅 시 드랍 포지션이 잘못 계산되는 현상 수정 | [![#1057](https://img.shields.io/github/pulls/detail/state/pqina/filepond/1057)](https://github.com/pqina/filepond/pull/1057) |
-->

#### Documentation & Minor Fixes

| 프로젝트 | 기여 내용 | PR |
|---|---|---|
| <img src="image/org-helm.png" width="20"/> [helm-www](https://github.com/helm/helm-www) | Helm v4 문서 플러그인 섹션 한국어 번역 | [![#2047](https://img.shields.io/github/pulls/detail/state/helm/helm-www/2047)](https://github.com/helm/helm-www/pull/2047) |
