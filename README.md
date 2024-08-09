## Projeto de Cadastro e Login
Este projeto é uma aplicação simples para gerenciamento de usuários com funcionalidades de login, cadastro e edição de registros. É composto por duas telas principais: uma tela de login e uma tela de cadastro.

Funcionalidades
Tela de Login

## Campos: Email e Senha
Validação: Verifica se ambos os campos estão preenchidos. Se algum campo estiver vazio, exibe um alerta solicitando o preenchimento dos campos.
Redirecionamento: Se ambos os campos estiverem preenchidos, o usuário é redirecionado para a tela de cadastro (cadastro.html).
Tela de Cadastro

## Campos: Nome do Usuário
Ações Disponíveis:
Salvar Usuário: Adiciona o nome do usuário ao array dadosLista e atualiza a tabela de usuários.
Editar Usuário: Permite editar o nome de um usuário selecionado. O nome é removido da lista e colocado no campo de entrada para edição.
Excluir Usuário: Remove o nome do usuário da lista e da tabela.

## Uso
Acesse o index.html para iniciar o login.
Preencha os campos de email e senha e clique no botão de acesso.
Na tela de cadastro, insira o nome do usuário e clique em "Salvar Usuário" para adicionar o nome à lista.
Edite ou exclua nomes da lista usando os botões apropriados.

## Observações
Certifique-se de que os IDs dos elementos HTML correspondam aos usados no JavaScript.
A tabela de usuários é atualizada dinamicamente toda vez que um nome é adicionado, editado ou excluído.


## Fontes consultadas

https://developer.mozilla.org/en-US/docs/Web/API/HTMLTableElement/deleteRow 

https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/splice