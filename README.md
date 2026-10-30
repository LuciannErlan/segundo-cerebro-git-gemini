# 🧠 Segundo Cérebro: Especialista em Git e GitHub

Repositório desenvolvido como entrega do desafio prático da **DIO (Digital Innovation One)** sobre construção de um "Segundo Cérebro com IA" utilizando o **Gemini Notebook (NotebookLM)**.

---

## 🎯 Objetivo
> *Construir um segundo cérebro especializado em versionamento com Git e GitHub, focado em arquitetura interna, estratégias de ramificação e automação CI/CD, fundamentado exclusivamente em documentação oficial e literatura técnica de referência.*

🔗 **Link do Caderno Compartilhado:** [Acessar Gemini Notebook](https://notebook.google.com/notebook/7a49b550-44d1-48d8-88ff-835f193b867e) 

---

## 📚 Curadoria de Fontes e Critérios de Confiabilidade

O caderno foi alimentado com 33 fontes em múltiplos formatos, selecionadas para equilibrar fundamentos práticos e engenharia de baixo nível:

1. **Documentação Oficial e Guias de Referência (Web):**
   - *Git SCM Official Book & Docs* (Git Objects, Git Rebase): Referência canônica do motor de versionamento.
   - *GitHub Docs* (Branch Protection, Custom Actions, Dependabot Alerts): Padrões oficiais de segurança e governança de código.
2. **Literatura Didática Estruturada (PDF):**
   - *Git e Github.pdf* (Fernanda Santos): Visão pedagógica com conceitos de ciclo de vida local (*working directory*, *stage*, *commit*).
3. **Engenharia e Artigos Técnicos de Arquitetura:**
   - *A Deep Dive into Git Internals (DEV Community)* e *Git Object Model*: Explicação do modelo de objetos (*blobs*, *trees*, *commits*, *refs*).
   - *Atlassian & LaunchDarkly*: Análise comparativa entre *Trunk-Based Development* e *Git Flow*.

---

## 🤖 Diretriz de Comportamento (Prompt de Especialista)

> *"Atue como um Arquiteto de Software especialista em controle de versão e DevOps. Suas respostas devem ser estritamente fundamentadas nas fontes anexadas neste caderno. Ao explicar comandos ou estratégias, justifique com a mecânica interna do Git (blobs, trees e commits) ou com as boas práticas documentadas do GitHub, sempre indicando a fonte exata consultada e alertando quando um tópico não constar no material de apoio."*

---

## 💬 Validação e Evidências com Citações

### Pergunta 1: Como o Git armazena dados internamente e qual a função dos objetos `blob` e `tree`?
* **Resposta sintetizada pelo Notebook:** O Git opera como um sistema de arquivos endereçado por conteúdo (chave-valor baseado em SHA-1/SHA-256). O objeto `blob` (*binary large object*) armazena exclusivamente o conteúdo bruto do arquivo, sem metadados nem nome. O objeto `tree` funciona como o diretório, mapeando os nomes dos arquivos, permissões e associando-os aos hashes dos respectivos `blobs` ou sub-árvores.
* **Fontes citadas:**
  - *Git Objects - Git SCM Book*
  - *A Deep Dive into Git Internals: Blobs, Trees, and Commits (DEV Community)*

### Pergunta 2: Quando utilizar Trunk-Based Development em vez de Git Flow?
* **Resposta sintetizada pelo Notebook:** O Git Flow utiliza branches de longa duração (*develop*, *release*, *feature*), sendo adequado para softwares com ciclos de lançamento tradicionais. Já o Trunk-Based Development preconiza que todos trabalhem em uma branch única (*main/trunk*) com branches de vida curtíssima ou *feature flags*, ideal para esteiras de Integração Contínua (CI/CD) e entregas frequentes.
* **Fontes citadas:**
  - *Trunk-based Development | Atlassian*
  - *Git Branching Strategies vs. Trunk-Based Development - LaunchDarkly*



## 📦 Materiais Gerados no Estúdio

A partir do conhecimento sintetizado nas fontes, foram gerados e exportados:
- [x] **Guia de Estudos / Resumo:** Resumo das funções essenciais e fluxo de trabalho Git (`assets/guia-de-estudos.pdf`).
- [x] **Mapa Mental:** Diagrama conceitual do ciclo de vida dos arquivos e objetos Git (`assets/mapa-mental-git.png`).
- [x] **Evidências do Chat:** Capturas de tela comprovando a ancoragem das respostas nas fontes (`assets/chat-evidencia-01.png`).

---

## 📋 Checklist de Submissão

- [x] Repositório público no GitHub com nome legível em minúsculas e sem acentos (`segundo-cerebro-git-gemini`).
- [x] Respostas no README com indicação explícita das fontes de origem.
- [x] Link do caderno compartilhado e acessível.
- [x] Materiais do Estúdio anexados e referenciados no repositório.
