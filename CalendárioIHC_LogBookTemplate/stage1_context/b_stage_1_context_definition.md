[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| TeamUp | Calendário Web | Sistema mais simples mas com todas as funcionalidades base para uma ou mais pessoas |
| Morgen | Calendário em App para Computador | Sistema mais complexo, com algum apoio IA                                 |
| Clockwise | Calendário Web | Sistema com muita utilização de IA para gerir calendários de equipas |




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method

Para fazer a avaliação Heurística da gerenciadora de calendários TeamUp, 3 analistas avaliaram separadamente a capacidade da plataforma para concluir as tarefas básicas de qualquer calendário, como a marcação de eventos, assim como a apresentação e compreesão do layout da perspetiva do utilizador comum, tudo com base nas heurísticas de usabilidade de Nielsen. 

Após as avaliações conluídas, foi organizada uma sessão de apresentação e comparação destas e foi criada uma lista de consenso.



#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Não permite definir um evento como absoluto | 2            | 2        | 0        | Devia existir opção de definir um evento sem sobreposição |
| Permite criar dois eventos com mesmo nome e descrição   | 3            | 0        | 4        | Verificar se existem eventos com o mesmo nome e confirmar com utilizador                    |
| Falta de indicação de como realizar ações de adicionar/editar/remover eventos, fornecer tutoriais             | 2             |    2      |     2     |              Adicionar botôes para estas ações na barra de ferramentas                               |
|Demasiadas opções de visualização dos horários | 1 | 1 | 1 | Eliminar algumas das opções da visualização geral  |
| Carregar num dia no calendário apresentado no topo esquerdo não direciona para esse dia | 2 | 0 | 0 | Direcionar para o dia quando selecionado no calendário |
| Layout demasiado simples | 1 | 1 | 1 | Utilizar cores diferentes e figuras mais apelativas |
| Não permite criar um calendário quando cria novo evento| 0 | 3 | 0 | Dar opção de adicionar um novo calendário no menu de criação de um evento |
|Introdução de datas e horas inválidas (evento acaba antes de começar)| 0 | 0 | 4 | Quando utilizador seleciona um horário inválido, notificar o erro e repetir a seleção de horário|



---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Buyng a grammar book** | Search for available grammar books     |
|                             | Identify a specific book from the list |
|                             | Add the selected book to the cart      |
|                             | Proceeed to checkout                   |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Booking a train ticket** | Select departure and destination cities |
|                               | Choose travel date and time             |
|                               | Pick a seat (if applicable)             |
|                               | Confirm booking and make payment        |


#### Results

Task: [This is the task]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Step 1 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | [Step 2 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | [Step 3 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| ...    | [Further steps]        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |



---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
