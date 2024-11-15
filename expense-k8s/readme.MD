# k8s HPA

**vertical vs horizontal scaling**

**To implement and work with Horizontal Pod Autoscaler (HPA) in Kubernetes, below are the key steps required:**

* Set Up Metrics Server
* Create a Deployment with CPU/memory requests and limits
* Define and apply HPA configuration
* Verify HPA status
* Test HPA scaling by applying load
* Monitor scaling events and HPA behavior.

**Install Metrics server**

```
kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml
```

**Install k9s for monitoring with UI**

```
curl -sS https://webinstall.dev/k9s | bash
```
