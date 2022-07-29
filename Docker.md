# Instalação do Docker #

> O docker foi instalado e habilitado com os seguintes comandos:

````
$ sudo dnf install –y dnf-utils zip unzip
$ sudo dnf config-manager –-add- repo= https : // download.docker.com/linux/centos/docker-ce.repo
$ sudo dnf install –y docker-ce --nobest --allowerasing
````

````
$ systemctl enable docker.service
$ systemctl start docker.service
$ systemctl status docker.service
````

