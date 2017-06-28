# br.com.lucas
Projeto universitário de CRUD com JPA

## Obtendo o projeto

`git clone https://github.com/lucasviniciosfs/CRUD---JPA-JSP-JAVA`

## Executando a aplicação

`mvn org.apache.tomcat.maven:tomcat7-maven-plugin:run -Dmaven.tomcat.port=9090`

ou

`./mvnw tomcat7:run`

## Acessando a aplicação

Acesse `http://localhost:9090/br.com.lucas/br.com.lucas.crudAluno/aluno` em qualquer navegador.

## Como o projeto foi construído

### "Embutindo" o Maven

Para que não seja necessário instalar e configurar o Maven, ele foi embutido no projeto com o seguinte comando:

`mvn io.takari:maven:0.3.3:wrapper -Dmaven=3.3.9`