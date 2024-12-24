# Analisar ataques à rede de computadores

## Arquivos

- wireshark tcp_http log é o arquivo que contém os registros gerados pelo wireshark.
- Cibersecurity incident report é a análise feita sobre o incidente.

## Essa atividade foi feita com um cenário fictício

Você trabalha como analista de segurança em uma agência de publicidade que anuncia vendas e promoções no site da empresa. Os funcionários da empresa acessam regularmente a página de vendas da empresa na Web para pesquisar pacotes de férias que seus clientes possam gostar.

Certa tarde, você recebe um alerta automático do seu sistema de monitoramento indicando um problema com o servidor da Web. Você tenta visitar o site da empresa, mas recebe uma mensagem de erro de Pausa na conexão em seu navegador.

Você usa um sniffer de pacotes para capturar pacotes de dados em trânsito de e para o servidor da Web. Você percebe um grande número de solicitações TCP SYN provenientes de um endereço IP desconhecido. O servidor da Web parece estar sobrecarregado pelo volume do tráfego de entrada e está perdendo a capacidade de responder ao número anormalmente grande de solicitações SYN. Você suspeita que o servidor esteja sendo atacado por um agente mal-intencionado. 

Você coloca o servidor temporariamente off-line para que a máquina possa se recuperar e voltar ao status operacional normal. Você também configura o firewall da empresa para bloquear o endereço IP que estava enviando o número anormal de solicitações SYN. Você sabe que sua solução de bloqueio de IP não durará muito, pois um ataque pode spoofing outros endereços IP para contornar esse bloqueio. Você precisa alertar seu gerente sobre esse problema rapidamente e discutir as próximas etapas para deter esse atacante e evitar que esse problema ocorra novamente. Você precisará estar preparado para contar ao seu chefe sobre o tipo de ataque que descobriu e como ele estava afetando o servidor da Web e os funcionários.

## Objetivo

Nesta atividade, foi feita uma análise de um cenário que envolve um cliente da empresa que enfrenta um Problema de segurança ao acessar o site da empresa. A causa provável da interrupção do serviço terá que ser identificada. Haverá uma explicação de como ocorreu o ataque e o impacto negativo que ele teve no site. 
