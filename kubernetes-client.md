# Kubernetes-client on mac

How to install kubernetes client on the mac

## Steps

1) Install cfssl using mac package manager called homebrew

   ```brew install cfssl```
   
2) Get kubectl using curl

    ```curl -o kubectl https://storage.googleapis.com/kubernetes-release/release/v1.12.0/bin/darwin/amd64/kubectl```

3) change the permission on the file

    ```chmod +x kubectl```
    
4) Move the file to the /usr/local/bin/

    ```sudo mv kubectl /usr/local/bin/```
    
5) Installation is done please verifiy both of them is installed

    ```cfssl version```
    
    ```kubectl version --client```
