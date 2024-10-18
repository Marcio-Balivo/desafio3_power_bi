## Desafio 3: Limpeza e transformação de _datasets_

### Exemplo do relatório gerado a partir do tratamento dos dados
![Relatório](https://github.com/Marcio-Balivo/desafio3_power_bi/blob/main/desafio3_Limpeza_Transforma%C3%A7%C3%A3o-1.png)

### Etapas da Limpeza e Transformação
1. Ajustei o nome das colunas.
2. Exclui as colunas de metadados.
3. Ajustei os tipos de dado de moeda para decimal com duas casas de precisão.
4. Verifiquei a existência de nulos (apenas um empregado possui o atributo nulo no campo "Ssn do Supervisor", provavelmente é o presidente da empresa).
5 e 6. Verifiquei se há algum departamento sem gerente, mas não há.
7. Verifiquei o número de horas por projeto com a função "Group by"  

| Projeto | Horas/Trabalhadas |
| :---: |	:---: | 
| 1	| 52,5 |
| 2 | 37,5 |
| 3 | 50 |
| 10 | 55 |
| 20 | 25 |
| 30 | 55 |

8. Separei as colunas complexas (Endereço na tabela Employee)
9. Mesclei as tabelas "employee" e "departament" para obter uma nova consulta contendo o nome do empregoda e do departamento correspondente. 
10. Exclui as colunas desnecessárias da consulta criada no passo anterior.
11. Fiz a junção entre dos colaboradores e respectivos nomes dos gerentes.
12. Mesclei as colunas nome e sobreno dos empregados.
13. Mesclei o nome do departamento com a sua localização.
14. Podemos utilizar apenas a mescla porque é a única função que permite correlacionar os dados entre duas tabelas a fim de estabelecer uma relação entre seus atributos (campos).
15. Agrupei os dados para saber quantos empregados há por gerente

| Supervisor | Empregados |
| --- | :---: |
| Franklin Wong | 3 |
| James Borg | 2 |
| Jennifer Wallace | 2 |
| Sem Supervisor | 1 |

16. Exclui todas as colunas desnecessárias.

