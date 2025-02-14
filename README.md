Sistema CRUD de Planetas com Flutter
Descrição
Este projeto consiste no desenvolvimento de um aplicativo Android utilizando o framework Flutter. O objetivo é implementar um sistema CRUD (Create, Read, Update, Delete) para gerenciar informações de planetas. O sistema armazena os dados localmente utilizando o banco de dados SQLite, oferecendo uma interface amigável para adicionar, visualizar, editar e excluir planetas.

Requisitos
Funcionalidades
Criação (Create): Permitir o cadastro de novos planetas.

Campos obrigatórios para o cadastro:

Nome do planeta.

Distância do sol (em unidades astronômicas).

Tamanho (em quilômetros).

Campo não obrigatório:

Apelido

Validação dos campos:

Todos os campos obrigatórios devem ser preenchidos.

Valores numéricos devem ser positivos.

Leitura (Read): Exibir uma lista de planetas cadastrados.

Dados exibidos:

Nome do planeta.

Apelido.

Possibilidade de acessar detalhes do planeta, mostrando todas as informações cadastradas.

Atualização (Update): Permitir a edição dos dados de planetas cadastrados.

Validar os campos de entrada para garantir a consistência dos dados.

Atualizar a interface após a alteração.

Exclusão (Delete): Permitir a exclusão de planetas da base de dados.

Implementar uma confirmação antes de realizar a exclusão.

Atualizar a interface para remover o planeta da lista.

Persistência e Confiabilidade
Os dados devem permanecer salvos mesmo após o encerramento do aplicativo.

Requisitos de Interface (UI)
Tela inicial com a lista de planetas.

Botão flutuante (Floating Action Button) para adicionar novos planetas.

Formulário para cadastro/edição de planetas.

Tela de detalhes do planeta com todas as informações.

Feedback visual para ações realizadas (ex.: mensagem de sucesso ou erro).

Requisitos Técnicos
Linguagem: Dart.

Framework: Flutter.

Banco de Dados: SQLite.

Requisitos de Qualidade
Código modular e organizado seguindo o padrão MVC ou MVVM.

Comentários no código para facilitar a manutenção.

Nomes de classes, métodos e variáveis claros e descritivos.

Testes básicos para validar operações de CRUD.
