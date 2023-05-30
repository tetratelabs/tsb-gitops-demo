# TSB GitOps Demo

This repository demonstrates TSB GitOps support integrated with ArgoCD, ArgoRollout, FluxCD for canary deployments and progressive deliver automation. 

## Application

Istio's [bookinfo](application/) app has been used as a sample application.

### Argo Integration

[argo](argo/) folder demonstrates canary deployments integrations using [Argo Rollouts](https://argoproj.github.io/argo-rollouts/)

### Flagger Integration

[flagger](flagger/) folder demonstrates canary deployments integrations using [Flagger](https://docs.flagger.app/tutorials/istio-progressive-delivery)

### Repo structure

```
.
├── README.md
├── application
│   ├── bookinfo.yaml
│   └── namespace.yaml
├── argo
│   ├── README.md
│   ├── rollout
│   │   ├── analysis.yaml
│   │   └── rollout.yaml
│   └── tsb
│       └── conf.yaml
└── flagger
    ├── canary
    │   └── canary.yaml
    └── tsb
        └── conf.yaml
```