# Resumo dos Comandos Git
Um resumo dos principais comandos utilizados no Git para trabalharmos com repositórios no Github

### Resumo - Criando um novo repositório local e enviando para o Github
```
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin endereço-do-repositorio.git
$ git push -u origin main
```

### Resumo - Enviando repositório local para o Github
```
$ git remote add origin endereço-do-repositorio.git
$ git branch -M main
$ git push -u origin main
```

### Resumo - Criando Branch e enviando arquivo para o repositório Github
```
$ git -b nome-branch
$ git add nome-arquivo
$ git commit -m "add-commit"
$ git push origin nome-branch
```

### Resumo - Enviando todas alterações recentes para o repositório Github
```
$ git -b nome-branch
$ git add .
$ git commit -m "add-commit"
$ git push origin nome-branch
```

## Instalação do Git
* [Link download Git](https://git-scm.com/downloads)

## Criar repositório
* Criar um diretório 
* Abrir o Git Bash e entrar no diretório criado
* Digitar o comando `$ git init` para inicializar o repositório
* A pasta `.git` é criada

## Arquivo README.md
* Você pode adicionar um arquivo README a um repositório para comunicar informações importantes sobre o seu projeto, porque o seu projeto é útil, o que elas podem fazer com o seu projeto e como podem usá-lo por exemplo.
* Um README é geralmente o primeiro item que um visitante verá ao visitar seu repositório. 

* Se você colocar seu arquivo README na raiz do repositório docs, ou .githubdiretório oculto , o GitHub reconhecerá e exibirá automaticamente seu README para os visitantes do repositório.
* Se você adicionar um arquivo README à raiz de um repositório público com o mesmo nome de seu nome de usuário, esse README aparecerá automaticamente em sua página de perfil.

## markdown = .md
* [Link guia sintaxe markdown](https://www.markdownguide.org/basic-syntax/)

### Links relativos e caminhos de imagem em arquivos README
* Você pode definir links relativos e caminhos de imagem em seus arquivos renderizados para ajudar os leitores a navegar para outros arquivos em seu repositório.
* Por exemplo, se você tiver um arquivo README na raiz de seu repositório e tiver outro arquivo em docs / CONTRIBUTING.md , o link relativo para CONTRIBUTING.md em seu README pode ser assim:

`[Contribution guidelines for this project](docs/CONTRIBUTING.md)`

### Sintaxe báscia de formatação para arquivo .md
* [Link docs Git](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# Comandos Git

## config
* Definir email e nome nas configurações
```
$ git config user.email "seu_email"
$ git config user.name "seu_nome"
```

## remote
* Para conectar o repositório local com o GitHub
```
$ git remote add origin link-do-repositorio
```

### add
* Prepare o arquivo para confirmação em seu repositório local
```
$ git add .
```

### rm --cached 
* Retira o arquivo adicionado
```
$ git rm --cached <file>
```

### reset
* Desfazer algo que você adicionou
```
$ git reset <arquivo>
```
ou
```
$ git reset
```

### reset (commit)
* Desfazer um commit
```
$ git reset ~HEAD
```

## status
* Para verificar arquivos que possuem modificações
```
$ git status
```

### commit
* Confirma o arqivo no repositório local
```
$ git commit -m "Confirma a alteração aqui"
```

### commit --amend
* Edita o último commit
```
$ git commit --amend -m "novo commit"
```

### log
* Mostra o log com commits
```
$ git log
```
ou
```
$ git log --oneline
```

## tag
* Mostra tags existentes
```
$ git tag
```

## tag -a
* Cria tag anotada
```
$ git tag -a <v1.0.0> -m "my tag v1.0.0"
```

## show
* Ver dados da tag junto com o commit
```
$ git show <v1.0.0>
```

## push
* Envia as alterações do repositório local para o GitHub.com
```
$ git push -u origin sua-branch
``` 

## push --tags
* Envia as tags do repositório local para o GitHub.com
```
$ git push --tags
``` 

## branch
* Criar uma branch
```
$ git branch nome-da-branch
```

* Criar uma branch e entrar nela
```
$ git checkout -b "sua-branch"
```

* Deletar branch
```
$ git branch -D <nome da branch>
```

## checkout
* Acessar uma branch
```
$ git checkout nome-branch
```

* Alterar nome da branch principal `master` para `main` (recomendado)
```
$ git branch -M "main"
```

## mv
* Renomear arquivo
```
$ git mv velho_arquivo novo_arquivo
```

## rm
* Remover arquivos de um repositório
```
$ git rm <arquivo>
```

## rm -r
* Remover diretório de um repositório
```
$ git rm -r <diretório>
```

## merge
* Incorporar as alterações de uma branch ao branch principal
```
$ git merge nome-branch
```

## clone
* Baixar um repositório para a máquina local
```
$ git clone link-repositorio-github
```
* Baixar o conteúdo de um repositório dentro de um diretório
```
$ git clone link-repositorio-github .
```

## pull
* Atualizar o repositório local com as atualizações do github
```
$ git pull
```
## git flow init
* Inicializa o Git Flow que automatiza o gerenciamento do versionamento.
```

## Software Free GUI
* [Link guia programa Sourcetree](https://www.sourcetreeapp.com)


