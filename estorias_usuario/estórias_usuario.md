## **História de Usuário**

### **ID:**  
HU-001

### **Título:**  
Reporte de Sintomas e Casos Suspeitos de Dengue

### **Descrição:**  
Como **usuário da população geral**, eu quero **reportar sintomas e casos suspeitos de dengue pelo aplicativo** para que **possa informar as autoridades de saúde sobre possíveis novos casos de forma rápida e fácil**.

### **Critérios de Aceitação:**

#### Cenário 1: Reporte de sintomas com sucesso
- **Dado** que o usuário está na tela de reporte de sintomas,
- **Quando** o usuário preenche o formulário com seus sintomas e localização,
- **E** envia o formulário,
- **Então** o sistema deve confirmar o recebimento dos dados e enviar uma notificação às autoridades de saúde.

#### Cenário 2: Falha no envio por falta de dados
- **Dado** que o usuário está na tela de reporte de sintomas,
- **Quando** o usuário tenta enviar o formulário sem preencher todos os campos obrigatórios,
- **Então** o sistema deve exibir uma mensagem de erro solicitando o preenchimento dos dados obrigatórios,
- **E** o usuário deve poder preencher os dados que faltam.

### **Prioridade:**  
Alta

### **Estimativa de Esforço:**  
5 Story Points

### **Dependências:**  
- Integração com o sistema de monitoramento de autoridades de saúde.

### **Notas/Comentários Adicionais:**
- O sistema deve garantir que a localização do usuário seja precisa para o envio de alertas regionais.

## **História de Usuário**

### **ID:**  
HU-002

### **Título:**  
Dicas e Informações de Prevenção contra a Dengue

### **Descrição:**  
Como **usuário da população geral**, eu quero **receber dicas e informações de prevenção contra a dengue diretamente no aplicativo** para que **eu saiba as formas mais adequadas de como me proteger e ajudar a combater a propagação da doença**.

### **Critérios de Aceitação:**

#### Cenário 1: Recebimento de dicas com sucesso
- **Dado** que o usuário tem o aplicativo instalado,
- **Quando** há novas informações ou dicas de prevenção,
- **Então** o sistema deve enviar notificações ou mensagens dentro do aplicativo com essas informações.

#### Cenário 2: Falha no recebimento de dicas
- **Dado** que o usuário tem o aplicativo instalado,
- **Quando** ocorre uma falha na entrega de dicas ou notificações,
- **Então** o sistema deve exibir uma mensagem de erro e registrar o problema para ser resolvido.

### **Prioridade:**  
Média

### **Estimativa de Esforço:**  
3 Story Points

### **Dependências:**  
- Conexão estável com o servidor e atualização de conteúdo de prevenção.

### **Notas/Comentários Adicionais:**
- As dicas devem ser adaptadas para cada região, de acordo com o nível de risco.

## **História de Usuário**

### **ID:**  
HU-003

### **Título:**  
Visualização em Tempo Real da Incidência de Dengue

### **Descrição:**  
Como **autoridade de saúde pública**, eu quero **visualizar em tempo real os dados sobre a incidência de dengue em diferentes regiões** para que **eu possa tomar decisões estratégicas e intervir rapidamente nas áreas com maior risco**.

### **Critérios de Aceitação:**

#### Cenário 1: Monitoramento em tempo real
- **Dado** que a autoridade de saúde está na tela de monitoramento,
- **Quando** há novos dados de casos de dengue,
- **Então** o sistema deve atualizar automaticamente os dados no mapa e nos gráficos.

#### Cenário 2: Falha na atualização dos dados
- **Dado** que a autoridade de saúde está na tela de monitoramento,
- **Quando** ocorre uma falha na atualização dos dados,
- **Então** o sistema deve exibir uma mensagem de erro e notificar o suporte técnico.

### **Prioridade:**  
Alta

### **Estimativa de Esforço:**  
 8 Story Points
 
### **Dependências:**  
- Integração com a base de dados de casos reportados.

### **Notas/Comentários Adicionais:**
- As autoridades devem poder visualizar filtros por região e por período.

## **História de Usuário**

### **ID:**  
HU-004

### **Título:**  
Relatórios e Alertas Automáticos

### **Descrição:**  
Como **autoridade de saúde pública**, eu quero **receber relatórios automáticos e alertas quando houver aumento de casos em uma determinada região** para que **eu possa direcionar os recursos de forma eficiente e rápida para o controle da doença**.

### **Critérios de Aceitação:**

#### Cenário 1: Recebimento de relatórios e alertas automáticos com sucesso
- **Dado** que a autoridade de saúde pública está cadastrada no sistema,
- **Quando** os casos de dengue aumentam significativamente em uma região específica,
- **Então** o sistema deve enviar relatórios automáticos e alertas à autoridade responsável.

#### Cenário 2: Falha no envio de relatórios e alertas
- **Dado** que os dados de dengue estão disponíveis no sistema,
- **Quando** ocorre uma falha no envio de relatórios e alertas automáticos,
- **Então** o sistema deve registrar a falha e notificar o suporte técnico para correção.

### **Prioridade:**  
Alta

### **Estimativa de Esforço:**  
6 Story Points

### **Dependências:**  
- Integração com o sistema de monitoramento de casos e geração de relatórios automáticos.

### **Notas/Comentários Adicionais:**
- Os relatórios devem conter informações detalhadas sobre a área de incidência e recomendações de ação.

## **História de Usuário**

### **ID:**  
HU-005

### **Título:**  
Confirmação de Casos de Dengue

