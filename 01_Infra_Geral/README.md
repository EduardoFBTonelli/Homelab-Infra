# 🗺️ 01. Documentação de Infraestrutura Geral

Esta pasta contém o planejamento lógico de toda a rede Homelab, incluindo o diagrama de topologia e o plano de endereçamento IPv4.

---

## 1. Topologia da Rede

[Insira aqui a imagem da sua topologia de rede (ex: Topologia.png). Você pode usar uma ferramenta como draw.io ou Visio.]

## 2. Segmentação de VLANs e Endereçamento

| VLAN ID | Nome | Sub-rede | Propósito | Gateway |
| :--- | :--- | :--- | :--- | :--- |
| **VLAN 1** | Gerenciamento | 192.168.1.0/24 | Acesso administrativo a switches/roteadores. | 192.168.1.1 |
| **VLAN 10** | Clientes (Wi-Fi) | 192.168.10.0/24 | Dispositivos móveis e PCs de usuários. | 192.168.10.1 |
| **VLAN 20** | Servidores | 192.168.20.0/24 | Servidor Minecraft, Webserver, VM's. | 192.168.20.1 |

[Link para o arquivo de Endereçamento IP Detalhado (a ser criado depois): ./Enderecamento_Detalhado.md]
