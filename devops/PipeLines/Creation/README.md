# ������
�ο��ű�
## k8s
helm delete --purge microservice.autodevopspipeline.v1
kubectl delete namespace microservice-autodevopspipeline-v1

## gateway
delete FROM routes where created_at>'2019-01-10';
delete FROM services where created_at>'2019-01-10';