# Conhecendo Spring Data JPA na Prática

Objetivo do Projeto
------------------------------
Conhecer os principais conceitos de mapeamento objeto relacional (ORM) usando o Spring Data JPA. Para isso, uma API RESTful será desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.


Atividades Desenvolvidas
------------------------------
-> Configuração do banco de dados (SGBD PostgreSQL)
-> Aplicando as annotations
-> Execução do fluxo back-end: Controller - Service - Repository
-> Validação - Hibernate Validator
-> Consultas Avançadas - Derived Query - Native Query


Tecnologias Utilizadas
------------------------------
-> Java 11
-> Maven
-> Spring Web
-> Spring Data JPA
-> PostgreSQL Driver
-> Hibernate Validator
-> Lombok
-> Postman


Anotações de Mapeamento
------------------------------
@Entity Usada para especificar que a classe anotada atualmente representa um tipo de entidade.

@Table Usada para especificar a tabela principal da entidade atualmente anotada.

@Id Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.

@GeneratedValue Especifica que o valor do identificador de entidade é gerado automaticamente.

@Column Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.

@JoinColumn Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.

@OneToMany Usada para especificar um relacionamento de banco de dados um-para-muitos.

@OneToOne Usada para especificar um relacionamento de banco de dados um-para-um.

@ManyToOne Usada para especificar um relacionamento de banco de dados muitos-para-um.

cascade Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho.

mappedBy Indica qual é o lado inverso ou não dominante da relação.

Página com todas anotações de mapeamento: https://strn.com.br/artigos/2018/12/11/todas-as-anota%C3%A7%C3%B5es-do-jpa-anota%C3%A7%C3%B5es-de-mapeamento/








