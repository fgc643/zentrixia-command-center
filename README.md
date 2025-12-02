<div align="center">

# 🎛️ Centro de Comando Zentrixia

### Sistema Profissional de Gestão de Infraestrutura Docker em Produção

![Health Score](https://img.shields.io/badge/Health_Score-87%2F100-success?style=for-the-badge)
![Containers](https://img.shields.io/badge/14_Containers-Production-blue?style=for-the-badge)
![Uptime](https://img.shields.io/badge/Uptime-99.8%25-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Live_Now-Online-success?style=for-the-badge)

### 🎥 [Assista ao Sistema em Funcionamento](https://youtu.be/s3U20BzH0cA) • 🌐 [Acesse o Painel Ao Vivo](https://painel.zentrixia.com.br/)

</div>

---

## 💡 Por Que Este Projeto é Diferente?

**Não é mais um projeto de portfólio.** Este é um **sistema real em produção** gerenciando **infraestrutura crítica 24/7**.

Enquanto a maioria dos desenvolvedores mostra "to-do lists" e projetos locais, **este repositório documenta um ambiente de produção completo** com:

- ✅ **14 containers Docker** rodando simultaneamente
- ✅ **99.8% de uptime** comprovado em ambiente real
- ✅ **Sistema de monitoramento** com health checks automatizados
- ✅ **Domínio próprio** com SSL configurado
- ✅ **Automações complexas** com múltiplos bots WhatsApp
- ✅ **Arquitetura escalável** com cache distribuído (Redis Primary/Secondary)

**Resultado:** Um case real que comprova capacidade técnica, não apenas teoria.

---

## 🎥 Veja o Sistema em Ação

[![Zentrixia Command Center - Demo Completa](https://img.youtube.com/vi/s3U20BzH0cA/maxresdefault.jpg)](https://youtu.be/s3U20BzH0cA)

**🔗 Link direto:** https://youtu.be/s3U20BzH0cA

---

## 📊 Números Reais de Produção

| Indicador | Valor | Status |
|-----------|-------|--------|
| **Containers Gerenciados** | 14 | 🟢 Todos Operacionais |
| **Containers Ativos** | 12 (86%) | 🟢 Excelente |
| **Health Score Global** | 87/100 | 🟢 Saudável |
| **Uptime Médio** | 99.8% | 🟢 Produção |
| **Uso de CPU** | 1.1% | 🟢 Otimizado |
| **Uso de Memória** | 2.4GB / 8GB (30%) | 🟢 Confortável |
| **Uso de Disco** | 50.2% | 🟡 Monitorado |
| **Tempo Online** | 45+ dias | 🟢 Estável |

---

## 🏗️ Arquitetura Técnica

### Containers em Produção

| Container | CPU | Memória | Porta | Uptime |
|-----------|-----|---------|-------|--------|
| **N8N** | 3.2% | 259MB | 5678 | 2d 14h |
| **Ollama** | 0.8% | 108MB | 11434 | 3d 2h |
| **PostgreSQL** | 0.2% | 45MB | 5432 | 12d 5h |
| **Redis Primary** | 0.1% | 28MB | 6379 | 45d |
| **Redis Secondary** | 0.1% | 25MB | 6380 | 45d |
| **WhatsApp Bot 1** | 0.7% | 60MB | 9000 | 1d 9h |
| **WhatsApp Bot 2** | 0.8% | 66MB | 9001 | 1d 9h |
| **WhatsApp Bot 3** | 0.8% | 66MB | 7777 | 1d 9h |
| **WhatsApp Bot 4** | 0.8% | 66MB | 8081 | 1d 9h |
| **Zentrix Python** | 0.3% | 38MB | 8000 | 1d 2h |
| **Build System** | 3.7% | 303MB | 3006 | 1d 9h |
| **Zentrixia Redis** | 0.1% | 20MB | int | 5d |
| **Docker Proxy** | 0.4% | 40MB | 3000 | 10d |
| **Nginx** | 0.1% | 59MB | 80/443 | 2h 35m |

---

## 🛠️ Stack Tecnológica

- 🐳 **Docker & Docker Compose** - Orquestração de containers
- 🔄 **N8N** - Automação de workflows
- 🐘 **PostgreSQL** - Banco de dados relacional
- 🔴 **Redis** (Primary + Secondary) - Cache distribuído
- 🌐 **Nginx** - Reverse proxy e load balancer
- 💬 **WhatsApp Bots** - 4 instâncias para automação
- 🤖 **Ollama** - LLM local para IA
- 🐍 **Python Services** - Microserviços customizados

---

## 📸 Screenshots do Sistema Real

### Dashboard Principal
![Dashboard Principal](Captura%20de%20tela%202025-12-01%20203338.png)

### Health Score Detalhado
![Health Score](Captura%20de%20tela%202025-12-01%20203354.png)

### Gestão de Containers Docker
![Containers Docker](Captura%20de%20tela%202025-12-01%20203409.png)

### Monitoramento Completo
![Monitoramento](Captura%20de%20tela%202025-12-01%20203430.png)

---

## 🚀 Como Rodar Este Sistema

### Pré-requisitos

- Docker 24.0+
- Docker Compose 2.20+
- Ubuntu 20.04+ / Debian 11+
- 4GB RAM mínimo (8GB recomendado)
- 50GB de disco disponível

### Instalação
```bash
# Clone o repositório
git clone https://github.com/fgc643/zentrixia-command-center.git
cd zentrixia-command-center

# Configure as variáveis de ambiente
cp .env.example .env

# Inicie os containers
docker-compose up -d

# Verifique o status
docker ps
```

---

## 💪 Diferenciais Técnicos

### Alta Disponibilidade Real
- Redis replicado (Primary + Secondary)
- Auto-restart em todos os containers
- Health checks a cada 30 segundos
- 99.8% de uptime em 45+ dias

### Sistema de Health Score Inteligente
Algoritmo que calcula pontuação 0-100 baseado em CPU, memória, disco e disponibilidade.

### Escalabilidade Comprovada
14 containers simultâneos com apenas 1.1% de CPU e 30% de memória.

### Segurança em Produção
- SSL/TLS com Let's Encrypt
- Firewall configurado
- Autenticação obrigatória
- Logs de auditoria

---

## 📈 Roadmap

- [ ] Dashboard com gráficos históricos
- [ ] Sistema de alertas via Telegram/Email
- [ ] API REST pública
- [ ] Suporte a múltiplos servidores
- [ ] Auto-scaling baseado em carga
- [ ] Mobile app para monitoramento

---

## 🤝 Como Contribuir

1. Fork o projeto
2. Crie uma branch: `git checkout -b feature/MinhaFeature`
3. Commit: `git commit -m 'Adiciona funcionalidade X'`
4. Push: `git push origin feature/MinhaFeature`
5. Abra um Pull Request

---

## 👨‍💻 Sobre o Autor

<div align="center">

### **Flavio Silva**
**Arquiteto Híbrido | Especialista em Infraestrutura Docker & Automação**

Profissional com experiência em arquitetura de sistemas, infraestrutura cloud e automação de processos. Este projeto representa **meses de refinamento** em ambiente de produção real.

### Entre em Contato

- 🌐 **Sistema ao Vivo:** [painel.zentrixia.com.br](https://painel.zentrixia.com.br)
- 💼 **LinkedIn:** [linkedin.com/in/flaviosilva-arquiteto-hibrido](https://www.linkedin.com/in/flaviosilva-arquiteto-hibrido)
- 📧 **Email:** zentrixiasolucoes@gmail.com
- 🐙 **GitHub:** [github.com/fgc643](https://github.com/fgc643)
- 🚀 **Empresa:** Zentrixia - Soluções em Automação e Infraestrutura

### Disponível Para
- 💼 Oportunidades CLT (Híbrido/Remoto)
- 🤝 Projetos Freelance/PJ
- 🎓 Consultoria Técnica
- 👥 Palestras e Workshops

---

## ⭐ Se Este Projeto Foi Útil, Deixe Uma Estrela!

![GitHub stars](https://img.shields.io/github/stars/fgc643/zentrixia-command-center?style=social)
![GitHub forks](https://img.shields.io/github/forks/fgc643/zentrixia-command-center?style=social)

---

### 🔥 **Este não é mais um projeto de portfólio.**
### **É a prova de que eu sei construir e manter sistemas reais em produção.**

---

**Desenvolvido com 💙 e ☕ por Flavio Silva**

*"Código que roda em produção vale mais que mil tutoriais."*

</div>
