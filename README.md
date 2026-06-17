# 🖧 Projeto 01 - Rede Local Simples com Switch ![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=%23000000)


![Status](https://img.shields.io/badge/Status-Concluído-success)
![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-blue)
![IPv4](https://img.shields.io/badge/IPv4-Configurado-orange)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido no Cisco Packet Tracer com o objetivo de praticar os fundamentos de redes de computadores.

A simulação representa uma rede local (LAN) composta por quatro computadores conectados a um switch Cisco 2960. Todos os dispositivos foram configurados manualmente com endereços IPv4 pertencentes à mesma rede, permitindo comunicação direta entre os hosts.

## 🎯 Objetivos de Aprendizagem

* Compreender o funcionamento de uma rede local (LAN);
* Configurar endereços IPv4 manualmente;
* Entender a função de um switch em uma rede;
* Realizar testes de conectividade utilizando Ping;
* Praticar conceitos básicos de endereçamento IP.

## 🖼️ Topologia da Rede

![Topologia da Rede](imagens/topologia.png)

 
### Dispositivos Utilizados

| Equipamento       | Quantidade |
| ----------------- | ---------- |
| PC                | 4          |
| Switch Cisco 2960 | 1          |

## 🌐 Endereçamento IP

| Dispositivo | Endereço IP  | Máscara de Sub-rede |
| ----------- | ------------ | ------------------- |
| PC0         | 192.168.1.10 | 255.255.255.0       |
| PC1         | 192.168.1.11 | 255.255.255.0       |
| PC2         | 192.168.1.12 | 255.255.255.0       |
| PC3         | 192.168.1.13 | 255.255.255.0       |


### Rede Utilizada

```text
Rede: 192.168.1.0/24
```

## 🔧 Configurações Realizadas

* Adição de um Switch Cisco 2960;
* Conexão dos computadores utilizando cabos Copper Straight-Through;
* Configuração manual de IPv4 em todos os hosts;
* Validação da comunicação entre dispositivos através do comando Ping.

## 🧪 Testes de Conectividade

Após a configuração dos endereços IP, foram realizados testes de conectividade entre todos os computadores.

### Exemplo

```bash
ping 192.168.1.11
```

Resultado esperado:

```text
Reply from 192.168.1.11: bytes=32 time<1ms TTL=128
Reply from 192.168.1.11: bytes=32 time<1ms TTL=128
Reply from 192.168.1.11: bytes=32 time<1ms TTL=128
Reply from 192.168.1.11: bytes=32 time<1ms TTL=128
```

### Evidência

[Testes de Ping](imagens)


## 📚 Conceitos Praticados

* Redes de Computadores
* LAN (Local Area Network)
* Endereçamento IPv4
* Máscara de Sub-rede
* Switches
* Comunicação entre Hosts
* Protocolo ICMP
* Testes de Conectividade

## 🛠️ Tecnologias Utilizadas

* Cisco Packet Tracer
* IPv4
* ICMP
* Ethernet
* Cisco 2960 Switch

## 👩‍💻 Autora

**Nicolle Assis**

Estudante de Redes de Computadores

* LinkedIn: https://www.linkedin.com/in/nicolle-assis/
* GitHub: https://github.com/nicolle-assis

## 📄 Licença
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
License MIT
