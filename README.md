## Desafio Técnico: Web Scraping e Banco de Dados SQLite3

### Introdução

Este desafio tem como objetivo avaliar suas habilidades em **web scraping** e manipulação de **banco de dados**. Você deverá desenvolver uma aplicação simples em **Python** que realiza uma busca de produtos no site [Loja Maeto](https://www.lojamaeto.com/) e armazena as informações extraídas em um banco de dados SQLite3.

### Requisitos

1. **Busca de produtos**: Sua aplicação deve permitir que o usuário insira um termo de busca (ex: nome de um produto, categoria, etc.). O programa então deve realizar a busca no site da Loja Maeto. A interação com o usuário pode ser algo bem simples(um input através do prompt de comando ou terminal já é o suficiente).

2. **Extração dos dados dos produtos**: Para cada produto encontrado na busca, você deve extrair as seguintes informações:
   - **SKU (PK)**: A chave única de cada produto;
   - **Título do Produto**;
   - **Preço**;
   - **Preço no PIX**;
   - **Valor da Parcela**;
   - **Número de Parcelas**;
   - **Informações Técnicas**.

3. **Armazenamento no banco de dados SQLite3**: Após a extração dos dados, sua aplicação deve armazená-los em um banco de dados SQLite3. Você deve desenvolver um modelo de banco de dados, criá-lo e armazenar os resultados de sua extração nele. A(s) tabela(s) deve(m) ser estruturada(s) de forma a garantir a **unicidade do SKU** (isto é, não podem existir dois produtos com o mesmo SKU). Caso o produto já exista no banco, ele deve ser atualizado.

4. **Resolução de conflitos**: Caso um produto seja retornado em buscas diferentes ou se o usuário tentar realizar uma nova busca para um produto já existente, a aplicação deve verificar se o SKU já está no banco e, se necessário, realizar a atualização dos dados.

5. **Tecnologias**:
   - A aplicação **deve ser desenvolvida em Python**;
   - Você pode quaisquer bibliotecas que deseja para completar o desafio.

6. **Observações**

    - Não deixe o arquivo do banco de dados no seu Repositório. Crie um script simples para gerar o banco e nomeio-o "create_database.py";
    - Forneça-nos um passo-a-passo de como executar sua aplicação através de um arquivo README.md;
    - Não mencione no seu repositório o desafio, apenas deixe-o público e nos mande o link;
    - Atente-se a modelagem do banco de dados.


### Boa sorte!
