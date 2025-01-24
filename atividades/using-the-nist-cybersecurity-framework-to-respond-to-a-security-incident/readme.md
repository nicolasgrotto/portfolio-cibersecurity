# Usar o Framework de Cibersegurança NIST para responder a um incidente de segurança

## Arquivos

- Incident report analysis: é o relatório completo que contém um plano de melhoria da segurança de rede.

## Essa atividade foi desenvolvida com base em uma empresa e cenário fictício.

Você é um analista de segurança cibernética e trabalha para uma empresa de multimídia que oferece serviços para pequenas empresas. Sua organização sofreu recentemente um ataque DDoS, que comprometeu a rede interna por duas horas até ser resolvido.

Durante o ataque, os serviços de rede de sua organização pararam de responder repentinamente devido a um fluxo de entrada de pacotes ICMP. O tráfego normal da rede interna não conseguia acessar nenhum recurso da rede. A equipe de gerenciamento de incidentes respondeu bloqueando a entrada de pacotes ICMP, interrompendo todos os serviços de rede não críticos off-line e restaurando os serviços de rede críticos.

Em seguida, a equipe de segurança cibernética da empresa investigou o evento de segurança. Eles descobriram que um agente mal-intencionado havia enviado um ataque flood de pings ICMP para a rede da empresa por meio de um firewall não configurado. Essa vulnerabilidade permitiu que o invasor mal-intencionado sobrecarregasse a rede da empresa por meio de um ataque distribuído de negação de serviço (DDoS).

Para resolver esse evento de segurança, a equipe de segurança de rede implementou:

  - Uma nova regra de firewall para limitar a taxa de entrada de pacotes ICMP

  - Verificação do endereço IP de origem no firewall para verificar se há endereços IP falsos nos pacotes ICMP recebidos

  - Software de monitoramento de rede para detectar padrões de tráfego anormais

  - Um sistema IDS/IPS para filtrar algum tráfego ICMP com base em características suspeitas

## Objetivo Principal

Como analista de segurança cibernética, você tem a tarefa de usar esse evento de segurança para criar um plano para melhorar a segurança de rede da sua empresa, seguindo a Estrutura de Segurança Cibernética (CSF) do Instituto Nacional de Padrões e Tecnologia (NIST).


