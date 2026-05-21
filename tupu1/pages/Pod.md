## Purpose

Smallest deployable unit in Kubernetes.
- ## Related
- [[Deployment]]
- [[Service]]
- [[Container]]
- [[Node]]
- ## Lifecycle
- Pending
- Running
- Succeeded
- Failed
- Unknown
- ## Common Issues
- [[CrashLoopBackOff]]
- [[Evicted]]
- [[ImagePullBackOff]]
- ## Useful Commands
  
  ```bash
  kubectl get pods -A
  
  kubectl describe pod <pod>
  
  kubectl logs <pod>
  
  kubectl exec -it <pod> -- sh