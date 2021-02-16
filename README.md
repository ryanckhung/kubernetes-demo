Reference:
https://cwhu.medium.com/kubernetes-basic-concept-tutorial-e033e3504ec0


Command:

create pods with nginx
> kubectl run nginx --image=nginx

Check Pods Details
> kubectl get pods
/ kubectl get pods -o wide
/ kubectl describe pod <pod-name>
  
delete pods
> kubectl delete pod <pod-name>
  
Update Pods
Update the pod-definition file and use 'kubectl apply' command or use 'kubectl edit pod <pod-name>' command.
  
  
Get Number of Nodes
> kubectl get nodes
/ kubectl get nodes -o wide (show more details)
