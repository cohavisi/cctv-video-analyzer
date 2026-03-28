** overview **
this project will implement "cctv video analyzer" - it main purpose is to monitor cctv stream
and recored human and car details:
 - human: faces, height, velocity and sound.
 - vehicle: license plate, color, model.

implementation instructions:
this project will be composed out of multiple services:
 - frontend: implement with react or other popular language.
 - backend: 1 service (or more), impelment with python/golang (or other according to suggestion)
 - all services will be containerize and will be able to be tested via docker-compose.
 - all services will be k8s deployments (helm charts) and will be able to be tested on minikube.

technical details:
  - cctv system can be access via the local network: camera stream/synology survilance system.
  - databse can be sql or non-sql according to best practice.
  - storage can be NAS server or Azure Storage.