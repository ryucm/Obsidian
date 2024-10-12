-  워커 노드와 상호 작용하여 Pod를 생성 및 삭제를 한다.
# Kube-API-Server
- 워커와 마스터 노드 간 통신을 담당한다.

# ETCD

# Kube-Scheduler
- Pod를 관찰하며 워커 노드에게 어떤 일을 수행할 지에 대해 알린다.

# Kube-controller-manager
- 워커 노드 전체를 감시하고 제어하며 적당한 수의 Pod를 가동 중에 있는지 확인한다.
- Scheduler와 API server와 긴밀하게 연동한다.

# Cloud-Controller-Manager
- Cloud Provider(AWS, GCP, Azure)에 따라 다르다.