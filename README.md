## Estrutura inicial de um projeto utilizando Arquitetura Limpa

Este projeto é uma estrutura inicial de configuração dos módulos baseada no livro "Clean Architecture" de Robert C. Martin (Uncle Bob). Ele foi criado para fornecer uma base sólida para o desenvolvimento de aplicativos com uma arquitetura limpa e bem organizada. A arquitetura limpa é uma abordagem de organização de código que visa tornar o sistema altamente testável, independente de frameworks e tecnologias, e de fácil manutenção.

## Estrutura do Projeto

O projeto está dividido em diferentes módulos e pacotes, seguindo os princípios da arquitetura limpa. Aqui está uma visão geral da estrutura do projeto:

### Módulo "Core"

- **`core/domain`**: Este pacote contém as classes de domínio do projeto. São classes que representam as entidades e objetos de negócios do sistema.

- **`core/use-case`**: Neste pacote, você encontrará os casos de uso ou interações principais da aplicação. Os casos de uso definem as regras de negócios e a lógica da aplicação.

### Módulo "Adapter"

- **`adapter/input`**: Os adaptadores de entrada são responsáveis por receber as solicitações do mundo exterior. Isso pode incluir controladores REST, classes de serialização, entre outros.

- **`adapter/output`**: Os adaptadores de saída são responsáveis por fornecer saídas para o mundo exterior. Isso pode incluir repositórios de dados, serviços externos, armazenamento em banco de dados, entre outros.

### Módulo "App"

- **`app/spring-app`**: Este é o módulo de aplicação da sua arquitetura. Aqui, você pode encontrar a configuração e componentes específicos do Spring Boot, como a classe principal de inicialização.


## Modelo Base da Estrutura do Projeto

<p align="center">
  <img align="center" alt="" src="https://raw.githubusercontent.com/RodrigoAntonioCruz/assets/main/clear.png" />
</p>