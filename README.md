# PHP Projeto Login-Cadastro

> Pequeno site que possui, área de Login, Cadastro, Listagem de usuários e clientes com paginação e redefinição de senha.

## Login

Na área de Login, deve-se digitar o endereço de e-mail e senha do usuário que já possui cadastro no banco de dados do site.
Se o usuário tiver esquecido de sua senha, será necessário redefini-la. Acione o link "Esqueci minha senha".
Caso seja o primeiro acesso, deverá ser acionado o link "Cadastre-se", que redirecionará o usuário a tela de cadastro.

## Recuperação de Senha

Aqui, o usuário, previamente cadastrado, deverá inserir o e-mail ao qual usou para se cadastrar no sistema. Ao confirmar a redefinição de senha, um e-mail automático será enviado para o e-mail informado, contendo a nova senha que será usada para acessar o sistema.


## Cadastro de Usuário

Na tela de cadastro, o novo usuário deverá preencher todos os campos com informações válidas:

* Nome Completo
* Endereço de E-mail
* Senha
* Gênero
* Telefone
* Estado
* Cidade

Se já possuir cadastro, o usuário poderá voltar a tela de Login ao acionar o link "Entrar" no rodapé do formulário.

## Página Inicial (Lista de Clientes)

Ao ser autenticado, o usuário será redirecionado para a página inicial, onde se encontra uma tabela com os dados de todos os clientes salvos no banco de dados.
É possível alternar entre tabelas, uma com os dados de clientes, e a outra com os dados dos usuários, para isso, é preciso pressionar ou o botão "Usuários" ou "Clientes", localizados no canto direito superior da tabela. Na mesma linha se encontra uma caixa "Buscar" com uma lupa ao lado. Atráves do uso do botão pesquisar, é possível filtrar informações da tabela com o conteúdo inserido na busca como:

* Estado
* Cidade
* Nome
* Situação
* Origem

Encontra-se na coluna "Ações" dois icones. O icone "Azul", ao ser clicado, levará o usuário a página de "Editar Cliente". O icone "Vermelho", excluirá o cliente presente na linha.
No rodapé da tabela, no canto esquerdo, temos o botão de "Logoff", que desconectará o usuário do sistema, levando o mesmo para a tela de "Login". Acima do "Logoff" temos um icone "Verde", que levará o usuário a tela de "Cadastrar Cliente".
Já no canto inferior direito da tabela é possível visualizar a paginação, que ao interagir, fará a mudança das páginas para a visualização do restante do conteúdo, caso haja.

## Cadastro de Cliente

Atráves do formulário contido nessa página, o usuário já autenticado, será possível adicionar dados de novos clientes ao banco de dados. Todos os campos deverão ser preenchidos de maneira correta:

* Nome Completo
* Endereço de E-mail
* Documento (CNPJ)
* Telefone
* Origem (Poderá ser mais de uma)
* Estado
* Cidade
* Observação (Não é obrigatório)

No fim do formulário o usuário poderá retornar a página inicial ou, cadastrar um novo cliente.



