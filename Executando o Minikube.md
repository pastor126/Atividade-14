> Ao tentar rodar o Minikube foi apresentado o seguinte erro:

> ![Captura minikube --force](https://user-images.githubusercontent.com/108673073/181839289-e9d0f37e-04d5-48fa-b07b-940a7bcc2f67.jpg)

> Para resolver foi copiado a chave primária id_rsa para o diretório /root/.minikube/machines/minikube

> Depois foi adequado a permissão da chave:

````
# chmod 644 id_rsa
````
> Ainda assim apresentou erro e o sistema sugeriu o seguinte comando:

````
$ sudo sysctl fs.protected_regular=0
````
> Depois executei o minikube com sucesso:

````
$ sudo minikube start --container-runtime=docker --force
````
<br>
