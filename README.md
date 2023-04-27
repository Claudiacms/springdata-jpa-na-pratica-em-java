# springdata-jpa-na-pratica-em-java
Conhecendo o Projeto Spring Data JPA na Prática

O que é um projeto Spring?
Resultado de imagem
Inicialmente desenvolvido para criação de aplicações web escritas em Java, e anteriormente denominado como Spring Framework, o Spring é um ecossistema de desenvolvimento para facilitar a criação de aplicações Java utilizando diversos módulos independentes.

Como funciona o Spring Data JPA?
O Spring Data JPA (Java Persistence API) é um projeto da Spring Source e subprojeto do Spring Data com proposta de padronizar e facilitar o acesso a diferentes tecnologias de armazenamento de dados, como bancos de dados relacionais e não relacionais, utilizando as funcionalidades da especificação JPA.

O Spring Data é um conjunto de diversas frameworks que possuem o objetivo de facilitar o processo de persistência de dados em aplicações Spring, sendo que cada uma dessas frameworks foram pensadas para um contexto diferente.

Tendo em vista esse cenário, o Spring criou o framework Spring Data JPA, cujo principal objetivo é permitir que o desenvolvimento com JPA se torne mais fácil, prático e menos repetitivo. É importante saber que o Spring Data JPA utiliza as próprias funcionalidades da especificação JPA, mas encapsula os seus recursos.

Ao herdar a interface JpaRepository, dois propósitos são preenchidos: no primeiro, uma variedade de métodos como save(), delete(), findAll(), entre outros, são fornecidos; e no segundo, o reconhecimento desta interface como um bean do Spring, o que é útil para a injeção de dependência.

O @Data (importado do Lombok) serve para gerar automaticamente os getters, settters, toString (não cria o construtor). Basta colocá-lo em cima da classe model para ativá-lo. Também é possível colocar o @Getter e o @Setter em cada um dos atributos (caso não queira gerar todos eles com o @Data)
