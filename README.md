# TSB GitOps Demo

This repository demonstrates TSB GitOps support integrated with ArgoCD, ArgoRollout, FluxCD & SkyWalking for canary deployments and progressive delivery automation. 

### Application

Istio's [bookinfo](application/) app has been used as a sample application.

### Argo Integration

[Argo](argo/) demonstrates canary deployments integrations and auto promotion using [Argo Rollouts](https://argoproj.github.io/argo-rollouts/) & [SkyWalking](https://skywalking.apache.org/)

### Flagger Integration

[Flagger](flagger/) demonstrates canary deployments integrations using [Flagger](https://docs.flagger.app/tutorials/istio-progressive-delivery)

### Repo Structure

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
