# resumo-do-lab

# ☁️ Fundamentos de Computação em Nuvem (Azure)

## 📌 Domínio e Objetivo da Computação em Nuvem

A computação em nuvem tem como principal objetivo fornecer recursos de TI sob demanda pela internet, sem a necessidade de infraestrutura física local.

Em vez de comprar servidores, armazenamentos e redes, utilizamos serviços oferecidos por provedores como a Microsoft Azure.

### 🎯 Principais objetivos:
- Escalabilidade sob demanda
- Redução de custos operacionais
- Alta disponibilidade
- Agilidade no provisionamento
- Foco no negócio (menos gestão de infraestrutura)

---

## ☁️ O que é Computação em Nuvem?

É a entrega de serviços de computação como:
- Servidores
- Banco de dados
- Armazenamento
- Redes
- Software

Tudo isso via internet, com pagamento conforme o uso (*pay-as-you-go*).

---

## 🌎 Modelos de Implantação de Nuvem

### 🔹 Nuvem Pública
- Infraestrutura compartilhada
- Gerenciada por provedores como Azure, AWS e GCP  
- Acesso via internet

✅ Vantagens:
- Baixo custo inicial
- Alta escalabilidade
- Sem manutenção física

---

### 🔹 Nuvem Privada
- Infraestrutura exclusiva de uma organização
- Pode ser local (on-premises) ou em data centers dedicados

✅ Vantagens:
- Maior controle
- Mais segurança (em cenários específicos)

---

### 🔹 Nuvem Híbrida
- Combina nuvem pública + privada

✅ Vantagens:
- Flexibilidade
- Permite manter dados sensíveis localmente
- Integração gradual com a nuvem

---

## ⚙️ Modelos de Serviço em Nuvem

### 🔹 IaaS (Infrastructure as a Service)
- Você gerencia:
  - Sistema operacional
  - Aplicações
- O provedor gerencia:
  - Hardware

📌 Exemplo prático (Azure):
- Criar uma Máquina Virtual (VM)
- Instalar manualmente:
  - .NET / Node / Python
  - Banco de dados
- Usar para rodar uma API (como seu Inventory Service)

---

### 🔹 PaaS (Platform as a Service)
- Você gerencia:
  - Código da aplicação
- O provedor gerencia:
  - Infraestrutura + runtime

📌 Exemplo prático (Azure):
- Azure App Service:
  - Fazer deploy direto da sua API (.NET, Node, etc.)
  - Sem se preocupar com servidor
- Azure SQL Database:
  - Banco gerenciado sem precisar instalar SQL Server

---

### 🔹 SaaS (Software as a Service)
- Tudo é gerenciado pelo provedor

📌 Exemplo:
- Microsoft 365  
- Google Docs  

📌 Uso prático:
- Apenas acessar via navegador (sem instalação ou manutenção)

---

## 💰 CAPEX vs OPEX

### 🔹 CAPEX (Capital Expenditure)
- Investimento inicial alto
- Compra de infraestrutura física

📉 Exemplo:
- Comprar servidores
- Montar data center local

---

### 🔹 OPEX (Operational Expenditure)
- Pagamento conforme uso
- Sem investimento inicial significativo

📈 Exemplo:
- Usar Azure e pagar apenas pelos recursos consumidos

---

### ⚖️ Comparação

| Característica | CAPEX | OPEX |
|------|--------|------|
| Investimento inicial | Alto | Baixo |
| Manutenção | Responsabilidade própria | Provedor |
| Escalabilidade | Limitada | Alta |
| Risco | Alto | Reduzido |

---

## 🚀 Benefícios da Computação em Nuvem

- Elasticidade (escala automática)
- Alta disponibilidade
- Redução de custos
- Deploy rápido
- Backup e recuperação facilitados

---

## 🧪 Exemplos Práticos no Azure

### 🔹 1. Deploy de API (PaaS)
- Criar um App Service
- Subir sua API (ex: Inventory Service)
- Integrar com banco Azure SQL
- Acessar via URL pública

---

### 🔹 2. Banco de Dados Gerenciado
- Criar um Azure SQL Database
- Configurar connection string
- Integrar com backend

---

### 🔹 3. Armazenamento de Arquivos
- Usar Azure Blob Storage
- Upload de imagens, documentos ou backups
- Acesso via URL ou SDK

---

### 🔹 4. Máquina Virtual (IaaS)
- Criar uma VM Linux/Windows
- Acessar via SSH ou RDP
- Instalar manualmente sua aplicação

---

### 🔹 5. Escalabilidade Automática
- Configurar auto scale no App Service
- Aumentar instâncias conforme demanda
- Reduzir custos quando não há uso

---

## 📌 Conclusão

A computação em nuvem transforma a forma como sistemas são desenvolvidos e escalados, permitindo utilizar recursos sob demanda com eficiência e baixo custo.

O Azure se destaca como uma plataforma completa para desenvolvimento moderno, permitindo desde infraestrutura básica até aplicações totalmente gerenciadas.

---

