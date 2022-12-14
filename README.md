# everest-k8s

- Contains k8s files to run everest system as a whole to run in a single node k8s cluster

  `kubectl apply -f ./
`

  `kubectl get all
`

- We can use port forwarding to access the apps using localhost. Alternatively, use the ip with appropriate external ports from the above command

  `minikube ip` => 192.168.64.7

  => http://192.168.64.7:34524/

- TBD: We can further enhance this setup by

  - enabling ingress for external routing
  - configure zipkin to run with k8s or exteernally

- TBD: Next we can also run the frontend within k8s with nginx web server
