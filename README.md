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

### 1º Cenario: Login

| BDD | Status |
| --- | --- |
| Quando eu esteja na tela de login, Quando preencher usuario corretamente e Senha incoretamente, O sistema deve informar "Login ou Senha incorreta" |     |
| Quando eu esteja na tela de login, Quando preencher usuario incorretamente e Senha coretamente  O sistema deve informar "Login ou Senha incorreta" |     |

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
