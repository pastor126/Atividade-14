> Seguindo o item 1 e obedendo os itens 4 e 5, segue aqui a descrição detalhada da instalação da VM Oracle Linux:
> Abrindo o VirtualBox como administrador clicamos em NOVO e irá abrir uma janela onde vamos inserir o nome da máquina e o sistema operacional.

<div>
  <img src="https://user-images.githubusercontent.com/108673073/179530069-ad83fc09-8ec0-47e3-acce-5e4e4dd83715.png" width=40%/>
  </div>
  
> Na sequência basta ir inserindo os dados pedidos em cada caixa de diálogo conforme a necessidade. No caso selecionei 2993M de RAM e criei um disc image dinamicamente alocado de 41GB.
> Criado a máquina dei início e selecionei a pasta onde esta a iso do OracleLinux-R8-U6-x86_64-dvd.
> Agora defini as características e parâmetros:

<div>
  <img src="https://user-images.githubusercontent.com/108673073/179544247-809b6bbb-795a-480e-9eff-de3be4f3eb54.png" width=35% />
  </div>
  
 >   -Keyboard / portuguese;

 >   -Selecionado o disco virtual;

 >   -Root Password;
   
 >   -Usuário e senha (selecionando como administrador para ser possível o SUDO)  
   
 >   -Seleção de software / Minimal Install com os pacotes exceto "Scientific Support" e "Smart Card Support";

 >   -Em Network ligar a Ethernet (enp0s3).

 >   -Begin Installation

> Funcionando a VM e logando fiz o Update:
````
$ sudo dnf update
````

 > Agora a instalação do sistema operacional ORACLE LINUX está completa e atualizada o próximo passo são as configurações propostas na atividade.
