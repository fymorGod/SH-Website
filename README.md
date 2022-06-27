*Documentação do projeto - SH Website*

### Ambiente de Desenvolvimento

* https://git-scm.com/download
* https://nodejs.org/pt-br/download/
* https://code.visualstudio.com/

### Passos para a Instalação do projeto

* passo 1: fazer um clone do projeto do github [obs][Solicitar acesso ao repositório]
* passo 2: instalar a ( node_modules ) -> npm install ou apenas yarn
* passo 3: executar no terminal -> npm run dev ou yarn dev 
* passo 4: criar sua branch no projeto

### Padrão dos commits

* Nosso padrão para os commits, segue este modelo

  " O que está sendo feito - versão - o que foi feito"

  exemplo: "Atualização Readme - v1.0.0 - Inserido as funcionalidades do formulário".


### Comandos básicos GIT
# Inicializar o projeto com o Git
	- git init
	- criar o arquivo a ser codificado
	- adicionar esse arquivo como um ponto na história do projeto
	- git add "nome do arquivo"
	- git commit -m " texto para referenciar o motivo da alteracao "
	- git log para verificar o que já foi feito
	- git status para caso haja alteração no arquivo indentificar
		que algo foi alterado.
	- git branch "nome da branch" - significa ramificação
	- git checkout para mudar de branch
	- git merge "nome da branch" para adicionar as atualizações ao projeto principal
	- git branch -D "nome da branch" para deletar a branch criada
# Processo pós criar repositório local
    - é preciso criar um repositório no github
    - git remote add origin https://github.com/fymorGod/intensivo-git-mirante.git
    - clonar algum projeto usando git clone
    - git commit -am " nome do arquivo " - faz com que preparamos o arquivo e já criamos o ponto no tempo
    - git checkout "codido da linha do tempo alterada" -- "nome do arquivo a ser resgatado