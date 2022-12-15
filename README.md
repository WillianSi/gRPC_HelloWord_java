# gRPC-Java HelloWord

A construção de um serviço ou API baseado em gRPC começa com a definição do serviço em um arquivo descritor que inclui tanto as operações disponíveis quanto as estruturas de dados que incluem os nomes dos campos e tipos que as chamadas para gRPC recebem e retornam como respostas. funções remotas. O arquivo do descritor de serviço segue o formato de Protocol Buffers .

Neste exemplo, o serviço HelloWorld tem duas operações HelloMessage e HelloStream que recebem e retornam duas estruturas de dados HelloRequest e HelloResponse . A operação HelloStream mostra como enviar ao cliente um número indeterminado de mensagens para o cliente que as processa à medida que são enviadas pelo servidor. O esquema também contém algumas opções utilizadas pelo gRPC para customizar a geração das classes que servem de base para a implementação.

# :hammer: Informações:
- Repositorio de referencia: https://github.com/picodotdev/blog-ejemplos.
- IDE utilizada foi o IntelliJ Community, você pode usar a que você quiser.
- Java 18.
