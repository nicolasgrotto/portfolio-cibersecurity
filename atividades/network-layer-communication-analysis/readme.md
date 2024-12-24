# Análisar a comunicação na camada de rede

## Arquivos

- tcpdump analysis é a foto dos pacotes de dados capturados.
- cibersecurity incident report é a análise do incidente com base nos pacotes de dados capturados.

## Essa atividade foi desenvolvida com uma história fictícia 

Você é um analista de segurança cibernética que trabalha em uma empresa especializada em fornecer serviços de TI para clientes. Vários clientes relataram que não conseguiram acessar o site da empresa e viram o erro "porta de destino inalcançável" depois de esperar que a página fosse carregada.


- Erro Inicial: Ao tentar acessar um site, ocorreu o erro "destination port unreachable" (porta de destino inalcançável).
- Análise com tcpdump: Foi utilizada a ferramenta tcpdump para capturar e analisar os pacotes de rede enquanto a página era carregada.
  
Fluxo do Problema:

1. O navegador enviou uma consulta DNS via protocolo UDP para recuperar o endereço IP associado ao nome de domínio do site.
2. O servidor DNS respondeu com um pacote ICMP contendo a mensagem de erro: "porta UDP 53 inacessível".

## Objetivo

Com os pacotes de dados capturados usando uma ferramenta de análise de rede, sua tarefa é identificar qual protocolo de rede e serviço foram afetados por esse incidente. Em seguida, você precisará escrever um relatório de acompanhamento.
