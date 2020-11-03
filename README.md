# awesome-devops

A list of truly awesome SRE or DevOps related stuff.

## Kubernetes

- [pluto](https://github.com/FairwindsOps/pluto) - A cli tool to help discover deprecated apiVersions in Kubernetes https://fairwinds.com
- [kube-node-init](https://github.com/mumoshu/kube-node-init) - Kubernetes daemonset for node initial configuration. Currently for modifying files and systemd services on eksctl nodes without changing userdata
- [Vitess](https://vitess.io/) - A database clustering system for horizontal scaling of MySQL
- [Kraken](https://github.com/uber/kraken) - P2P Docker registry capable of distributing TBs of data in seconds
- [Forecastle](https://github.com/stakater/Forecastle) - Forecastle is a control panel which dynamically discovers and provides a launchpad to access applications deployed on Kubernetes
- [KubeStitch](https://github.com/zloeber/KubeStitch) - Kubernetes deployment stitcher - local development and demo stack.
- [trow](https://github.com/ContainerSolutions/trow) - Container Registry and Image Management for Kubernetes Clusters
- [Harbor](https://goharbor.io/) - An open source trusted cloud native registry project that stores, signs, and scans content.
- [Dragonfly](https://github.com/dragonflyoss/Dragonfly) - Dragonfly is an intelligent P2P based image and file distribution system

### Storage

- [longhorn](https://github.com/longhorn/longhorn) - Cloud-Native distributed block storage built on and for Kubernetes

## Terraform

- [blast-radius](https://github.com/28mm/blast-radius) - Interactive visualizations of Terraform dependency graphs using d3.js - https://28mm.github.io/blast-radius-docs/
- [Atlantis](https://www.runatlantis.io/) - Terraform Pull Request Automation


## Logs and Observability

### Logs

- [Kail](https://github.com/boz/kail) - kubernetes log viewer
- [loghouse](https://github.com/flant/loghouse) - Ready to use log management solution for Kubernetes storing data in [ClickHouse](https://github.com/ClickHouse/ClickHouse) and providing web UI.
- [Loki](https://github.com/grafana/loki) - Like Prometheus, but for logs. https://grafana.com/loki

### Network logging

- [goreplay](https://github.com/buger/goreplay) - GoReplay is an open-source tool for capturing and replaying live HTTP traffic into a test environment in order to continuously test your system with real data. It can be used to increase confidence in code deployments, configuration changes and infrastructure changes. https://goreplay.org

### Observability

- [Prometheus](http://prometheus.io/) - Obviously ...
- [kubespy](https://github.com/pulumi/kubespy) - Tools for observing Kubernetes resources in real time, powered by Pulumi. https://pulumi.io/
- [kube-ops-view](https://github.com/hjacobs/kube-ops-view) - Kubernetes Operational View - read-only system dashboard for multiple K8s clusters

#### Prometheus

- [M3](https://eng.uber.com/m3/) - M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform https://m3db.io/


## Automation and tasking

- [awesome_bot](https://github.com/dkhamsing/awesome_bot) - awesome_bot checks for valid URLs in a file, it can be used to verify pull requests updating a README.
- [Keiko](https://github.com/keikoproj/keiko#keiko-components) - Keiko - Enable Kubernetes at scale - from Intuit. Creators of Argo CD etc.

## Orchestration

- [OperatorHub](https://operatorhub.io/) - OperatorHub.io is a new home for the Kubernetes community to share Operators. Find an existing Operator or list your own today.
- [ArgoCD](https://github.com/argoproj/argo-cd) - Declarative continuous deployment for Kubernetes. https://argoproj.github.io/argo-cd/

## Command Line and Tooling

- [Script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go
- [Whalebrew](https://github.com/whalebrew/whalebrew) - Homebrew, but with Docker images
- [aliases](https://github.com/k-kinzal/aliases) - Resolve dependency on all commands by container
- [EnvCLI](https://github.com/EnvCLI/EnvCLI) - Don't install Node, Go, ... locally - use containers you define within your project. If you have a new machine / other contributors you just have to install docker and envcli to get started.
- [asdf](https://github.com/asdf-vm/asdf) - Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more https://asdf-vm.com/
  - [asdf-k3d](https://github.com/spencergilbert/asdf-k3d) - k3d plugin for asdf version manager https://github.com/asdf-vm/asdf
  - [Variant](https://github.com/mumoshu/variant) - Wrap up your bash scripts into a modern CLI today. Graduate to a full-blown golang app tomorrow.

  
## Templating and configuration management

- [gomplate](https://github.com/hairyhenderson/gomplate) - A flexible commandline tool for template rendering. Supports lots of local and remote datasources. https://gomplate.ca
- [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul
- [remco](https://github.com/HeavyHorst/remco) - remco is a lightweight configuration management tool https://heavyhorst.github.io/remco/
- [Konfigurator](https://github.com/stakater/Konfigurator) - A kubernetes operator that dynamically generates and manages app configuration based on kubernetes resources
- [Bullet Train](https://bullet-train.io/) - Manage feature flags across web, mobile and server side applications


## ChatOps

- [BotKube](https://github.com/infracloudio/botkube) - App that helps you monitor your Kubernetes cluster, debug critical deployments & gives recommendations for standard practices https://botkube.io

## Docker

- [await](https://github.com/saltside/await) - Await tool to check resource status.

## Documentation

- [Grip](https://github.com/joeyespo/grip) - Preview GitHub Markdown files like Readme locally before committing them.
