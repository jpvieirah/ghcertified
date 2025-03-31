---
archetype: "questions"
title: "Questão 012"
question: "O GitHub Copilot pode usar informações semânticas de um arquivo que é ignorado pelas exclusões de conteúdo do GitHub Copilot?"
---

> https://docs.github.com/en/copilot/managing-copilot/configuring-and-auditing-content-exclusion/excluding-content-from-github-copilot#limitations-of-content-exclusions
1. [x] Sim, se as informações forem fornecidas indiretamente pelo IDE.
1. [ ] Não, ele ignorará todas as informações de arquivos excluídos.
> É possível que o Copilot use informações semânticas de um arquivo excluído se essas informações forem fornecidas indiretamente pelo IDE. Exemplos de tais conteúdos incluem informações de tipo e definições exibidas ao passar o mouse sobre símbolos usados no código, bem como propriedades gerais do projeto, como informações de configuração de build.
