# landing page - techflow

## objetico
desenvolver uma landing page a techflow, uma startup de tecnologia sustentavel para visitantes e capturar leads
 
 ## escopo
 -header fixo com navegação.
 -seção inicial com chamada para ação.
  -formulario de contato funcional.
 -desing responsivo basico.

 # levantamentos de requisitos

antes da criação das issuues, foi realizada uma entrevista inicial com clientes para entender as necessidades do projeto.

# requisitos não funcionais
-layout responsivo
-ultilizar cores associdas á sustentabilidade.
-codigo html validos
-projeto versionado e gerenciado via github

# requisitos funcionais
-apresentar uma seção inicial com chamada principal
-disponibilizar um formulario de contato
-coletar nome e-mail no formulario
exibir configuração visual apos envio do formulario  

# tecnologias
-html, css3, javascript (vanilla)

# gestão do projeto
-metodologia kanban via github projects
-planejamento aba projects com colunas a fazer, em progresso e concluido
-desenvolvimento issues para criação fechadas ao implantar
-qualidade issues para testar fechadas apos validação no github actions
-historia commits estruturadoos com conventional commits
-mudanças registros neste readme e no kanban.

##gestão de mudanças

Título: Relatório de Gestão de Mudanças - TechFlow Solutions 


Cenário Inicial: O projeto previa um CRUD básico de tarefas para a startup de logística, focado em título, descrição e status.


A Mudança: Após a primeira Sprint, identificou-se a necessidade de gerenciar o nível de urgência das entregas para otimizar a frota. Foi implementada a funcionalidade de Priorização de Tarefas (Baixa, Média, Alta).
+2

Impacto no Projeto: * Kanban: Adição de um novo card no quadro "To Do" para implementar o campo de prioridade. * Código: Atualização da classe Task e da interface visual para suportar e exibir o novo atributo. * Qualidade: Criação de testes unitários específicos para validar se a prioridade "Média" é atribuída por padrão.
+4


Justificativa Ágil: Essa alteração reflete a flexibilidade do framework Kanban, permitindo que a TechFlow Solutions entregue uma ferramenta que realmente atenda à dor da startup: a necessidade de identificar o que deve ser transportado primeiro