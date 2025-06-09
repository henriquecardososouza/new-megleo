# ✅ Checklist Completo para Recriação de Sistema

## 📌 1. Tecnologias e Linguagens
- [ ] Linguagens e tecnologias a serem utilizadas
- [ ] Gerenciador de dependências definido (npm, pip, composer etc.)

## 📄 2. Documentação Inicial
- [ ] Documento de requisitos completo
- [ ] Usuários e perfis do sistema
- [ ] Requisitos funcionais
- [ ] Requisitos não funcionais
- [ ] Regras de negócio
- [ ] Funcionalidades detalhadas do sistema
- [ ] Manual do usuário (se aplicável)

## 🧩 3. Diagramas e Modelagem
- [ ] Diagrama de casos de uso
- [ ] Diagramas de sequência (fluxos principais)
- [ ] Diagrama entidade-relacionamento (ER)
- [ ] Modelagem de dados
- [ ] Diagrama de arquitetura (MVC, MVVM, Clean Architecture etc.)

## 🔄 4. Organização de Código e Projeto
- [ ] Convenção de nomenclatura de variáveis, classes, constantes, funções, colunas do banco
- [ ] Convenção de organização de código definida (.editorconfig, linters)
- [ ] Padrões de commit (ex: Conventional Commits)
- [ ] Estratégia de branches (main, develop, feature/*, hotfix/* etc.)
- [ ] Regras de merge (code review obrigatório?)
- [ ] Estrutura de pastas e camadas documentada
- [ ] Documentação atualizada (pasta `docs/`)

## 🧪 5. Qualidade e Testes
- [ ] Testes unitários
- [ ] Testes de integração
- [ ] Testes end-to-end
- [ ] Coverage mínimo estabelecido
- [ ] É necessário passar em todos os testes?
- [ ] Testes automatizados em pipeline CI

## 🚦 6. Definição de Pronto (Definition of Done)
- [ ] Funciona localmente
- [ ] Funciona em ambiente de homologação
- [ ] Passa nos testes estabelecidos
- [ ] Revisão por líder do setor
- [ ] Documentação atualizada e completa
- [ ] Aprovado em controle de qualidade (ex: Teste AB)

## 🚀 7. Deploy e Infraestrutura
- [ ] Sistema de conteinerização (Docker)
- [ ] Ambiente local configurado com docker-compose
- [ ] Ambiente de homologação (staging) definido
- [ ] Ambiente de produção e pipeline de deploy automatizado
- [ ] Plano de rollback documentado
- [ ] Versionamento de banco de dados (Flyway, Prisma, Liquibase etc.)
- [ ] Backup e plano de recuperação de desastre

## 📜 8. Versionamento e Histórico
- [ ] Histórico de mudanças ao sistema (CHANGELOG.md)
- [ ] Versionamento semântico (SemVer)
- [ ] Controle de versões do banco de dados

## 🔐 9. Segurança e Privacidade
- [ ] Política de autenticação e autorização (JWT, OAuth, RBAC)
- [ ] Criptografia de dados sensíveis
- [ ] Proteção contra ataques (XSS, CSRF, SQL Injection)
- [ ] Rate limiting
- [ ] Controle de permissões por tipo de usuário
- [ ] LGPD / GDPR / políticas de privacidade

## 🕵️ 10. Auditoria e Rastreabilidade
- [ ] Log de ações críticas (edição, exclusão, login, etc.)
- [ ] Histórico de alterações por entidade
- [ ] Identificação do autor de cada ação

## 📊 11. Relatórios e Métricas
- [ ] Relatórios gerenciais essenciais definidos
- [ ] KPIs definidos (taxa de conversão, tempo médio por estágio, etc.)

## 🌍 12. Internacionalização (se aplicável)
- [ ] Sistema multi-idioma
- [ ] Formatos regionais (datas, moedas)

## 🔔 13. Monitoramento e Observabilidade
- [ ] Sistema de logs (completo, parcial, quando necessário)
- [ ] Monitoramento de uptime, erros e performance
- [ ] Alertas automáticos (ex: Sentry, Grafana, Prometheus)

## 🔌 14. Integrações Externas
- [ ] Integrações com e-mail, telefonia, ERPs ou APIs
- [ ] Estratégia de autenticação para integrações (API Key, OAuth)
- [ ] Documentação de APIs externas utilizadas

## 🧑‍💼 15. Governança e Processo
- [ ] Processo de aprovação de funcionalidades
- [ ] Rituais ágeis definidos (Sprint, Daily, Review)
- [ ] Papéis definidos (PO, Dev, QA, DevOps)
- [ ] Políticas de versionamento e publicação
