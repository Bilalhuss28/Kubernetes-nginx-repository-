This configuration will create a Deployment named “hello-world” with pods labeled “app: hello-world”, expose the nginx service inside and outside the cluster on the specified ports, and configure nginx to respond with “Hello, world!” to HTTP requests. 

To apply them to your kubernetes cluster run this for each file
# kubectl apply -f Deployment.yaml
# kubectl apply -f Service.yaml
# kubectl apply -f ConfigMap.yaml
