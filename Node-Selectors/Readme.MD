# taint and untaint the node

## taint
```
kubectl taint nodes <node-name> key=value:NoSchedule
```

Ex.
```
kubectl taint nodes ip-192-168-44-187.ec2.internal hardware=gpu:NoSchedule
```

## untaint
```
kubectl taint nodes <node-name> key=value:NoSchedule-
```

Ex.
```
kubectl taint nodes ip-192-168-44-187.ec2.internal hardware=gpu:NoSchedule-
```

## label node
```
kubectl label nodes <node-name> key=value
```
Ex.
```
kubectl label nodes ip-192-168-44-187.ec2.internal hardware=gpu
```