# Portfólio — Fundamentos de Git e GitHub

Portfólio individual desenvolvido como Projeto Integrador Final do curso
**Fundamentos de Git e GitHub**, do CEFET-MG. O projeto reúne uma apresentação
do curso, registros das práticas realizadas e uma reflexão pessoal sobre o
processo de aprendizagem.

## Sobre o projeto

O objetivo deste repositório é demonstrar, por meio de um projeto organizado,
o uso de Git e GitHub em um fluxo de trabalho individual. A proposta inclui
registrar alterações com commits semânticos, organizar o trabalho em branches,
integrar mudanças por pull requests e documentar o processo.

## O que foi praticado

- Controle de versão local com Git pelo terminal.
- Criação de commits com mensagens no padrão Conventional Commits.
- Organização de alterações em branches.
- Colaboração e integração de mudanças por pull requests no GitHub.
- Acompanhamento de tarefas com issues.
- Publicação de uma página estática com GitHub Pages.

## Estrutura

```text
.
├── index.html    # Página inicial do portfólio
├── reflexao.md   # Reflexão individual sobre o aprendizado
└── README.md     # Apresentação e instruções do projeto
```

## Como visualizar

Abra `index.html` em um navegador. A página não depende de instalação de
pacotes ou de um servidor.

## Publicação com GitHub Pages

O site estático é publicado a partir da branch `main` (pasta `/ (root)`):

1. Acesse **Settings → Pages** no repositório do GitHub.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha a branch `main` e a pasta `/ (root)`, depois clique em **Save**.

## Histórico e colaboração

O desenvolvimento foi organizado com histórico semântico no padrão **Conventional Commits** (`feat`, `docs`, `style`, `fix`) e dividido em três branches temáticas integradas via Pull Requests:

- `feat/estilizacao-e-autoria`: personalização do portfólio e melhorias visuais em `index.html`.
- `docs/readme-completo`: documentação profissional e instruções do projeto em `README.md`.
- `docs/reflexao-aprendizado`: análise crítica do aprendizado em `reflexao.md`.

As tarefas do projeto foram registradas em Issues e encerradas automaticamente por meio da referência `Closes #N` nos Pull Requests correspondentes.

## Reflexão

Leia [reflexao.md](reflexao.md) para registrar, com suas próprias palavras, o
que aprendeu, os desafios encontrados e como pretende aplicar Git e GitHub em
outros projetos.

## Autoria

**Estudante:** João Pedro  
**Curso:** Fundamentos de Git e GitHub — CEFET-MG  
**Formato:** Projeto individual
