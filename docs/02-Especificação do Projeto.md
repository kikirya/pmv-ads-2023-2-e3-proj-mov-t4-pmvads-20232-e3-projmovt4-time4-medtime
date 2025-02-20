# Especificações do Projeto

## Personas

<img src="img/persona_marina.png"><br><br>
<img src="img/persona_samira.png"><br><br>
<img src="img/persona_anasilva.png"><br><br>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
| Marina Alves    | Um canal confiável e programação de entregas regulares de medicamentos com base nos horários especificados | Reduzir o risco de esquecimento e melhorar a saúde                        |
| Juliana Rodrigues | Lembretes dos horários corretos para administração dos medicamentos | Garantir resposta eficaz ao tratamento proposto                            |
| Juliana Rodrigues | Receber todos os medicamentos em casa                               | Conquistar mais tempo para outras atividades                               |
| Samira Santana  | Receber medicamentos em casa separados por horário                  | Simplificar rotina e gerenciamento de doses                               |
| Marta Silva     | Receber medicamentos em casa com lembretes para tomar remédios     | Evitar interrupção no tratamento e receber lembretes                       |
| Larissa Gonçalves| Economia na compra e gestão dos medicamentos                       | Economizar dinheiro e tempo, ser lembrada para tomar os medicamentos      |
| Ana Silva       | Encontrar serviço de entrega que organize por horário               | Simplificar rotina e evitar erros na administração dos medicamentos       |

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O aplicativo deve permitir que os usuários se cadastrem usando e-mail, senha ou conta Google existente. | ALTA | 
|RF-002| O aplicativo deve fornecer aos usuários cadastrados uma tela de login.    | ALTA |
|RF-003| O aplicativo deve enviar notificações push para atualizar os usuários.    | MÉDIA |
|RF-004| O aplicativo deve permitir que os usuários editem seus perfis, incluindo nome, foto, informações pessoais e detalhes médicos.   | MÉDIA |
|RF-005| O aplicativo deve ter uma “tab bar” que apresente todas as suas funcionalidades ao usuário (login, perfil de usuário, notificações, configurações, favoritos, contato, etc).    | MÉDIA |
|RF-006| O aplicativo deve conceder aos usuários uma seção de contato direto com os cuidadores, onde podem enviar mensagens de texto ou anexar fotos digitalizadas de receitas.    | MÉDIA |
|RF-007| O aplicativo deve disponibilizar um canal de suporte para que os usuários possam entrar em contato em caso de dúvidas, problemas ou assistência adicional.    | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O aplicativo deve ser compatível com os sistemas Android e IOS em suas mais recentes versões.  | ALTA | 
|RNF-002| O aplicativo deve ser executado sem problemas em diferentes tamanhos de tela e resoluções.  |  ALTA | 
|RNF-003| O aplicativo deve fornecer fontes e  elementos de interface com tamanho suficiente para garantir a legibilidade em dispositivos móveis.  | ALTA | 
|RNF-004| O aplicativo deve ser funcional tanto em conexões Wi-Fi quanto em redes móveis.  |  MÉDIA | 
|RNF-005| O aplicativo deve processar requisições do usuário em no máximo 5 segundos. | BAIXA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 04/12/2023.  |
|RE-02| O aplicativo disponibilizará apenas o idioma PT-BR.         |
|RE-03| O aplicativo não será publicado em nenhuma plataforma digital (Google Play, App Store, etc).  |
|RE-04| Não será desenvolvido um back-end para o aplicativo.       |


## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.


# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)



# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
