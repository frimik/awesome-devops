# awesome-devops

A list of truly awesome SRE or DevOps related stuff.

## Kubernetes

- [pluto](https://github.com/FairwindsOps/pluto) - A cli tool to help discover deprecated apiVersions in Kubernetes https://fairwinds.com
- [helm-mapkubeapis](https://github.com/hickeyma/helm-mapkubeapis) - This is a Helm plugin which map deprecated or removed Kubernetes APIs in a release to supported APIs
- [kube-node-init](https://github.com/mumoshu/kube-node-init) - Kubernetes daemonset for node initial configuration. Currently for modifying files and systemd services on eksctl nodes without changing userdata
- [Vitess](https://vitess.io/) - A database clustering system for horizontal scaling of MySQL
- [Kraken](https://github.com/uber/kraken) - P2P Docker registry capable of distributing TBs of data in seconds
- [Forecastle](https://github.com/stakater/Forecastle) - Forecastle is a control panel which dynamically discovers and provides a launchpad to access applications deployed on Kubernetes
- [KubeStitch](https://github.com/zloeber/KubeStitch) - Kubernetes deployment stitcher - local development and demo stack.
- [trow](https://github.com/ContainerSolutions/trow) - Container Registry and Image Management for Kubernetes Clusters
- [Harbor](https://goharbor.io/) - An open source trusted cloud native registry project that stores, signs, and scans content.
- [Dragonfly](https://github.com/dragonflyoss/Dragonfly) - Dragonfly is an intelligent P2P based image and file distribution system
- [Kuard](https://github.com/kubernetes-up-and-running/kuard) - Demo app for Kubernetes Up and Running book - Useful for testing basics of readynesschecks behaviours etc.
- [nodetaint](https://github.com/wish/nodetaint) - Controller to manage taints for nodes in a k8s cluster.
- [nidhogg](https://github.com/uswitch/nidhogg) - Kubernetes Node taints based on Daemonset Pods
- [gangway](https://github.com/heptiolabs/gangway) - An application that can be used to easily enable authentication flows via OIDC for a kubernetes cluster.
- [kapp](https://get-kapp.io/) - Deploy and view groups of Kubernetes resources as "applications". Apply changes safely and predictably, watching resources as they converge.
- [k8s-metadata-injector](https://github.com/almariah/k8s-metadata-injector) - Inject metadata into kubernetes resources based on namespces
- [kubeapps](https://kubeapps.com/) - Your Application Dashboard for Kubernetes
- [helm-controller](https://github.com/k3s-io/helm-controller) - A simple way to manage helm charts (v2 and v3) with a Custom Resource Definitions in k8s.
- [carvel](https://carvel.dev/) - Carvel provides a set of reliable, single-purpose, composable tools that aid in your application building, configuration, and deployment to Kubernetes.
- [k8s-image-swaper](https://github.com/estahn/k8s-image-swapper) - :wheel_of_dharma: Mirror images into your own registry and swap image references automatically.
- [kubernetes-mixin](https://github.com/kubernetes-monitoring/kubernetes-mixin) - Prometheus Monitoring Mixin for Kubernetes - A set of Grafana dashboards and Prometheus alerts for Kubernetes.
- [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults) - A Vault swiss-army knife: a K8s operator, Go client with automatic token renewal, automatic configuration, multiple unseal options and more. A CLI tool to init, unseal and configure Vault (auth methods, secret engines). Direct secret injection into Pods.



## EC2

- [ec2-instance-selector](https://github.com/aws/amazon-ec2-instance-selector.git) - A CLI tool and go library which recommends instance types based on resource criteria like vcpus and memory

### Development environments

- [Skaffold](https://skaffold.dev/) - Skaffold handles the workflow for building, pushing and deploying your application, allowing you to focus on what matters most: writing code.
- [Tilt](https://tilt.dev/) - Productivity for teams building Kubernetes apps.
Smart Rebuilds, Continuous Feedback, Live Updates, Snapshots, and a lot more. tilt up and grok your workflow.
- [DevSpace](https://github.com/devspace-cloud/devspace) - DevSpace - The Fastest Developer Tool for Kubernetes zap Automate your deployment workflow with DevSpace and develop software directly inside Kubernetes.
- [Loft](https://github.com/loft-sh/loft) - Namespace & Virtual Cluster Manager for Kubernetes - Lightweight Virtual Clusters, Self-Service Provisioning for Engineers and 70% Cost Savings with Sleep Mode


### Storage

- [longhorn](https://github.com/longhorn/longhorn) - Cloud-Native distributed block storage built on and for Kubernetes
- [minio](https://min.io/) - Kubernetes Native, High Performance Object Storage


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
- [kube-ops-view](https://codeberg.org/hjacobs/kube-ops-view) - Kubernetes Operational View - read-only system dashboard for multiple K8s clusters
- [gosivy](https://github.com/nakabonne/gosivy) - Another visualization tool for Go process metrics.
- [cloudprober](https://cloudprober.org/) - An active monitoring software to detect failures before your customers do.

#### Prometheus

- [M3](https://eng.uber.com/m3/) - M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform https://m3db.io/


## Automation and tasking

- [awesome_bot](https://github.com/dkhamsing/awesome_bot) - awesome_bot checks for valid URLs in a file, it can be used to verify pull requests updating a README.
- [Keiko](https://github.com/keikoproj/keiko#keiko-components) - Keiko - Enable Kubernetes at scale - from Intuit. Creators of Argo CD etc.
- [renovate](https://github.com/renovatebot/renovate.git) - Renovatebot - Universal dependency update tool that fits into your workflows.


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
- [FlagSmith](https://flagsmith.com/) - Manage feature flags across web, mobile and server side applications


## ChatOps

- [BotKube](https://github.com/infracloudio/botkube) - App that helps you monitor your Kubernetes cluster, debug critical deployments & gives recommendations for standard practices https://botkube.io

## Docker

- [await](https://github.com/saltside/await) - Await tool to check resource status.
- [aws-ecr-public](https://github.com/monken/aws-ecr-public) - Public endpoint for AWS Elastic Container Registry
- [whoami](https://github.com/traefik/whoami) - Tiny Go webserver that prints os information and HTTP request to output
- [local-docker-registry-proxy](https://github.com/frimik/local-docker-registry-proxy) - Local Docker registry proxy stack for swift K3D (and other) container-related workflows.

## Build tools

- [Earthly](https://www.earthly.dev/) - Build automation for the container era
- [Makisu](https://github.com/uber/makisu) - Fast and flexible Docker image building tool, works in unprivileged containerized environments like Mesos and Kubernetes.

## On prem

- [seesaw](https://github.com/google/seesaw) - Seesaw v2 is a [Linux Virtual Server (LVS) based load balancing platform](https://opensource.googleblog.com/2016/01/seesaw-scalable-and-robust-load.html). Binaries: [Shelmangroup](https://github.com/shelmangroup/seesaw)

## Documentation

- [Grip](https://github.com/joeyespo/grip) - Preview GitHub Markdown files like Readme locally before committing them.

## Continuous Integration / Continuous Delivery 

- [Concourse CI](https://concourse-ci.org/) - Continuous thingdoer - Concourse presents a general approach to automation that makes it great for CI/CD.

## Other

- [Proxmox](https://www.proxmox.com/en/) - powerful and efficient open-source software to simplify your server management
