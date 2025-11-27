# Homelab-Infra
Portfólio de infraestrutura de redes 
# 🏡 Portfólio: Homelab de Redes e Sistemas [Eduardo Felipe Barbosa Tonelli]

Este projeto documenta a evolução da minha infraestrutura de redes doméstica, servindo como laboratório prático para as certificações **CCNA**, **MikroTik MTCNA** e **LPIC**.

---

## 1. Visão Geral da Topologia

* **Objetivo:** Simular um ambiente de provedor de serviços (ISP) com segmentação de tráfego.
* **Equipamentos Chave:** MikroTik, Cisco Switch, Servidor Proxmox (Virtualização).

[Aqui será o link para o seu diagrama de rede: ./01_Infra_Geral/Topologia.md]

## 2. Áreas de Conhecimento em Destaque

| Área | Pasta de Configurações | Prática Aplicada |
| :--- | :--- | :--- |
| **Roteamento** | `02_Equipamentos_Rede/MikroTik_RB750` | NAT, Firewall, PPPoE. |
| **Switching** | `02_Equipamentos_Rede/Cisco_2960` | VLANs, Trunking (802.1Q), Port Security. |
| **Serviços (SI)** | `03_Servicos_Específicos/Minecraft_Server` | DNS SRV, Port Forwarding, Linux Server Hardening. |
| **Automação** | `04_Automacao_Scripts/` | Scripts de backup de configuração (Python/Bash). |

---

## 3. Próximos Passos (To-Do)

* [ ] Documentar o plano de endereçamento IPv4.
* [ ] Adicionar a configuração inicial do switch Cisco.
* [ ] Criar um script Python para verificar o *status* do DDNS.

---

Ao terminar de editar, clique em **"Commit changes"** (Comprometer alterações) na parte inferior da página. Sua estrutura inicial estará pronta!
