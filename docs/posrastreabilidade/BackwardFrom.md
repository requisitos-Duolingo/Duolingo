## Introdução

Este documento visa ligar todos os requisitos elicitados durante a matéria de Requisito de Software aos seus respectivos métodos de elicitação e modelagem, utilizando o método de rastreabilidade **Backward-from.**

## Metodologia

## Tabelas

### Legendas

|**Código**|**Significado**|
|:--------:|:--------------|
| Q   | Questionãrio         |
| AP  | Análise de Protocolo |
| AD  | Brainstorm           |
| ENT | Entrevista           |
| INT | Instrospecção        |
| ST  | Story Teling         |
| F   | Feature              |

### Requisitos Funcionais

| ID | Descrição | Origem | Elos |
|:--:|:----------|:------|:----:|
| RF01 | O aplicativo deve permitir o usuário praticar antes de se cadastrar | [AP01](../AnaliseDeProtocolo) | [**EF01**](#elos-funcionais) |
| RF02 | O aplicativo permite que o usuário escolha o(s) idioma(s) que ele deseja aprender | [AP02](../AnaliseDeProtocolo), [AD01](../Brainstorming), [INT03](../Introspecção)| [**EF02**](#elos-funcionais) |
| RF03 | O aplicativo deve ter metas diárias para engajamento do usuário | [AP03](../AnaliseDeProtocolo), [AD11](../Brainstorming), [ENT07](../Entrevista) | [**EF03**](#elos-funcionais) |
| RF04 | O usuário deve poder escolher o nível de conhecimento que têm no idioma | [AP04](../AnaliseDeProtocolo), [INT13](../Instrospecção) | [**EF04**](#elos-funcionais) |
| RF05 | O aplicativo deve desbloquear as lições que estão abaixo no nível de conhecimento prévio do usuário | [AP05](../AnaliseDeProtocolo) | [**EF05**](#elos-funcionais) |
| RF06 | O aplicativo deve exibir feedback durante as lições | [AP06](../AnaliseDeProtocolo), [AD06](../Brainstorming), [Q06](../Questionario) | [**EF06**](#elos-funcionais) |
| RF07 | O aplicativo exibir as conquistas ao finalizar das atividades | [AP](../AnaliseDeProtocolo) | [**EF07**](#elos-funcionais) |
| RF08 | Deve existir anúncio após as lições | [AP08](../AnaliseDeProtocolo) | [**EF08**](#elos-funcionais) |
| RF09 | O usuário deve poder criar sua conta na plataforma | [AP09](../AnaliseDeProtocolo), [INT34](../Introspecção) | [**EF09**](#elos-funcionais) |
| RF10 | O aplicativo deve me permitir entrar com minha conta | [AP10](../AnaliseDeProtocolo) | [**EF10**](#elos-funcionais) |
| RF11 | O aplicativo deve me permitir sair da minha conta | [AP11](../AnaliseDeProtocolo) | [**EF11**](#elos-funcionais) |
| RF12 | Deve existir uma assinatura premium | [AP12](../AnaliseDeProtocolo), [ENT12](../Entrevista) | [**EF12**](#elos-funcionais) |
| RF13 | Caso o usuário tenha assinatura premium ele não deve ver anúncios | [AP13](../AnaliseDeProtocolo) | [**EF13**](#elos-funcionais) |
| RF14 | O usuário deve poder editar seu perfil na plataforma | [AP14](../AnaliseDeProtocolo) | [**EF14**](#elos-funcionais) |
| RF15 | O aplicativo deve permitir que o usuário faça login com email/facebook ou conta do google | [AD02](../Brainstorming) | [**EF15**](#elos-funcionais) |
| RF16 | O aplicativo deve permitir que o usuário veja o seu progresso | [AD03](../Brainstorming) | [**EF16**](#elos-funcionais) |
| RF17 | O aplicativo permite que o usuário adicione e siga amigos | [AD04](../Brainstorming) | [**EF17**](#elos-funcionais) |
| RF18 | O aplicativo deve permitir o usuário a fazer questões de escuta, leitura, escrita e fala | [AD02](../Brainstorming), [ENT02](../Entrevista) | [**EF18**](#elos-funcionais) |
| RF19 | O sistema é divido em níveis e com uma progressão ideal para cada módulo | [AD10](../Brainstorming), [ENT13](../Entrevista), [Q02](../Questionario) | [**EF19**](#elos-funcionais) |
| RF20 | Cada aula deve ter exercícios para serem realizados | [AD02](../Brainstorming), [ENT02](../Entrevista) | [**EF20**](#elos-funcionais) |
| RF21 | O aplicativo deve apresentar as aulas/exercícios de forma progressiva | [ENT03](../Entrevista), [Q03](../Questionario) | [**EF21**](#elos-funcionais) |
| RF22 | O aplicativo deve ter uma pontuação que reflita o número de aulas/exercícios feitos | [ENT04](../Entrevista), [INT46](../Introspecção) | [**EF22**](#elos-funcionais) |
| RF23 | O aplicativo deve ter ligas/grupos, que sejam progressivas, que separem os usuários de acordo com seu desempenho | [ENT05](../Entrevista) | [**EF23**](#elos-funcionais) |
| RF24 | O aplicativo deve ter um ranking dos usuários que estão em uma mesma divisão | [ENT02](../Entrevista), [Q05](../Questionario) | [**EF24**](#elos-funcionais) |
| RF25 | O aplicativo deve contabilizar o número de dias seguidos que usuário cumpre sua meta diária | [ENT08](../Entrevista), [Q06](../Questionario) | [**EF25**](#elos-funcionais) |
| RF26 | O aplicativo deve notificar o usuário sobre as metas diárias | [ENT09](../Entrevista) | [**EF26**](#elos-funcionais) |
| RF27 | O aplicativo deve possuir uma moeda, que sirva de recompensa para os exercícios realizados | [ENT10](../Entrevista) | [**EF27**](#elos-funcionais) |
| RF28 | O aplicativo deve possuir uma loja aonde ele poderá gastar suas moedas adquiridas | [ENT11](../Entrevista), [INT59](../Introspecção) | [**EF28**](#elos-funcionais) |
| RF29 | O aplicativo deve repetir exercícios, de forma que ajude o usuário a aprender/relembrar | [ENT14](../Entrevista) | [**EF29**](#elos-funcionais) |
| RF30 | Se o usuário ficar algum tempo sem utilizar o aplicativo, o aplicativo deve fazer com que ele volte ao início do curso | [ENT15](../Entrevista) | [**EF30**](#elos-funcionais) |
| RF31 | Deve aparecer uma mensagem dando Boas Vindas | [INT01](../Introspecção) | [**EF31**](#elos-funcionais) |
| RF32 | Devo ser apresentado com a opção de Registro ou Login | [INT02](../Introspecção) | [**EF32**](#elos-funcionais) |
| RF33 | Deve haver mais de uma opção de idioma disponível para aprender | [INT04](../Introspecção), [Q01](../Questionario) | [**EF33**](#elos-funcionais) |
| RF34 | Deve apresentar uma opção para ver mais idiomas disponíveis | [INT05](../Introspecção) | [**EF34**](#elos-funcionais) |
| RF35 | Deve existir um teste de nivelamento | [INT18](../Introspecção) | [**EF35**](#elos-funcionais) | 
| RF36 | O aplicativo deve aumentar a pontuação do usuário a cada aula finalizada | [INT24](../EntreviIntrospecçãosta) | [**EF36**](#elos-funcionais) |
| RF37 | O usuário deve receber incentivos e dicas durante os exercícios | [INT28](../Introspecção) | [**EF37**](#elos-funcionais) |
| RF38 | O aplicativo deve mostrar os Termos e Política de Privacidade | [INT35](../Introspecção) | [**EF38**](#elos-funcionais) |
| RF39 | O usuário deve poder testar a versão premium gratuitamente | [INT44](../Introspecção) | [**EF39**](#elos-funcionais) |
| RF40 | O usuário deve poder escolher um novo idioma a qualquer momento | [INT50](../Introspecção) | [**EF40**](#elos-funcionais) |
| RF41 | O usuário deve poder ajustar quanto tempo por dia ele quer gastar fazendo lições | [Q08](../Questionario) | [**EF41**](#elos-funcionais) |
| RF42 | O usuário deve poder ajustar as configurações dos exercícios | [Q09](../Questionario) |  |
| RF43 | O usuário deve poder compartilhar seu progresso | [Q10](../Questionario) |  |
| RF44 | Eu como usuário desejo criar uma conta para começar a utilizar o app | [ST01](../Storytelling) |  |
| RF45 | Eu como usuário desejo entrar no sistema e selecionar uma novo idioma para aprender uma nova língua | [ST02](../Storytelling) |  |
| RF46 | Eu como usuário desejo entrar no sistema e verificar o meu nível no curso para conseguir acompanhar o meu progresso | [ST03](../Storytelling) |  |
| RF47 | Eu como usuário desejo entrar no sistema e verificar o nível dos meus amigos no curso para acompanhar a evolução deles | [ST05](../Storytelling) |  |
| RF48 | Eu como usuário desejo entrar no sistema e ver o ranking para ver o meu nível comparado com as outras pessoas | [ST06](../Storytelling) |  |
| RF49 | Eu como usuário desejo fazer os exercícios do curso para aprender mais sobre a língua | [ST07](../Storytelling) |  |
| RF50 | Eu como usuário desejo entrar no sistema e fazer uma pergunta na comunidade para tirar as minhas dúvidas | [ST08](../Storytelling) |  |
| RF51 | Eu como usuário desejo entrar no sitema e me cadastrar como professor para ajudar as outras pessoas | [ST09](../Storytelling) |  |
| RF52 | Eu como usuário desejo entrar no sistema e responder as perguntas na comunidade para tirar as dúvidas das outras pessoas | [ST10](../Storytelling) |  |

### Requisitos Não-Funcionais

| ID | Descrição | Origem | Elos |
|:--:|:----------|:-------| ---------- |
| RNF01 | O aplicativo deve engajar o usuário | [AP15](../AnaliseDeProtocolo) |  |
| RNF02 | O aplicativo deve ser fácil de usar | [AP16](../AnaliseDeProtocolo), [AD07](../Brainstorming), [ENT16](../Entrevista), [Q11](../Questionario) |  |
| RNF03 | O aplicativo deve interativo | [AP17](../AnaliseDeProtocolo) |  |
| RNF04 | O aplicativo deve ser monetizado | [AP18](../AnaliseDeProtocolo) |  |
| RNF05 | O aplicativo deve ser gameficado | [AD08](../Brainstorming) |  |
| RNF06 | O usuário deve ser recompensado por seu progresso | [AD09](../Brainstorming) |  |
| RNF07 | O software deve ser multiplataforma | [AD12](../Brainstorming) |  |  |
| RNF08 | O aplicativo deve permitir a segurança dos dados do usuário | [INT35](../Introspecção) |  |
| RNF09 | O aplicativo deve ser rápido de usar | [Q12](../Questionario) |  |
| RNF10 | O aplicativo funcionar 24/7 | [Q13](../Questionario) |  |
| RNF11 | O aplicativo deve estimular a competitividade | [Q14](../Questionario) |  |
| RNF12 | O aplicativo deve promover a integração dos usuário | [Q04](../Questionario) |  |

## Elos Funcionais

### EF01

**Categoria:**

**Elos:**

### EF02

**Categoria**: Desenvolvimento

**Elos**
Representação: [AP02](../AnaliseDeProtocolo) representa US29
Agregação: [INT03](../Introspecção) agrega [AD01](../Brainstorming)

### EF03

**Categoria**: Desenvolvimento

**Elos:**
Agregação: [AD11](../Brainstorming) agrega [AP03](../AnaliseDeProtocolo)
Representação: [INT03](../Introspecção) representa [ENT07](../Entrevista)

### EF04

**Categoria:**

**Elos:**

### EF05

**Categoria:**

**Elos:**

### EF06

**Categoria:**

**Elos:**

### EF07

**Categoria:**

**Elos:**

### EF08

**Categoria:**

**Elos:**

### EF09

**Categoria:**

**Elos:**

### EF10

**Categoria:**

**Elos:**

### EF11

**Categoria:**

**Elos:**

### EF12

**Categoria:**

**Elos:**

### EF13

**Categoria:**

**Elos:**

### EF14

**Categoria:**

**Elos:**

### EF15

**Categoria:**

**Elos:**

### EF16

**Categoria:**

**Elos:**

### EF17

**Categoria:**

**Elos:**

### EF18

**Categoria:**

**Elos:**

### EF19

**Categoria:**

**Elos:**

### EF20

**Categoria:**

**Elos:**

### EF21

**Categoria:**

**Elos:**

### EF22

**Categoria:**

**Elos:**

### EF23

**Categoria:**

**Elos:**

### EF24

**Categoria:**

**Elos:**

### EF25

**Categoria:**

**Elos:**

### EF26

**Categoria:**

**Elos:**

### EF27

**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [ENT09](../Entrevista) satifaz [AD09](../Brainstorming) </br> INT61 também é satisfeito por [AD09](../Brainstorming)

Representação: US43, US44, US45 representam o C07

### EF28

**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [ENT09](../Entrevista) satifaz [AD09](../Brainstorming) </br> INT61 também é satisfeito por [AD09](../Brainstorming)

Representação: US43, US44, US45 representam o C07

### EF29

**Categoria:**

**Elos:**

### EF30

**Categoria:** 

**Elos:**

### EF31

**Categoria:**

**Elos:**

### EF32

**Categoria:** Desenvolvimento

**Elos:**

Representação: UC01 representa [INT02](../Introspecção) </br>
Representação: US04 representa [AD02](../Brainstorming) 

### EF33

**Categoria:** Desenvolvimento

**Elos:**

Representação: [UC05](../CasosDeUso) representa [INT04](../Introspecção)

Agregação: [Q01](../Questionario) agrega [AD01](../Brainstorming)

### EF34

**Categoria:** Desenvolvimento

**Elos:**

Representação: [UC05](../CasosDeUso) representa [INT05](../Introspecção)

### EF35

**Categoria:** Desenvolvimento

**Elos:**

Representação: US01 representa [INT18](../Introspecção) </br>
Agregação: [INT18](../Introspecção) agrega [AP04](../AnaliseDeProtocolo)


### EF36

**Categoria:** Desenvolvimento

**Elos:**

Representação: C03 representa [INT24](../EntreviIntrospecçãosta)</br>
Agregação: AP07 agrega [AD09](../Brainstorming)


### EF37

**Categoria:** Desenvolvimento

**Elos:**

Agregação: [INT28](../Introspecção) agrega [Q06](../Questionario)</br>
Agregação: F11 é composta pela C05 e C11</br>
Agregação: [AP06](../AnaliseDeProtocolo) agrega INT25

### EF38

**Categoria:** Desenvolvimento

**Elos:**

Agregação: [INT35](../Introspecção) agrega UC02</br>
Agregação: UC03 agrega C01

### EF39

**Categoria:** Desenvolvimento

**Elos:**

Representação: [INT44](../Introspecção) representa US51

### EF40

**Categoria:** Desenvolvimento

**Elos:**

Representação: [UC05](../CasosDeUso) representa [AD01](../Brainstorming)</br>
Agregação: [AP02](../AnaliseDeProtocolo) agrega Q01</br>
Representação: US28 representa [INT50](../Introspecção)

### EF41

**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [Q08](../Questionario) satisfaz [AD11](../Brainstorming)

## Referências

[Guiabolso, Github, requisitos.](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/pos-rastreabilidade/backward/)

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
