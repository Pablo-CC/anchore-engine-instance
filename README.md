# Anchore Engine instance

## TL;DR
```
git clone https://github.com/Pablo-CC/anchore-engine-instance.git
kubectl apply -f persistentVolume.yaml
helm install --name=anchore stable/anchore-engine -f values.yaml
```
