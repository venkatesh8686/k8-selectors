#Selectors


Taint the node cmd:
---

kubectl taint nodes ip-192-168-13-190.ec2.internal hardware=gpu:NoSchedule

untaint:
---

kubectl taint nodes ip-192-168-13-190.ec2.internal hardware=gpu:NoSchedule-

tolerations:
--
- key: "key1"
  operator: "Equal"
  value: "value1"
  effect: "NoSchedule"

lebel node
---

kubectl label nodes ip-192-168-13-190.ec2.interna hardware=gpu
REF:
https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes/