### **Descrição:**  
Como **profissional de saúde em um postinho**, eu quero **confirmar e reportar casos diagnosticados de dengue no sistema** para que **os dados sejam coletados corretamente e ajudem a monitorar a situação na minha área**.

### **Critérios de Aceitação:**

#### Cenário 1: Confirmação de casos com sucesso
- **Dado** que o profissional de saúde está na tela de confirmação de casos,
- **Quando** o profissional insere os dados de um paciente diagnosticado com dengue,
- **E** envia os dados,
- **Então** o sistema deve confirmar o recebimento e registrar o caso no banco de dados central.

#### Cenário 2: Falha no envio de dados de casos
- **Dado** que o profissional de saúde está inserindo os dados de um paciente,
- **Quando** ocorre uma falha no envio dos dados ao sistema,
- **Então** o sistema deve exibir uma mensagem de erro e permitir o reenvio após a correção.

### **Prioridade:**  
Alta

### **Estimativa de Esforço:**  
5 Story Points

### **Dependências:**  
- Conexão com o sistema central de registro de casos de dengue.

### **Notas/Comentários Adicionais:**
- O sistema deve permitir que os profissionais de saúde filtrem os casos confirmados por região.

## **História de Usuário**

### **ID:**  
HU-006

### **Título:**  
Acesso Diferenciado para Profissionais de Saúde a Informações Sensíveis sobre Dengue

### **Descrição:**

Como **profissional de saúde**, eu quero **ter acesso diferenciado ao sistema para visualizar informações sensíveis e exclusivas sobre casos confirmados de dengue,** para que **possa gerenciar e reportar os dados de forma segura e eficaz.**

### **Critérios de Aceitação:**

#### Cenário 1: Reporte de sintomas com sucesso
- **Dado** que o profissional de saúde está autenticado no sistema,
- **Quando** o profissional acessa a seção de casos confirmados de dengue,
- **Então** o sistema deve exibir informações detalhadas e sensíveis sobre os casos, como dados pessoais do paciente e histórico de saúde.

#### Cenário 2: Falha no envio por falta de dados
- **Dado** que um usuário não autorizado tenta acessar a seção de informações sensíveis,
- **Quando** o usuário tenta visualizar dados restritos,
então o sistema deve exibir uma mensagem de erro informando que o acesso não é permitido e seu respectivo acesso deve ser negado.
- **Então** o sistema deve exibir uma mensagem de erro informando que o acesso não é permitido,
- **E**o acesso deve ser negado.

#### Cenário 3: Reporte de dados com sucesso
- **Dado** que o profissional de saúde está na tela de gerenciamento de dados,
- **Quando** o profissional preenche o relatório de um novo caso confirmado,
E o acesso deve ser negado.
- **Então** o sistema deve salvar os dados com segurança e enviar uma notificação para o sistema central de monitoramento de dengue.

### **Prioridade:**  
Alta

### **Estimativa de Esforço:**  
8 Story Points

### **Dependências:**  
- Sistema de autenticação e controle de acesso baseado em níveis de permissão.
Integração com a base de dados de monitoramento de dengue.

### **Notas/Comentários Adicionais:**
- O acesso a essas informações deve estar em conformidade com a legislação de proteção de dados pessoais (LGPD/GPDR).

## **História de Usuário**

### **ID:**

HU-007

### **Título:**

Identificação de Áreas de Risco

### **Descrição:**

Como **uma autoridade de saúde pública**, eu quero **acessar ferramentas de análise que me permitam identificar tendências e áreas de risco de forma eficiente**, para que **possa implementar estratégias de prevenção e controle da dengue nas regiões mais afetadas**.

### **Critérios de Aceitação:**

#### Cenário 1: Acesso bem-sucedido às ferramentas de análise

- **Dado** que o usuário está autenticado como autoridade de saúde pública,
- **Quando** o usuário acessar a seção de ferramentas de análise,
- **Então** o sistema deve exibir as tendências e áreas de risco.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

6 Story Points

### **Dependências:**

- Conexão estável com o servidor de informações de saúde.

### **Notas/Comentários Adicionais:**

- As informações devem ser atualizadas conforme novas diretrizes ou descobertas sobre a dengue.

- É importante que o sistema tenha alta usabilidade, permitindo que as autoridades possam navegar e interagir com as ferramentas de análise com facilidade, mesmo sem conhecimentos técnicos avançados.

## **História de Usuário**

### **ID:**

HU-008

### **Título:**

Acesso a Informações de Sintomas da Dengue

### **Descrição:**

Como **usuário da população geral**, eu quero **acessar informações detalhadas sobre os sintomas da dengue através do aplicativo**, para que **possa identificar rapidamente se estou com sintomas da doença e buscar atendimento adequado**.

### **Critérios de Aceitação:**

#### Cenário 1: Acesso bem-sucedido às informações de sintomas

- **Dado** que o usuário está na tela de informações de saúde,
- **Quando** o usuário acessa a seção de sintomas da dengue,
- **Então** o sistema deve exibir uma lista clara e detalhada dos sintomas da dengue com descrições fáceis de entender.

#### Cenário 2: Falha no carregamento das informações de sintomas

- **Dado** que o usuário está na tela de informações de saúde,
- **Quando** o sistema falha ao carregar as informações de sintomas,
- **Então** o sistema deve exibir uma mensagem de erro e permitir que o usuário tente recarregar as informações.

### **Prioridade:**

Alta

### **Estimativa de Esforço:**

4 Story Points

### **Dependências:**

- Conexão estável com o servidor de informações de saúde.

### **Notas/Comentários Adicionais:**

- As informações devem ser atualizadas conforme novas diretrizes ou descobertas sobre a dengue.

