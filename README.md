# K8S-Task

1. "cronjob.yaml" file will run uname command in a single busybox container by using bahs script. 
The command will run every minute and complete within 10 seconds or it will be terminated by Kubernetes.

2. "myapp.yaml" file:   pod have 4 containers using nginx, redis, memchached and consul images.

3. "rediska.yaml" file will create a pod from redis image, running in web namesapces and listening port 9090.

4. "test.yaml" file create a pod in test namespace and set resource limit to 1Gi of memory and 200m CPU.
