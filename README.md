# Proway Computers - Loja Virtual

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)

> **Nota:** Você pode acessar a demonstração ao vivo do projeto [clicando aqui](https://ritajeveaux.github.io/proway-computers/).

Este é um projeto de uma loja virtual de produtos de informática, desenvolvido como parte de um portfólio para demonstrar habilidades em desenvolvimento web com o framework Angular. O site permite que os usuários visualizem produtos, adicionem itens ao carrinho e entrem em contato com a loja.

## 📜 Descrição

A Proway Computers é uma simulação de e-commerce focada em hardware e periféricos de computador. A aplicação possui as funcionalidades essenciais de uma loja online, desde a vitrine de produtos até um carrinho de compras funcional e uma página de contato.

## ✨ Funcionalidades

- **Listagem de Produtos**: Página inicial que exibe todos os produtos disponíveis com imagem, nome e preço.
- **Pesquisa de Produtos**: Funcionalidade de busca na barra de navegação para filtrar produtos por descrição.
- **Detalhes do Produto**: Página dedicada para cada produto, mostrando mais informações e permitindo a seleção de quantidade.
- **Carrinho de Compras**:
  - Adicionar produtos ao carrinho a partir da página de detalhes.
  - Visualizar todos os itens no carrinho.
  - Remover itens individualmente.
  - Limpar todos os itens do carrinho.
  - O carrinho persiste os dados utilizando o `localStorage` do navegador.
- **Página de Contato**: Formulário para envio de mensagens com validações de campos (nome, assunto, telefone, e-mail e mensagem) e um mapa de localização incorporado.
- **Notificações**: Feedback visual para o usuário ao adicionar um produto ao carrinho.
- **Roteamento**: Navegação fluida entre as diferentes seções da loja (produtos, detalhes, carrinho, contato).

## 🛠️ Tecnologias Utilizadas

- **Angular**: Framework principal para a construção da Single-Page Application (SPA).
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **HTML5 & CSS3**: Estruturação e estilização das páginas.
- **Angular Router**: Para gerenciamento das rotas da aplicação.
- **Angular Forms (Reactive Forms)**: Para a construção e validação do formulário de contato.

## 🚀 Como Executar o Projeto

Para executar este projeto localmente, você precisará ter o Node.js e o Angular CLI instalados.

1.  **Clone o repositório:**

    ```bash
    git clone <url-do-seu-repositorio>
    ```

2.  **Navegue até o diretório do projeto:**

    ```bash
    cd proway-computers
    ```

3.  **Instale as dependências:**

    ```bash
    npm install
    ```

4.  **Inicie o servidor de desenvolvimento:**

    ```bash
    ng serve
    ```

5.  Abra seu navegador e acesse `http://localhost:4200/`.

## 🏗️ Build para Produção

Para gerar os arquivos de build para produção, execute o seguinte comando:

```bash
ng build
```

Os arquivos otimizados para produção serão gerados no diretório `dist/proway-computers`.

_© 2023 - Rita Jeveaux_
