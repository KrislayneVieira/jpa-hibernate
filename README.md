# Projeto de Treinamento em JPA

Este projeto foi desenvolvido como parte de um treinamento focado exclusivamente no entendimento da JPA (Java Persistence API) e seus recursos avançados, sem a utilização de frameworks adicionais. O objetivo foi proporcionar um aprendizado prático e profundo sobre a JPA, explorando desde conceitos básicos até funcionalidades avançadas.

## Estrutura do Projeto

O projeto foi construído de forma incremental, com novas funcionalidades sendo adicionadas à medida que novos conceitos da JPA eram apresentados. Abaixo estão descritas as principais etapas e funcionalidades implementadas ao longo do treinamento.

### Entidades Básicas

- **Produto**: Entidade principal que representa um produto.
- **Categoria**: Entidade que representa a categoria de um produto.
- **Cliente**: Entidade que representa um cliente.

### Herança

Para abordar as estratégias de herança na JPA, foram criadas subclasses de `Produto`:

- **Livro**: Subclasse de `Produto` que representa um livro.
- **Informática**: Subclasse de `Produto` que representa um produto de informática.

### @Embedded e @Embeddable

Utilizamos as anotações `@Embedded` e `@Embeddable` para organizar melhor a estrutura das classes, separando atributos como endereço e telefone em classes específicas.

### Consultas Avançadas

O estudo de consultas avançadas incluiu:

- **Funções de agregação**: Utilizadas para realizar cálculos e sumarizações em consultas.
- **"SELECT new"**: Utilizado para criar consultas que retornam objetos personalizados, facilitando a criação de relatórios.
- **JOIN FETCH**: Utilizado para o carregamento planejado de dados, melhorando a performance de consultas complexas.

### Parâmetros Dinâmicos nas Consultas

Foi abordado técnicas para lidar com parâmetros dinâmicos nas consultas, tanto usando JPQL (Java Persistence Query Language) quanto a API de Criteria, o que foi fundamental para criar queries flexíveis e adaptáveis às necessidades do sistema.

## Estrutura Final do Projeto

No final do treinamento, o projeto contava com uma estrutura robusta que permitia explorar diversos recursos avançados da JPA. A abordagem hands-on, sem a utilização de frameworks, foi essencial para que os alunos pudessem compreender profundamente o funcionamento interno da JPA e como aplicá-la de forma eficiente em seus próprios projetos.
