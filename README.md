# Integração Azure Data Factory com Azure DevOps

Este projeto demonstra como integrar o **Azure Data Factory** com o **Azure DevOps**, habilitando versionamento de pipelines, controle de mudanças, backups automáticos e estruturação para CI/CD.

## 📌 Objetivos

- Controlar versões de pipelines e datasets no Data Factory.
- Rastrear mudanças e facilitar rollback.
- Automatizar backups com templates ARM.
- Preparar o ambiente para CI/CD com DevOps.

## 🔧 Estrutura do Projeto

- `datafactory/ARMTemplate`: Contém os arquivos exportados do ADF.
- `devops/`: Exemplo de pipeline CI/CD.
- `scripts/`: Scripts de automação, como exportação de templates.
- `config/`: Arquivos auxiliares de configuração.

## 🧪 Etapas do Projeto

1. **Criação da organização e projeto no Azure DevOps**
2. **Configuração do Git no Azure DevOps**
3. **Conexão com o Azure Data Factory via Git**
4. **Exportação dos templates ARM do ADF**
5. **Versionamento no repositório Git**
6. **(Opcional) Pipeline de CI/CD no DevOps**

## 📸 Screenshots

> Adicione imagens em `/docs/imagens` mostrando a integração e as etapas do processo.

## 📁 Exemplo de Pipeline (CI)

Veja `devops/pipeline-exemplo.yml` para um modelo básico de CI/CD com deploy automatizado.


