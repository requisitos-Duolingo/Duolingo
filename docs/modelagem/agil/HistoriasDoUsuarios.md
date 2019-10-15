## Introdução

O Backlog do Produto é uma lista de funcionalidades desejadas de um produto, ou seja, os requisitos que um cliente espera receber ao final do projeto, descrito com sua própria linguagem.

## Metodologia

## Épicos

**Legenda**:

* T: Temas.

| **Épico** | **Descrição** | **Features** |
|:----------|:-------------:|:-------------|
| T01 - Cadastro e Autenticação | Engloba toda a parte de cadastramento, login, lougout e chaves de acesso. | > Cadastro; </br> > Login; </br> > Logout. |
| T02 - Perfil | Engloba toda a parte de informações de usuário, configurações da aplicação, notificações. | > Perfil; </br> > Configurações Gerais; </br> > Avisos; </br> > Central de Ajudas e Sugestões.  |
| T03 - Cursos | Engloba toda a parte de aprendizagem do usuário. | > Curso; </br> > Aula; </br> > Seção. |
| T04 - Gameficação | Engloba toda a parte que mantém o usuário engajado. | > Ranking; </br> > Conquistas; </br> > Amigos; </br> > Ofensiva; </br> > Nível; </br> > Lingots; </br> > Loja. |
| T05 - Lucro | Engloba toda a parte de monetização do aplicativo. | > Duolingo Plus; </br> Anúncios. |

## Features

**Legenda**:

* US: Histórias de Usuários.

### Feature 1 - Cadastro e Autenticação

| **ID** | **Nome** |
|:-------|:---------|
| US01 | Elaborar formulário de interese de curso |
| Descrição | _Eu, como_ desenvolvedor, _desejo_ elaborar um formulário com os dados interesse de curso do usuário _para que eu possa_ efetuar o cadastro na aplicação |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Qual idioma quero aprender </br> > Por que você está aprendendo um idioma </br> > Quantos minutos por dia eu posso estudar </br> > Começar do básico ou teste de nivelamento |

| **ID** | **Nome** |
|:-------|:---------|
| US02 | Elaborar formulário de informações pessoais |
| Descrição | _Eu, como_ desenvolvedor, _desejo_ elaborar um formulário com as informações pessoais do usuario _para que eu possa_ efetuar o cadastro na aplicação |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Idade </br> > Nome </br> > E-mail </br> > Senha |

| **ID** | **Nome** |
|:-------|:---------|
| US03 | Validação do formulário de informações pessoais |
| Descrição | _Eu, como_ desenvolvedor, _desejo_ elaborar um processo de validação das informações pessoais do usuário _para que eu possa_ garantir a veracidade dos dados |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> **Idade** </br> > Apenas caracteres numéricos e inteiros </br> > Não pode ser negativo </br> >  Não pode ser maior que 149 </br> **Nome** </br> > Apenas caracteres do alfabeto </br> **Email** </br> > Tem que ser email válido segundo este [link](https://www.devmedia.com.br/validando-e-mail-em-inputs-html-com-javascript/26427) </br> > Não pode ser um email duplicado </br> **Senha** </br> > Tem que ter, no mínimo, 7 caracteres da Tabela ASCII |

| **ID** | **Nome** |
|:-------|:---------|
| US04 | Fazer login |
| Descrição | _Eu, como_ usuário, _desejo_ fazer login na plataforma _para que eu possa_ entrar na minha conta e dar continuidade nas atividades da plataforma |
| Critérios  de Aceitação | Deve conter as seguintes opções: </br> > Implementar caixa de texto para inserir email e senha </br> > Opção de recuperar senha </br> > Opção de entrar com Google/Facebook </br> > Opção que redireciona para parte de criar cadastro </br> > Ter opção de visualizar senha inserida |

| **ID** | **Nome** |
|:-------|:---------|
| US05 | Validação do formulário de login |
| Descrição | _Eu, como_ desenvolvedor, _desejo_ elaborar um processo de validação das informações de login do usuário _para que eu possa_ autenticá-lo |
| Critérios de Aceitação | Deve conter as seguintes opções: **Email** </br> > Tem que ser email válido segundo este [link](https://www.devmedia.com.br/validando-e-mail-em-inputs-html-com-javascript/26427) </br> > Não pode ser um email já cadastrado </br> **Senha** </br> > Tem que ter, no mínimo, 7 caracteres da Tabela ASCII </br> A senha tem que corresponder a senha de castramento do usuário |

| **ID** | **Nome** |
|:-------|:---------|
| US06 | Fazer lougout |
| Descrição | _Eu, como_ usuário, _desejo_ fazer lougout na plataforma _para que eu possa_ fazer o login em outra conta |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Tem que ter uma opção para o usuário poder sair de sua conta |

### Feature 2 - Perfil

### Feature 3 - Cursos

| **ID** | **Nome** |
|:-------|:---------|
| US11 | Escolher um curso |
| Descrição | _Eu como_ usuário _Desejo_ escolher qual curso de idioma fazer _Para Que Eu Possar_ aprender |
| Críterios de Aceitação| Deve contém as seguintes opções: </br> > Tem que haver uma lista de cursos para escolher </br> |

| **ID** | **Nome** |
|:-------|:---------|
| US12 | Adicionar um curso |
| Descrição | _Eu como_ usuário _Desejo_ escolher outro idioma para cursar _Para Que Eu Possar_ ganhar mais conhecimento |
| Críterios de Aceitação| Deve contém as seguintes opções: </br> > Tem que haver uma lista de cursos para escolher </br> |

| **ID** | **Nome** |
|:-------|:---------|
| US13 | Realizar aulas |
| Descrição | _Eu como_ usuário _Desejo_ ter aulas a serem realizadas _Para Que Eu Possar_  aprender |
| Críterios de Aceitação| Deve contém as seguintes opções: </br> > Tem que haver uma lista de atividades </br> > Tem que haver exercícios de conversação </br>  > Tem que haver exercícios de compreensão </br> |

| **ID** | **Nome** |
|:-------|:---------|
| US14 |  Aulas organizadas por seção |
| Descrição | _Eu como_ usuário _Desejo_ ter aulas organizadas por seção _Para Que Eu Possar_  organizar o meus estudos de um novo idioma |
| Críterios de Aceitação| Deve contém as seguintes opções: </br> > Tem que haver aulas dividas por nível de dificuldade </br> > Realizar aulas da próxima seção ao concluir um teste nivelamento da seção anterior </br> > Realizar aulas da próxima seção ao concluir aulas da seção anterior </br> |

### Feature 4 - Gameficação

### Feature 5 - Lucro

## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 46 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
