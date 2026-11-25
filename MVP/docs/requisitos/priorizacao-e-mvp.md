# Priorização e MVP

## Técnica MoSCoW

| Categoria | Significado |
|---|---|
| 🔴 **M - Must Have** | Requisito indispensável |
| 🟠 **S - Should Have** | Muito importante, mas pode esperar temporariamente |
| 🟢 **C - Could Have** | Desejável se houver tempo e recursos |
| ⚪ **W - Won't Have Now** | Não será implementado nesta entrega |

## Matriz de priorização

| ID | Requisito | MoSCoW | Justificativa |
|---|---|:---:|---|
| RF01 | Cadastro de recrutadores | 🔴 M | Sem recrutadores não há vagas |
| RF02 | Cadastro de alunos (login UDF) | 🔴 M | Sem alunos não há público, e o login garante que são da UDF |
| RF03 | Publicar vagas | 🔴 M | É o conteúdo central do portal |
| RF04 | Currículo no perfil | 🟠 S | Muito útil, mas a candidatura inicial pode usar os dados do cadastro |
| RF05 | Certificações no perfil | 🟢 C | Complementa o currículo |
| RF06 | Foto e legenda no perfil | 🟢 C | Estética, sem impacto no fluxo principal |
| RF07 | Barra de pesquisa | 🔴 M | Resolve diretamente a dificuldade de encontrar vagas |
| RF08 | Filtros de pesquisa | 🟠 S | Refina a busca, mas a pesquisa simples já funciona |
| RF09 | Candidatura dentro do portal | 🔴 M | Evita o uso de outros sites para se candidatar |
| RF10 | Lembretes de novas vagas | 🟠 S | Notificação foi considerada necessária no levantamento, mas depende de haver vagas |
| RF11 | Avaliações de empresas | 🟢 C | Ajuda a N02, mas exige massa de usuários para ter valor |
| RF12 | Chat recrutador-aluno | ⚪ W | Alto esforço (tempo real e moderação) e o contato pode ser feito fora do portal no início |
| RQ01 | Desempenho | 🟠 S | Importante para a experiência, com volume baixo no início |
| RQ02 | Segurança | 🔴 M | Dados pessoais e exigência da LGPD |
| RQ03 | Usabilidade e interação | 🟠 S | A baixa visibilidade foi a causa do problema do sistema atual |
| RQ04 | Confiabilidade | 🟠 S | Desejável, mas instabilidade é aceitável no MVP |
| RQ05 | Compatibilidade e portabilidade | 🟢 C | Cobrir os navegadores principais já é suficiente |

## Requisitos da primeira versão (MVP)

| Ordem | ID | Requisito | Por que na primeira versão? |
|:---:|---|---|---|
| 1 | RF02 | Cadastro de alunos com login UDF | Base de usuários e garantia de que são alunos da UDF |
| 2 | RF01 | Cadastro de recrutadores | Origem das vagas |
| 3 | RF03 | Publicar vagas | Conteúdo central do portal |
| 4 | RF07 | Barra de pesquisa | Principal necessidade do aluno: achar vagas |
| 5 | RF09 | Candidatura no portal | Fecha o ciclo aluno, vaga e recrutador |

!!! info "E o RQ02 (Segurança)?"
    Também é Must, mas como característica transversal ele vale para todos os cinco requisitos acima, e por isso não ocupa uma das cinco vagas.

### Critérios de aceitação do MVP

- [ ] **RF02**: aluno com credenciais válidas da UDF consegue criar o perfil; credenciais inválidas são recusadas.
- [ ] **RF01**: recrutador consegue se cadastrar informando nome, empresa e e-mail de contato.
- [ ] **RF03**: recrutador cadastrado publica uma vaga com todos os campos obrigatórios e ela aparece na listagem.
- [ ] **RF07**: ao digitar uma palavra-chave, o aluno vê apenas vagas relacionadas.
- [ ] **RF09**: o aluno se candidata, o recrutador vê a candidatura e o aluno vê que já se candidatou.

## Requisitos para versões futuras

| ID | Requisito | Motivo para adiar | Impacto |
|---|---|---|---|
| RF12 | Chat recrutador-aluno | Alto esforço técnico (tempo real, moderação) | Baixo: o contato pode ocorrer por e-mail no início |
| RF11 | Avaliações de empresas | Só gera valor com muitos usuários | Médio: atenderia melhor a N02 mais adiante |
| RF06 | Foto e legenda nos perfis | Não afeta o fluxo principal | Baixo: apenas estético |
| RF05 | Certificações no perfil | Complementa o currículo, que também fica fora do MVP | Baixo a médio |
