![GitHub License](https://img.shields.io/github/license/nicolasmath/lab-redes-01)

# Laboratório de Redes 1 - Projeto de Rede local

Aluno: Nicolas Matheus Ribeiro Lopes

Professor: José de Assis

Data: 09/03/2026

---

## **1. Objetivo:**
Implementar uma rede local simples conectando 3 notbooks a um roteador wireless com switch e uma impressora de rede.

O projeto será dividido em 2 etapas:

1. Simulação da Rede no Cisco Packet Tracer
2. Implementação da rede no laboratório real

---

## **2. Equipamentos usados nesse laboratpório:**

- 3 Notebooks
- 1 Roteador Wireless com 1 porta WAN e 4 portas LAN
- 1 Impressora de rede
- Cabos de rede

---

## **3. Topologia da Rede:**

Diagrama lógico da rede usada neste laboratório. 
```mermaid
graph TD

WAN[Internet / WAN do provedor]

Router[Roteador Wireless<br>1 Porta WAN<br>4 Portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[Impressora de Rede]

WAN --> |Porta WAN| Router 

Router --> |LAN 4| PC1
Router --> |LAN 4| PC2
Router --> |LAN 4| PC3
Router --> |LAN 4| Printer
```
Imagem da topologia usada neste laboratório:
![topologia](<img width="693" height="486" alt="image" src="https://github.com/user-attachments/assets/d3e2f1dc-6470-4a09-840f-e510b732a195" />
)

