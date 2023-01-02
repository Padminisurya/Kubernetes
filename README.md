# Kubernetes
Kubernetes definition files


Command to run the definition file
------------------------------------------
kubectl create -f pod-definition1.yml

To get the list of pods
---------------------------
kubectl get pods

To get the list of pods along with IP address  and which node the pod is running
---------------------------
kubectl get pods -o wide  

To delete the pod created from the above file
---------------------
kubectl delete -f  pod-definition1.yml
