# 13th Meetup With Adi Polak: Bursty Workload - Cutting Cost in K8s

In the 13th edition of DevOps Kathmandu meetup, Adi Polak talked about Virtual Kubelet and Azure Container Instances by the help of which we can leverage the scalability of Kubernetes and cost efficiency.

## Event Date and Time
16th July, 17:00 Nepal Time on Google Meet

## Meetup
https://www.meetup.com/DevOps-Kathmandu/events/271694045/

## Youtube Recording
https://www.youtube.com/watch?v=0lrbid0ODG4

## Learning resources:
* [Kubernetes and Virtual Kubelet in a nutshell](https://dev.to/adipolak/kubernetes-and-virtual-kubelet-in-a-nutshell-gn4)
* [Netflix implementation of virtual kubelet](https://www.youtube.com/watch?v=eFnDwwckrKU)
* [Virtual Kubelet (Git Repo)](https://github.com/virtual-kubelet/virtual-kubelet)
* [Virtual Kubelet Turns 1.0 — Deep Dive](https://medium.com/microsoftazure/virtual-kubelet-turns-1-0-deep-dive-b64056061b18)

## Queries and Discussion:
1. Is virtual kublet is  integrated as a built-in type in Azure, what options are there for other providers (AWS,GCloud)? 
2. Is it possible to specify machine type like storage size, ssd, gpu
2. Unlike azure and aws, spot instance grace shutdown period in GCP is just 30 seconds, so using spot instances may not be a good option to reduce k8s cost in case of GCP, what are your thoughts on this?
3. How virtual kublets are cost wise? To be able to deploy it fast - should resources be reserved?

**(Grab more from discussion area: http://bit.ly/devops-kathmandu-area)**
