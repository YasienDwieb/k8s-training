# k8s-training
### To run this example project:

1. Create the `secret` component as it would be used by both MongoDB and MongoDB-express `deployments`.\
  `$ kubectl apply -f mongodb-secret.yaml`
  
2. Create MongoDB `deployment`.\
  `$ kubectl apply -f mongodb-deployment.yaml`

3. Create MongoDB `configmap` component as it would be used by MongoDB-express `deployment`.\
  `$ kubectl apply -f mongodb-configmap.yaml`

4. Create MongoDB-express `deployment`.\
  `$ kubectl apply -f mongodb-express-deployment.yaml`
