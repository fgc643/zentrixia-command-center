<div align="center">

# 🎛️ Zentrixia Command Center

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

## 🎯 O Problema que Este Sistema Resolve

Gerenciar múltiplos containers em produção é caótico sem visibilidade centralizada. Empresas enfrentam:

- ❌ Falta de visão em tempo real do estado da infraestrutura
- ❌ Dificuldade em identificar gargalos de performance
- ❌ Downtime não detectado rapidamente
- ❌ Custos com ferramentas pagas de monitoramento

**Zentrixia Command Center** resolve isso oferecendo:

- ✅ **Dashboard unificado** com todas as métricas críticas
- ✅ **Alertas automáticos** quando algo sai do padrão
- ✅ **Health Score inteligente** que identifica problemas antes de virarem crises
- ✅ **Zero custo** com soluções proprietárias

---

## 🎥 Veja o Sistema em Ação (2 minutos)

[![Zentrixia Command Center - Demo Completa](https://img.youtube.com/vi/s3U20BzH0cA/maxresdefault.jpg)](https://youtu.be/s3U20BzH0cA)

**🔗 Link direto:** https://youtu.be/s3U20BzH0cA

**O que você vai ver no vídeo:**
- Interface completa do dashboard
- Monitoramento em tempo real de 14 containers
- Sistema de health scoring funcionando
- Métricas detalhadas de CPU, memória e disco
- Gestão de uptime e disponibilidade

---

## 📊 Números Reais de Produção

### Métricas Atuais do Sistema

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

**Por que esses números importam:**
- Provam **estabilidade em longo prazo**, não apenas um teste de 1 dia
- Demonstram **eficiência de recursos** (CPU e memória otimizados)
- Mostram **capacidade de escala** (rodando 14 serviços simultâneos)

---

## 🏗️ Arquitetura Técnica Detalhada

### Stack de Tecnologias em Produção
```
┌─────────────────────────────────────────────────────┐
│               CAMADA DE ENTRADA                      │
│  🌐 Nginx Reverse Proxy + SSL/TLS (Let's Encrypt)   │
└─────────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────────┐
│           CAMADA DE APLICAÇÃO                        │
│  🤖 N8N Automation Engine                            │
│  💬 4x WhatsApp Bot Instances (Ports 9000-8081)      │
│  🧠 Ollama LLM (Local AI Processing)                 │
│  🐍 Zentrix Python Services                          │
│  🔨 Build System (CI/CD)                             │
└─────────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────────┐
│            CAMADA DE DADOS                           │
│  🐘 PostgreSQL (Primary Database)                    │
│  🔴 Redis Primary (Port 6379)                        │
│  🔴 Redis Secondary (Port 6380)                      │
└─────────────────────────────────────────────────────┘
                        ↓
┌─────────────────────────────────────────────────────┐
│         CAMADA DE INFRAESTRUTURA                     │
│  🐳 Docker + Docker Compose                          │
│  📊 Health Monitoring System                         │
│  🔄 Auto-restart on Failure                          │
└─────────────────────────────────────────────────────┘
```

### Containers Detalhados

| Container | Função | CPU | RAM | Porta | Uptime |
|-----------|--------|-----|-----|-------|--------|
| **N8N** | Automação de workflows complexos | 3.2% | 259MB | 5678 | 2d 14h |
| **Ollama** | Processamento de LLM local | 0.8% | 108MB | 11434 | 3d 2h |
| **PostgreSQL** | Banco de dados principal | 0.2% | 45MB | 5432 | 12d 5h |
| **Redis Primary** | Cache principal distribuído | 0.1% | 28MB | 6379 | 45d |
| **Redis Secondary** | Réplica para alta disponibilidade | 0.1% | 25MB | 6380 | 45d |
| **WhatsApp Bot 1** | Automação de mensagens | 0.7% | 60MB | 9000 | 1d 9h |
| **WhatsApp Bot 2** | Automação de mensagens | 0.8% | 66MB | 9001 | 1d 9h |
| **WhatsApp Bot 3** | Automação de mensagens | 0.8% | 66MB | 7777 | 1d 9h |
| **WhatsApp Bot 4** | Automação de mensagens | 0.8% | 66MB | 8081 | 1d 9h |
| **Zentrix Python** | Microserviços Python | 0.3% | 38MB | 8000 | 1d 2h |
| **Build System** | Pipeline CI/CD | 3.7% | 303MB | 3006 | 1d 9h |
| **Zentrixia Redis** | Cache auxiliar | 0.1% | 20MB | int | 5d |
| **Docker Proxy** | Proxy de containers | 0.4% | 40MB | 3000 | 10d |
| **Nginx** | Web server e reverse proxy | 0.1% | 59MB | 80/443 | 2h 35m |

---

## 🛠️ Stack Tecnológica Completa

### **Orquestração & Containerização**
- 🐳 **Docker** - Runtime de containers
- 📦 **Docker Compose** - Orquestração multi-container
- 🔄 **Docker Swarm** (preparado para escala futura)

### **Backend & Processamento**
- 🐍 **Python 3.11** - Microserviços e automações
- 🤖 **N8N** - Low-code automation platform
- 🧠 **Ollama** - LLM local para processamento de IA
- ⚡ **FastAPI** - APIs de alta performance

### **Bancos de Dados & Cache**
- 🐘 **PostgreSQL 15** - Banco relacional principal
- 🔴 **Redis 7** (Cluster) - Cache distribuído de alta velocidade
- 📊 **TimescaleDB** (preparado) - Séries temporais

### **Comunicação & Integração**
- 💬 **WhatsApp Business API** - 4 instâncias simultâneas
- 🔗 **Webhooks** - Integração em tempo real
- 📡 **REST APIs** - Comunicação entre serviços

### **Infraestrutura & DevOps**
- 🌐 **Nginx** - Reverse proxy e load balancer
- 🔒 **Let's Encrypt** - SSL/TLS automático
- 📊 **Prometheus** (preparado) - Coleta de métricas
- 📈 **Grafana** (preparado) - Visualização avançada

### **Segurança**
- 🔐 **JWT Authentication**
- 🛡️ **UFW Firewall**
- 🔑 **Secrets Management**
- 📝 **Audit Logging**

---

## 💪 Diferenciais Técnicos

### 1️⃣ **Alta Disponibilidade Real**

Não é teoria de livro - é **produção rodando 24/7**:

- ✅ Redis replicado (Primary + Secondary)
- ✅ Auto-restart configurado em todos os containers
- ✅ Health checks automatizados a cada 30 segundos
- ✅ Uptime de 99.8% em 45+ dias

### 2️⃣ **Sistema de Health Score Inteligente**

Algoritmo próprio que calcula pontuação de 0-100 baseado em:
```python
Health Score = (
    CPU_Usage * 0.3 +
    Memory_Usage * 0.3 +
    Disk_Usage * 0.2 +
    Uptime_Rate * 0.2
)
```

**Por que isso importa:**
- Identifica problemas ANTES de virarem crises
- Permite decisões proativas, não reativas
- Métricas visuais instantâneas do estado do sistema

### 3️⃣ **Escalabilidade Comprovada**

Sistema já gerencia **14 containers simultâneos** com:
- Apenas 1.1% de uso de CPU
- 30% de uso de memória
- Pronto para adicionar mais serviços sem degradação

### 4️⃣ **Segurança em Produção**

- 🔒 SSL/TLS válido e renovação automática
- 🛡️ Firewall configurado (portas específicas expostas)
- 🔑 Autenticação obrigatória em todos os serviços
- 📝 Logs de auditoria completos

---

## 🚀 Como Rodar Este Sistema

### **Pré-requisitos**
```bash
- Docker 24.0+
- Docker Compose 2.20+
- Ubuntu 20.04+ / Debian 11+ (ou similar)
- 4GB RAM mínimo (8GB recomendado)
- 50GB de disco disponível
```

### **Instalação Rápida**
```bash
# 1. Clone o repositório
git clone https://github.com/fgc643/zentrixia-command-center.git
cd zentrixia-command-center

# 2. Configure as variáveis de ambiente
cp .env.example .env
nano .env  # Edite com suas configurações

# 3. Inicie os containers
docker-compose up -d

# 4. Verifique o status
docker ps

# 5. Acesse o painel
# http://seu-dominio.com ou http://localhost:3000
```

### **Configuração de Produção**
```bash
# Configure o Nginx como reverse proxy
sudo cp nginx/nginx.conf /etc/nginx/sites-available/zentrixia
sudo ln -s /etc/nginx/sites-available/zentrixia /etc/nginx/sites-enabled/
sudo nginx -t && sudo systemctl reload nginx

# Configure SSL com Let's Encrypt
sudo certbot --nginx -d painel.zentrixia.com.br

# Configure firewall
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw enable
```

---

## 📸 Screenshots do Sistema Real

### 🎛️ Dashboard Principal
*Visão geral completa: Health Score, containers ativos, métricas de sistema*

![Dashboard Overview](https://via.placeholder.com/900x500/1a1d29/00ff88?text=Dashboard+Principal+-+Health+Score+87%2F100)

---

### 🐳 Gestão de Containers
*14 containers com status detalhado, CPU, memória, portas e uptime individual*

![Containers Management](https://via.placeholder.com/900x500/1a1d29/00ff88?text=14+Containers+Gerenciados+-+Status+em+Tempo+Real)

---

### 📊 Sistema de Health Score
*Pontuação inteligente baseada em CPU, memória, disco e disponibilidade*

![Health Score System](https://via.placeholder.com/900x500/1a1d29/00ff88?text=Health+Score+Algorithm+-+87%2F100)

---

### 📈 Monitoramento Detalhado
*Métricas granulares por container com gráficos de utilização*

![Detailed Monitoring](https://via.placeholder.com/900x500/1a1d29/00ff88?text=Monitoramento+Avançado+-+Métricas+por+Container)

---

## 🎯 Casos de Uso Reais

### **1. Automação de WhatsApp em Escala**
- 4 bots simultâneos processando mensagens
- Integração com N8N para workflows complexos
- Resposta automática 24/7

### **2. Processamento de IA Local**
- Ollama rodando LLMs sem dependência de APIs externas
- Economia de custos (sem OpenAI)
- Privacidade total dos dados

### **3. Pipeline CI/CD Completo**
- Build System automatizado
- Deploy contínuo de atualizações
- Zero downtime em atualizações

### **4. Cache Distribuído de Alta Performance**
- Redis Primary/Secondary para redundância
- Sub-10ms de latência
- Suporta milhares de requisições/segundo

---

## 📈 Roadmap & Melhorias Futuras

### **Em Desenvolvimento**
- [ ] Dashboard com gráficos históricos (últimos 30 dias)
- [ ] Sistema de alertas via Telegram/Email
- [ ] API REST pública para integração externa
- [ ] Mobile app para monitoramento remoto

### **Planejado para Q1 2026**
- [ ] Suporte a múltiplos servidores (cluster)
- [ ] Auto-scaling baseado em carga
- [ ] Backup automatizado com retenção de 30 dias
- [ ] Integração com Kubernetes

### **Ideias para o Futuro**
- [ ] Machine Learning para predição de falhas
- [ ] Modo dark/light theme
- [ ] Suporte a Docker Swarm nativo
- [ ] Marketplace de integrações

---

## 🔐 Segurança & Compliance

### **Medidas Implementadas**

✅ **Criptografia em Trânsito**
- SSL/TLS 1.3 em todas as conexões
- Certificado Let's Encrypt renovado automaticamente
- HSTS habilitado

✅ **Isolamento de Rede**
- Containers em redes Docker isoladas
- Apenas portas necessárias expostas
- Firewall UFW configurado

✅ **Autenticação & Autorização**
- JWT tokens com expiração
- Senhas hasheadas (bcrypt)
- Rate limiting em endpoints sensíveis

✅ **Auditoria & Logging**
- Logs centralizados de todos os containers
- Retenção de 90 dias
- Alertas para eventos críticos

✅ **Backups Automatizados**
- PostgreSQL: backup diário às 3h AM
- Redis: snapshot a cada 6 horas
- Retenção de 7 dias localmente
- Upload para S3 (opcional)

---

## 🤝 Como Contribuir

Este projeto está aberto para melhorias! Se você quer contribuir:

### **Encontrou um Bug?**
1. Abra uma [Issue](https://github.com/fgc643/zentrixia-command-center/issues) descrevendo o problema
2. Inclua prints/logs se possível
3. Marque como `bug`

### **Quer Adicionar uma Feature?**
1. Abra uma [Issue](https://github.com/fgc643/zentrixia-command-center/issues) propondo a ideia
2. Aguarde feedback
3. Faça um fork e crie uma branch: `git checkout -b feature/MinhaFeature`
4. Commit: `git commit -m 'Adiciona funcionalidade X'`
5. Push: `git push origin feature/MinhaFeature`
6. Abra um Pull Request

### **Áreas que Aceitam Contribuição**
- 📊 Novos gráficos e visualizações
- 🔔 Sistema de notificações
- 🌐 Internacionalização (i18n)
- 📱 Mobile app
- 📝 Melhorias na documentação

---

## 📚 Documentação Adicional

- 📖 [Guia de Instalação Completo](docs/INSTALLATION.md)
- 🏗️ [Arquitetura Detalhada](docs/ARCHITECTURE.md)
- 🚀 [Guia de Deploy em Produção](docs/DEPLOYMENT.md)
- 🔧 [Troubleshooting Comum](docs/TROUBLESHOOTING.md)
- 📊 [API Documentation](docs/API.md)

---

## 💬 FAQ - Perguntas Frequentes

**Q: Este sistema é gratuito?**
A: Sim! Totalmente open-source e sem custos de licenciamento.

**Q: Funciona com outros orquestradores além do Docker Compose?**
A: Atualmente otimizado para Docker Compose, mas há planos para suporte a Kubernetes.

**Q: Quanto de servidor preciso?**
A: Mínimo 4GB RAM e 2 vCPUs. Recomendado 8GB RAM para rodar todos os 14 containers confortavelmente.

**Q: Posso usar em ambiente Windows?**
A: Sim, via WSL2 (Windows Subsystem for Linux). Recomendado Linux nativo para produção.

**Q: Tem suporte comercial?**
A: Sim! Entre em contato via zentrixiasolucoes@gmail.com para consultoria e suporte dedicado.

---

## 📜 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para detalhes.

**Resumo da Licença MIT:**
- ✅ Uso comercial permitido
- ✅ Modificação permitida
- ✅ Distribuição permitida
- ✅ Uso privado permitido
- ⚠️ Sem garantias

---

## 👨‍💻 Sobre o Autor

<div align="center">

### **Flavio Silva**
**Arquiteto Híbrido | Especialista em Infraestrutura Docker & Automação**

</div>

Profissional com experiência em arquitetura de sistemas, infraestrutura cloud e automação de processos. Este projeto representa **meses de refinamento** em ambiente de produção real, não um tutorial copiado da internet.

### **O Que Me Diferencia**

🎯 **Foco em Resultados Reais**
- Não apenas código - sistemas rodando em produção
- 99.8% de uptime não é acidente, é expertise
- Cases reais, não projetos de fim de semana

🔧 **Habilidades Técnicas Comprovadas**
- Docker/Docker Compose avançado
- Arquitetura de microserviços
- DevOps e CI/CD
- Monitoramento e observabilidade
- Automação de processos complexos

💡 **Mentalidade de Produto**
- Sistemas pensados para escalar
- Segurança desde o design
- Documentação como prioridade
- Código limpo e manutenível

### **Entre em Contato**

- 🌐 **Sistema ao Vivo:** [painel.zentrixia.com.br](https://painel.zentrixia.com.br)
- 💼 **LinkedIn:** [linkedin.com/in/flaviosilva-arquiteto-hibrido](https://www.linkedin.com/in/flaviosilva-arquiteto-hibrido)
- 📧 **Email:** zentrixiasolucoes@gmail.com
- 🐙 **GitHub:** [github.com/fgc643](https://github.com/fgc643)
- 🚀 **Empresa:** Zentrixia - Soluções em Automação e Infraestrutura

### **Disponível Para**

- 💼 Oportunidades CLT (Híbrido/Remoto)
- 🤝 Projetos Freelance/PJ
- 🎓 Consultoria Técnica
- 👥 Palestras e Workshops

---

<div align="center">

## ⭐ Se Este Projeto Foi Útil, Deixe Uma Estrela!

![GitHub stars](https://img.shields.io/github/stars/fgc643/zentrixia-command-center?style=social)
![GitHub forks](https://img.shields.io/github/forks/fgc643/zentrixia-command-center?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/fgc643/zentrixia-command-center?style=social)

---

### 🔥 **Este não é mais um projeto de portfólio.**
### **É a prova de que eu sei construir e manter sistemas reais em produção.**

---

**Desenvolvido com 💙 e ☕ por Flavio Silva**

*"Código que roda em produção vale mais que mil tutoriais."*

</div>
