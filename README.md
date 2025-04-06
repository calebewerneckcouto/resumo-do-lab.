# Resumo do Lab - Fundamentos de Computação em Nuvem na DIO ☁️

Este repositório contém o resumo do que aprendi durante o desenvolvimento do laboratório da DIO, focado nos fundamentos de computação em nuvem e na plataforma Microsoft Azure.

---

## 🚀 O que eu aprendi

### 📘 Criação da Conta na Azure
Aprendi como criar uma conta gratuita na Microsoft Azure com os seguintes passos:
- Acesso ao site oficial.
- Cadastro com e-mail, verificação por número de telefone e cartão (sem cobrança).
- Exploração do painel inicial com recursos gratuitos.

> **Importante**: A conta na Azure é única por pessoa ou organização, mas os **recursos disponíveis variam conforme a região geográfica** e o tipo de empresa ou assinatura utilizada.

---

### 🌍 Configuração do Portal Azure

Durante o lab, também aprendi a:
- **Alterar o idioma do portal para português**, facilitando a navegação.
- **Personalizar a aparência do menu**, escolhendo entre visualização em forma de ícones, texto ou categorias.
- Utilizar o **menu "Todos os Serviços"** para localizar recursos organizados por **categorias**, como:
  - Computação
  - Rede
  - Armazenamento
  - Segurança
  - Identidade

---

### 🔐 Azure Bastion – Acesso Seguro (Jump Server)

O **Azure Bastion** permite acessar máquinas virtuais (VMs) via navegador, sem necessidade de IP público ou conexão via RDP ou SSH externa.  
> Funciona como um **jump server gerenciado**, oferecendo um meio **seguro e integrado** para acessar servidores.

**Vantagens:**
- Elimina a exposição de portas como 3389 (RDP) e 22 (SSH) à internet.
- Melhora a segurança do ambiente.
- Acesso direto pelo navegador do portal Azure.

---

### 🖥️ Faixa de Servidores, Discos e Migração

- **Faixa de Servidores (VM Sizes)**: Azure oferece diferentes tamanhos de máquinas virtuais com quantidades variadas de CPU, RAM e armazenamento, conforme a necessidade da aplicação.
- **Discos**: Possuem diferentes tipos (Standard HDD, Premium SSD, etc.), podendo ser usados como disco do SO ou de dados.
- **Migração para Azure**: O Azure fornece ferramentas como o **Azure Migrate** para mover servidores físicos, VMs de outros provedores ou ambientes on-premise para a nuvem de forma segura e planejada.

---

### ☁️ Comparação entre Modelos de Nuvem

| Modelo de Nuvem   | Descrição                                                                 | Exemplo                     |
|-------------------|---------------------------------------------------------------------------|-----------------------------|
| **Nuvem Pública** | Recursos fornecidos por terceiros via internet e compartilhados.         | Azure, AWS, Google Cloud    |
| **Nuvem Privada** | Recursos exclusivos para uma única organização, com mais controle.       | Data center interno         |
| **Nuvem Híbrida** | Combinação entre nuvem pública e privada, oferecendo flexibilidade.      | Integração on-premise + Azure |
| **Multicloud**    | Uso de dois ou mais provedores de nuvem diferentes ao mesmo tempo.       | Azure + AWS, por exemplo    |

---

### 💰 CapEx vs OpEx

| CapEx (Capital Expenditure)                             | OpEx (Operational Expenditure)                                |
|---------------------------------------------------------|---------------------------------------------------------------|
| Despesas de capital, investimento antecipado            | Despesas operacionais, pagamento conforme uso                 |
| Compra de servidores, data centers                      | Serviços de nuvem (ex: Azure, AWS)                            |
| Alto custo inicial, retorno ao longo do tempo           | Custos menores, previsíveis e escaláveis                      |
| Exemplo: montar seu próprio data center                 | Exemplo: contratar um servidor virtual na Azure               |

---

## ✅ Conclusão

Este laboratório me proporcionou uma base sólida sobre computação em nuvem e o uso do Microsoft Azure. Aprendi desde a criação da conta, personalização do portal, até conceitos técnicos como acesso seguro com Bastion, tamanhos de VMs, tipos de discos e opções de migração.

Estou cada vez mais preparado para trabalhar com infraestrutura em nuvem de forma segura, escalável e moderna! 💪☁️

---

Feito com 💻 dedicação e vontade de evoluir na carreira tech!  
[🔗 Meu LinkedIn](https://www.linkedin.com/in/calebe-werneck-571091295)
