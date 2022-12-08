# DevOps Practice Guide

How to evaluate the tools? Please feel free to consider the following aspects:

| Item | Importance | Description |
|---|---|---|
| Extensibility | | |
| Single sign-on (SSO) | | Allow users log in all platforms with a single account |

## Tool Chain

| Category | Tool | License |
|---|---|---|
| Git | [Gitlab](https://gitlab.com/gitlab-org/gitlab) ||
| Git | [Gitea](https://github.com/go-gitea/gitea) | MIT |
| CI | [Jenkins](https://github.com/jenkinsci/jenkins) | MIT |
| CI | [Argo Workflow](https://github.com/argoproj/argo-workflows) | Apache-2.0 |
| CI | [Tekton](https://github.com/tektoncd/pipeline) | Apache-2.0 |
| CD | [Argo CD](https://github.com/argoproj/argo-cd) ||
| CD | [Flux CD](https://github.com/fluxcd/flux2) ||
| Code Analysis | [SonarQube](https://github.com/SonarSource/sonarqube) ||

## Cache
Below are local cache solutions table:

| Stage | Solution | License |
|---|---|---|
| Golang Build | [goproxy](https://github.com/goproxyio/goproxy/) | MIT |
| Image Pull | [Nexus](https://github.com/sonatype/nexus-public) | EPL-1.0 |
| Maven Build | [Nexus](https://github.com/sonatype/nexus-public) | EPL-1.0 |
| NPM Build | [Verdaccio](https://github.com/verdaccio/verdaccio) | MIT |
