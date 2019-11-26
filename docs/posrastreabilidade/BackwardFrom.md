## Introdução

Este documento visa ligar todos os requisitos elicitados durante a matéria de Requisito de Software aos seus respectivos métodos de elicitação e modelagem, utilizando o método de rastreabilidade **Backward-From**.

## Metodologia

Foi organizados os Requisitos Funcionais e Não Funcionais previamente [Elicitados](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/RequisitosElicitados/) formando as tabelas abaixo com os rastros dos mesmo, assim, realizou-se uma verificação dos elos relacionados a cada artefatos.

## Tabelas

**Legendas:**

- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- Q: Questionãrio
- AP: Análise de Protocolo
- AD: Brainstorm
- ENT: Entrevista
- INT: Instrospecção
- ST: Story Teling
- C: Cenários
- E: Épico
- F: Feature
- US: Histórias de Usuário
- UC: Casos de Uso

### Requisitos Funcionais

| ID | Descrição | Origem | Elos |
|:--:|:----------|:------|:----:|
| RF01 | O aplicativo deve permitir o usuário praticar antes de se cadastrar | [AP01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF01**](#ef01) |
| RF02 | O aplicativo permite que o usuário escolha o(s) idioma(s) que ele deseja aprender | [AP02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados), [AD01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados), [INT03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)| [**EF02**](#ef02) |
| RF03 | O aplicativo deve ter metas diárias para engajamento do usuário | [AP03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados), [AD11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados), [ENT07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF03**](#ef03) |
| RF04 | O usuário deve poder escolher o nível de conhecimento que têm no idioma | [AP04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados), [INT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF04**](#ef04) |
| RF05 | O aplicativo deve desbloquear as lições que estão abaixo no nível de conhecimento prévio do usuário | [AP05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF05**](#ef05) |
| RF06 | O aplicativo deve exibir feedback durante as lições | [AP06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados), [AD06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados), [Q06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF06**](#ef06) |
| RF07 | O aplicativo exibir as conquistas ao finalizar das atividades | [AP](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF07**](#ef07) |
| RF08 | Deve existir anúncio após as lições | [AP08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF08**](#ef08) |
| RF09 | O usuário deve poder criar sua conta na plataforma | [AP09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados), [INT34](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF09**](#ef09) |
| RF10 | O aplicativo deve me permitir entrar com minha conta | [AP10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF10**](#ef10) |
| RF11 | O aplicativo deve me permitir sair da minha conta | [AP11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF11**](#ef11) |
| RF12 | Deve existir uma assinatura premium | [AP12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados), [ENT12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF12**](#ef12) |
| RF13 | Caso o usuário tenha assinatura premium ele não deve ver anúncios | [AP13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF13**](#ef13) |
| RF14 | O usuário deve poder editar seu perfil na plataforma | [AP14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**EF14**](#ef14) |
| RF15 | O aplicativo deve permitir que o usuário faça login com email/facebook ou conta do google | [AD02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) | [**EF15**](#ef15) |
| RF16 | O aplicativo deve permitir que o usuário veja o seu progresso | [AD03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) | [**EF16**](#ef16) |
| RF17 | O aplicativo permite que o usuário adicione e siga amigos | [AD04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) | [**EF17**](#ef17) |
| RF18 | O aplicativo deve permitir o usuário a fazer questões de escuta, leitura, escrita e fala | [AD05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados), [ENT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF18**](#ef18) |
| RF19 | O sistema é divido em níveis e com uma progressão ideal para cada módulo | [AD10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados), [ENT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [Q02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF19**](#ef19) |
| RF20 | Cada aula deve ter exercícios para serem realizados | [AD02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados), [ENT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF20**](#ef20) |
| RF21 | O aplicativo deve apresentar as aulas/exercícios de forma progressiva | [ENT03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [Q03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF21**](#ef21) |
| RF22 | O aplicativo deve ter uma pontuação que reflita o número de aulas/exercícios feitos | [ENT04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [INT46](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF22**](#ef22) |
| RF23 | O aplicativo deve ter ligas/grupos, que sejam progressivas, que separem os usuários de acordo com seu desempenho | [ENT05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF23**](#ef23) |
| RF24 | O aplicativo deve ter um ranking dos usuários que estão em uma mesma divisão | [ENT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [Q05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF24**](#ef24) |
| RF25 | O aplicativo deve contabilizar o número de dias seguidos que usuário cumpre sua meta diária | [ENT08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [Q06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF25**](#ef25) |
| RF26 | O aplicativo deve notificar o usuário sobre as metas diárias | [ENT09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF26**](#ef26) |
| RF27 | O aplicativo deve possuir uma moeda, que sirva de recompensa para os exercícios realizados | [ENT10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF27**](#ef27) |
| RF28 | O aplicativo deve possuir uma loja aonde ele poderá gastar suas moedas adquiridas | [ENT11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [INT59](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF28**](#ef28) |
| RF29 | O aplicativo deve repetir exercícios, de forma que ajude o usuário a aprender/relembrar | [ENT14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF29**](#ef29) |
| RF30 | Se o usuário ficar algum tempo sem utilizar o aplicativo, o aplicativo deve fazer com que ele volte ao início do curso | [ENT15](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) | [**EF30**](#ef30) |
| RF31 | Deve aparecer uma mensagem dando Boas Vindas | [INT01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF31**](#ef31) |
| RF32 | Devo ser apresentado com a opção de Registro ou Login | [INT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF32**](#ef32) |
| RF33 | Deve haver mais de uma opção de idioma disponível para aprender | [INT04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados), [Q01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF33**](#ef33) |
| RF34 | Deve apresentar uma opção para ver mais idiomas disponíveis | [INT05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF34**](#ef34) |
| RF35 | Deve existir um teste de nivelamento | [INT18](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF35**](#ef35) |
| RF36 | O aplicativo deve aumentar a pontuação do usuário a cada aula finalizada | [INT24](../EntreviIntrospecçãosta) | [**EF36**](#ef36) |
| RF37 | O usuário deve receber incentivos e dicas durante os exercícios | [INT28](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF37**](#ef37) |
| RF38 | O aplicativo deve mostrar os Termos e Política de Privacidade | [INT35](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF38**](#ef38) |
| RF39 | O usuário deve poder testar a versão premium gratuitamente | [INT44](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF39**](#ef39) |
| RF40 | O usuário deve poder escolher um novo idioma a qualquer momento | [INT50](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**EF40**](#ef40) |
| RF41 | O usuário deve poder ajustar quanto tempo por dia ele quer gastar fazendo lições | [Q08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF41**](#ef41) |
| RF42 | O usuário deve poder ajustar as configurações dos exercícios | [Q09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) |  [**EF42**](#ef42)  |
| RF43 | O usuário deve poder compartilhar seu progresso | [Q10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**EF43**](#ef43)  |
| RF44 | Eu como usuário desejo criar uma conta para começar a utilizar o app | [ST01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) |  [**EF44**](#ef44)  |
| RF45 | Eu como usuário desejo entrar no sistema e selecionar uma novo idioma para aprender uma nova língua | [ST02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) | [**EF45**](#ef45)  |
| RF46 | Eu como usuário desejo entrar no sistema e verificar o meu nível no curso para conseguir acompanhar o meu progresso | [ST03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) | [**EF46**](#ef46) |
| RF47 | Eu como usuário desejo entrar no sistema e verificar o nível dos meus amigos no curso para acompanhar a evolução deles | [ST05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) | [**EF47**](#ef47) |
| RF48 | Eu como usuário desejo entrar no sistema e ver o ranking para ver o meu nível comparado com as outras pessoas | [ST06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) | [**EF48**](#ef48)  |
| RF49 | Eu como usuário desejo fazer os exercícios do curso para aprender mais sobre a língua | [ST07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) |  [**EF49**](#ef49)  |
| RF50 | Eu como usuário desejo entrar no sistema e fazer uma pergunta na comunidade para tirar as minhas dúvidas | [ST08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) | [**EF50**](#ef50)  |
| RF51 | Eu como usuário desejo entrar no sitema e me cadastrar como professor para ajudar as outras pessoas | [ST09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) | [**EF51**](#ef51) |
| RF52 | Eu como usuário desejo entrar no sistema e responder as perguntas na comunidade para tirar as dúvidas das outras pessoas | [ST10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) | [**EF52**](#ef52) |

### Requisitos Não-Funcionais

| ID | Descrição | Origem | Elos |
|:--:|:----------|:-------| ---------- |
| RNF01 | O aplicativo deve engajar o usuário | [AP15](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**ENF01**](#enf01) |
| RNF02 | O aplicativo deve ser fácil de usar | [AP16](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados), [AD07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados), [ENT16](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [Q11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**ENF01**](#enf02) |
| RNF03 | O aplicativo deve interativo | [AP17](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**ENF03**](#enf03) |
| RNF04 | O aplicativo deve ser monetizado | [AP18](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) | [**ENF04**](#enf04) |
| RNF05 | O aplicativo deve ser gameficado | [AD08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) | [**ENF05**](#enf05) |
| RNF06 | O usuário deve ser recompensado por seu progresso | [AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) | [**ENF06**](#enf06) |
| RNF07 | O software deve ser multiplataforma | [AD12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) | [**ENF01**](#enf07) |
| RNF08 | O aplicativo deve permitir a segurança dos dados do usuário | [INT35](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) | [**ENF08**](#enf08) |
| RNF09 | O aplicativo deve ser rápido de usar | [Q12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**ENF09**](#enf09) |
| RNF10 | O aplicativo funcionar 24/7 | [Q13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**ENF10**](#enf10) |
| RNF11 | O aplicativo deve estimular a competitividade | [Q14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**ENF11**](#enf11) |
| RNF12 | O aplicativo deve promover a integração dos usuário | [Q04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) | [**ENF12**](#enf12) |

## Elos Funcionais

### EF01

**Categoria:**

**Elos:** --

### EF02

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [AP02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) representa [US29](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-8-curso) </br>
Agregação: [INT03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) agrega [AD01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF03

**Categoria**: Desenvolvimento

**Elos:** </br>
Agregação: [AD11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [AP03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) </br>
Representação: [INT03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) representa [ENT07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados)

### EF04

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AP04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [INT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### EF05

**Categoria:** Desenvolvimento

**Elos:** </br>
Recurso: [ENT14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) depende do requisito levantado [AP05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados)

### EF06

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [Q06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) representa [AD06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Satisfação: [AD06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) satisfaz [AP06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) </br>
Agregação: [INT47](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) agrega [INT60](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### EF07

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AP07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF08

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [US53](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-19-anuncios) representa [AP08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados)

### EF09

**Categoria:**

**Elos:** </br>
Representação: [INT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) representa [AP09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) </br>
Representação: [F01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-1-cadastro-e-autenticacao) representa [C01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario001) </br>
Representação: [UC01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc01-fazer-login) representa [F01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-1-cadastro-e-autenticacao) </br>
Agregação: [AD02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [INT34](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### EF10

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AD02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [INT34](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Representação: [UC02](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc02-cadastrar-usuario) representa [US04](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-2-login) </br>
Recurso: [F02](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-2-login) depende de [US04](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-2-login)

### EF11

**Categoria:**

**Elos:** --

### EF12

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AP13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [AP12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) </br>
Representação: [INT44](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) e [INT54](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) representam [ENT12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) </br>
Representação: [UC07](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc07-acessar-loja) representa [E05](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/Backlog/#epico05-lucro), [F18](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-18-duolingo-plus)

### EF13

**Categoria:**

**Elos:** --

### EF14

**Categoria:**

**Elos:** --

### EF15

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [F04](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-4-perfil) representa [AP14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados)

### EF16

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AD03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [INT28](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Agregação: [Q06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) agrega [ST03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados)

### EF17

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC04](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc04-acessar-loja) representa [AD04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Representação: US39 representa [ST05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) </br>
Agregação: [Q05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) agrega [INT57](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Satisfação: [INT57](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) satisfaz [Q04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

### EF18

**Categoria:** Desnvolvimento

**Elos:** </br>
Agregação: [AD05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [ENT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) </br>
Representação: US30, US31, US32 representam [ENT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados)

### EF19

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AD10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [ENT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) </br>
Agregação: [ENT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) agrega [Q03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)    </br>
Representação: US34 representa [AD10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF20

**Categoria:** 

**Elos:** --

### EF21

**Categoria:** Dsenvolvimento

**Elos:** </br>
Agregação: [AD10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [ENT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) </br>
Agregação: [ENT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) agrega [Q03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)    </br>
Representação: US34 representa [AD10](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF22

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [ENT04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) agrega [INT46](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### EF23

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: US35, US36, US37 representam [ENT05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) </br>
Representação: [UC08](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc08-acessar-loja) representa [ENT05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados)

### EF24

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC08](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc08-acessar-loja) representa [ENT06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados)

### EF25

**Categoria:** Desenvolvimento 

**Elos:** </br>
Agregação: [ENT08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) agrega [Q07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)    </br>
Representação: US40 representa [ENT08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados)

### EF26

**Categoria:** Desenvolvimento

**Elos:** </br>
[AD11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) [ENT09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) ST04 C04 US22    </br>
Representação: US22 representa ST04 </br>
Representação: C04 representa [ENT09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) </br>
Agregação: [ENT09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) agrega [AD11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) 


### EF27

**Categoria:** Desenvolvimento

**Elos:** </br>
Satisfação: [ENT09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) satifaz [AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Satisfação: [INT61](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) satisfaz [AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Representação: [US43](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-16-lingots), [US44](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-16-lingots), [US45](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-16-lingots) representam o [C07](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario007)

### EF28

**Categoria:** Desenvolvimento

**Elos:** </br>
Satisfação: [ENT09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) satifaz [AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Satisfação: [INT61](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) satisfaz [AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Representação: [US43](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-16-lingots), [US44](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-16-lingots), [US45](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-16-lingots) representam o [C07](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario007)

### EF29

**Categoria:**

**Elos:** --

### EF30

**Categoria:**

**Elos:** --

### EF31

**Categoria:**

**Elos:** --

### EF32

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-1-cadastro-e-autenticacao) representa [INT02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Representação: [US04](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-2-login) representa [AD02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF33

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC05](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc05-selecionar-curso) representa [INT04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Agregação: [Q01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) agrega [AD01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF34

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC05](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc05-selecionar-curso) representa [INT05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### EF35

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [US01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-1-cadastro-e-autenticacao) representa [INT18](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Agregação: [INT18](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) agrega [AP04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados)

### EF36

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [C03](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario003) representa [INT24](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)</br>
Agregação: [AP07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF37

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [INT28](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) agrega [Q06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)</br>
Agregação: [F11](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-11-ranking) é composta pela [C05](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario005) e [C11](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario011) </br>
Agregação: [AP06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [INT25](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### EF38

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [INT35](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) agrega [UC02](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc02-cadastrar-usuario) </br>
Agregação: [UC03](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc03-visualizar-perfil) agrega [C01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario001)

### EF39

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [INT44](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) representa [US51](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-18-duolingo-plus)

### EF40

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC05](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc05-selecionar-curso) representa [AD01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)</br>
Agregação: [AP02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [Q01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) </br>
Representação: [US28](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-8-curso) representa [INT50](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### EF41

**Categoria:** Desenvolvimento

**Elos:** </br>
Satisfação: [Q08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) satisfaz [AD11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF42

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: US14, US15 representam [Q09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

### EF43

**Categoria:** -- 

**Elos:** --

### EF44

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [C01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario001), [US01](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-1-cadastro-e-autenticacao) representam [ST01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados)

### EF45

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC05](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc05-acessar-loja) representa [ST02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) </br>
Representação: [US29](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/#feature-8-curso), C02 representa [AD01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Agregação: [INT04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) agrega [AD01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Agregação: [AP02](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [AD01](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### EF46

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AD03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) agrega [INT28](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Agregação: [Q06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) agrega [ST03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados)

### EF47

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [UC08](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc08-acessar-loja) representa [ENT06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados)

### EF48

**Categoria:** Desenvolvimento

**Elos:** </br>
Representação: [C05](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/#cenario005) representa [AD04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>
Representação: [UC04](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc04-acessar-loja) representa [ST06](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) </br>
Representação: US39 representa [INT57](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) </br>
Agregação:[INT57](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados) agrega [Q05](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

### EF49

**Categoria:** Desenvolvimento

**Elos:** </br> 
Representação: US33 representa [ST07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) </br>
Representação: [UC06](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/CasosDeUso/#uc06-acessar-loja) representa [ENT13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) </br>
Agregação: [ENT03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados), [ENT14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) agregam [ST07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Storytelling/#requisitos-elicitados) 

### EF50

**Categoria:** --

**Elos:** -- 

### EF51

**Categoria:** --

**Elos:** --

### EF52

**Categoria:** --

**Elos:** --

## Elos Não Funcionais

### ENF01

**Categoria:** Desenvolvimento

**Elos:** </br>
Agregação: [AP03](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) agrega [Q14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados) </br>
Agregação: C04 agrega [AP15](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) </br>
Representação: E04 representa [AD08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados) </br>

### ENF02

**Categoria:** Desenvolvimento

**Elos:** </br>
[AD07](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)
Agregação: [ENT16](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/#requisitos-elicitados) agrega [AP16](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados) </br>
[Q11](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

### ENF03

**Categoria:** Desenvolvimento

**Elos:** </br>
[AP17](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados)

### ENF04

**Categoria:** Desenvolvimento

**Elos:** </br>
[AP18](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/#requisitos-elicitados)

### ENF05

**Categoria:** Desenvolvimento

**Elos:** </br>
[AD08](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### ENF06

**Categoria:** Desenvolvimento

**Elos:** </br>
[AD09](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### ENF07

**Categoria:** Desenvolvimento

**Elos:** </br>
[AD12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/#requisitos-elicitados)

### ENF08

**Categoria:** Desenvolvimento

**Elos:** </br>
[INT35](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Instrospeccao/#requisitos-elicitados)

### ENF09

**Categoria:** Desenvolvimento

**Elos:** </br>
[Q12](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

### ENF10

**Categoria:** Desenvolvimento

**Elos:** </br>
[Q13](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

### ENF11

**Categoria:** Desenvolvimento

**Elos:** </br>
[Q14](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

### ENF12

**Categoria:** Desenvolvimento

**Elos:** </br>
[Q04](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Questionario/#requisitos-elicitados)

## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

[Guiabolso, Github, Requisitos.](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/pos-rastreabilidade/backward/)
