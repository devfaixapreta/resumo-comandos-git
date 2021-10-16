# Resumo dos Comandos Git
Um resumo dos principais comandos utilizados no Git para trabalharmos com repositorios no Github

### Resumo - Criando um novo repositório
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/devfaixapreta/resumo-comandos-git.git
git push -u origin main
```

### Resumo - Enviando para o repositório
```git remote add origin https://github.com/devfaixapreta/resumo-comandos-git.git
git branch -M main
git push -u origin main
```

## Instalação do Git
* [Link gownload Git](https://git-scm.com/downloads)

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

### Links relativos e caminhos de imagem em arquivos README
* Você pode definir links relativos e caminhos de imagem em seus arquivos renderizados para ajudar os leitores a navegar para outros arquivos em seu repositório.
* Por exemplo, se você tiver um arquivo README na raiz de seu repositório e tiver outro arquivo em docs / CONTRIBUTING.md , o link relativo para CONTRIBUTING.md em seu README pode ser assim:

`[Contribution guidelines for this project](docs/CONTRIBUTING.md)`

# Comandos Git

## remote
* Para conectar o repositorio local com o GitHub
```
$ git remote add origin link-do-repositorio
```

### add
* Prepare o arquivo para confirmação em seu repositório local
```
$ git add .
```

## status
* Para verificar as mudanças preparadas para confirmação
```
$ git status
```

### commit
* Confirma o arqivo no repositorio local
```
$ git commit -m "Confirma a alteração aqui"
```

### push
* Envia as alterações do repositorio local para o GitHub.com
```
$ git push -u origin sua-branch
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

## merge
* Unir as alterações de uma branch ao branh principal
```
$ git merge nome-branch
```

## clone
* Baixar um repositório para local
```
$ git clone link-repositorio-github
```

## pull
* Atualizar o repositorio local com as atualizações do github
```
$ git pull
```



