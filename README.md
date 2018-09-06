# eca-draft

Prerequisites:

- Oracle Cloud Account (DevCS, OCIR, OKE)
  - DevCS
  - OCIR
  - OKE - Microservices platform installed

Scenario:

- [Designing an API](tutorials/design.api.md)
- [Define a DevCS Project and add members and issues to a sprint](tutorials/DevCS.md)
- Add a git repository to your project - use this repository as source repository.
- [Create container repository using Oracle Cloud Infrastructure Registry to store container packaged services (V1, V2)](devcs.build.jobs.md#1-create-container-repository-using-oracle-cloud-infrastructure-registry-to-store-container-packaged-services)
- [Create build job to package service V1 in container and push to container registry](devcs.build.jobs.md#2-create-build-job-to-package-service-v1-in-container-and-push-to-container-registry)
- [Deploy service V1 to Microservices platform and test](devcs.build.jobs.md#3-deploy-service-v1-to-microservices-platform-and-test)
- [Create build job to package service V2 in container and push to container registry](devcs.build.jobs.md#4-create-build-job-to-package-service-v2-in-container-and-push-to-container-registry)
- [Deploy service V2 to Microservices platform](devcs.build.jobs.md#5-deploy-service-v2-to-microservices-platform)
- [Check that service is still being served fully by V1](devcs.build.jobs.md#6-check-that-service-is-still-being-served-fully-by-v1)
- [Change the Istio rule to define canary deployment and define traffic percentages as 50/50 and check that half of the requests are being served by V1 and half by V2](devcs.build.jobs.md#7-change-the-istio-rule-to-define-canary-deployment-and-define-traffic-percentages-as-5050-and-check-that-half-of-the-requests-are-being-served-by-v1-and-half-by-v2)
- [Change the Istio rule to define canary deployment and define traffic percentages as 0/100 and check that all requests are being served by V2](devcs.build.jobs.md#8-change-the-istio-rule-to-define-canary-deployment-and-define-traffic-percentages-as-0100-and-check-that-all-requests-are-being-served-by-v2)
- [Creating an API Policy Implementation](tutorials/create.api.md)
- [Deploy API](tutorials/deploy.api.md)
