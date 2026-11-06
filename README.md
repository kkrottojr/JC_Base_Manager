# JC Base Manager

O **JC Base Manager** é uma interface gráfica para montar tabelas a partir de dados de várias fontes. Em vez de escrever consultas SQL, a pessoa seleciona e organiza os campos por **arrastar e soltar**, aplica filtros e gera a tabela que precisa.

## Demonstração de portfólio

A demonstração combina três conjuntos de dados fictícios: clientes, contratos e pagamentos. Cada contrato aparece em uma linha. Quando há mais de um pagamento, os valores são somados antes de calcular o saldo.

1. Baixe o arquivo [index.html](index.html) e abra-o em um navegador.
2. Arraste campos de **Campos disponíveis** para **Colunas da tabela**. Arraste novamente para mudar a ordem ou devolver um campo. Também é possível usar os botões.
3. Filtre pelo status do contrato e confira o resultado na prévia.
4. Clique em **Exportar CSV** para salvar as linhas e colunas exibidas.

### Exemplo

Para montar uma tabela de saldos em aberto, selecione **Cliente · Nome**, **Contrato · Código**, **Pagamento · Total pago (R$)** e **Contrato · Saldo (R$)**. Em seguida, filtre os contratos pelo status **Ativo**.

A demonstração roda no navegador e usa apenas os dados fictícios incluídos no arquivo. A aplicação operacional em Python e suas conexões com bancos de dados ficam separadas.
