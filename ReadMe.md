kubectl get storageclass

secret generation => Imparative way

kubectl create secret generic <secret_name> --from-literal <key>=<value>
