**Docker** (~4 YOE - Jan 2026)

1. Difference between CMD entrypoint

2. Docker lifecycle

3. Types of docker networking and what is the default one, explain

4. How to reduce the docker image size, rather than using distroless images and multi stage builds

5. Write a docker file
6. What commands you used in your docker file?
7. How one docker container communicate with other?
8. Once the docker is created it's exciting immediately, and running successfully in local but when you try to run as container it's failing. how do you troubleshoot?
9. Specific container is consuming more cpu, How do you limit the docker container resources consumption?
10. When you'll use multi stage docker files?
11. Your container is running but the application running inside the container is not accessible. What might be the reason and how to troubleshoot?
12. Container is started and running but not showing logs, how do you troubleshoot?
13. Where do you access the docker logs?
14. How do you attach docker volume to a container?
15. Docker is consuming more disk, how do you reduce the disk consumption by docker
16. How do you remove unwanted docker images, and what that command will do?
17. What command used to remove images?
18. What is the need of docker volumes?
19. How to deploy prod app using docker?

---


**Docker-Compose** (~4 YOE - Jan 2026)
1. Diff b/w docker & docker compose?
2. How you use docker compose to scale the services?


---
**Kubernetes** (~4 YOE - Jan 2026)



1. Types of deployment strategies, explain. Stretched on blue green deployment

2. If we can access app using pod ip, why we need service

3. Write a rolling update deployment file.

4. What is maxUnavailable and maxSurge in deployment

5. What is taint and tolerance

6. What is pv and pvc, explain

7. What is liveliness probe, readiness probe and startup probe, explain all
8. What is the architecture of k8s and diff b/w deployments and statefulsets
9. Scenario. You’re pods are going to pending state/crashloop back error, how do you resolve it
10. How you monitor pod health
11. Pod is utilising high CPU, what are your next steps
12. Where we’ll give the resource quota for pods
13. what are HPA & VPA, are you using it? explain
14. Difference b/w CMD & Entrypoint
15. diff b/w add & copy
16. Have you setup RBAC in k8s
17. Have you used csi driver in k8s, what is it used for
18. Explain types of services in k8s?
19. How to access node port service
20. External name service is used for?
21. How do you scale your eks workload if there is heavy traffic?
22. Based on what metrics hpa will scale?
23. If there is a service which having heavy workload and there is another service which have very minimal workload. In this case how you're eks cluster look like? Do you provision both the services in same node or different nodes?
24. How you're using helm?
25. How you configure eks cluster for high availability?
26. How and where do you define if the traffic for specific path should route to specific set of pods
27. What are your next steps for crashloopbackoff and pending status to resolve and why we get these errors
28. How do you create node groups?
29. How you’re handling EKS upgrades?
30. Explain core components of k8s?
31. Explain namespaces & usecases?
32. Explaining k8s autoscaling & the types?
33. How you perform rolling updates?
34. What happens to the pod, if we assigned the resource limits and it’s going beyond limits?
35. How ingress works?
36. How you rate yourself in k8s?
37. Diff b/w nodes & pods?
38. You deployed app in prod and pods restarting continuously, how you troubleshoot. Even after roll back it’s not working, the app team is saying everything is good from there side and it’s infra issue only. How do you troubleshoot?
39. What is the role of ingress & egress in k8s?
40. What is replica set?
41. DIff b/w liveliness and readiness probe?
42. DIff b/w deploy, stateful set & replica set?
