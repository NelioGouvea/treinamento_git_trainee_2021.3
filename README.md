# **Treinamento - Git - 2021.1**

## Instalação e Primeira configuração

Pra instalar, basta acessar a página de [downloads](https://git-scm.com/downloads) e seguir as instruções\
Pra se conectar, utilize os seguinte comandos: <sub>(Substitua o nome e o e-mail para o seu)<sub/>
```
git config --global user.name "Darlanzinho"
```
```
git config --global user.email darlanzinho@codejr.com
```

## Começar um projeto

Abra uma pasta, clique com o botão direito e selecione "Git Bash Here" para abrir o terminal do git\
Clone o repositório
```
git clone https://github.com/antoniomarcossouza/treinamento_git_trainee_2021.1
```
Entre na pasta criada pelo comando clone
```
cd ./treinamento_git_trainee
```
Crie sua branch usando como o padrão o nome da funcionalidade que você vai desenvolver
```
git checkout -b contato_frontend
```
Após criada a branch você será redirecionado automaticamente a ela, já podendo começar o desenvolvimento\


## Rotina

Adicionar uma alteração específica
```
git add nomeDoArquivo
```
Adicionar todas as alterações
```
git add .
```
Conferir em qual branch está e quais alterações foram adicionadas
```
git status
```
Dê um commit com uma mensagem especificando as alterações realizadas
```
git commit -m "mensagem"
```
Envie o commit feito para sua branch
```
git push origin nomeDaBranch
```

## Quando terminar a funcionalidade

Volte para a main
```
git checkout main
```
Atualize a main
```
git pull
```
Volte pra sua branch
```
git checkout nomeDaBranch
```
Mescle a main com a sua branch <sub>(estando dentro da sua branch)<sub/>
```
git merge main
```
Confirme o merge <sub>(quando solicitado pelo Scrum Master)<sub/>
```
git push origin nomeDaBranch
```
Espere a confirmação do seu Scrum Master\
Volte para a main
```
git checkout main
```
Mescle a main com as alterações enviadas para sua branch <sub>(quando solicitado pelo Scrum Master)<sub/> 
```
git merge nomeDaBranch
```
Confirme o merge <sub>(quando solicitado pelo Scrum Master)<sub/>
```
git push origin main
```