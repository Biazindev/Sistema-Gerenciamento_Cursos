Sistema de Gestão de Cursos e Matrículas <br> <br>
Bem-vindo ao Sistema de Gestão de Cursos e Matrículas! Este projeto é uma aplicação Java utilizando JPA (Java Persistence API) para gerenciar cursos e matrículas de estudantes. O sistema permite o cadastro de cursos, matrículas de estudantes em cursos, e a busca e exclusão dessas informações no banco de dados.
<br> <br>
Índice<br>
Descrição<br>
Funcionalidades<br>
Tecnologias Utilizadas<br>
Instalação<br>
Uso<br>
Testes<br>
Contribuição<br>
Licença<br>
Descrição<br>
Este sistema foi desenvolvido para facilitar a gestão de cursos e matrículas. Ele utiliza o JPA com Hibernate como provedor de persistência para realizar operações de CRUD (Create, Read, Update, Delete) em um banco de dados relacional.
<br> <br>
Funcionalidades <br>
Cadastro de Cursos: Permite cadastrar novos cursos no sistema.<br>
Cadastro de Matrículas: Permite matricular estudantes em cursos.<br>
Busca de Cursos: Permite buscar todos os cursos cadastrados.<br>
Busca de Matrículas: Permite buscar matrículas por curso e por código do curso.<br>
Exclusão de Cursos e Matrículas: Permite excluir cursos e matrículas do sistema.<br>
Tecnologias Utilizadas<br>
Java: Linguagem de programação principal.<br>
JPA (Java Persistence API): API para persistência de dados.<br>
Hibernate: Implementação do JPA.<br>
JUnit: Framework de testes.<br>
Maven: Ferramenta de automação de build.<br>
H2 Database: Banco de dados em memória para testes.<br>
Instalação<br>
Para executar o projeto localmente, siga os passos abaixo:<br>
<br>
Clone o repositório:<br>
bash<br>
Copiar código<br>
git clone https://github.com/seu-usuario/nome-do-repositorio.git<br>
cd nome-do-repositorio<br>
Compile e instale as dependências com Maven:<br>
bash<br>
Copiar código<br>
mvn clean install<br>
Configure o banco de dados:<br>
Edite o arquivo src/main/resources/META-INF/persistence.xml com as configurações do seu banco de dados, se necessário.<br>
<br><br>
Uso<br>
Após a instalação, você pode executar a aplicação utilizando seu IDE de preferência (Eclipse, IntelliJ, etc.) ou via linha de comando.<br>
<br><br>
Executando os Testes<br>
Para executar os testes, utilize o comando Maven:<br>
<br><br>
bash<br>
Copiar código<br>
mvn test<br>
Estrutura de Pastas<br>
src/main/java: Código fonte principal.<br>
src/test/java: Testes unitários.<br>
Testes<br>
O projeto inclui testes unitários para verificar as funcionalidades principais do sistema. Os testes estão localizados na pasta src/test/java e podem ser executados com o comando mvn test.<br>
<br><br>
Contribuição<br>
Contribuições são bem-vindas! Siga os passos abaixo para contribuir com o projeto:<br>
<br><br>
Faça um fork do projeto.<br>
Crie uma branch para sua feature (git checkout -b feature/nova-feature).<br>
Commit suas mudanças (git commit -m 'Adiciona nova feature').<br>
Faça push para a branch (git push origin feature/nova-feature).<br>
Abra um Pull Request.<br>
Licença<br>
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.<br>

