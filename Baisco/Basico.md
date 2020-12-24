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
### 4- Restaurar Commit
  * 4.1 Restaurar
      `git reset "tipo da restauração" "Hash do commit"`
   * 4.2 Tipos de Restauração
        - 4.2.1  soft (retorna sem commitar)
        - 4.2.2  mixed (retorna sem adicionar)
        - 4.2.3  hard (retorna tudo)
   
###  5- Branch
  * 5.1 - Criar nova branch
                 `git branch "nome da branch"`
  * 5.2 Mudar branch
                 `git checkout " Nome" `
  * 5.3 Deletar branch
                  `git branch -d "nome da branch`
