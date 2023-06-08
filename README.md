# Projeto Java 17 e SpringBoot

## Criação de uma API RestFul
Definição de RestFul
Uma API RESTful (Representational State Transfer) é uma abordagem arquitetural para projetar e desenvolver serviços web. Ela é baseada nos princípios do REST, que é um estilo de arquitetura de software para sistemas distribuídos.

Uma API RESTful permite que os sistemas se comuniquem e compartilhem recursos de forma padronizada, usando os métodos HTTP (como GET, POST, PUT, DELETE) para realizar operações em recursos específicos. Aqui estão algumas características importantes de uma API RESTful:

    Arquitetura orientada a recursos: Uma API RESTful modela a funcionalidade em torno de recursos, que podem ser objetos, entidades, serviços ou qualquer coisa que você queira expor por meio da API. Cada recurso possui uma URI (Uniform Resource Identifier) exclusiva para acessá-lo.

    Operações HTTP: A API RESTful usa métodos HTTP para indicar a operação a ser realizada no recurso. Os métodos mais comuns são:
        GET: Obtém informações sobre um recurso existente.
        POST: Cria um novo recurso.
        PUT: Atualiza completamente um recurso existente.
        PATCH: Atualiza parcialmente um recurso existente.
        DELETE: Remove um recurso existente.

    Formato de representação: A API RESTful retorna representações dos recursos em formatos comuns, como JSON (JavaScript Object Notation) ou XML (eXtensible Markup Language). Essas representações podem ser usadas para ler ou modificar o estado dos recursos.

    Stateless (sem estado): Cada solicitação enviada para uma API RESTful contém todas as informações necessárias para processar a solicitação. Isso significa que o servidor não mantém nenhum estado das solicitações anteriores do cliente. Cada solicitação é tratada de forma independente, o que torna a API escalável e mais fácil de manter.

    Hypermedia as the Engine of Application State (HATEOAS): É um princípio no qual a API fornece links em suas respostas para permitir a descoberta dinâmica de recursos relacionados. Isso permite que os clientes naveguem pela API de forma autônoma, seguindo os links fornecidos.

As APIs RESTful são amplamente utilizadas na construção de serviços web e aplicativos modernos. Elas oferecem uma abordagem flexível e escalável para expor e consumir recursos através da internet. Ao projetar ou consumir uma API RESTful, é importante seguir as práticas recomendadas e aderir aos princípios do REST para garantir uma arquitetura consistente e de alto desempenho.


## Para base de dados estou utilizando MySql versão 8.0

