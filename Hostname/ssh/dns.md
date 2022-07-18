> criado o hostname Atv14 com o seguinte comando:

````
$ hostnamectl set-hostname Atv14
````

> Para atender o requisito 3 da atividade foi executado os seguintes passos:

````
$ sudo service sshd start
$ chkconfig sshd on
$ systemctl enable sshd.service
````
> colocado como comentário o acesso ssh para root no arquivo /etc/ssh/sshd_config 

> inserido uma linha com o IP 10.0.2.1 e dns reysmysqllabcontainer no arquivo /etc/hosts

> inserido uma linha com o IP 10.0.2.2 e dns atividade14 no arquivo /etc/hosts da máquina da atividade docker.
