# Laboratorio Básico de duas redes de provedores.

Rede do provedor Forum Telecom e Sardinha Telecom.

Dois provedores, duas redes distintas com intuito de conectar a matriz com a filial. Foram designados IP's /30 para os dois provedores. Os clientes se conectam a partir de um servidor PPPoe configurado nos RB que levam link para os clientes.
Também foi feito uma VPN através do EOIP Tunnel com roteamento estático para as VPN do Mercado Matriz e Filial, utilizando um RB de Gambiarra para obterem rota, pois devido ao laboratorio ser virtualizado não teria como utilizar um IP Público.

Uma rede simples, mas aonde foi possível aplicar conhecimentos da primeira parte do curso de Analista de Redes do Forum Telecom, como Configuração de IP estático no Mikrotik, servidor DHCP, NAT, SNTP Client, VPN, PPPoe e Client PPPoe, Roteamento estático, DNS, Acesso aos RB da rede através do RoMON, aplicação de redudância e aplicação dos usuários PPPoe via terminal no MK dos clientes.

Um treinamento básico, entretanto aonde colocamos em prática o roteamento estático e entendemos como é complexo a administração de uma rede, onde cada RB/Router é importante estar devidamente configurado para não afetar a rede de um cliente.

No segundo passo será aplicado conceitos de OSPF para otimizar o roteamento e a administração da rede. Top!
