# DevOps Practice Guide

How to evaluate the tools? Please feel free to consider the following aspects:

| Item | Importance | Description |
|---|---|---|
| Extensibility | | Support to enhance the features by plugin or extension mechanism |
| Workflow or Task level reusable | | How to reuse a workflow or task to make the workflow be simple |
| UI || Having the UI management |
| Single sign-on (SSO) | | Allow users log in all platforms with a single account |

## Tool Chain

| Category | Tool | Activity | License |
|---|---|---|---|
| Git | [Gitlab](https://gitlab.com/gitlab-org/gitlab) |||
| Git | [Gitea](https://github.com/go-gitea/gitea) | |MIT |
| CI | [Jenkins](https://github.com/jenkinsci/jenkins) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/jenkinsci/jenkins) | MIT |
| CI | [Argo Workflow](https://github.com/argoproj/argo-workflows)| ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/argoproj/argo-workflows) | Apache-2.0 |
| CI | [Tekton](https://github.com/tektoncd/pipeline) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/tektoncd/pipeline) | Apache-2.0 |
| CD | [Argo CD](https://github.com/argoproj/argo-cd) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/argoproj/argo-cd) ||
| CD | [Flux CD](https://github.com/fluxcd/flux2) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/fluxcd/flux2) ||
| Code Analysis | [SonarQube](https://github.com/SonarSource/sonarqube) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/SonarSource/sonarqube) ||
| Artifact | [MinIO](https://github.com/minio/minio) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/minio/minio) | AGPL-3.0 |
| Artifact | [Harbor](https://github.com/goharbor/harbor) | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/goharbor/harbor) | Apache-2.0 |

## Cache
Below are local cache solutions table:

| Stage | Solution | License |
|---|---|---|
| Golang Build | [goproxy](https://github.com/goproxyio/goproxy/) | MIT |
| Image Pull | [Nexus](https://github.com/sonatype/nexus-public) | EPL-1.0 |
| Maven Build | [Nexus](https://github.com/sonatype/nexus-public) | EPL-1.0 |
| NPM Build | [Verdaccio](https://github.com/verdaccio/verdaccio) | MIT |

## References
* [Learning guide for Jenkins](https://github.com/LinuxSuRen/jenkins-learning-guide)
* [Argo Workflows Guide](https://github.com/LinuxSuRen/argo-workflows-guide) (in Chinese)
