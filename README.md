# Bootcamp PayLivre + BeAcademy

![](./img/git+github.png)

## Conhecendo Git & GitHub
1. [git init](#git-init)
2. [git status](#git-status)
3. [git add](#git-add)
4. [git log](#git-log)
5. [git branch](#git-branch)
6. [git checkout](#git-checkout)
7. [git merge](#git-merge)
8. [git remote](#git-remote)
9. [git clone](#git-clone)

##### git init

* Cria repositório local
  
  ```bash
  git init <diretório> # omita o <diretório> para criar no diretório atual
  ```

##### git status

* Lista arquivos modificados/novos que não foram comitados
  
  ```bash
  git status
  ```

##### git add

* Adiciona arquivo ao staging
  
  ```bash
  git add <nome_do_arquivo>
  ```

* Adiciona todos os arquivos ao staging
  
  ```bash
  git add .
  ```

##### git log

* Mostra registros dos commits
  
  ```bash
  git log
  ```

##### git branch

* Lista todos os branches locais
  
  ```bash
  git branch 
  ```

* Cria nova branch
  
  ```bash
  git branch <nome_da_branch> # -d <nome_da_branch> # deleta branch
  ```

##### git checkout

* Troca de branch & atualiza diretório
  
  ```bash
  git checkout <nome_da_branch> # -b <nome_da_branch> # cria & altera branch
  ```

##### git merge

* Mescla branch A com branch B
  
  ```bash
  git merge <nome_da_branch>
  ```

##### git remote

* Mostra todas conexões remotas
  
  ```bash
  git remote -v
  ```

* Adiciona repositório remoto
  
  ```bash
  git remote add <apelido> <url>
  ```

##### git clone

* Baixa repositório remoto
  
  ```bash
  git clone <url>
  ```
