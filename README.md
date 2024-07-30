# Custom_Resource_Definition
Go to this URL: https://github.com/nidhishabraham/Custom_Resource_Definition.git

kubectl apply -f ./crd.yaml

Once the CRD is registered, verify it by running the kubectl get crds command. Alternatively, you can use kubectl api-resources | grep myplatform to check. 🔍

Creating the custom resources
kubectl apply -f ./cr.yaml

kubectl get myp
