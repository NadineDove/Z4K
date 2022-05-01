# Supported Platforms

Zerto for Kubernetes can be deployed on multiple Kubernetes platforms.

| Platform                             | Version  |Notes |
| ------------------------------------ |--|------ |
| Amazon Elastic Kubernetes Service (Amazon EKS)|  |    |
| Azure Kubernetes Service (AKS)|   |    |
| Google Kubernetes Engine (GKE)|    | COS nodes are not supported. And therefore, Autopilot deployment is not supported.|  |
| Red Hat OpenShift |   | Zerto for Kubernetes supports from OpenShift version 4.6 or higher.|  |
| IBM Cloud Kubernetes Service (IKS) |  |    |
| VMware Tanzu  | VMware 6.7 | Supported in combination with Rook, from VMware ??? and onwards full native support. |
|   | VMware 7.0u2 | Kubernetes 1.19.9\1.20.5 or higher (CSI Block device support) on top of Tanzu Kubernetes Grid (TKG) |
|   | Kubernetes 1.19.9\1.20.5 or higher | CSI Block device support on top of Tanzu Kubernetes Grid (TKG)  |
| Oracle Container Engine for Kubernetes (OKE) |   |Supported in combination with Rook. ||

## Services

| Platform                             | Notes |
| ------------------------------------ |------ |
| Amazon Elastic Kubernetes Service (Amazon EKS)| Full support.  |
| Azure Kubernetes Service (AKS)|Full support.  |                                                                                    |
| IBM Cloud Kubernetes Service (IKS)| Full support.  |

## Engines

| Platform                             | Notes |
| ------------------------------------ |------ |
| Google Kubernetes Engine (GKE)| COS nodes are not supported. And therefore, Autopilot deployment is not supported.| 
| Red Hat OpenShift | Zerto for Kubernetes only supports OpenShift version 4.6 or higher.|Full support.  |
| Oracle Container Engine for Kubernetes (OKE)|Supported in combination with Rook. |Full support.   |

## VMware

| Platform                             | Version  |Notes |
| ------------------------------------ |--|------ |
| VMware Tanzu  | VMware 6.7 | Supported in combination with Rook, from VMware ??? and onwards full native support. |
|   | VMware 7.0u2 |Kubernetes 1.19.9\1.20.5 or higher (CSI Block device support) on top of Tanzu Kubernetes Grid (TKG).  |
|   | Kubernetes 1.19.9\1.20.5 or higher | CSI Block device support on top of Tanzu Kubernetes Grid (TKG). |
