PART 4 EKS DEMO IS AVAILABLE AT THE FOLLOWING LINK: 



Parts 1-8 (not including 4) are in our files below and this describes each one:

**todoapp.yaml**

All deployment information for the flask app and pod. This includes prometheus, probes setup, replication, and rolling update strategy

**mongodb.yaml**
All deployment information for the mongodb app and pod. This includes replication, probes, and rolling update strategy

**todoapp-svc.yaml**

Service for our flask app

**mongo-pvc.yaml**

PVC creation for mongodb to work

**mongodb-svc.yaml**

Service for our MongoDB app

**docker-compose.yml**

Docker Compose File for Part 3

**todo-prometheus.yaml**

Config Map for Prometheus

**todo-prometheus-svc.yaml**

Service for Prometheus to Monitor

**AlertManagerConfig.yaml**

Config for AlertManager


**AlertTemplateConfigMap.yaml**

Config for AlertManagerTemplate Response

**deployment.yaml**

Deployment for AlertManager


**alert-service.yaml**

Service for AlertManager


**Dockerfile**

Docker file used to build the todoapp image called alfonsolv3/flask-v2





