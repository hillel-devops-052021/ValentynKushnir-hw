# valetnynkushnir-hw

k8s hometask milestones:
1. installed Hyper-Kit on my MacOS computer
2. installed the latest kubectl (version 1.21.2)
3. spinned up two clusters ("first-cluster" and "second-cluster")
4. checked namespaces, roles cluster roles.
	* there were no roles in default namespace because we have created none so far. But you may ask why there were no roles by default? well, perhaps because we haven't created a single service yet to which we'd like to give access
5. checked roles in cluster kube-system
6. removed second-cluster
7. copied previous project from root to k8s directory
8. renamed old FE Dockerfile and created new Dockerfile
9. built new FE image and pushed to docker hub
10.created FE and BE deployment files
11.added CSI addon
12.created PVC and statefulset for mongo
13.edited statefulset_mongo.yml file and created statefulset
