# 🚀 Desafio DevOps - Implementação de Práticas DevOps na Empresa Fictícia “Tech”

## 🧩 Visão Geral

Este documento apresenta um plano completo para implementação de práticas DevOps em um ambiente empresarial fictício, utilizando os pilares **CALMS** e as **Três Maneiras do DevOps**.

---

## 🏢 Sobre a Empresa “Tech”

A **Tech** é uma empresa especializada em desenvolvimento de software, oferecendo soluções para diversos setores com foco em inovação e eficiência.

### Equipes:
- **Desenvolvimento:** 14 devs (Java, C#, JS). Apenas 1 dev com experiência em Delphi.
- **Operações:** 4 profissionais com dificuldades em escalar e manter sistemas eficientes.

### Projetos em Andamento:
1. **Sistema de Gestão de Vendas (LEGADO)** — feito em Delphi.
2. **Plataforma de E-commerce** — moderna e escalável, voltada ao varejo.

---

## 🧭 1. Diagnóstico Cultural (C de CALMS)

### 🎯 Processo Escolhido:
**Entrega de código e deploy em produção.**

### 📍 Situação Atual:
- Deploys manuais e sem padronização.
- Entrega de código da equipe de Dev para a de Ops via pacotes.
- Testes e monitoramento feitos manualmente pela equipe de operações.

### ⚠️ Pontos de Atrito:
- Baixa colaboração entre Dev e Ops.
- Responsabilidade centralizada em Ops.
- Alta taxa de erros após deploys.

### 🔧 Oportunidades:
- Implementação de CI/CD.
- Testes automatizados.
- Cultura de colaboração e ownership compartilhado.

---

## 🤖 2. Automação (A de CALMS)

### 🚀 Proposta:
**Pipeline de CI/CD com build, testes automatizados, análise de qualidade e deploy contínuo.**

### 🛠️ Ferramentas Sugeridas:
- **GitHub Actions / GitLab CI / Jenkins**
- **Docker** para padronizar ambientes
- **SonarQube** para qualidade de código
- **JUnit / xUnit / Selenium** para testes
- **Prometheus + Grafana** para observabilidade

### 🔄 Etapas do Pipeline:
1. Trigger: Pull Request.
2. Build + Testes Unitários.
3. Análise de Qualidade.
4. Testes de Integração/End-to-End.
5. Deploy automático em Staging.
6. Deploy com aprovação manual em Produção.

### 🧭 Plano de Ação:
- Mapear processos atuais com as equipes.
- Implementar pipeline mínimo viável no sistema legado.
- Expandir automação para a nova plataforma.
- Workshops internos para reduzir resistência e fomentar cultura DevOps.

---

## 📊 3. Mensuração (M) e Compartilhamento (S) de Conhecimento

### 📈 Métricas:
| Indicador                    | Situação Atual     | Meta com DevOps      |
|-----------------------------|--------------------|-----------------------|
| Tempo até o deploy          | 2 dias             | 30 minutos            |
| Sucesso dos deploys         | 80%                | > 95%                 |
| Incidentes pós-deploy       | 2 por semana       | < 1 por semana        |
| MTTR (tempo de recuperação) | 4 horas            | < 1 hora              |

### 📘 Compartilhamento:
- **Repositório interno de boas práticas**
- **Retrospectivas técnicas quinzenais**
- **Newsletter técnica / Blog interno**
- **Sessões de Brown Bag (almoço + palestra)**
- **Code Reviews e Pair Programming**

---

## 🔁 4. As Três Maneiras do DevOps

### 🛣️ Primeira Maneira – Acelerar o Fluxo:
- Deploys pequenos e frequentes.
- Containers para ambientes homogêneos.
- Integração contínua desde o commit até o deploy.

### 🔄 Segunda Maneira – Ampliar o Feedback:
- Dashboards em tempo real (Grafana).
- Alertas automáticos (Prometheus).
- Feedback visual direto nos PRs.

### 🧪 Terceira Maneira – Experimentar e Aprender:
- Feature Toggles para releases controladas.
- Postmortems sem culpa após falhas.
- Ambiente seguro para experimentação.
- Reconhecimento a iniciativas, mesmo com falhas.

---

## ✅ Resultados Esperados

| Métrica                     | Antes     | Esperado     |
|----------------------------|-----------|--------------|
| Tempo até deploy           | 2 dias    | 30 minutos   |
| Sucesso nos deploys        | 80%       | >95%         |
| Incidentes semanais        | 2         | <1           |
| MTTR                       | 4 horas   | <1 hora      |

---

## 🧾 Conclusão

Este plano fornece uma abordagem prática e abrangente para aplicar as práticas DevOps na empresa fictícia **Tech**, promovendo colaboração entre times, automação, mensuração e aprendizado contínuo.



