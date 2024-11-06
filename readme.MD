kubectl taint nodes ip-192-168-34-152.ec2.internal project=expense:NoSchedule-
kubectl label nodes ip-192-168-34-152.ec2.internal project=expense

kubectl taint nodes ip-192-168-34-152.ec2.internal hardware=gpu:NoSchedule-

ip-192-168-61-104.ec2.internal

kubectl taint nodes ip-192-168-61-104.ec2.internal project=roboshop:NoExecute-
kubectl label nodes ip-192-168-61-104.ec2.internal project=roboshop