# Primeiros comandos com Git
## Iniciando o Git e criando um commit
- Iniciar o GIT (git init)
- Iniciar o versionamento (git add)
- Criar um commit (git commit)

### Commands Git
`git init [nome-do-repositório]`\
Esse comando server para iniciar o gerenciamento da pasta pelo git.

`git add * or .`\
Esse comando serve para adicionar todos os arquivos para serem gerenciados pelo git.

`git commit -m "Título do commit"`\
Esse comando serve para atualizar o versionamento do repositório local.

`git status`\
Esse comando serve para mostrar o estado do repositório.

`git remote add origin [endereço-do-repositório]`\
Esse comando serve para adicionar todos os arquivos para serem gerenciados pelo git no servidor remoto.

`git push origin master`\
Esse comando server para empurrar o repositório que está local, para o servidor remoto.

`git pull origin master`\
Esse comando serve para puxar a versão do repositório que está no servider para o meu repositório local.

### Criando um autor

`git config --global user.email "endereço@gmail.com"`

`git config --global user.name name`

`git config --list`

`git config --global --unset user.name`

---

[Markdown Referece](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)




[Back :back:](../README.md)
