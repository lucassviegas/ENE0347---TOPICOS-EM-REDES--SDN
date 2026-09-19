# ENE0347 — Tópicos em Redes: SDN

Repositório com os relatórios dos experimentos práticos da disciplina **ENE0347 — Tópicos em Redes (SDN)**, cursada na Universidade de Brasília (UnB).

Os experimentos exploram conceitos e ferramentas de **Redes Definidas por Software (SDN)** em ambiente emulado com **Mininet**, cobrindo controladoras como **POX** e **Ryu**, protocolo **OpenFlow**, análise de tráfego e desempenho de rede.

## Experimentos

| Experimento | Tema |
|---|---|
| [01 — Ferramentas](experimento-01-ferramentas/README.md) | Ferramentas de análise e monitoramento de redes no Mininet (Wireshark, Iperf, Tcpdump) |
| [03 — Módulos Python/Mininet](experimento-03/README.md) | Módulos e comandos internos do Mininet |
| [04 — Topologias e Comutação](experimento-04/README.md) | Configuração e análise de topologias, comutação e roteamento em SDN |
| [04A — Topologias em Árvore](experimento-04a/README.md) | Construção de topologias em árvore no Mininet |
| [05 — Controlador POX](experimento-05/README.md) | Funcionamento do controlador POX e seus módulos |
| [06 — Spanning Tree (STP)](experimento-06/README.md) | Protocolo Spanning Tree com a controladora Ryu |
| [07/08 — Roteador SDN (Ryu)](experimento-07-08/README.md) | Roteamento avançado com `ryu.app.rest_router` |
| [09 — Firewall SDN (Ryu)](experimento-09/README.md) | Módulo de firewall com `ryu.app.rest_firewall` |
| [Trabalho Final](trabalho-final/README.md) | Avaliação comparativa de desempenho entre as controladoras POX e Ryu |

## Ferramentas utilizadas

- **Mininet** — emulação de redes SDN
- **POX** e **Ryu** — controladoras SDN
- **OpenFlow** — protocolo de comunicação switch-controlador
- **Wireshark**, **tcpdump**, **iperf** — análise e medição de tráfego
