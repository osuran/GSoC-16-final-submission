# GSoC-16-final-submission

My proposal for [Cloud] Native Cloud Support for Running WSO2 Middleware on Microsoft Azure was selected for Google Summer of Code 2016. I worked with the organization WSO2 under the mentorship of Imesh Gunaratne and Isuru Haththotuwa. Following is the project description.

##Description


WSO2 middleware can be deployed on Microsoft Azure either using virtual machines or containers. In this project will focus on Virtual Machine approach as container support is still primitive on Azure (except for running Kubernetes on Azure). To do this we need implement a Carbon Membership Scheme for providing automatic cluster discovery similar to Kubernetes Membership Scheme.
In addition, we need to demonstrate how following areas would work on Microsoft Azure with native Azure features:


* Auto healing
* Autoscaling
* Automatic cluster discovery
* Dynamic load balancing
* VM/Container support
* Multi-tenancy
* Configuration orchestration
* Artifact distribution
* Software update distribution
* Multi-region/cloud deployments
* Centralized logging
* Monitoring
* Metering

##Deliverables 


* Carbon Membership Scheme for Microsoft Azure
* Artifacts needed for deploying WSO2 products on Microsoft Azure
* A document explaining steps for deploying WSO2 products on Microsoft Azure

##Completed tasks

* Carbon Membership Scheme for Microsoft Azure
* Documentation of how to deploy Carbon membership scheme on azure.
* Documentation on how WSO2 products can be deployed with 

            1) Auto scaling, 
            2) Centralized logging
            3) Automatic cluster discovery, 
            4) Dynamic load balancing, 
            5) Monitoring 
      in Azure

##Tasks yet to be completed

* Artifacts needed for deploying WSO2 products on Microsoft Azure

##Github repositories I worked on,

* [Azure Membership Scheme](https://github.com/osuran/azure-membership-scheme)
* [Azure Artifacts](https://github.com/osuran/azure-artifacts)
* [Auto Scaling template](https://github.com/osuran/Azure-templates)

##Links to list of commits

* [https://github.com/osuran/azure-membership-scheme/commits/master](https://github.com/osuran/azure-membership-scheme/commits/master)
* [https://github.com/osuran/azure-artifacts/commits/master](https://github.com/osuran/azure-artifacts/commits/master)
* [https://github.com/osuran/Azure-templates/commits/master](https://github.com/osuran/Azure-templates/commits/master)

##Link to the PR on wso2-incubator

* [https://github.com/wso2-incubator/azure-artifacts/pull/1/commits](https://github.com/wso2-incubator/azure-artifacts/pull/1/commits)

##Link to the blog post where documentation on Auto scaling, Centralized logging, Automatic cluster discovery, Dynamic load balancing, Monitoring and Carbon Membership Scheme fro Azure can be found

* [https://osuran.blogspot.com/](https://osuran.blogspot.com/)

##Conclusion

It was a great experience working for four months in my GSoC project under WSO2. I sincerely thank my mentors Imesh Gunaratne and Isuru Haththotuwa and others in the community for their support. Thanks Google and WSO2 for giving me this opportunity. 
