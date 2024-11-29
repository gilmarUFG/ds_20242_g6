## ds_20242_g6
Repositório definido para a manutenção do controle de versão dos artefatos do projeto de do Grupo 6, da Disciplina de Domínios de Software, no semestre 2024-2.

### Nome do Projeto:
InfoDengue

### Descrição:
O sistema proposto busca melhorar a coleta e análise de dados sobre a dengue, servindo como um canal de comunicação e orientação para a população, por meio da disponibilização de informações atualizadas para prevenir e combater a doença, além contribuir significativamente para o controle e combate da dengue, com a emissão de relatórios e dados úteis para profissionais e autoridades de saúde.

### Problema
- *Falta de Informação e Conscientização:*
  - A população muitas vezes não sabe identificar sintomas de dengue ou o que fazer em casos suspeitos.
  - Necessidade de um canal direto de comunicação entre a população e as autoridades de saúde.

- *Subnotificação e Atraso na Coleta de Dados:*
  - Ineficiência na notificação de casos de dengue, dificultando a ação rápida.
  - Dados fragmentados que dificultam a análise e a tomada de decisões.

- *Incapacidade de Monitoramento em Tempo Real:*
  - Ausência de um sistema integrado que permita o monitoramento em tempo real da incidência de dengue.


### Objetivos da Solução
1. *Coleta de Dados*
   - Coletar dados sobre casos de dengue de duas fontes: população geral e postos de saúde.

2. *Auxílio à População*
   - Fornecer informações e dicas sobre dengue, incluindo prevenção e o que fazer em caso de suspeita.
   - Permitir que a população reporte sintomas e casos suspeitos através de um aplicativo.

3. *Análise e Ação Governamental*
   - Fornecer dados precisos e em tempo real sobre a incidência de dengue para as autoridades.
   - Ajudar na identificação de áreas de risco e na tomada de decisões para intervenções

### Grupo
Este projeto será desenvolvido pelos componentes do grupo 6:

