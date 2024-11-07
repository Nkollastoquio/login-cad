## Sistema de Cadastro de Usuários
Este projeto é uma aplicação web simples para cadastro e gestão de usuários. A página permite adicionar usuários com nome, e-mail e CPF, bem como visualizar a lista de usuários em uma tabela.

## Funcionalidades
Cadastro de Usuários: Permite adicionar usuários com nome, e-mail e CPF.
Validação de Campos: Verifica se os campos são preenchidos e se o CPF e e-mail estão em formato válido.
Exibição de Lista: Mostra a lista de usuários em uma tabela com a opção de editar e excluir entradas (dependente do JavaScript implementado).

## Tecnologias Utilizadas
* HTML: Estrutura da página.
* CSS: Estilização dos componentes (utilizando Bootstrap e um arquivo CSS personalizado).
* JavaScript: Lógica para validar e manipular dados dos usuários.

## Sistema de Cadastro de Usuários

Este projeto é uma aplicação web simples para cadastro de usuários, com validação de CPF e e-mail. Ele permite adicionar, editar e excluir usuários, e exibe uma lista de usuários cadastrados.

Funcionalidades
* Validação de CPF: Verifica se o CPF informado é válido.
* Validação de E-mail: Verifica se o e-mail informado tem um formato válido.
* Cadastro de Usuários: Permite adicionar usuários com nome, e-mail e CPF.
* Edição de Usuários: Permite editar informações de usuários existentes.
* Exclusão de Usuários: Permite remover usuários da lista.
* Tecnologias Utilizadas
* HTML: Estrutura da página.
* CSS: Estilização dos componentes (não incluído neste exemplo).
* JavaScript: Lógica de validação e manipulação dos dados.

1. Funcionalidades da Página
Tela de Login
Campos: E-mail e Senha.
Botão: Acessar (redireciona para a página de cadastro se ambos os campos estiverem preenchidos).
Tela de Cadastro
Campos: Nome, E-mail e CPF.
Botão: Salvar (adiciona um usuário à lista se os campos forem válidos).
Tabela: Exibe a lista de usuários com botões para Editar e Excluir.
2. Funções JavaScript
* validarCPF(cpf): Valida o CPF informado.
* acessar(): Verifica o preenchimento dos campos de login e redireciona.
* salvarUser(): Salva os dados do usuário na lista e atualiza a tabela.
*  criarLista(): Atualiza a exibição da lista de usuários.
* editar(index): Permite editar os dados de um usuário.
* excluir(index): Remove um usuário da lista.
