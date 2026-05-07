# Pipeline HTML Simples com GitHub Actions

Este projeto demonstra um exemplo básico de automação utilizando **GitHub Actions** para monitorar alterações em arquivos HTML e executar validações automáticas.

O objetivo é apresentar conceitos iniciais de **CI (Continuous Integration)**, eventos automatizados e importância da documentação em projetos de software.

---

# Objetivo do Pipeline

Sempre que houver alteração em arquivos `.html` no repositório, o GitHub Actions executará automaticamente um workflow que:

- Detecta alterações em arquivos HTML;
- Realiza uma validação simples;
- Dispara um job de notificação simulando um processo automatizado.

---

# Estrutura do Projeto

```text
.
├── .github
│   └── workflows
│       └── pipeline-html.yml
├── index.html
└── README.md