# Google Cloud Platform
- [Introduction](#introduction)
- [Google Cloud](#google-cloud)
- [Dev Library](#dev-library)
- [GitHub](#github)
- [Managing Cluster Level Configuration](#managing-cluster-level-configuration)
- [Serverless](#serverless)
- [GKE Google Kubernetes Engine](#gke-google-kubernetes-engine)
- [Anthos. Google's Hybrid And Multi-Cloud Platform](#anthos-googles-hybrid-and-multi-cloud-platform)
- [Python](#python)
- [Cloud Code](#cloud-code)
- [Google Cloud Buildpacks](#google-cloud-buildpacks)
- [Cloud SQL](#cloud-sql)
- [Tools](#tools)

## Introduction
* [cloud.google.com](https://cloud.google.com)
* [cloud.google.com: DevOps](https://cloud.google.com/devops)
* [Cloud Developer Tools](https://cloud.google.com/products/tools)
* [Google Cloud Code](https://cloud.google.com/code)
* [Google Cloud Build](https://cloud.google.com/cloud-build)
* [medium.com/google-cloud/tagged/devops](https://medium.com/google-cloud/tagged/devops)
* [Platform comparisons](https://cloud.google.com/docs/compare)
    * [AWS and GCP comparison](https://cloud.google.com/docs/compare/aws)
    * [Mapping of AWS services to Google Cloud](https://gregsramblings.com/blog/compare-google-cloud-to-aws/)
* [whizlabs.com: Introduction To Google Cloud Platform](https://www.whizlabs.com/blog/google-cloud-platform/)

## Google Cloud
- [New Cloud Shell Editor: Get your first cloud-native app running in minutes](https://cloud.google.com/blog/products/application-development/introducing-cloud-shell-editor)
- [techradar.com: Google Cloud is making it easier for developers to smuggle ‘secrets’ in their code](https://www.techradar.com/news/google-cloud-is-making-it-easier-for-developers-to-smuggle-secrets-in-their-code) Google Cloud wants to make building secure applications simpler
- [venturebeat.com: Google Cloud announces Network Connectivity Center to simplify hybrid cloud management](https://venturebeat.com/2021/03/23/google-cloud-announces-network-connectivity-center-to-simplify-hybrid-cloud-management)
- [cloud.google.com: Demystifying Cloud Spanner multi-region configurations](https://cloud.google.com/blog/topics/developers-practitioners/demystifying-cloud-spanner-multi-region-configurations) Cloud Spanner remains unique as a managed relational database that scales across regions while maintaining strong consistency. How does the regional and multi-regional setup differ? 
- [cloud.google.com: Compare AWS and Azure services to Google Cloud](https://cloud.google.com/free/docs/aws-azure-gcp-service-comparison)
- [thecloudgirl.dev: What is Google Cloud Load Balancing?](https://thecloudgirl.dev/CLB.html)
- [cloud.google.com: Secret Manager Best Practices](https://cloud.google.com/secret-manager/docs/best-practices)
- [cloud.google.com: Choose the best way to use and authenticate service accounts on Google Cloud](https://cloud.google.com/blog/products/identity-security/how-to-authenticate-service-accounts-to-help-keep-applications-secure)
- [cloud.google.com: 5 cheat sheets to help you get started on your Google Cloud journey 🌟](https://cloud.google.com/blog/products/gcp/5-google-cloud-product-cheat-sheets-2021) Sometimes a picture is worth a thousand words, and that’s where these cheat sheets come in handy. Cloud Developer Advocate Priyanka Vergadia has built a number of guides that help developers visually navigate critical decisions, whether it’s determining the best way to move to the cloud, or deciding on the best storage options. Below are five of her top cheat sheets in one handy location.
- [thenewstack.io: Configuring the Google Cloud Platform for High Availability](https://thenewstack.io/configuring-for-high-availability-in-google-cloud-platform/)
- [zdnet.com: Google Cloud rolls out new security tools as threat landscape heats up](https://www.zdnet.com/article/google-cloud-rolls-out-new-security-tools-as-threat-landscape-heats-up/) New tools for the public sector will help agencies comply with President Joe Biden's cybersecurity executive order, while other tools give Google Cloud customers more automated security operations and access to Palo Alto Networks' threat detection technologies.
- [cloud.google.com: Consume services faster, privately and securely - Private Service Connect now in GA](https://cloud.google.com/blog/products/networking/private-service-connect-is-now-generally-available)
- [cloud.google.com: VPN network overview](https://cloud.google.com/vpc/docs/vpc) Most VPC products in the public cloud take a regional approach. If you want to interconnect a bunch of regional VPCs later on, it's tricky. Not with googlecloud. A single VPC is global with automatic communication across regions.
- [kinsta.com: Top 7 Advantages of Choosing Google Cloud Hosting](https://kinsta.com/blog/google-cloud-hosting/)
- [cloud.google.com: Monitor and troubleshoot your VMs in context for faster resolution](https://cloud.google.com/blog/products/operations/better-access-to-observability-data-for-virtual-machines)
- [infoq.com: Google Releases Its Certificate Authority Service into General Availability](https://www.infoq.com/news/2021/08/google-cloud-cas-ga/)
- [cloud.google.com: Your Google Cloud database options, explained](https://cloud.google.com/blog/topics/developers-practitioners/your-google-cloud-database-options-explained)
- [cloud.google.com: A container story - Google Kubernetes Engine](https://cloud.google.com/blog/topics/developers-practitioners/container-story-google-kubernetes-engine)
- [cloud.google.com: Save money and time with automated VM management and suspend/resume](https://cloud.google.com/blog/products/compute/guide-to-cost-optimization-through-automated-vm-management)
- [cloud.google.com: Traffic Director explained!](https://cloud.google.com/blog/topics/developers-practitioners/traffic-director-explained)

## Dev Library
- [devlibrary.withgoogle.com 🌟](https://devlibrary.withgoogle.com/) New open source content library from Google, a showcase of what developers like you have built with Google technologies.

## GitHub 
- [github.com/GoogleCloudPlatform](https://github.com/GoogleCloudPlatform)
- [github.com/GoogleCloudPlatform/cloud-code-samples](https://github.com/GoogleCloudPlatform/cloud-code-samples)
- [kelseyhightower/cmd-tutorial](https://github.com/kelseyhightower/cmd-tutorial) This tutorial will walk you through provisioning some VMs on GCP so you can kick the tires on Cmd -- Track and Control Users in Production.

## Managing Cluster Level Configuration
- [Config Sync Overview](https://cloud.google.com/kubernetes-engine/docs/add-on/config-sync/overview) One of the most challenging day two concerns for Kubernetes users is managing cluster level configuration, think namespaces, CRDs, and RBAC rules, across multiple clusters. For GKE customers Config Sync is a game changer.

## Serverless
- [Cloud Functions, meet VPC functionality](https://cloud.google.com/blog/products/serverless/learn-how-to-use-advanced-vpc-functionality-with-your-cloud-functions)

## GKE Google Kubernetes Engine
- [Fetches all Primitive and Predefined GCP IAM Roles](https://github.com/darkbitio/gcp-iam-role-permissions)
- [Using new traffic control features in External HTTP(S) load balancer](https://cloudblog.withgoogle.com/products/networking/how-to-use-new-traffic-control-features-in-cloud-load-balancing/amp/)
- [Setting up NodeLocal DNSCache](https://cloud.google.com/kubernetes-engine/docs/how-to/nodelocal-dns-cache)
- [Looking ahead as GKE, the original managed Kubernetes, turns 5](https://cloudblog.withgoogle.com/products/containers-kubernetes/5-ways-google-cloud-is-making-gke-the-best-place-to-run-kubernetes/amp/)
- [blog.doit-intl.com: How to Set Up Multi-Cluster Load Balancing with GKE](https://blog.doit-intl.com/how-to-setup-multi-cluster-load-balancing-with-gke-4b407e1f3dff)
- [codeburst.io: Google Kubernetes Engine Logging by Example](https://codeburst.io/google-kubernetes-engine-logging-by-example-df6946dcba6b)
- [cloud.google.com: Discover and invoke services across clusters with GKE multi-cluster services](https://cloud.google.com/blog/products/containers-kubernetes/introducing-gke-multi-cluster-services)
- [Introducing GKE Autopilot: a revolution in managed Kubernetes 🌟](https://cloud.google.com/blog/products/containers-kubernetes/introducing-gke-autopilot)
* [techcrunch.com: Google Cloud puts its Kubernetes Engine on autopilot](https://techcrunch.com/2021/02/24/google-cloud-puts-its-kubernetes-engine-on-autopilot/)
* [zdnet.com: Google introduces GKE Autopilot for hands-off Kubernetes](https://www.zdnet.com/article/google-introduces-gke-autopilot-for-hands-off-kubernetes/) The new GKE Autopilot, generally available now, steps up the level of automation involved in Kubernetes management, down to eliminating all node management.
* [thenewstack.io: Google’s New ‘Autopilot’ for Kubernetes](https://thenewstack.io/googles-new-autopilot-for-kubernetes)
* [cloud.google.com: GKE Autopilot 🌟](https://cloud.google.com/kubernetes-engine/docs/concepts/autopilot-overview)
* [medium: How to provision Kubernetes Cluster in GCP Cloud (K8s)? 🌟](https://medium.com/avmconsulting-blog/kubernetes-google-kubernetes-engine-gke-99abf912f912)
* [youtube: GKE Autopilot - Fully Managed Kubernetes Service From Google 🌟](https://youtu.be/Zztufl4mFQ4)
* [insights.project-a.com: Using GitHub Actions to deploy to Kubernetes in GKE 🌟](https://insights.project-a.com/using-github-actions-to-deploy-to-kubernetes-122c653c0b09)
* [faun.pub: How to automate the setup of a Kubernetes cluster on GCP](https://faun.pub/how-to-automate-the-setup-of-a-kubernetes-cluster-on-gcp-e97918bf41de) Using Ansible to install, setup, and configure a Google Kubernetes Cluster (GKE) on Google Cloud Platform (GCP).
* [Kubernetes Cloud DNS](https://cloud.google.com/kubernetes-engine/docs/how-to/cloud-dns#vpc_scope_dns) GCP now makes it easy to query DNS for Kubernetes services across multiple clusters from anywhere inside the VPC! The less stuff users have to run in their clusters, the more they can use for their own apps. It was always problematic to make users admin their own DNS.
* [seroter.com: Using the new Google Cloud Config Controller to provision and manage cloud services via the Kubernetes Resource Model](https://seroter.com/2021/08/18/using-the-new-google-cloud-config-controller-to-provision-and-manage-cloud-services-via-the-kubernetes-resource-model/) I look at a new managed service that provisions cloud-native services as if they were k8s resources.

## Anthos. Google's Hybrid And Multi-Cloud Platform
- [Anthos 🌟](https://cloud.google.com/anthos/)
- [Everything You Want To Know About Anthos - Google's Hybrid And Multi-Cloud Platform](https://www.forbes.com/sites/janakirammsv/2019/04/14/everything-you-want-to-know-about-anthos-googles-hybrid-and-multi-cloud-platform/)
- [itnext.io: Anthos — Multi-cluster Management](https://itnext.io/anthos-multi-cluster-management-aa6f2c03120d)
- [itnext.io: Ingress for Anthos — Multi-cluster Ingress and Global Service Load Balancing](https://itnext.io/ingress-for-anthos-multi-cluster-ingress-and-global-service-load-balancing-c56c57b97e82)
- [A hybrid cloud-native DevSecOps pipeline with JFrog Artifactory and GKE on-prem 🌟](https://cloud.google.com/solutions/partners/a-hybrid-cloud-native-devsecops-pipeline-with-jfrog-artifactory-and-gke-on-prem) Running in a hybrid environment means that some of your processing happens on Google Cloud and other processing remains on-premises. Anthos helps you manage both an on-premises Kubernetes cluster and a cluster running on Google Cloud. 
- [Bringing Kubernetes’ goodness to Windows Server apps with Anthos](https://cloud.google.com/blog/topics/anthos/windows-server-support-comes-to-anthos-on-prem) Windows container support to GKE on-premises through Anthos.

## Python
- [anderfernandez.com: Cómo automatizar un script de Python en Google Cloud](https://anderfernandez.com/blog/automatizar-script-python-google-cloud/)

## Cloud Code
- [Cloud Code 🌟](https://cloud.google.com/code) Everything you need to write, debug, and deploy your cloud-native applications.

## Google Cloud Buildpacks
- [Google Cloud Buildpacks](https://github.com/GoogleCloudPlatform/buildpacks)

## Cloud SQL
- [Testing Cloud SQL failover: Where to begin](https://cloud.google.com/blog/topics/developers-practitioners/testing-cloud-sql-failover-where-begin)

## Tools
- [db-auth-gateway](https://github.com/kloeckner-i/db-auth-gateway) An authentication proxy for Google Cloud managed databases

<center>
<iframe src="https://www.youtube.com/embed/Zztufl4mFQ4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>