# Setup
This guide will walk you through the process of setting up the necessary cloud resources for the Cloud-Native Multicloud: Enabling Cross-Cloud Application Management project.

## Prerequisites
* An AWS account with access to Outposts
* An Azure account with access to Azure Arc
* A Google Cloud account with access to Anthos
## AWS Outposts
* Log in to the AWS Management Console
* Navigate to the Outposts service
* Create a new Outpost, specifying the necessary parameters such as the availability zone and the instance type.
* Connect your on-premises infrastructure to your Outpost
* Configure the Outpost to access other AWS services as needed.
## Azure Arc
* Log in to the Azure portal
* Navigate to the Azure Arc service
* Create a new Arc enabled Kubernetes cluster by specifying the necessary parameters such as the location, resource group, and the number of nodes.
* Connect your on-premises or multi-cloud infrastructure to your Arc enabled Kubernetes cluster
* Configure the Arc enabled Kubernetes cluster to access other Azure services as needed.
## Google Cloud Anthos
* Log in to the Google Cloud Console
* Navigate to the Anthos service
* Create a new Anthos cluster by specifying the necessary parameters such as the location, the number of nodes, and the cluster version.
* Connect your on-premises or multi-cloud infrastructure to your Anthos cluster
* Configure the Anthos cluster to access other Google Cloud services as needed.
## erify the setup
* verify that the necessary cloud resources have been created by checking the respective consoles
* Verify that you can access the resources and that they are in the correct state
* Verify that you can access the resources from your local machine
