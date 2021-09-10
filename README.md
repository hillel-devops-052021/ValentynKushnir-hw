# valetnynkushnir-hw

k8s hometask-01 milestones:
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
14.created svc_mongo.yml and created mongo service
15.formatted deployment_backend.yml and created backend deployment
16.formatted deployment_frontend.yml and created frontend deployment
17.added ingress
18.created service files for FE and BE, also created k8s services for these two
19.added ingresses manifests for FE and BE, and created ingresses themselves
20.added service,deployment and ingress for mongo admin access
21.changed API_ROOT to read from environment varialbe

k8s hometask-02 milestones:
1. installed ingress and csi addons
2. copied mongo manifests under mongo/templates directory
3. created k8s ingredients pv, pvs, pods for mongo, upgraded release
4. copied backend manifests under realworld-be/templates directory
5. created k8s ingredients deployment, service, ingress for backend
6. copied frontend manifests under realworld-fe/templates directory
7. created k8s ingredients deployment, service, ingress for frontend
8. added backend and frontend dependencies in Chart.yaml file
9. removed automatically added .tgz archives
10.added dependency on mongo to backend Chart.yaml
