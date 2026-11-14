# CRUD de Filmes — Isabelle Moura Oliveira Rocha

Projeto da atividade de Spring Boot com MVC, Thymeleaf, Spring Data JPA, MySQL e Bean Validation. Tema: filmes de terror.

## Requisitos
- Java 17 ou superior
- Maven 3.6+
- XAMPP com MySQL iniciado

## Preparar o banco
1. No phpMyAdmin, crie o banco `crud_filmes` com codificação `utf8mb4` ou execute `banco.sql`.
2. Copie `src/main/resources/application-example.properties` para `src/main/resources/application.properties`.
3. Ajuste usuário e senha locais do MySQL no arquivo local. Não publique suas credenciais.
4. Inicie a aplicação; o Hibernate cria/atualiza a tabela `filme`.
5. Para inserir os três filmes de exemplo, execute `dados_exemplo.sql` depois que a tabela for criada.

## Executar
Na pasta do projeto, rode `mvn spring-boot:run` e acesse http://localhost:8080/filmes.

## Funcionalidades
- Listar e pesquisar filmes pelo título
- Cadastrar, editar e excluir
- Validar título, gênero e nota entre 0 e 10

## Filmes de exemplo
- O Exorcista — Terror — nota 9,0
- Invocação do Mal — Terror — nota 8,5
- A Freira — Terror — nota 7,5

## Entrega
- Repositório público: https://github.com/Isabelleuiui/crud-filmes-spring-boot
- Anexar a captura da listagem e da tabela `filme` no phpMyAdmin com os mesmos registros.
