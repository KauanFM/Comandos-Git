<h1 align="center">COMANDOS GIT <img src="https://github.com/KauanFM/Comandos-Git/assets/112914411/d26ccb19-b903-471b-8d55-7e0bf649110e" width="50" height="50"> </h1>


<h3 align="center">Aprenda comandos GIT para a utilização no dia a dia.</h3> <br>

<h3  align="center">A documentação está no seguinte formato:</h3> <br>

```
comando git (comentário sobre o comando)
//comentário extra sobre o comando
```
---
<h3 align="center">Aqui estão alguns dos comandos mais úteis para versionamento do seu código:</h3> <br>


<h3 align="center">Iniciando um repositório Git</h3> <br>

```
git init (Inicia um repositório Git localmente)
```

<h3 align="center">Commit (Adicionar alterações feitas no repositório)</h3> <br>

```
git add . (Prepara todas as alterações feitas nos arquivos para commit)
git add nome-do-arquivo (Prepara apenas um arquivo específico para commit)
git commit -m "primeiro commit" (Commit as alterações realizadas no projeto)
//**-m "primeiro commit"**: criando o nome para o commit
```

<h3 align="center">Status atual da sua ramificação no projeto (Branch)</h3> <br>

```
git status (Retorna a branch atual e qual o estado da nossa branch)
```

<h3 align="center">Histórico de alterações</h3> <br>

```
git log (Histórico de commits, autores, data, nome do commit e código Hash do commit)
git diff (Mostra as **diferenças** de alterações na branch)
```

<h3 align="center">Descartar alterações</h3> <br>

```
git restore nome-do-arquivo (Remove as modificações atuais feitas)
```

<h3 align="center">Criar ramificações (Branches)</h3> <br>

```
git branch (Retorna a branch atual do projeto)
git checkout -b nome-da-branch (Cria uma nova branch para novas alterações)
git checkout master/main (retorna a branch principal do sistema)
//**checkout**: saindo da branch atual (pode ser usada para retornar a branch anterior)
//**-b nome-da-minha-branch**: criando uma nova Branch
```

<h3 align="center">Mesclar alterações entre branches (Merge)</h3> <br>

```
git checkout -b branch1 (Criando uma nova branch para fazer alterações)
git checkout master (retornando para a branch principal do sistema)
git merge branch1 (Mescla as alterações feitas de uma branch para a master)
```

<h3 align="center">Publicar no GitHub</h3> <br>

```
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git push origin master/main (Empurra a branch master/main como branch default no repositório do GitHub)
git push origin nome-da-branch (Empurra uma nova branch para o repositório do GitHub)
```

<h3 align="center">Puxar a branch mais atualizada para sua maquina local</h3> <br>

```
git pull origin nome-da-branch (Puxa os arquivos que estão remotamente no GitHub)
```

<h3 align="center">Sincronizar alterações remotas com as alterações local</h3> <br>

```
git fetch (Sincroniza as alterações do projeto remoto para a sua maquina local)
```




