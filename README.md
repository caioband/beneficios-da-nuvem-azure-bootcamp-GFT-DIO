# ☁️ Benefícios da Nuvem Microsoft Azure

Este repositório faz parte das atividades do **bootcamp GFT Start .NET – DIO** e tem como objetivo resumir os principais benefícios da computação em nuvem utilizando a plataforma **Microsoft Azure**, com base nos laboratórios, materiais de apoio e práticas estudadas.

---

## ⚙️ Escalabilidade e Elasticidade

### 🔄 **Escalabilidade**
- Capacidade de **aumentar ou reduzir recursos computacionais sob demanda**, sem precisar reconfigurar manualmente o ambiente.
- Pode ser **vertical (scale up)** ou **horizontal (scale out)**.
- Exemplo: um app pode aumentar o número de instâncias automaticamente durante horários de pico.

🔗 Referência:  
[What is scalability in cloud computing – Microsoft Learn](https://learn.microsoft.com/en-us/azure/architecture/best-practices/auto-scaling)

---

### 🧬 **Elasticidade**
- A **capacidade da nuvem de se adaptar automaticamente à carga de trabalho em tempo real**, liberando recursos quando o uso diminui.
- Evita desperdício de recursos e reduz custos.

🔗 Referência:  
[Scalability and elasticity in cloud design – Microsoft Learn](https://learn.microsoft.com/en-us/azure/architecture/guide/design-principles/scalability)

---

## 🛡️ Confiabilidade, Previsibilidade e Segurança

### 🔒 **Confiabilidade**
- Azure oferece **alta disponibilidade** com redundância geográfica.
- Serviços como **Availability Sets**, **Availability Zones** e **Load Balancer** garantem continuidade mesmo em falhas.

🔗 Referência:  
[High availability for Azure applications – Microsoft Learn](https://learn.microsoft.com/en-us/azure/architecture/resiliency/high-availability-azure)

---

### 📏 **Previsibilidade**
- Com **monitoramento em tempo real**, logs, métricas e alertas, a plataforma permite identificar gargalos, quedas de performance e falhas antes que causem impacto.

🔗 Referência:  
[Azure Monitor Overview – Microsoft Learn](https://learn.microsoft.com/en-us/azure/azure-monitor/overview)

---

### 🔐 **Segurança**
- Infraestrutura da Microsoft segue padrões como **ISO 27001, SOC, GDPR, LGPD e NIST**.
- Recursos de segurança integrados:
  - **Azure Active Directory (AAD)**
  - **Role-Based Access Control (RBAC)**
  - **Microsoft Defender for Cloud**
  - **Encryption at rest e in transit**

🔗 Referências:
- [Security best practices – Microsoft Learn](https://learn.microsoft.com/en-us/security/compass/azure-security-best-practices)
- [Azure security documentation](https://learn.microsoft.com/en-us/azure/security/)

---

## 🧭 Governança e Gerenciabilidade

### 📚 **Governança**
- Azure oferece ferramentas para controlar **acesso, compliance, custo e políticas corporativas**:
  - **Azure Policy**
  - **Management Groups**
  - **Blueprints**
  - **Resource Locks**

🔗 Referência:  
[Azure governance documentation](https://learn.microsoft.com/en-us/azure/governance/)

---

### 🧩 **Gerenciabilidade**
- Gerenciamento simplificado de recursos via:
  - **Azure Portal (interface web)**
  - **Azure CLI / PowerShell**
  - **Azure Resource Manager (ARM Templates)**
- Possibilidade de **automatizar provisionamento**, aplicar tags e configurar ambientes inteiros com infraestrutura como código (IaC).

🔗 Referência:  
[Manage Azure resources – Microsoft Learn](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview)

---

## 📃 SLA: O Compromisso de Disponibilidade da Microsoft

A **Microsoft define SLA (Service Level Agreement)** como o **compromisso de manter os serviços disponíveis com base em um percentual mensal.**

### Exemplos de SLA da Azure:
| Serviço                  | SLA Garantido |
|--------------------------|----------------|
| Azure SQL Database       | 99,99%         |
| Azure Virtual Machines   | 99,9% a 99,99% (com zonas de disponibilidade) |
| Azure App Service        | 99,95%         |
| Azure Functions          | 99,95%         |

> 🧠 Se a disponibilidade prometida não for cumprida, a Microsoft oferece **créditos financeiros** ao cliente proporcionalmente ao impacto.

🔗 Referência:
- [Service Level Agreements – Microsoft](https://www.microsoft.com/licensing/docs/view/Service-Level-Agreements-SLA-for-Online-Services)

---

## ✅ Conclusão

O Microsoft Azure se destaca por oferecer:

- Escalabilidade automática
- Segurança de nível corporativo
- Confiabilidade com alta disponibilidade
- Ferramentas robustas de monitoramento, controle e automação
- Transparência em relação à performance através de SLAs públicos

Isso permite que empresas e desenvolvedores criem aplicações com foco em **qualidade, segurança e eficiência**, com liberdade para escalar e se adaptar a qualquer cenário.

---

> _“Computação em nuvem não é mais o futuro — é o novo padrão. E com Azure, o padrão é alto.”_
