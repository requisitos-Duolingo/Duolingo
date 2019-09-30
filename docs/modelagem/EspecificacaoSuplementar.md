## Introdução

### Finalidade

A finalidade deste documento é explicitar os requisitos não funcionais da aplicação duolingo. Pegando todos aqueles requisitos que não foram pegos pelo Caso de uso. A fim de deixar os stakeholders atualizados quanto aos atributos de qualidade dos sistema abrangendo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade.


### Escopo

O escopo desta especificação suplementar se resume à aplicação duolingo  que é uma plataforma de ensino de idiomas gamificado com sistema de pontuação e ranking para deixar usuário motivado a continuar estudando. 


### Definições

Consulta aos Léxicos.

## Funcionalidades

As funcionalidades foram elicitadas  e podem ser encontradas em Elicitação de requisitos  e nos Casos de usos levantados. 

## Usabilidade


Este tópico lida com os requisitos relacionados a facilidade do usuário de interagir com a aplicação.

### Interface intuitiva e de fácil compreensão 

A Interface Gráfica tem um Design simples,intuitivo e de  fácil manuseio. Além de ser minimalista a fim de reduzir a curva de aprendizado do usuário.
Na tela inicial do aplicativo temos unidade e os  módulos com ícones interativos e de fácil inicialização com o seu nível naquele módulo e lição no mesmo.
Além de ter cores vivas com a predominância de branco e verde.

Rastro: [Brainstorm](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/) e [Entrevista](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Entrevista/).

### Divisão do sistema em níveis 

O sistema é dividido em níveis e com uma progressão ideal para cada módulo abrangendo pessoa com nenhum conhecimento prévio de inglês ou com algum conhecimento intermediário ou avançado. 

Rastro: [Brainstorm](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/)

### Aplicação Gamificada

A aplicação Duolingo é gamificada para manter o usuário engajado e motivado. Com recompensas rápidas a cada lição concluída, metas diárias que, quando cumpridas, lhe dão mais recompensas e estímulos para continuar aprendendo. E no comprimento das metas diárias e na obtenção de recompensas o usuário consegue ter o sentimento de conquista(Accomplishment).  Além disso, a aplicação tem um Ranking de amigos e Um Ranking com a liga que o usuário está inserido, dando assim um estímulo externo ao usuário a passar de nível e conseguir mais XP conseguindo passar ao usuário os sentimentos de Influência Social e Empoderamento.

Rastro: [Brainstorm](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/)

### Feedbacks

O sistema dá feedback a cada questão acertada ou errada pelo usuário,  e também das demais atividades dentro da aplicação como conquistas, recompensas e a cada nível passado.

Rastro: [Análise de Protocolo](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/AnaliseDeProtocolo/) e [Brainstorm](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/Brainstorming/)

## Confiabilidade

Esse tópico lida com os requisitos relacionados ao quanto a aplicação é confiável.

### Disponibilidade

O Duolingo mantém a aplicação ativa(tanto mobile quanto web) o maior tempo possível com seus servidores operando em atividade em quase 100% do tempo. E se houver alguma imprevisibilidade ou manutenção o usuário deve ser previamente avisado.

Rastro: Não possui

### Segurança no armazenamento de dados


O Duolingo segue uma política de armazenamento de dados baseado em sua  Política de Privacidade em que o duolingo não compartilha dados pessoais, apenas informações básicas como nível e nickname a título de interação com outros usuários. A Política de Provacidade pode ser acessada [aqui](https://www.duolingo.com/privacy) 

Em relação a dados de pagamentos para usuário do duolingo plus a aplicação segue os padrões estabelecidos pela indústria como sistema de pagamento da Google Play e da App Store como intermediário. 


Rastro: Não possui


### Suporte a falhas

O sistema deve fornecer ao usuário segurança em caso de falhas e proteger o usuário e seus dados sensíveis.

Rastro: Não Possui


## Desempenho


### Rapidez de resposta

Ao acessar o Duolingo e executar uma ação como: fazer uma lição ou fazer um teste para pular de nível o usuário tem um tempo de resposta mínimo da aplicação. Em questões de segundo o usuário consegue terminar uma ação e começar logo outra em seguida. Logo o usuário se mantém mais engajado no sistema e assim ele consegue concluir mais lições em um curto espaço de tempo.

### Armazenamento 

O aplicativo precisa de 122,9 MB(megabyte) na apple store e na Google stora varia de acordo com o aplicativo.

Rastro: [Duolingo Google Store](https://play.google.com/store/apps/details?id=com.duolingo&hl=pt&referrer=utm_source%3Dduolingo.com%26utm_medium%3Dduolingo_web%26utm_content%3Dtext_link%26utm_campaign%3Dfooter_site-map) [Duolingo Apple Store](https://apps.apple.com/br/app/duolingo-learn-spanish-french/id570060128)

### Acessos simultâneos

A aplicação deve ser capaz de atender milhares de acessos simultâneos,cada um em sua devida conta e ter uma lógica de balanceamento de carga de requisições ao servidor.

Rastro: Não possui

## Suportabilidade

### Web

A aplicação Duoligo pode ser acessada e utilizada via navegador em Desktop, tablets ou smartphone apenas necessitando de conexão a internet.

Rastro: [Duolingo Web](https://www.duolingo.com)


### Android

A aplicação mobile destinada a dispositivos Android deve ser utlizada no sistemas Android 6.0 ou versões superiores.

Rastro: [Duolingo Google play](https://play.google.com/store/apps/details?id=com.duolingo&hl=pt&referrer=utm_source%3Dduolingo.com%26utm_medium%3Dduolingo_web%26utm_content%3Dtext_link%26utm_campaign%3Dfooter_site-map)

### IOS

A aplicação mobile destinada a dispositivos Apple deve ser utilizada no sistemas iOS 11.0 ou posterior.

Rastro: [Duolingo Apple Store](https://apps.apple.com/br/app/duolingo/id570060128)

### Windows

A aplicação destina a desktop com sistema operacional Windows requer o Sistema Windows 10 versão 10240.0 ou superior  com arquitetura x86 ou  x64.

Rastro: [Duolingo Microsoft Store](https://www.microsoft.com/pt-br/p/duolingo-cursos-gratis-de-ingles-espanhol-e-frances/9wzdncrcv5xn?activetab=pivot:regionofsystemrequirementstab)

### Windows Phone

A aplicação mobile destinada a Dispositivos Windows deve ser utilizada no Sistema Windows 8 Mobile ou superior com arquitetura ARM ou ARM64.

Rastro: [Duolingo Microsoft Store](https://www.microsoft.com/pt-br/p/duolingo-cursos-gratis-de-ingles-espanhol-e-frances/9wzdncrcv5xn?activetab=pivot:regionofsystemrequirementstab)

## Requisitos de Licenciamento 

### Termos de Uso

O Duolingo apresenta um termo de uso para que o usuário concorde em utilizar as informações da Aplicação dentro dos limites estabelecidos.

Rastro: [Termo de Uso Duolingo](https://www.duolingo.com/terms)

### Termos de Privacidade

O Duolingo aprensenta um termo de privacidade para que o usuário concorde com a utilização alguns de suas dados pessoas(como nickname) em Ranking na liga em que ele estiver ou com seus amigos.

Rastro: [Termo de Privacidade Duoligo](https://www.duolingo.com/privacy)


|  | Especificação Suplementar |
|----|------------|
| **Versão** | Atual:1.0 (26/09/2019) |
| **Descrição** | Especificação do requisitos não funcionais  |


## Referências

SEQ18RRANO, Maurício; SERRANO, Milene. Requisitos - Aula 11. 1º/2019. 40 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
