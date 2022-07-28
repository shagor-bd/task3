## Highly available microservices architecture deployment on-premise or in the cloud

![how-to-auto-deploy-a-multi-nodes-highly-available-kubernetes-cluster-Architecture](https://user-images.githubusercontent.com/90903877/181618073-9a277962-16fc-4796-91b7-db3a050b6ff6.png)

As we can see from the image hear we have 3 master node which  actually ensure cluster high availability and if we check the worker node it will ensure application level high availability. We can add more worker, so this cluster is scalable. For make the cluster fault tolerance we must configure another K8s cluster in separate zone or region.  

Recovery we may configure the container backup with the help of container backup application.

For logging we can us flunted (as demon set) and Elasticsearch and Kibana for graphical view.  And alerting we can use Prometheus.

Now a days cloud gives us highly available using multiple zones, region concept. Also highly scalable, fault tolerant also with so many features. If we consider e-commerce, telecom and ride sharing we may consider cloud. It reduces our cost. Also, its very much flexible for resource increase and decrease.

