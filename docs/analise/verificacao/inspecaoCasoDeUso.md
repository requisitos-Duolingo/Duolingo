## Introdução

Este documento tem como objetivo inspecionar os diagramas de casos de uso, estes diagramas foram desenvolvidos na disciplina de Requisitos no módulo de Modelagem de Requisitos. Foi utilizado o Checklist para fazer essa verificação o que facilita a identificação de erros. Checklist é básicamente um conjunto de perguntas ou afirmações sobre determinada circunstância ao qual se deseja verificar, dependendo da sua finalidade e objetivo.

## Metodologia

Para inspecionar os casos de uso foi feito um checklist levando em consideração os topicos relevantes para a qualidade de um casos de uso. Esses topícos foram inspecionados e a partir desta inspeção o checklist foi preenchido. E com isso é possível analisar os dados presentes no checklist e por fim chegar a uma conclusão, se o caso de uso esta bem feito, atende ao modelo de caso de uso, segue a metodologia para o mesmo dentre outras conclusões.

### Perguntas

|ID|Questão|Justificativa|
|--|--|--|
|1 | A descrição de caso de uso está consistente com a representação no diagrama?|Para se ter uma boa descrição ela deve ser condizente com a imagem que representa o caso de uso|
|2 | O caso de uso mostra o fluxo principal? |E necessário deixar claro qual é o fluxo principal e distinguilos dos demais|
|3 | O caso de uso possui fluxos alternativos? |O app guiaBolso possui muitos fluxos alternativos, logo caso não possua pode ser uma exceção ou um erro|
|4 | A descrição do caso de uso possui fluxos de exceção? |pelo que foi visto o app em geral possui muitos fluxos de exceção caso não possua pode ser uma exceção ou um erro|
|5 | As frases representam um diálogo entre ator e sistema, evideciando a ação do ator? |E necessário para que se possa ter uma compreenção facilitada.|
|6 | As frases utilizam o tempo presente? |por padrão os casos de uso utilizam este tempo.|
|7 | As frases procuram ser objetivas, evitando redundâncias ou informações desnecessárias?|O caso de uso deve ser objetivo e claro no que pretende mostrar|
|8 | O caso de uso segue a formatação padrão no modelo proposto?|Foi preparado um card de modelo, e a padronização e um ponto considerado importante|
|9 | O caso de uso possui a data nas suas versões?|O versionamento possuindo as datas são de grande importancia em alguns casos|
|10 | Os icones presentes no diagrama seguem a padronização das cores? |Foi decidido pelo grupo seguir o padrão de icones logo caso não esteja no padrão deve ser corrigido|
|11 | O caso de uso possui alguma rastreabilidade?|Isto ajuda e visualizar a rastreabilidade dos casos de uso |
|12 | O modelo de casos de uso apresenta o comportamento do sistema de modo claro | É fácil entender o que o sistema faz quando se revisa o modelo: <br> * Não existem longas cadeias de relacionamentos de inclusão e de extensão, tal como quando um caso de uso incluído é estendido ou quando um caso de uso estendido inclui outros casos de uso.  Isso pode comprometer o entendimento. <br> * Interdependências mínimas onde um caso de uso de inclusão, de extensão ou especializado deve conhecer a estrutura e o conteúdo de outros casos de uso de inclusão, de extensão ou especializado. | 
|13 | Todos os relacionamentos entre os casos de uso são necessários | |

## Inspeção

|UC|1|2|3|4|5|6|7|8|9|10|11|12|13|Qualidade|
|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
|[UC01](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|[UC02](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|[UC03](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|Bom|
|[UC04](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:x:|:x:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:x:|Regular|
|[UC05](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:x:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:x:|Ruim|
|[UC06](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:x:|Regular|
|[UC07](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:x:|Regular|
|[UC08](../../modelagem/CasosDeUso.md)|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:x:|:x:|:heavy_check_mark:|:heavy_check_mark:|:x:|:heavy_check_mark:|:heavy_check_mark:|:x:|Regular|
| Total | 8/8 | 8/8 | 6/8 | 4/8 | 6/8 | 2/8 | 7/8 | 4/8 | 8/8 | 1/8 | 8/8 | 4/8 | 3/8 | Regular |

## Melhorias

| UC | Melhoria |
|:-------|:---------|
| UC02 | Padronizar a cor do bloco de descrição de itens |
| UC03 | Declarar casos de uso no imperativo <br> Padronizar a cor do bloco de descrição de itens |
| UC04 | Opções como "Motivo no qual quer aprender um idioma" não é um caso de uso, é apenas uma opção <br> Não está claro como é o fluxo <br> Declarar casos de uso no imperativo <br> Padronizar a cor do bloco de descrição de itens <br> Verificar se realmente não existe um fluxo de excessão |
| UC05 | Verificar se não existe um fluxo de excessão <br> Verificar se não existem fluxos alternativos <br> Retirar relacionamentos redundantes <br> "Lições a serem realizadas não é um caso de uso" |
| UC06 | Verificar se não existe um fluxo de excessão <br> Clicar em um botão não é necessariamente um caso de uso <br> Retirar relacionamentos cíclicos |
| UC07 | Verificar se não existe um fluxo alternativo <br> "Deve ser apresentado um ranking" não é um caso de uso <br> O caso de uso é apresentado de forma superficial |
| UC08 | Verificar se não existe um fluxo excessão <br> Uma ação como clicar em um botão não é necessariamente um caso de uso <br> O caso de uso é apresentado de forma superficial |

## Conclusão

Todos os casos de uso foram analisados. Observa-se que os casos de uso não estão padronizados, várias ações (como apertar um botão ou algo aparecer na tela) foram confundidads de casos de uso, vários casos de uso não estão no imperativo. Assim o documentos de diagrama e especificação de casos de uso pode ser considerado **Regular**, e várias erros devem ser arrumados.

|Verificação realizada por|Local|Data|
|-------------------------|-----|----|
|Lude Ribeiro e Luis Gustavo|Google Hangouts|29 de outubro de 2019|


## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 11. 2º/2019. 40 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 20. 2º/2019. 53 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

Lista de Verificação: Modelo de Casos de Uso. Diponível em: http://mds.cultura.gov.br/core.base_rup/guidances/checklists/use-case_model_7737BEDD.html . Acesso em 29/10/2019.