|Matrícula|Nome|Usuário Git|
|---|---|---|
|202201690|FREDERICO GARCEZ RODRIGUES|[<usuario_github>](https://github.com/<usuario_github>)|
|202201693|HUGO MORENO I VEIGA JARDIM|[hugojardim](https://github.com/hugojardim)|
|202105042|KELVIN DE OLIVEIRA|[<usuario_github>](https://github.com/<usuario_github>)|
|202201718|VITOR PAULO ETERNO GODOI|[akzvitor](https://github.com/akzvitor)|
|202405056|WENDEL MÁRCIO DE OLIVEIRA FILHO|[Wendel-Fl](https://github.com/Wendel-Fl)|

## Backlog do Produto

### Requisitos Funcionais

1. RF001 - População geral pode informar os sintomas e casos de suspeita de dengue.

2. RF002 - População geral recebe orientações e dicas de prevenção à dengue.

3. RF003 - Autoridades de saúde, população e profissionais de saúde podem visualizar em tempo real a incidência dos casos de dengue.

4. RF004 - Autoridades de saúde recebem relatórios e alertas automáticos.

5. RF005 - Profissionais de saúde podem confirmar e reportar casos diagnosticados de dengue.

6. RF006 - Profissionais de saúde possuem acesso a informações sensíveis sobre pacientes e a dengue.

7. RF007 - Autoridades de saúde possuem acesso a ferramentas de análise para identificar tendências e áreas de risco.

8. RF008 - População geral possuem acesso a informações detalhadas sobre a dengue e seus sintomas.

### Requisitos Não Funcionais

1. RNF001 - Usabilidade
    - O sistema deve ser intuitivo e fácil de usar, com uma interface gráfica clara e consistente, garantindo que o usuário consiga realizar suas tarefas de forma eficiente com um mínimo de esforço e treinamento.

2. RNF002 - Manutenibilidade
    - O sistema deve ser projetado de forma modular e documentada para facilitar a realização de futuras atualizações e correções, sem impacto significativo nas funcionalidades existentes.

3. RNF003 - Conectividade
    - O sistema deve ser capaz de se conectar com outros sistemas externos através de APIs padrão, suportando protocolos como REST, garantindo comunicação em tempo real e troca de informações entre diferentes plataformas.

4. RNF004 - Confiabilidade
    - O sistema deve operar de forma consistente, garantindo que as funcionalidades estejam disponíveis para uso 99,9% do tempo durante horários críticos de monitoramento (7h às 22h).

5. RNF005 - Segurança
    - Todas as tentativas de acesso não autorizado devem ser registradas, e alertas devem ser enviados à administração do sistema.

6. RNF006 - Portabilidade
    - O sistema deve permitir a migração de dados para diferentes sistemas de banco de dados relacionais (como SQL Server, PostgreSQL ou MySQL) sem perda de informações, seguindo padrões de interoperabilidade e documentação clara.

7. RNF007 - Desempenho
    - O tempo de resposta da API deve ser inferior a 2 segundos para 95% das requisições sob carga normal (até 100 requisições simultâneas).

### Regras de Negócio
1. RN01 - Apenas usuários autenticados podem registrar casos suspeitos de dengue no sistema..
2. RN02 - Um usuário pode relatar no máximo três casos suspeitos por dia a partir de seu dispositivo..
3. RN03 - Relatos de sintomas feitos pela população devem ser marcados como "não confirmados" até serem analisados por profissionais de saúde ou confirmados por autoridades.
4. RN04 - Autoridades de saúde podem acessar dados consolidados sobre casos suspeitos e confirmados, segmentados por região, data e faixa etária.
5. RN05 - Autoridades devem ser notificadas automaticamente quando o número de casos suspeitos em uma região ultrapassar 50 relatos em um período de 7 dias.
6. RN06 - Apenas profissionais de saúde vinculados a um posto previamente autorizado podem registrar casos confirmados de dengue.
7. RN07 - Os profissionais de saúde podem revisar relatos da população e atualizá-los para "sob investigação" caso entrem em contato com o paciente para verificar os sintomas relatados.
8. RN08 - Caso uma região esteja identificada como "área de surto", profissionais de saúde dessa localidade devem receber alertas prioritários para priorizar atendimentos.
9. RN09 - Dados pessoais dos usuários devem ser protegidos conforme a LGPD (Lei Geral de Proteção de Dados), garantindo que informações sensíveis sejam acessadas apenas por usuários autorizados.

### Modelo Arquitetural
O Modelo Arquitetural do sistema será baseado em Microserviços.

### Modelo de Interfaces Gráficas
O modelo de Interfaces será realizado por meio de um projeto Figma - [InfoDengue](https://www.figma.com/design/gmeExAkk7vDHjXwUQvQ9pY/InfoDengue?node-id=0-1&t=O3nl1Yg0QdzqHRQA-1)

### Tecnologia de Persistência de Dados
Primeiramente iremos usar `PostgreSQL`, mas também testaremos a possibilidade de usar bancos _NoSQL_ como `MongoDB`.

### Local do _Deploy_
O nosso planejamento inicial é hospedar a aplicação back-end no [Heroku](https://www.heroku.com/) e a aplicação front-end na [Versel](https://vercel.com/), sendo crucial para nossa escolha a facilidade de configuração e também os recursos ofertados na versão gratuita. Apesar da escolha, também analisaremos a possibilidade de usar a `AWS`.

### Cronograma de Desenvolvimento

|Descrição|Data Início|Data Fim|Responsável|Situação|
|---|---|---|---|---|
|Concepção|30/08/2024|13/09/2024|Grupo|Concluída|
|Preparação|14/09/2024|27/09/2024|Grupo|Conluída|
|Design e Planejamento Inicial, definição dos diagramas e Histórias de Usuário|28/09/2024|10/10/2024|Grupo|Concluída|
|Histórias de Usuário|28/09/2024|08/10/2024|Grupo|Concluída|
|Construção dos diagramas de classe, sequência, atividades e classes de análise|11/10/2024|11/11/2024|Grupo|Parcialmente concluída|
|Construção do Diagrama C4 Model|20/11/2024|11/12/2024|Grupo|Em andamento|
|Design de interfaces no Figma |27/11/2024|12/12/2024|Grupo|Em andamento|
|Apresentação do Projeto|13/12/2024|13/12/2024|Grupo|Programada|

* Implementação se aplicará, se os itens da iteração em andamento, forem eleitos para validação do projeto do trabalho.