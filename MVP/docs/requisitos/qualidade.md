# Requisitos de qualidade

Escritos de forma **mensurável e verificável**.

| ID | Característica | Requisito | Como será verificado |
|---|---|---|---|
| RQ01 | Desempenho | O sistema deve exibir o resultado de uma busca de vagas em até 3 segundos para 95% das requisições, com até 500 vagas ativas. | Teste de carga simples (por exemplo, k6 ou JMeter) e medição no navegador |
| RQ02 | Segurança | O sistema deve armazenar senhas com hash, trafegar dados via HTTPS e permitir que currículo e dados pessoais sejam vistos apenas pelo próprio aluno e pelo recrutador da vaga à qual ele se candidatou. | Revisão de código e testes de acesso por perfil (aluno, recrutador, visitante) |
| RQ03 | Usabilidade e interação | Pelo menos 80% dos alunos de um teste com 5 ou mais participantes devem conseguir se cadastrar e se candidatar a uma vaga em até 5 minutos, sem ajuda. | Teste de usabilidade com alunos da UDF e cronometragem |
| RQ04 | Confiabilidade | O sistema deve ter disponibilidade mínima de 99% ao mês, medida em horário comercial. | Monitoramento de uptime (por exemplo, UptimeRobot) |
| RQ05 | Compatibilidade e portabilidade | O sistema deve funcionar nas duas últimas versões de Chrome, Firefox e Edge e em telas a partir de 360 px de largura. | Testes manuais nos navegadores e no modo responsivo do DevTools |
