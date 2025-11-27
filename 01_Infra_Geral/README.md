# 🗺️ 01. Documentação de Infraestrutura Geral

Esta pasta contém o planejamento lógico de toda a rede Homelab, incluindo o diagrama de topologia e o plano de endereçamento IPv4.

---

## 1. Topologia da Rede

[Insira aqui a imagem da sua topologia de rede (ex: Topologia.png). Você pode usar uma ferramenta como draw.io ou Visio.]

## 2. Segmentação de VLANs e Endereçamento

| VLAN ID | Nome | Sub-rede | Propósito | Gateway |
| :--- | :--- | :--- | :--- | :--- |
| **VLAN 1** | Gerenciamento | | Acesso administrativo a switches/roteadores. |   |
| **VLAN 10** | Clientes (Wi-Fi) | 192.168.10.0/24 | Dispositivos móveis e PCs de usuários. |   |
| **VLAN 20** | Servidores |  | Servidor Minecraft, Webserver, VM's. |   |

[Link para o arquivo de Endereçamento IP Detalhado (a ser criado depois): ./Enderecamento_Detalhado.md]
