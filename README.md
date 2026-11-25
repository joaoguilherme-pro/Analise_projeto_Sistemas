<p align="center">
  <img src="https://placehold.co/1200x260/123b70/ffffff?text=UDF+NEED+VAGAS" alt="UDF NeedVagas" width="100%">
</p>

<p align="center">
  Canal oficial de estágios para aproximar estudantes da UDF e recrutadores.<br>
  Projeto da disciplina Análise de Projeto de Sistemas — Centro Universitário UDF, turma D2, 2026.
</p>

<p align="center">
  <a href="https://joaoguilherme-pro.github.io/Analise_projeto_Sistemas/"><strong>Documentação</strong></a> ·
  <a href="ProjetoAPS/">Projeto acadêmico</a> ·
  <a href="MVP/">Documentação MkDocs</a>
</p>

---

## Sobre

O **UDF NeedVagas** é uma proposta de canal oficial de estágios voltada aos estudantes da UDF. O projeto busca aproximar alunos e recrutadores, facilitando a divulgação e a consulta de oportunidades em um ambiente direcionado à comunidade acadêmica.

Hoje, as vagas nem sempre estão atualizadas ou são fáceis de encontrar. O projeto pretende tornar o processo mais eficiente, permitindo a divulgação de oportunidades adequadas aos cursos da UDF e oferecendo aos estudantes um ambiente organizado para conhecer vagas e apresentar seus dados profissionais.

A visão do produto, os requisitos funcionais e de qualidade, as regras de negócio, a rastreabilidade e a priorização do MVP estão disponíveis na [documentação do projeto](https://joaoguilherme-pro.github.io/Analise_projeto_Sistemas/).

## Organização do repositório

| Onde | O quê |
| --- | --- |
| [`MVP/`](MVP/) | documentação do produto em MkDocs Material |
| [`MVP/docs/`](MVP/docs/) | páginas sobre cenário, solução, requisitos, processo e equipe |
| [`ProjetoAPS/`](ProjetoAPS/) | materiais de levantamento, priorização e análise dos requisitos |
| [`LICENÇA`](LICENÇA) | termos de uso e distribuição deste projeto |

## Rodar a documentação

```bash
cd MVP
pip install mkdocs-material
mkdocs serve
```

Acesse `http://127.0.0.1:8000/` no navegador.

## Publicar no GitHub Pages

O site é publicado pelo GitHub Actions na branch `gh-pages`. Nas configurações de *Pages* do repositório, selecione a branch `gh-pages` como fonte da publicação.

## Equipe UDF NeedVagas

João Guilherme Sousa Sales · Enzo Cortes de Lima · Caio Gomes Neto Maia da Silva · Samuel Borges Cordeiro

## Licença

Consulte o arquivo [`LICENÇA`](LICENÇA) para verificar os termos de uso deste projeto.
