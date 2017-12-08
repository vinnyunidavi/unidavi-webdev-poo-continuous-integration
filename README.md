# Projeto

## Objetivos 

* Aplicar a integração contínua através do uso das ferramentas git, maven, sonarqube e jenkins

## Tarefas

* Criar projeto git com nome `unidavi-webdev-poo-continuous-integration` na conta do aluno no github 
* Criar um commit com classe App contendo o método main e projeto maven com configuração mínima
* Copiar para esse projeto a classe de testes automatizados de 1 dos seguintes de desafios do `exercism.io`:
   ** http://exercism.io/exercises/java/book-store/readme
   ** http://exercism.io/exercises/java/word-count/test-suite
   ** http://exercism.io/exercises/java/wordy/test-suite
   ** http://exercism.io/exercises/java/bank-account/test-suite
   ** http://exercism.io/exercises/java/change/readme
* Criar um commit com a classe de testes automatizadas compilando mas com todos os testes ignorados
* Criar um commit com 2 testes automatizando passando
* Criar um commit com propriedade configurada para encoding UTF8 em código fonte e relatórios (`build.sourceEncoding`, `report.outputEncoding`)
* Criar um commit com código fonte e javadoc configurados como relatório no site do projeto
* Criar um commit com sonar configurado para identificar cobertura de código do projeto
* Criar um commit com resolução de todas as issues relatadas pelo sonarqube
* Criar um commit com cobertura de código superior a 80%
* Criar um job jenkins chamado `PROJECT-DEV-BUILD` que compila o código fonte, executa os testes automatizados e empacota o jar
* Criar um commit com uma cópia do arquivo do job jenkins, `config.xml`, armazenada em `src/jenkins/jobs/project-dev-build`
* Criar um job jenkins chamado `PROJECT-DEV-SITE` que gera o site do projeto
* Criar um commit com uma cópia do arquivo do job jenkins, `config.xml`, armazenada em `src/jenkins/jobs/project-dev-site`
* Criar um job jenkins chamado `PROJECT-DEV-DEPLOY` que versiona o projeto e publica em repositório local
* Criar um commit com uma cópia do arquivo do job jenkins, `config.xml`, armazenada em `src/jenkins/jobs/project-dev-deploy`

## Entrega
> Importante: cada aluno deve fazer a entrega em sua própria conta 

* Comunicar a conclusão da atividade `Integração Contínua` da ferramenta classroom indicando o endereço do repositório git

## Avaliação
* A nota das atividades é a média aritmética da nota das as atividades realizadas nas semanas 1 e 2
* A nota de cada atividade corresponde ao percentual de itens entregues conforme solicitado. 

### Exemplos
* 3 itens entregues completos de 5 solicitados corresponde a nota 6 
* 3 itens entregues incompletos de 5 solicitados corresponde a nota 3 
