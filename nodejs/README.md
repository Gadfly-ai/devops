# MongoDB & Nodejs


## Create a Deployment


```
kubectl create -f ./mongo-persistent-volume.yml
```

## Add a persistent volume claim



```
kubectl create -f ./mongo-persistent-volume-claim.yml
```

## Create a MongoDB deployment

```
kubectl create -f ./mongo-deployment.yml
```

## Running MongoDB Service


```
kubectl create -f ./mongo-service.yml
```

## Create a Node.js deployment

```
kubectl create -f ./node-deployment.yml
```


