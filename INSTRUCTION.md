To validate if app is running you shoud use command:
kubectl get pods -n todoapp
and after this you should watch on the pods status
To check if secret and configmap is mounted in pod, you should connect to pod and use ls command