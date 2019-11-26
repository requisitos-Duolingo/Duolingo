# NFR - Verificação

## Introdução

Nesta seção há uma verificação dos requisitos para saber se foram atendidos e supridos conforme o esperado.

## Método aplicado

Para confirmar se os artefatos estão de acordo, utilizou-se a técnica de inspeção e para ver se as funcionalidades foram supridas foi definido um checklist.

## Inspeção

**Questão** | **Justificativa**
:--------- | :------
Softgoals representam metas bem definidas? | A meta em um softgoal deve ser clara quanto ao que se deve satisfazer
Os softgoals compõem critérios de qualidade de requisitos funcionais e não funcionais? | À que se refere o softgoal
Os nomes escolhidos para os softgoals representam bem os conceitos e tarefas? | Cada nome deve ser o mais intuitívo possível
Antes do surgimento de uma tarefa bem definida, há um caminho justo pelo softgoal? | O softgoal deve ser amadurecido ao longo do caminho
Existe redundância para atingir o softgoal? | Variabilidade de caminho
Análise minunciosa para ver se o softgoal foi atendido até o último nível? | Se o softgoal foi atendido não deve haver problemas no caminho até o seu fim
Softgoals são divididos em sub operações? | Cada softgoal deve se decompor em operacionalizações.
As relações de & e OU são bem definidas entre os softgoals? | Há uma relação entre os softgoals que julgam uma dependencia ou interdependência
O sentido das setas e sinalizações do softgoal é coerente? | As operacionalizzações devem ter relação explicativa pelas setas.

## Checklist

Questões | NFR00 | NFR01 | NFR02 | NFR03 | NFR04 | NFR05 | NFR06 | NFR07
:-------- | :------ | :------ | :------ | :------ | :------ | :------ | :------ | :------
Softgoals representam metas bem definidas? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Os softgoals compõem critérios de qualidade de requisitos funcionais e não funcionais? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Os nomes escolhidos para os softgoals representam bem os conceitos e tarefas? | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Antes do surgimento de uma tarefa bem definida, há um caminho justo pelo softgoal? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Existe redundância para atingir o softgoal? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Análise minunciosa para ver se o softgoal foi atendido até o último nível? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
Softgoals são divididos em sub operações? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
As relações de & e OU são bem definidas entre os softgoals? | :heavy_check_mark: | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
O sentido das setas e sinalizações(eg. tracejado) do softgoal é coerente? | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:

## Observações

NFR | Observações
:-------- | :------
NFR00 | Falta descrição mais detalhada e marcação em negrito
NFR01 | Completo, sem idicativos críticos
NFR02 | Sem considerações, completo
NFR03 | Seta tracejada deve indicar dependência entre softgoal "Armazenamento" e "Cash para dados"
NFR04 | "Aplicação web" com marcação errada de interdepêndencia
NFR05 | Relação de interdependência deve ser melhorada
NFR06 | Relação de para objetivos críticos devem ser mais destacadas
NFR07 | Sem considerações, completo

## Conclusão

O NFR é fundamental para análise das relações entre requisitos não funcionais. Há ainda alguns erros sobre softgoals críticos e suas interdependências.

## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 36 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
