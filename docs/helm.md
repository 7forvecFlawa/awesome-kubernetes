# Helm Kubernetes Tool
- [Helm](#helm)
- [Helm Plugins](#helm-plugins)
- [Helm Chart Documentation](#helm-chart-documentation)
- [Kubecrt](#kubecrt)
- [Datree](#datree)
- [Helm Charts repositories](#helm-charts-repositories)
- [Helm Charts](#helm-charts)
- [Shalm. Scriptable helm charts](#shalm-scriptable-helm-charts)
- [Helmfile](#helmfile)
- [Database Migrations](#database-migrations)
- [Helm Tools](#helm-tools)
- [Helm Books](#helm-books)
- [Tweets](#tweets)

## Helm
* [thoughtworks.com: Helm](https://www.thoughtworks.com/radar/tools/helm)
* [helm.sh](https://helm.sh/)
    * [helm.sh/docs](https://helm.sh/docs) 
    * [helm.sh: Getting Started 🌟](https://helm.sh/docs/chart_template_guide/getting_started/)
* [GitHub: Helm, the Kubernetes Package Manager](https://github.com/helm/helm) Installing and managing Kubernetes applications
* [Helm and Kubernetes Tutorial - Introduction](https://www.youtube.com/watch?v=9cwjtN3gkD4)
* [Delve into Helm: Advanced DevOps](https://www.youtube.com/watch?v=cZ1S2Gp47ng)
* [Continuously delivering apps to Kubernetes using Helm](https://www.youtube.com/watch?v=CmPK93hg5w8)
* [Zero to Kubernetes CI/CD in 5 minutes with Jenkins and Helm](https://www.youtube.com/watch?v=eMOzF_xAm7w)
* [DevOps with Azure, Kubernetes, and Helm](https://www.youtube.com/watch?v=INv-VCZvM_o)
* [dzone: the art of the helm chart patterns](https://dzone.com/articles/the-art-of-the-helm-chart-patterns-from-the-offici)
* [dzone: 15 useful helm chart tools](https://dzone.com/articles/15-useful-helm-charts-tools)
* [dzone: create install upgrade and rollback a helm chart - part 1](https://dzone.com/articles/create-install-upgrade-and-rollback-a-helm-chart-p)
* [dzone: create install upgrade and rollback a helm chart - part 2](https://dzone.com/articles/create-install-upgrade-rollback-a-helm-chart-part)
* [dzone: cicd with kubernetes and helm](https://dzone.com/articles/cicd-with-kubernetes-and-helm)
* [dzone: do you need helm?](https://dzone.com/articles/do-you-need-helm)
* [dzone: managing helm releases the gitops way](https://dzone.com/articles/managing-helm-releases-the-gitops-way)
* [codefresh.io: Using Helm 3 with Helm 2 charts](https://codefresh.io/helm-tutorial/taking-helm-3-spin/)
* [banzaicloud.com: Helm 3, the Good, the Bad and the Ugly](https://banzaicloud.com/blog/helm3-the-good-the-bad-and-the-ugly/)
* [helm.sh: How to migrate from Helm v2 to Helm v3](https://helm.sh/blog/migrate-from-helm-v2-to-helm-v3/)
* [Helm 3: Validating Helm Chart Values with JSON Schemas 🌟](https://www.arthurkoziel.com/validate-helm-chart-values-with-json-schemas/)
* [hackernoon.com: Kubernetes and Helm: A Deadly Combo to Help You Deploy with Ease](https://hackernoon.com/kubernetes-and-helm-a-deadly-combo-to-help-you-deploy-with-ease-rjr30x2)
* [medium: Helm Chart — Development Guide 🌟](https://medium.com/swlh/helm-chart-development-guide-bbc525d3b448) Writing maintainable and reliable charts with few tricks
* [medium: Multi-namespace Helm deploy in Kubernetes](https://medium.com/analytics-vidhya/multi-namespace-helm-deploy-in-kubernetes-26d1baf1ca5c)
* [rancher.com: Create Reproducible Security in Kubernetes with Helm 3 and Helm Charts](https://rancher.com/blog/2020/helm-security)
* [daveops.xyz: Running DB migrations on Kubernetes with Helm](https://daveops.xyz/en/2020/09/18/running-db-migrations-on-kubernetes-with-helm/)
* [mbbaig.blog: How to create custom Helm charts 🌟](https://mbbaig.blog/how-to-create-custom-helm-charts/)
* [medium: Using Helm with Amazon EKS without kubeconfigs](https://medium.com/analytics-vidhya/using-helm-with-amazon-eks-without-a-kubeconfig-733f44a31b1d)
* [dev.to: Introduction to Helm 🌟](https://dev.to/edlegaultle/introduction-to-helm-50jl)
* [itnext.io: Helm 3 Umbrella Charts & Standalone Chart Image Tags — An Alternative Approach](https://itnext.io/helm-3-umbrella-charts-standalone-chart-image-tags-an-alternative-approach-78a218d74e2d) Helm umbrella charts, for those who aren’t familiar, describe and encapsulate a deployable collection of loosely couple Kubernetes components as a higher-order Helm chart. In other words, a collection of software elements that each have their own individual charts but, for whatever reason (e.g. design choices, ease of deployability, versioning complexities), must be installed or upgraded as a since atomic unit.
* [rancher.com: Create Reproducible Security in Kubernetes with Helm 3 and Helm Charts](https://rancher.com/blog/2020/helm-security)
* [jfrog.com: Steering Straight with Helm Charts Best Practices 🌟](https://jfrog.com/blog/helm-charts-best-practices/)
* [rancher.com: Create Reproducible Security in Kubernetes with Helm 3 and Helm Charts](https://rancher.com/blog/2020/helm-security)
* [youtube.com: Demystifying Helm 🌟](https://www.youtube.com/watch?v=2HPsPOwHOlY&ab_channel=DonovanBrown)
* [harness.io: Introduction to Helm: Charts, Deployments, & More 🌟](https://harness.io/blog/continuous-delivery/what-is-helm/)
* [freecodecamp.org: What is a Helm Chart? A Tutorial for Kubernetes Beginners](https://www.freecodecamp.org/news/what-is-a-helm-chart-tutorial-for-kubernetes-beginners)
* [youtube: GitOps Guide to the Galaxy: Working with Helm](https://www.youtube.com/watch?v=1FzOlSed5ts&ab_channel=OpenShift)
* [cncf.io: Quick application deployments on MicroK8s using Helm Charts](https://www.cncf.io/blog/2021/03/23/quick-application-deployments-on-microk8s-using-helm-chart)
* [cncf.io: Add Java Agents to Existing Kubernetes and Helm Applications Instantly](https://www.cncf.io/blog/2021/03/24/add-java-agents-to-existing-kubernetes-and-helm-applications-instantly)
* [medium: Create Helm Charts to manage Kubernetes applications](https://medium.com/marionete/create-helm-charts-to-manage-kubernetes-applications-9c4235acf99e) Understand what is Helm, Helm Charts and how to configure GitHub pages to store and share your Charts.
* [blog.heyal.co.uk: How to unit-test your helm charts with Golang 🌟](https://blog.heyal.co.uk/unit-testing-helm-charts/) Learn how to write Golang unit tests for your Helm charts to keep quality high and make changes with confidence.
* [bridgecrew.io: Part 1: Top trends from analyzing the security posture of open-source Helm charts](https://bridgecrew.io/blog/open-source-helm-security-research/)
    * [bridgecrew.io: Part 2: Top trends from analyzing the security posture of open-source Helm charts](https://bridgecrew.io/blog/open-source-helm-security-research-part-2/)
    * [bridgecrew.io: Part 3: Top trends from analyzing the security posture of open-source Helm charts](https://bridgecrew.io/blog/open-source-helm-security-research-part-3/)
* [redhat.com: Red Hat OpenShift Certification extends support for Kubernetes-native technologies with Helm 🌟](https://www.redhat.com/en/blog/red-hat-openshift-certification-extends-support-kubernetes-native-technologies-helm) **Helm or Operators: how to choose**
* [jasiek-petryk.medium.com: Setting up a private Helm chart repository on GitHub](https://jasiek-petryk.medium.com/setting-up-a-private-helm-chart-repository-on-github-4a767703cec8)
* [betterprogramming.pub: How To Continuously Test and Deploy Your Helm Charts on Kubernetes Clusters Using Kind](https://betterprogramming.pub/how-to-continuously-test-and-deploy-your-helm-charts-on-kubernetes-clusters-using-kind-d71e3585d2dc) Set up your CI/CD tools to easily test and publish charts on ephemeral Kubernetes clusters
* [blog.flant.com: Making the most out of Helm templates 🌟](https://blog.flant.com/advanced-helm-templating/) The standard Helm library and traditional approaches to creating Helm charts are generally okay to automate non-complex tasks. But the growing complexity and number of Helm charts rapidly make the minimalistic Helm templates and controversial standard Helm library insufficient. In this article, we will show you how to make your Helm templates much more flexible and dynamic by implementing your own Helm “functions” and exploiting the capabilities of the tpl function.
* [levelup.gitconnected.com: Helm 101 for Developers](https://levelup.gitconnected.com/helm-101-for-developers-1c28e734937e)
* [developers.redhat.com: Deploy Helm charts with Jenkins CI/CD in Red Hat OpenShift 4 🌟](https://developers.redhat.com/articles/2021/05/24/deploy-helm-charts-jenkins-cicd-red-hat-openshift-4)
* [developers.redhat.com: Deploy Node.js applications to Red Hat OpenShift with Helm](https://developers.redhat.com/articles/2021/07/20/deploy-nodejs-applications-red-hat-openshift-helm)
* [thenewstack.io: Upgrade Helm if You Don’t Want to Share Your Username and Password (Helm’s CVE-2021-32690) 🌟](https://thenewstack.io/upgrade-helm-if-you-dont-want-to-share-your-username-and-password/)
* [thedeveloperstory.com: Helm 101: Brief introduction to kubernetes package manager](https://thedeveloperstory.com/2021/07/12/helm-101-brief-introduction-to-kubernetes-package-manager/)
* [betterprogramming.pub: 6 Tips for Creating Helm Charts in Kubernetes Applications](https://betterprogramming.pub/6-tips-for-creating-helm-charts-in-kubernetes-applications-452a37446f31) Build, maintain, and control Helm chart releases with fewer bugs and code issues
* if you're having either https://github.com/helm/helm/issues/10005 or https://github.com/helm/helm/issues/10004, it's because the older Helm 2 backing store is finally gone. You REALLY should upgrade to Helm 3, and now. You're risking your security more than you should.
* [medium: Kubernetes Deployment using Helm Charts and Krane 🌟](https://medium.com/groupon-eng/kubernetes-deployment-using-helm-charts-and-krane-e0100b55d00c)
* [cloud.redhat.com: Application Management in Kubernetes Environments with Helm Charts and Kubernetes Operators](https://cloud.redhat.com/blog/application-management-in-kubernetes-environments-with-helm-charts-and-kubernetes-operators)
* [codersociety.com: 13 Best Practices for using Helm](https://codersociety.com/blog/articles/helm-best-practices) Helm is an indispensable tool for deploying applications to Kubernetes clusters. But it is only by following best practices that you’ll truly reap the benefits of Helm. Here are 13 best practices to help you create, operate, and upgrade applications using Helm.
* [bridgecrew.io: Applying Kubernetes security best practices to Helm charts](https://bridgecrew.io/blog/applying-kubernetes-security-best-practices-to-helm-charts/)
* [dzone.com: Deploy a Java application using Helm, Part 1 (OpenShift) 🌟](https://dzone.com/articles/deploy-a-java-application-using-helm-part-1)
* [codefresh.io: Using Helm with GitOps 🌟](https://codefresh.io/helm-tutorial/using-helm-with-gitops/)

## Helm Plugins
* [Helm Diff Plugin 🌟](https://github.com/databus23/helm-diff) A helm plugin that shows a diff explaining what a helm upgrade would change
* [Helm mapkubeapis Plugin](https://github.com/helm/helm-mapkubeapis) This is a Helm plugin which map deprecated or removed Kubernetes APIs in a release to supported APIs. **With kubernetes 1.22 dropping support for more beta APIs, you might be in need of a helmpack plugin to help you with that..** 

## Helm Chart Documentation
* [chart-doc-gen: Helm Chart Documentation Generator](https://github.com/kubepack/chart-doc-gen)
* [Frigate](https://frigate.readthedocs.io/) is a tool for automatically generating documentation for your Helm charts. It will use the chart’s Chart.yaml and values.yaml files in order to generate the content in a markup language of your choice.
* [rafay.co: Helm Chart Hooks Tutorial](https://rafay.co/the-kubernetes-current/helm-chart-hooks-tutorial/)
* [itnext.io: Helm: reusable chart — named templates, and a generic chart for multiple applications](https://itnext.io/helm-reusable-chart-named-templates-and-a-generic-chart-for-multiple-applications-13d9b26e9244) Designing reusable chart with Helm:  named templates, and a generic chart for multiple applications
* [jfrog.com: Helm is for everyone! (download your free helm guide) ](https://jfrog.com/assets/helm-is-for-everyone/)
* [thenewstack.io: Applying Kubernetes Security Best Practices to Helm Charts 🌟](https://thenewstack.io/applying-kubernetes-security-best-practices-to-helm-charts/)
* [medium: Highway to Helm: How to efficiently manage chart sources](https://medium.com/adevinta-tech-blog/highway-to-helm-how-to-efficiently-manage-chart-sources-f5749ba8031e) In this post, we’ll go through two ways to manage the source files of Helm charts, we’ll discuss the different factors that make one more suitable than the other, depending on your organisational structure, and we’ll provide guidance on choosing the right way to go by sharing what conditions are in favour of each of the two methods.

## Kubecrt
* [Kubecrt](https://github.com/blendle/kubecrt)
* [Kubecrt - Convert HELM charts to kubernetes resources 🌟](https://toolbox.kali-linuxtr.net/kubecrt-convert-helm-charts-to-kubernetes-resources.tool)

## Datree
* https://github.com/datreeio/datree Prevent Kubernetes misconfigurations from reaching production (again 😤 )! **Datree** is a CLI tool to ensure K8s manifests and Helm charts follow best practices as well as your organization’s policies. See our docs: https://hub.datree.io/
* [datree.io: How to build a Helm plugin in minutes](https://www.datree.io/resources/how-to-build-a-helm-plugin-in-minutes)

## Helm Charts repositories
* [codeengineered.com: 4 Places To Find Helm Charts](https://codeengineered.com/blog/2020/helm-find-charts/)
* [hub.helm.sh 🌟](http://hub.helm.sh) -> [artifacthub.io 🌟](https://artifacthub.io/) Find, install and publish
Kubernetes packages
    * [New Location For Stable and Incubator Charts](https://helm.sh/blog/new-location-stable-incubator-charts/)
    * [charts.helm.sh/stable 🌟](https://charts.helm.sh/stable)
    * [charts.helm.sh/incubator 🌟](https://charts.helm.sh/incubator/)
* [Bitnami Helm Charts](https://bitnami.com/stacks/helm)
* [JFrog ChartCenter](https://chartcenter.io/)
    * [Navigating Kubernetes With Helm 3 Charts and ChartCenter 🌟](https://dzone.com/articles/navigating-kubernetes-with-helm-3-charts-and-chart) ChartCenter is a free central repository for discovering Helm Charts, created to help manage your Kubernetes applications 
* [Artifact Hub 🌟](https://artifacthub.io/) Find, install and publish Kubernetes packages
* [KubeApps Hub](https://hub.kubeapps.com/)
* [github: Nova 🌟](https://github.com/fairwindsops/nova) Find outdated or deprecated Helm charts running in your cluster.
* [github: Kubernetes Deployment Orchestrator](https://github.com/SAP/kubernetes-deployment-orchestrator) This project brings the starlark scripting language to helm charts.
* [harness.io: Tutorial: Turning a GitHub Repo Into a Helm Chart Repo](https://harness.io/blog/devops/helm-chart-repo/)
  
## Helm Charts
* [Jenkins](https://github.com/helm/charts/tree/master/stable/jenkins) 
* [Codecentric Jenkins 🌟](https://github.com/codecentric/helm-charts/tree/master/charts/jenkins) Helm 3 compliant (Simpler and more secure than helm 2)
* [Nexus3](https://github.com/helm/charts/tree/master/stable/sonatype-nexus)
* [Choerodon Nexus3 🌟](https://hub.helm.sh/charts/choerodon/nexus3) Helm 3 compliant (Simpler and more secure than helm 2)
* [Sonar](https://github.com/helm/charts/tree/master/stable/sonarqube)
* [Selenium](https://github.com/helm/charts/tree/master/stable/selenium)
* [Jmeter](https://github.com/helm/charts/tree/master/stable/distributed-jmeter)
* [bitnami: create your first helm chart](https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/)
* [openshift.com: Introducing the Quarkus Helm Chart](https://www.openshift.com/blog/introducing-the-quarkus-helm-chart)
* [artifacthub.io: Official Helm charts for HAProxy and the HAProxy Kubernetes Ingress Controller on Artifact Hub 🌟](https://artifacthub.io/packages/search?repo=haproxytech)
* [prometheus-community.github.io: Prometheus Community Kubernetes Helm Charts 🌟](https://prometheus-community.github.io/helm-charts/)

## Shalm. Scriptable helm charts
* [shalm: Scriptable helm charts](https://github.com/wonderix/shalm) This project brings the starlark scripting language to helm charts.

## Helmfile
- [helmfile](https://github.com/linuxadvise/helmfile)
- [linuxadvise.com: Helmfile - Next Level to manage your helm Charts](https://www.linuxadvise.com/amp/helmfile-next-level-to-manage-your-helm-charts)
- [kubesandclouds.com: Helmfile: turbocharging Helm](https://kubesandclouds.com/index.php/2020/12/16/helmfile/)

## Database Migrations
- [itnext.io: Database migrations on Kubernetes using Helm hooks](https://itnext.io/database-migrations-on-kubernetes-using-helm-hooks-fb80c0d97805)

## Helm Tools 
- [redhat-certification: chart-verifier: Rules based tool to certify Helm charts 🌟](https://github.com/redhat-certification/chart-verifier)
- [helm-changelog: Create changelogs for Helm Charts, based on git history](https://github.com/mogensen/helm-changelog)
- [helm-scanner](https://github.com/bridgecrewio/helm-scanner/) Open source IaC security scanner for public Helm charts. Helm-scanner is a tool designed to automate discovering, templating, security scanning, then recording and providing easy access to the results for publicly available Helm charts

## Helm Books
- [Learn Helm](https://www.packtpub.com/cloud-networking/learn-helm)

## Tweets
<details>
  <summary>Click to expand!</summary>

<center>
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">What is Three-way Strategic Merge Update in <a href="https://twitter.com/hashtag/Helm?src=hash&amp;ref_src=twsrc%5Etfw">#Helm</a>?<br><br>A 3-way merge reconciles a modified configuration with an original configuration while preserving any changes or deletions made to the original configuration in the interim.<br>more... 👇<a href="https://twitter.com/learnk8s?ref_src=twsrc%5Etfw">@learnk8s</a> <a href="https://twitter.com/hashtag/kubernetes?src=hash&amp;ref_src=twsrc%5Etfw">#kubernetes</a> <a href="https://twitter.com/hashtag/cncf?src=hash&amp;ref_src=twsrc%5Etfw">#cncf</a> <a href="https://twitter.com/hashtag/k8s?src=hash&amp;ref_src=twsrc%5Etfw">#k8s</a> <a href="https://twitter.com/hashtag/devops?src=hash&amp;ref_src=twsrc%5Etfw">#devops</a> <a href="https://t.co/HlmPeHG8On">pic.twitter.com/HlmPeHG8On</a></p>&mdash; Rahul Rai🌥️ (@rahulrai_in) <a href="https://twitter.com/rahulrai_in/status/1397768176297865221?ref_src=twsrc%5Etfw">May 27, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Truth is, most applications don&#39;t need complex automation hooks. You can go a long way with health checks, liveness probes, metrics, logs, and basic signal handling, which is why generic automation tools like Helm works well for most situations.</p>&mdash; Kelsey Hightower (@kelseyhightower) <a href="https://twitter.com/kelseyhightower/status/1435644371773186049?ref_src=twsrc%5Etfw">September 8, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Highway To Helm ! <a href="https://t.co/2UkS5kD4AG">pic.twitter.com/2UkS5kD4AG</a></p>&mdash; Sébastien Blanc 🇪🇺 🥑 (@sebi2706) <a href="https://twitter.com/sebi2706/status/1459204115481911310?ref_src=twsrc%5Etfw">November 12, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Artifact Hub is now able to check if Helm charts stored in OCI registries have been signed with 𝐜𝐨𝐬𝐢𝐠𝐧 from <a href="https://twitter.com/projectsigstore?ref_src=twsrc%5Etfw">@projectsigstore</a> 🔏🚀 <a href="https://t.co/DL6Z30U8Vu">pic.twitter.com/DL6Z30U8Vu</a></p>&mdash; Artifact Hub (@cncfartifacthub) <a href="https://twitter.com/cncfartifacthub/status/1462824128390606858?ref_src=twsrc%5Etfw">November 22, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</center>
</details>