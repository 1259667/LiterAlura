Projeto API de Livros - Wilker Bibiano
Descrição do Projeto

Este projeto, desenvolvido por Wilker Bibiano, tem como objetivo explorar e aplicar conceitos avançados de requisições HTTP em Java utilizando as classes HttpClient, HttpRequest e HttpResponse, para interagir com a API de livros Gutendex
 e gerenciar informações de livros e autores.

O projeto está estruturado em diferentes fases, cada uma abordando aspectos importantes de requisições HTTP, manipulação de dados e construção de um catálogo de livros.

1. Construindo o Cliente para Requisições (HttpClient)

Na terceira fase do desafio, utilizamos a classe HttpClient para fazer requisições à API de livros.

Objetivo: Facilitar a conexão e a obtenção de respostas de maneira eficiente.

Benefício: Permite operações HTTP estruturadas e versáteis, criando uma base sólida para solicitações futuras.

2. Construindo a Solicitação (HttpRequest)

Nesta etapa, configuramos e personalizamos as requisições com HttpRequest.

Objetivo: Adaptar a consulta às necessidades específicas do projeto, como buscar livros por título ou idioma.

Benefício: Controle detalhado sobre os parâmetros da solicitação, garantindo consultas precisas à API.

3. Construindo a Resposta (HttpResponse)

Trabalhamos com a interface HttpResponse para gerenciar as respostas recebidas da API.

Objetivo: Extrair informações significativas, como códigos de status, cabeçalhos e corpo da resposta em JSON.

Benefício: Permite analisar os dados de forma estruturada, facilitando a manipulação posterior em Java.

4. Construção do Catálogo de Livros e Autores

Nesta fase, o foco foi criar um catálogo de livros e autores baseado nas consultas realizadas à API.

Funcionalidades:

Busca de livro por título:

Utiliza a URL base: https://gutendex.com/books/

Retém apenas o primeiro resultado obtido para simplificar a exibição.

Listagem de todos os livros buscados:

Exibe todos os livros que já foram consultados, permitindo que o usuário visualize o histórico de buscas.

Listagem por idioma:

Considera apenas o primeiro idioma da lista recebida do JSON, facilitando consultas simples e compreensíveis.

Atributos de cada livro:

Título

Autor

Idiomas

Número de downloads

Dica: O uso de classes Java para mapear os dados do JSON e a aplicação das anotações @JsonIgnoreProperties e @JsonAlias ajudam a tornar o código modular, legível e pronto para futuras funcionalidades.

5. Conversão de Dados e Manipulação

Transformação do JSON em objetos Java.

Métodos getters, setters e toString() para modularidade e facilidade de uso.

Filtragem de atributos essenciais, como título, autor, idioma e downloads.

6. Próximos Passos

Implementar filtros avançados, como busca por autor ou faixa de downloads.

Tratar possíveis erros de requisição HTTP.

Melhorar a interface de listagem para exibição amigável.

Autor

Wilker Bibiano – Desenvolvedor em Java, explorando o mundo das APIs e construção de catálogos de livros com manipulação de dados HTTP.
