Sistema de Gestão de Cursos e Matrículas <br>
Bem-vindo ao Sistema de Gestão de Cursos e Matrículas! Este projeto é uma aplicação Java utilizando JPA (Java Persistence API) para gerenciar cursos e matrículas de estudantes. O sistema permite o cadastro de cursos, matrículas de estudantes em cursos, e a busca e exclusão dessas informações no banco de dados.

Índice
Descrição
Funcionalidades
Tecnologias Utilizadas
Instalação
Uso
Testes
Contribuição
Licença
Descrição
Este sistema foi desenvolvido para facilitar a gestão de cursos e matrículas. Ele utiliza o JPA com Hibernate como provedor de persistência para realizar operações de CRUD (Create, Read, Update, Delete) em um banco de dados relacional.

Funcionalidades
Cadastro de Cursos: Permite cadastrar novos cursos no sistema.
Cadastro de Matrículas: Permite matricular estudantes em cursos.
Busca de Cursos: Permite buscar todos os cursos cadastrados.
Busca de Matrículas: Permite buscar matrículas por curso e por código do curso.
Exclusão de Cursos e Matrículas: Permite excluir cursos e matrículas do sistema.
Tecnologias Utilizadas
Java: Linguagem de programação principal.
JPA (Java Persistence API): API para persistência de dados.
Hibernate: Implementação do JPA.
JUnit: Framework de testes.
Maven: Ferramenta de automação de build.
H2 Database: Banco de dados em memória para testes.
Instalação
Para executar o projeto localmente, siga os passos abaixo:

Clone o repositório:
bash
Copiar código
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Compile e instale as dependências com Maven:
bash
Copiar código
mvn clean install
Configure o banco de dados:
Edite o arquivo src/main/resources/META-INF/persistence.xml com as configurações do seu banco de dados, se necessário.

Uso
Após a instalação, você pode executar a aplicação utilizando seu IDE de preferência (Eclipse, IntelliJ, etc.) ou via linha de comando.

Executando os Testes
Para executar os testes, utilize o comando Maven:

bash
Copiar código
mvn test
Estrutura de Pastas
src/main/java: Código fonte principal.
src/test/java: Testes unitários.
Testes
O projeto inclui testes unitários para verificar as funcionalidades principais do sistema. Os testes estão localizados na pasta src/test/java e podem ser executados com o comando mvn test.

Contribuição
Contribuições são bem-vindas! Siga os passos abaixo para contribuir com o projeto:

Faça um fork do projeto.
Crie uma branch para sua feature (git checkout -b feature/nova-feature).
Commit suas mudanças (git commit -m 'Adiciona nova feature').
Faça push para a branch (git push origin feature/nova-feature).
Abra um Pull Request.
Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

