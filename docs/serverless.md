# Serverless Architectures and Frameworks
- [Serverless Architectures](#serverless-architectures)
	- [FaaS: Function as a Service](#faas-function-as-a-service)
	- [Serverless Ecosystems Comparison](#serverless-ecosystems-comparison)
- [Serverless Framework (the most popular serverless ecosystem)](#serverless-framework-the-most-popular-serverless-ecosystem)
- [Orchestrators of Functions on Kubernetes (aka Kubernetes Native Serverless Frameworks or FaaS Providers)](#orchestrators-of-functions-on-kubernetes-aka-kubernetes-native-serverless-frameworks-or-faas-providers)
	- [OpenFaaS](#openfaas)
	- [Knative](#knative)
		- [OpenShift Serverless with Knative](#openshift-serverless-with-knative)
	- [Kubeless](#kubeless)
	- [OpenWhisk](#openwhisk)
	- [Dapr Microservices Frameworks](#dapr-microservices-frameworks)
- [Popular Deployment Frameworks for AWS Lambda](#popular-deployment-frameworks-for-aws-lambda)

## Serverless Architectures
* [martinfowler.com: Serverless Architectures](https://martinfowler.com/articles/serverless.html)
* [developers.redhat.com: Serverless Architecture](https://developers.redhat.com/topics/serverless-architecture/)
* [itnext.io: Scaling My App: Serverless vs Kubernetes 🌟](https://itnext.io/scaling-my-app-serverless-vs-kubernetes-cdb8adf446e1)
* [serverless.com: Comparisons - Serverless vs. other tools](https://www.serverless.com/learn/comparisons/)
* [Is Serverless The End Of Kubernetes?](https://towardsdatascience.com/kubernetes-serverless-differences-84699f370609) A comparison of both technologies to stop the debate about what is better.
* [freecodecamp.org: Serverless is cheaper, not simpler](https://www.freecodecamp.org/news/serverless-is-cheaper-not-simpler-a10c4fc30e49/)
* [medium: What a typical 100% Serverless Architecture looks like in AWS!](https://medium.com/serverless-transformation/what-a-typical-100-serverless-architecture-looks-like-in-aws-40f252cd0ecb)
* [theregister.com: Microservices guru says think serverless, not Kubernetes: You don't want to manage 'a towering edifice of stuff'](https://www.theregister.com/2020/09/22/microservices_talk_gotopia/)
* [serverless.com: Why we switched from docker to serverless](https://www.serverless.com/blog/why-we-switched-from-docker-to-serverless)
* [dzone: The Serverless Path to DevOps](https://dzone.com/articles/the-serverless-path-to-devops) Serverless and DevOps combine in this article the uses AWS services as examples of how serverless technologies benefit DevOps processes.
* [developers.redhat.com: Orchestrate event-driven, distributed services with Serverless Workflow and Kubernetes](https://developers.redhat.com/blog/2020/11/26/event-driven-distributed-service-orchestration-with-serverless-workflow/)

### FaaS: Function as a Service
* [wikipedia: FaaS Function as a Service](https://en.wikipedia.org/wiki/Function_as_a_service)
* [redhat.com: What is Function-as-a-Service (FaaS)?](https://www.redhat.com/en/topics/cloud-native-apps/what-is-faas)
* [stackify.com: What Is Function-as-a-Service? Serverless Architectures Are Here!](https://stackify.com/function-as-a-service-serverless-architecture/)

### Serverless Ecosystems Comparison
* [fauna.com: How does FaaS compare to PaaS and CaaS. A Comparison of Serverless Function (FaaS) Providers](https://fauna.com/blog/comparison-faas-providers)
* [techbeacon.com: An essential guide to the 2019 serverless ecosystem](https://techbeacon.com/enterprise-it/essential-guide-2019-serverless-ecosystem) The Serverless Framework, the most popular option, offers integrations with all major platform providers. Others to consider include (in alphabetical order): Architect (Node, AWS), Chalice (Python, AWS), Claudia.js (Node, AWS), Dawson (Node, AWS), DEEP (Node, AWS), Flogo (Go, AWS), Lambada Framework (Java, AWS), Python-Lambda (Python, AWS), Pulumi (Node/Python/Go, AWS/Azure/GCP/Kubernetes), Shep (Node, AWS), Sparta (Go, AWS), Spring Cloud Function (Java, AWS/Azure/OpenWhisk), and Zappa (Python, AWS).

## Serverless Framework (the most popular serverless ecosystem)
* [serverless.com: Serverless Framework](https://www.serverless.com/)
 
## Orchestrators of Functions on Kubernetes (aka Kubernetes Native Serverless Frameworks or FaaS Providers)
* [epsagon.com: Serverless Open-Source Frameworks: **OpenFaaS**, **Knative**, & More 🌟](https://epsagon.com/blog/serverless-open-source-frameworks-openfaas-knative-more/)
* [winderresearch.com: A Comparison of Serverless Frameworks for Kubernetes: OpenFaas, OpenWhisk, Fission, Kubeless and more](https://winderresearch.com/a-comparison-of-serverless-frameworks-for-kubernetes-openfaas-openwhisk-fission-kubeless-and-more/)
* [vshn.ch: A (Very!) Quick Comparison of Kubernetes Serverless Frameworks](https://vshn.ch/en/blog/a-very-quick-comparison-of-kubernetes-serverless-frameworks/)

### OpenFaaS
* [OpenFaaS](https://www.openfaas.com/)
* [itnext.io: Deploy your first Serverless Function to Kubernetes](https://itnext.io/deploy-your-first-serverless-function-to-kubernetes-232307f7b0a9)
* [magalix.com: Implementing FaaS in Kubernetes Using Kubeless](https://www.magalix.com/blog/implementing-faas-in-kubernetes-using-kubeless)
* [itnext.io: **arkade** by example — Kubernetes apps, the easy way 🌟](https://itnext.io/kubernetes-apps-the-easy-way-f06d9e5cad3c)
* [xenonstack.com: Serverless Architecture with OpenFaaS and Java](https://www.xenonstack.com/blog/serverless-openfaas-java/)
* [dzone: Getting Started with the OpenFaaS Kubernetes Operator on EKS 🌟](https://dzone.com/articles/getting-started-with-the-openfaas-kubernetes-opera)

### Knative
* [knative.dev](https://knative.dev/)
* [kn: knative client](https://github.com/knative/client) Knative developer experience, docs, reference Knative CLI implementation. The Knative client kn is your door to the Knative world. It allows you to create Knative resources interactively from the command line or from within Shell scripts.
* [redhat.com: What is knative?](https://www.redhat.com/en/topics/microservices/what-is-knative)
* [datacenterknowledge.com: Explaining Knative, the Project to Liberate Serverless from Cloud Giants](https://www.datacenterknowledge.com/open-source/explaining-knative-project-liberate-serverless-cloud-giants)

#### OpenShift Serverless with Knative
* [OpenShift Serverless](https://www.openshift.com/learn/topics/serverless)
* [developers.redhat.com: Build and deploy a serverless app with Camel K and Red Hat OpenShift Serverless 1.5.0 Tech Preview](https://developers.redhat.com/blog/2020/04/24/build-and-deploy-a-serverless-app-with-camel-k-and-red-hat-openshift-serverless-1-5-0-tech-preview/)
* [openshift.com: Why and When you need to consider OpenShift Serverless](https://www.openshift.com/blog/why-and-when-you-need-to-consider-openshift-serverless)

### Kubeless  
* [kubeless.io](https://kubeless.io/)
* [medium.com: Serverless - Build a Serverless Simple Flask Application with Kubeless on top of Kubernetes](https://medium.com/@peiruwang/serverless-build-a-serverless-simple-flask-application-with-kubeless-on-top-of-kubernetes-95c6682c3750)

### OpenWhisk
* [openwhisk.apache.org](https://openwhisk.apache.org/)

### Dapr Microservices Frameworks
- [Dapr](https://dapr.io/)
- [Building microservices? Give Dapr a try](https://www.infoworld.com/article/3604010/building-microservices-give-dapr-a-try.html) Microsoft’s open source, cross-platform microservices framework is ready for prime time at last.
- [versusmind.eu: Dapr - a serverless runtime for distributed applications 🌟](https://versusmind.eu/blog/dapr-a-serverless-runtime-for-distributed-applications)

## Popular Deployment Frameworks for AWS Lambda
* [lumigo.io: AWS Lambda Deployment Frameworks Compared](https://lumigo.io/blog/comparison-of-lambda-deployment-frameworks/)
* [thenewstack.io: Build a Serverless API with AWS Gateway and Lambda](https://thenewstack.io/build-a-serverless-api-with-aws-gateway-and-lambda/)

<center>
[![Serverless](images/from-monolith-to-serverless.jpg)](https://www.xenonstack.com/blog/serverless-openfaas-java/) 
</center>