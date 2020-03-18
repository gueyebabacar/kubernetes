# create pod 
kubectl create -f pod-definition.yml

# create replicat
kubectl create -f rc-definition.yml

# create replicaset
kubectl create -f rcset-definition.yml

# change replicat number 3 to 4
kubectl scale --replcat=4 -f rcset-definition.yml