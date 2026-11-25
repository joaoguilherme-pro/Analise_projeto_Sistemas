# Requisitos funcionais

Os requisitos funcionais descrevem o que o sistema **deve fazer**. A prioridade segue a técnica MoSCoW (veja [Priorização e MVP](priorizacao-e-mvp.md)).

!!! note "Legenda de prioridade"
    🔴 **M** Must · 🟠 **S** Should · 🟢 **C** Could · ⚪ **W** Won't (nesta entrega)

| ID | Requisito funcional | Fonte | Necessidade | Prioridade |
|---|---|---|---|:---:|
| RF01 | O sistema deve permitir o cadastro de recrutadores. | Coordenação, CIEE | N01 | 🔴 M |
| RF02 | O sistema deve permitir o cadastro de alunos usando as credenciais da área do aluno da UDF. | Coordenação, Alunos | N04 | 🔴 M |
| RF03 | O sistema deve permitir que o recrutador publique vagas com nome, especialização, remuneração (salário ou não remunerado), localidade e demais dados da vaga. | CIEE, Alunos | N01, N02, N03 | 🔴 M |
| RF04 | O sistema deve permitir que o aluno insira e atualize seu currículo no perfil. | Alunos | N01 | 🟠 S |
| RF05 | O sistema deve permitir que o aluno insira certificações no perfil. | Alunos | N02 | 🟢 C |
| RF06 | O sistema deve permitir foto e legenda (descrição curta) nos perfis de alunos e recrutadores. | Alunos | N04 | 🟢 C |
| RF07 | O sistema deve disponibilizar uma barra de pesquisa para buscar vagas por palavra-chave. | Alunos | N01, N04 | 🔴 M |
| RF08 | O sistema deve permitir filtrar vagas por especialização, remuneração, empresa e localidade. | Alunos | N01, N04 | 🟠 S |
| RF09 | O sistema deve permitir que o aluno se candidate a uma vaga dentro do portal. | Alunos | N01, N04 | 🔴 M |
| RF10 | O sistema deve enviar lembretes ao aluno sobre a abertura de novas vagas de seu interesse. | Alunos | N01 | 🟠 S |
| RF11 | O sistema deve permitir que alunos avaliem empresas e vagas. | Alunos, Coordenação | N02 | 🟢 C |
| RF12 | O sistema deve oferecer chat para comunicação entre recrutador e aluno. | Alunos, CIEE | N01 | ⚪ W |

!!! warning "RF09 foi adicionado na análise"
    A lista original de requisitos não tinha a candidatura, mas o levantamento cita "inscrições em vagas abertas" como tarefa repetitiva e a dificuldade de precisar de outros sites para se candidatar. Sem o RF09 o portal só listaria vagas. Confirmem com o grupo se concordam.
