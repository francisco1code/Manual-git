
   
###  1- Branch
  * 1.1 - Criar nova branch
                 `git branch "nome da branch"`
  * 1.2 Mudar branch
                 `git checkout " Nome" `
  * 1.3 Deletar branch
                  `git branch -d "nome da branch`
  * 1.4 Visualização grafica das branch
      `git log --graph`

### 2- Restaurar e reverter Commit 
  * 2.1 Restaurar
      `git reset "tipo da restauração" "Hash do commit"`
  * 2.2 Tipos de Restauração
        - 2.2.1  soft (retorna sem commitar)
        - 2.2.2  mixed (retorna sem adicionar)
        - 2.2.3  hard (retorna tudo)
  * 2.3 Reverter commit
        `git revert 'id commit'`

### 3- Merge X Rebase

  * 3.1 Como funciona
    - Merge serve para juntar 2 branch, mantendo todo os historico dos commits, mais sempre gerar um novo commit para poder fazer essa união. (Muito utilizada para o pull request)
    - Rebase serve para juntar 2 branch, não mantem esse historico dos commits, porem não gerar esse novo commit.(Muito utilizada para criar uma nova feature)

  * 3.2 Merger
      - `git merge "nome da branch"`

  * 3.3 Rebase 
      - `git rebase "nome da branch"`

  * 3.5 Representação
  <div align='center'><img src="https://raw.githubusercontent.com/francisco1code/Manual-git/master/images/merge_x_rebase.png"width="400" height="300"</div>


    


