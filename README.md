# Cadastro de Usuários

Este projeto é uma aplicação simples desenvolvida para atender ao desafio técnico da IBB Instituto Brasileiro de Biotecnologia e Inovação. O objetivo principal foi utilizar a lógica de forma eficiente e direta, conforme solicitado. 
A aplicação permite criar, editar e excluir usuários, com todos os dados armazenados no localStorage do navegador para uma implementação prática e acessível.

## Estrutura do Projeto

O projeto é composto por três arquivos principais:

- **`index.html`**: Define a estrutura da página.
- **`style.css`**: Define o estilo da página.
- **`main.js`**: Define a funcionalidade da aplicação.

### `index.html`

O arquivo HTML define a estrutura básica da aplicação. Ele inclui:
- Um formulário para o cadastro de novos usuários.
- Uma tabela para listar os usuários cadastrados.
- Um modal para editar as informações dos usuários.

### `style.css`

O arquivo CSS define o estilo da aplicação, incluindo:
- A aparência do cabeçalho.
- O estilo dos botões.
- O estilo do modal.
- A aparência da tabela.

### `main.js`

O arquivo JavaScript define a lógica da aplicação, incluindo:
- A abertura e fechamento do modal.
- A manipulação do `localStorage`.
- Operações CRUD (Criar, Ler, Atualizar, Excluir) para os usuários.

## Funcionalidades

- **Cadastro de Usuários**: Adiciona um novo usuário ao `localStorage` e atualiza a tabela.
- **Edição de Usuários**: Permite editar um usuário existente.
- **Exclusão de Usuários**: Remove um usuário da lista.
- **Validação de Formulário**: Verifica se os campos do formulário estão preenchidos corretamente.

## Como Usar

1. Abra o arquivo `index.html` em um navegador para usar a aplicação.
2. Utilize o formulário para adicionar novos usuários.
3. Clique em "Editar" na tabela para modificar informações de um usuário.
4. Clique em "Excluir" para remover um usuário da lista.

