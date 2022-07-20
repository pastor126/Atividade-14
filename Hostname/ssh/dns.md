> criado o hostname Atv14 com o seguinte comando:

````
$ hostnamectl set-hostname Atv14
````

> Para atender o requisito 3 da atividade foi executado os seguintes passos:

````
$ sudo service sshd start
$ chkconfig sshd on
$ systemctl enable sshd.service
`````

> Para o acesso sem a necessidade de senha, criando assim uma relação de confiança entre as VMs, foi criado uma chave pública e uma privada. A chave pública foi copiada e enviada para a outra máquina. O processo foi feito nas duas máquinas com os seguintes comandos:


`````
$ ssh-keygen -b 4096

`````

`````
$ scp id_rsa.pub (usuário)@(IP):~/.ssh/authorized_keys
`````



> Obs.: Outras máquinas só podem acessar via ssh com login e senha.


> colocado como comentário o acesso ssh para root no arquivo /etc/ssh/sshd_config 

> inserido uma linha com o IP 10.0.2.1 e dns reysmysqllabcontainer no arquivo /etc/hosts

> inserido uma linha com o IP 10.0.2.2 e dns atividade14 no arquivo /etc/hosts da máquina da atividade docker.
