# Projeto DIO Heineken Inteligencia Artificial Refinando Projeto Conceitual BD E-COMMERCE

:spiral_calendar: Atualizado em 9 de Fevereiro de 2025 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/under_construction.gif" />

- :blush: Este projeto está em estudo. Carga inicial realizada para manter cópia de segurança :blush:
- :blush: Meu interesse inicial é revisar todos os conceitos para incrementar a forma de trabalhar com banco de dados :blush:
- :blush: Para este projeto utilizei dados das aulas e pesquisas na internet :blush:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

Este projeto foi proposto pela Digital Innovation One
- Link do código original: [Github](https://github.com/julianazanelatto/mysql_sql_database_specialist/tree/main/M%C3%B3dulo%203/desafio)
- Professor: Juliana Mascarenhas
- Aulas: [DIO](https://web.dio.me/project/refinando-um-projeto-conceitual-de-banco-de-dados-e-commerce/learning/e731f9da-4b6d-458d-a577-6724668077be?back=/track/coding-the-future-heineken-ia-para-analise-de-dados&tab=undefined&moduleId=undefined)

## Descrição
- Modelamos juntos um contexto reduzido de e-commerce. Agora é a sua vez, podes escolher a ferramenta de modelagem para realizar o desafio. Contudo, fique atento! Caso opte por uma variação do modelo entidade relacionamento, como nas ferramentas Mysql Workbench ou DBDesigner será preciso especificar as PK e FKs corretamente. Apesar desse conceito não ser utilizado na modelagem conceitual exploramos brevemente suas definições. Sendo assim, seu entregável será o esquema conceitual para o cenário de E-commerce.
- O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

## Objetivo do desafio:
Refine o modelo apresentado acrescentando os seguintes pontos:
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;

## Ferramentas utilizadas
- [MySql Workbench](https://www.mysql.com/products/workbench/)

## Solução do desafio
- Cliente: foram criadas duas novas entidades PJ_Pessoa Juridica e PF_Pessoa Fisica contendo as informações de CNPJ e CPF.
- Pagamento: atribuída a outras duas entidades para detalhar as formas de pagamento : Cartão e Boleto.
- Entrega: criada para armazenar as informações de envio de cada pedido detalhar como data do pedido, data de envio e data de entrega.

<img src="https://github.com/rdeconti/Projeto-DIO-Heineken-Inteligencia-Artificial-Refinando-Projeto-Conceitual-BD-E-COMMERCE/blob/main/ecommerce_relational_schema_desafio.png" />

