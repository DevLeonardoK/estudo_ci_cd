# estudo_ci_cd
Repositório para estudar e desenvolver ci/cd

# Nome do Projeto

## 📋 Estrutura de Branches

- **main** - Branch principal (produção)
- **qa** - Ambiente de testes/homologação (protegida)
- **dev** - Ambiente de desenvolvimento

## 🔄 Fluxo de Trabalho

1. Desenvolvedores criam branches `feature/*` a partir de `dev`
2. Após desenvolvimento, abrem PR para `dev`
3. Para subir para QA, abrem PR de `dev` → `qa` (requer aprovação do gestor)

## 👥 Papéis

- **Desenvolvedores**: Criam features e abrem PRs
- **Gestor**: Aprova e faz merge para QA