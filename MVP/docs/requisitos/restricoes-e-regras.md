# Restrições e regras de negócio

## Restrições

| ID | Restrição | Categoria | Justificativa / fonte |
|---|---|---|---|
| RES01 | O sistema deve ser entregue dentro do prazo da disciplina de Análise de Projeto de Sistemas. | Prazo | Calendário da disciplina |
| RES02 | A integração com o login da área do aluno depende de autorização e disponibilização de acesso pela coordenação/TI da UDF. | Infraestrutura / tecnologia | Levantamento com a coordenação |
| RES03 | O tratamento de dados pessoais deve seguir a Lei Geral de Proteção de Dados (LGPD, Lei 13.709/2018). | Legislação | Necessidade de proteger informações dos usuários |

## Regras de negócio

| ID | Regra de negócio | Fonte |
|---|---|---|
| RN01 | Somente alunos regularmente matriculados na UDF podem criar perfil de aluno. | Coordenação |
| RN02 | Somente recrutadores cadastrados podem publicar vagas. | CIEE, Coordenação |
| RN03 | O currículo e os dados pessoais do aluno só ficam visíveis ao recrutador da vaga à qual ele se candidatou. | Alunos, LGPD |

!!! tip "Para validar com a coordenação"
    Perguntem se os cadastros de recrutadores precisam de aprovação prévia antes de publicar vagas (reforçaria a RN02).
