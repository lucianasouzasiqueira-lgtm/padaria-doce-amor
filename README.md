# Padaria Doce Sabor

Este é um sistema básico de gerenciamento para a Padaria Doce Sabor, desenvolvido utilizando HTML, CSS e JavaScript puro (framework-less).

O sistema inclui funcionalidades como:
- Cadastro básico de clientes frequentes.
- Uma calculadora de pedidos com descontos, impostos, taxa de entrega, cálculo de troco e uso de pontos de fidelidade.
- Um carrinho de compras simples.
- Gerenciamento de produtos favoritos.
- Sistema de notificações.

Além do sistema da padaria, este projeto também inclui exemplos e atividades focadas em conceitos de JavaScript, como:

- **Atividade 1: Funções Básicas para Cálculos:** Implementação de funções essenciais para um sistema de delivery (`boasVindas`, `calcularSubtotal`, `calcularDesconto`, `calcularTaxaEntrega`).
- **Atividade 2: Funções com Retorno:** Desenvolvimento de funções que retornam valores para cálculos de imposto, total final e verificação de frete grátis.
- **Atividade 3: Aplicação Prática Completa:** Criação de uma página web (`calculos_pedidos.html`) que simula um sistema de pedidos, utilizando as funções das atividades anteriores para realizar e exibir cálculos com base na entrada do usuário.
- **Atividade 4: Arrow Functions:** Demonstração do uso de arrow functions como uma sintaxe alternativa para funções, convertendo algumas funções tradicionais para este formato.

## Visual Presentation

A aplicação conta com uma apresentação visual aprimorada, incluindo:

- Uma **galeria de produtos** interativa que exibe os itens disponíveis com imagens e detalhes.
- A **logo da Padaria Doce Sabor** claramente exibida ao lado do título principal no cabeçalho para uma identidade visual forte.

## Variáveis Utilizadas

As principais variáveis e estruturas de dados utilizadas no arquivo `script.js` do sistema da padaria são:

### Informações da Padaria
- `nomePadaria`: Nome da padaria (string, `const`).
- `endereco`: Endereço da padaria (string, `const`).
- `telefone`: Telefone de contato da padaria (string, `const`).
- `descricaoPadaria`: Descrição da padaria (string, `var` - para demonstração).\n- `anoFundacao`: Ano de fundação da padaria (número, `const`).
- `clientesHoje`: Contador de clientes atendidos hoje (número, `let`).

### Produtos e Estoque
- `precoPaoFrances`, `precoBolo`, `precoSalgado`, etc.: Variáveis para armazenar os preços unitários dos produtos (número, `let`).
- `estoquePao`, `estoqueBolo`, `estoqueSalgado`, etc.: Variáveis para controlar a quantidade em estoque dos produtos (número, `let`).
- `produtos`: Array contendo os nomes dos produtos disponíveis (array de strings, `const`).
- `categorias`: Array contendo as categorias de produtos (array de strings, `const`).
- `produtoObjeto`: Exemplo de objeto representando um produto com diversas propriedades como nome, preço, estoque, etc. (objeto, `const`).
- `produtosDisponiveis`: Array contendo uma lista mais extensa de nomes de produtos disponíveis (array de strings, `let`).
- `vendasProdutos`: Objeto para registrar a quantidade vendida de cada produto para o ranking (objeto, onde as chaves são nomes de produtos e os valores são números, `{}`).

### Clientes e Fidelidade
- `clientesFrequentes`: Array de objetos, onde cada objeto representa um cliente frequente com propriedades como nome, telefone e pontos (array de objetos, `let`).

### Pedidos
- `carrinho`: Array de objetos que representa os itens atualmente no carrinho de compras (array de objetos, `let`). Cada item pode conter o produto e a quantidade.
- `historicoPedidos`: Array de objetos que registra os pedidos finalizados (array de objetos, `let`). Cada objeto de pedido pode conter informações sobre o cliente, itens, total, status e horário.

### Configurações
- `configuracoes`: Objeto contendo configurações gerais do sistema, como taxas de câmbio, regras de desconto por quantidade, percentual de imposto e taxa de entrega fixa (objeto, `const`).

## Como Executar o Projeto

Para executar o sistema da padaria, basta abrir o arquivo `index.html` em um navegador web compatível com HTML5, CSS3 e JavaScript.

Para visualizar as atividades focadas em funções, abra os arquivos HTML correspondentes (`calculos_delivery.html`, `calculos_pedidos.html`).
