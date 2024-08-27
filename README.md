# Qa_EduSphere

O Edusphere é uma plataforma para gerenciamento de atividades acadêmicas. Com ela, instituições de ensino podem gerenciar de forma fácil todos os módulos de cursos.

## Escopo do Projeto

1. Registro de Usuários:
- Administradores do sistema registram outros usuários (gestores de
departamento, professores e alunos) no sistema.
2. Registro de Departamentos:
- Administradores do sistema registram os departamentos no sistema.
3. Login:
- Implementar um sistema de autenticação seguro para garantir o acesso
adequado aos diferentes usuários.
4. Controle de Acesso:
- Definir níveis de permissão para garantir que cada usuário tenha acesso apenas
às funcionalidades apropriadas.

### Módulo do Aluno

Perfil do Aluno:
- Exibir informações pessoais e dados acadêmicos, apenas.
Efetuar matrícula em Disciplinas Oferecidas no semestre:
- O aluno poderá realizar a matrícula nas disciplinas disponibilizadas para ele.
  
### Módulo do Professor

7. Perfil do Professor:
- Exibir informações pessoais e dados acadêmicos, apenas.
  
### Módulo do Gestor de Departamento

8. Gerenciamento de Professores:
- Permitir a adição, remoção e edição de informações sobre professores.
10. Cadastro de Disciplinas:
- Cadastra no sistema as disciplinas que serão lecionadas.
11. Alocação de Disciplinas:
- Facilitar a atribuição eficiente de disciplinas aos professores.

## Casos de Teste

Link para planilha com os casos de teste QA_EduShere: https://docs.google.com/spreadsheets/d/154YdFsW36r9nLieqHUPfc2Kj2nai1_iODxsipl8ShoA/edit?usp=sharing

### 1º Cenario: Login

| BDD | Status | Descrição |
| --- | --- | --- |
| Quando eu esteja na tela de login, Quando preencher usuario corretamente e Senha incoretamente, O sistema deve informar "Login ou Senha incorreta" |     |   |
| Quando eu esteja na tela de login, Quando preencher usuario incorretamente e Senha coretamente  O sistema deve informar "Login ou Senha incorreta" |     |   |
| Quando eu esteja na tela de login, Quando preencher usuario corretamente e Senha coretamente  O sistema deve logar como (gestor, professor ou aluno) |    |   |
| Quando eu esteja na area de login, O usario tentar fazer login sem preencher alguma informação (deixar em branco), O sistema deve informar que o campo deve ser preenchido |    |    |  
| Quando eu esteja na area de login, Ao selecionar a opção manter conectado, Apos fazer login e logout a credencial de usuario deve ficar salva |    |   |
| Quando eu esteja na area de login, Ao selecionar a opção manter conectado, Apos tentar fazer login e nao consegui a credencial de usuario nao deve ficar salva |    |   |
| Quando eu esteja na area de login, Ao clicar na opção "Novo aqui? Criar conta", O sistema deve direcionar para tela de registar |    |   |
| Quando eu esteja na area de login, Ao clicar na opção esqueceu sua senha?, O sistema deve direcionar para tela de recuperar senha |    |   |

### 2º Cenario: Recuperar Senha

| BDD | Status | Descrição |
| --- | --- | --- |
| Quando eu esteja na area de recuperar senha  e digitar um email valido sera mandado um email para criar uma nova senha |    |   |   
| Quando eu esteja na area de recuperar senha e digitar um email invalido aparecera um aviso que o email não é cadastrado "Email não cadastrado" |    |   |
| Quando eu esteja na area de recuperar senha e nao digitar nada no campo de email o sistema deve informar campo em branco |    |   |

### 3º Cenario: Nova Senha

| BDD | Status | Descrição |
| --- | --- | --- |
| Quando digitei senhas campativeis no campo um e no campo dois. Aparece um aviso do sistema "Nova senha registrada" |    |   |
| Quando digitei senhas diferentes no campo um e no campo dois. Aparece um aviso "Senhas diferentes" |    |   |
| Quando deixei um campo em branco ou os dois campos em branco. O sistema deve informar de que esta vazio (fica vermelho ?) |    |   |

### 4º Cenario: Tela Padrao (Navbar)

| BDD | Status | Descrição |
| --- | --- | --- |
| Quando cliquei no botao de expadir com a navbar maximizada. Minimizar para modo recolhido |    |   |
| Quando cliquei no botao de expadir com a navbar recolhida. Maximizar para modo grande     |    |   |
| Quando cliquei no botão perfil a pagina foi direcionada para perfil |    |   |
| Quando cliquei no botão Usuarios a pagina foi direcionada para usuarios  |    |   |
| Quando cliquei no botão Departamento a pagina foi direcionada para departamentos |    |   |
| Quando cliquei no botão Cursos a pagina foi direcionada para cusos  |    |   |
| Quando cliquei no botão logout apereceu um aviso na tela para confirmação do logout   |    |   |

### 5º Cenario: Tela Adm Departamentos

| BDD | Status | Descrição |
| --- | --- | --- |
| Quando busquei um departamento por nome atualizou a tabela com informações corretas  |  |   |
| Quando busquei um departamento por codigo atualizou a tabela com informações corretas  |  |   |
| Ao pesquisar atualiza a tabela nomes?  |  |   |
| Ao pesquisar atualiza a tabela codigo? |  |   |
| Quando clicar nos botão < ou > a tabela atualiza os proximos dados  |  |   |
| A tabela mostra quantas paginas de dados tem no final ? |  |   |
| Ao clicar no botão apagar aparece um popup para confirmação de exclusao  |  |   |
| Ao clicar em apagar. Apaga corretamente o dado do BD e atualiza a tabala? |  |   |
| Todos itens da tabala mostra apenas como vizualização nao permitindo edição direto da tabela |  |   |
| Quando esteja na tabela as colunas ficam estaticas |  |   |
| Ao clicar no botão adicionar departamento abre o pop-up (Pop-up add Departamento) |  |   |
| No pop-up ao deixar alguma informação em branco na hora de salvar o departamento aparece o aviso em vermelho (Não foi possível cadastrar o departamento. Verifique e tente novamente.) |  |   |
| Ao preencher corretamente os campus e salvar aparece o aviso (Departamento adicionado com sucesso.) e o novo departamento é adicionado ao BD e pode ser vizualizado na tabela   |  |   |
| Ao clicar no botão voltar do pop-up volta para tela anterior nome e descrição  |  |   |

### 6º Cenario: 

| BDD | Status | Descrição |
| --- | --- | --- |

### 7º Cenario: 

| BDD | Status | Descrição |
| --- | --- | --- |

#### Cadastrar Novo gestores de departamento
- Preencher os campos obrigatórios com dados validos (nome, email, senha, tipo de usuário: Gestor).
- Enviar o formulário.
- Resultado Esperado: Usuário professor é registrado com sucesso e uma mensagem de confirmação é exibida.

#### Cadastrar Novo Professor
- Preencher os campos obrigatórios com dados validos (nome, email, senha, tipo de usuário: professor).
- Enviar o formulário.
- Resultado Esperado: Usuário professor é registrado com sucesso e uma mensagem de confirmação é exibida.

#### Cadastrar Novo Aluno
- Preencher os campos obrigatórios com dados validos (nome, email, senha, tipo de usuário: professor).
- Enviar o formulário.
- Resultado Esperado: Usuário professor é registrado com sucesso e uma mensagem de confirmação é exibida.

####
