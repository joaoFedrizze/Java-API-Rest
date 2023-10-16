# Java-API-Rest

## Introdução
Esse estudo deve ao fato de sempre ter um interesse em Java, por mais que eu tenha essa paixão por Java, nunca conseguir aplicar ele ao meu cotidiano, graças a esse curso da [Rocket Seat](https://www.rocketseat.com.br/)eu posso ter essa breve introdução a algo que eu utilizo com muita frequência, que no caso é o back-end para aplicações e aprender mais sobre a linguagem que eu sempre gostei, o Java

---
## Instalação / Requisitos

### Java
- Instalador
[Instalação do JDK Java 17](https://download.oracle.com/java/17/archive/jdk-17.0.6_windows-x64_bin.msi)
- Variável de ambiente
1. Nova Variável de ambiente -> Nome da variável: ``JAVA_HOME``, Nome do valor ``C:\Program Files\Java\jdk-17``, Note que é importante apontar ao local de instalação do java, pois o mesmo não é o nome atual da minha pasta e isso é só um exemplo
2. Editar Path -> Novo -> ``%JAVA_HOME%\bin``
3. Para testar a instalação é importante abrir um console novo ``windows + R`` e executar o comando ``java -version``
### Marven
- Arquivos
[Link para os arquivos do Marven](https://dlcdn.apache.org/maven/maven-3/3.9.5/binaries/apache-maven-3.9.5-bin.zip)
- Variável de ambiente
1. Extraia um arquivo em um diretório de fácil acesso, como por exemplo ``C:\marvem\``
2. Editar Path -> Novo -> ``C:\marvem\bin``, assim como no exemplo anterior o caminha pode ser diferente, mas é importante apontar a pasta bin.
3. Para testar a instalação é importante abrir um console novo ``windows + R`` e executar o comando ``mvn``, a resposta resultara em erro, mas isso significa que o Marven está instalado.
### VSCode plugins
- **vscjava.vscode-java-pack**
    - vscjava.vscode-java-debug
    - vscjava.vscode-java-test
    - vscjava.vscode-java-dependency
    - vscjava.vscode-maven
    - redhat.java
- **vscjava.vscode-spring-initializr**
- **vmware.vscode-spring-boot**
- **vscjava.vscode-spring-boot-dashboard**
### Rodando a aplicação
1. Se os plugins para o VSCode estiverem instalados, no arquivo ``.\src\main\java\br\com\wolf\todolist\TodolistApplication.java`` acima do ``main()`` aparecerá uma frase escrita ``run``, apenas precisa clicar nela.
