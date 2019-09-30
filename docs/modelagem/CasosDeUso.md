## Introdução
Casos de Uso são utilizados para descrever um conjunto de ações(casos de uso) que um sistema ou um conjunto de sistemas(sujeito) deve desempenhar em colaboração com um ou mais usuários externos ao sistema(ator). Cada caso de uso deverá prover algum resultado observável e de valor para os atores ou outros interessados do sistema.

## Metodologia
Para criação dos casos de uso foram identificados e analisados os documentos de elicitação de requisitos gerados na sprint anterior. A partir disso, foram feitos os casos de uso utilizando a ferramenta Astah.

## Casos de Uso & Especificação

### **UC01 - Fazer Login**

![Caso-de-Uso-Login](../images/UseCase-Login.png)

| UC01                     | Fazer Login |
| --------------           |:----------- |
| **Versão**               | Atual 1.0 (25/09) <br> Anterior: -- |
| **Autor(es)**            | Luis Gustavo e Vitor Alves |
| **Descrição**            | Fazer Login no Duolingo |
| **Ator(es)**             | > Usuário <br> > Duolingo |
| **Pré condições**        | > Usuário estar deslogado no aplicativo |
| **Fluxo principal**      | > Usuário acessa o Duolingo <br> > Usuário clica no botão "Já tenho uma conta" <br> > Usuário insere os dados de email ou nome de usuário e senha <br> > Usuário clica no botão "Entrar" <br> > Os dados de login são autenticados |
| **Fluxos alternativos**  | **Fluxo Alternativo 1 - Cadastro:** <br> > Usuário acessa o Duolingo <br> > Usuário clica no botão "Início" <br> > Usuário segue os passos para realizar o [cadastro](#uc02-cadastrar-usuario) <br> > O usuário é logado automaticamente ao criar seu cadastro |
| **Fluxos de exceção**    |  **Fluxo de Exceção 1 - Dados de Login inválidos:** <br> > Aplicativo apresentar uma mensagem de erro avisando que não foi possível fazer o Login <br> <br> **Fluxo de Excecão 2 - Usuário esqueceu a senha:** <br> > Usuário clica no botão "Esqueci a Senha" <br> > Usuário insere email para recuperar a senha <br> > É feita uma validação para identificar se existe um usuário cadastrado com aquele email <br> > É enviado um email para o usuário redefinir sua senha |
| **Pós condições**        | Usuário fica logado no Duolingo e é direcionado para a aba de aulas |
| **Rastreabilidade**      | INT02 |


### **UC02 - Cadastrar Usuário**

![Caso-de-Uso-Cadastro](../images/Caso-de-Uso-Cadastro.png)

| UC02                     | Cadastrar usuário |
| --------------           |:----------- |
| **Versão**               | Atual 1.0 (26/09) <br> Anterior: -- |
| **Autor(es)**            | Luis Gustavo e Vitor Alves |
| **Descrição**            | Criar cadastro para um usuário |
| **Ator(es)**             | > Usuário <br> > Duolingo |
| **Pré condições**        | > Usuário estar deslogado no aplicativo |
| **Fluxo principal**      | > Usuário acessa o Duolingo <br> > Usuário clica no botão "Início" <br> > Usuário insere do curso(idioma que deseja apreder, motivo de estar aprendendo um idioma, meta(minutos de estudo por dia) e caminho(aprender do início ou fazer um teste de nivelamento)) <br> > Usuário segue os passos para realizar uma [aula]() <br> > Usuário insere as informações de perfil(idade, nome, email e senha) <br> > Os dados de cadastro são autenticados |
| **Fluxos alternativos**  | **Fluxo Alternativo 1 - Usuário realiza mais aulas:** <br> > Usuário acessa o Duolingo <br> > Usuário clica no botão "Início" <br> > > Usuário insere do curso(idioma que deseja apreder, motivo de estar aprendendo um idioma, meta(minutos de estudo por dia) e caminho(aprender do início ou fazer um teste de nivelamento)) <br> > Usuário segue os passos para realizar uma [aula]() <br> > Usuário clica no botão "Depois" <br> > > Usuário segue os passos para realizar uma [aula]() <br> > Usuário clica no botão "Criar Perfil" <br> > Usuário segue os passos para realizar uma [aula]() <br> > Usuário insere as informações de perfil(idade, nome, email e senha) <br> > Os dados de cadastro são autenticados |
| **Fluxos de exceção**    |  **Fluxo de Exceção 1 - Email já cadastrado:** <br> > Aplicativo mostra que já existe um usuário cadastrado com esse email e fornece o campo de senha para fazer login nessa conta já cadastrada <br> <br> **Fluxo de Excecão 2 - Email inválido:** <br> > Aplicativo apresenta uma mensagem de erro pedindo para o usuário inserir um email válido <br> <br> **Fluxo de Excecão 3 - Idade inválida, negativa ou muito alta:** <br> > Aplicativo apresenta uma mensagem de erro pedindo para o usuário inserir uma idade válida |
| **Pós condições**        | Usuário fica logado no Duolingo e é direcionado para a aba de aulas |
| **Rastreabilidade**      | INT02 |

## Referências

SEQ18RRANO, Maurício; SERRANO, Milene. Requisitos - Aula 11. 1º/2019. 40 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.