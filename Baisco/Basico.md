# Nesta Secção iremos aborda a parte trivial do github


### 1- Registrar dados
  * 1.1 Registrar usuario e email
          `git confing --global user.name "seu usuario"`
          `git confing --global user.email "seu email"`
   * 1.2 Visualizar Registros
          `git config --list`

### 2- Criar novo Repositorio (local)
  * 2.1  Criar repositorio
                    `git init`
  * 2.1 Adiciona no seu repositorio remoto
          `git remote add origin "endereço do seu pepositorio remoto"`
 ### 3- Primeiro Commit 
  * 3.1 Adicionar o arquivo mudado em seu repositorio locar
                     `git add "nome do arquivo"`
  * 3.2 Commitar sua alteração
                    `git commit -m "alteração feita"`
  * 3.3 Visualizar commit
                    `git log`
  * 3.4 Subir seu commit para o reposirotio remoto
      `git push origin "nome da branch" `