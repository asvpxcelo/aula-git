# Git e Github

Guia pŕatico para iniciantes

# Scenes
- [x] você deseja criar pontos na história da produçao do seu projeto -> git init(para iniciar o projeto) / -> touch para selecionar o item do projeto, (realize a alteração do projeto) -> git add(projeto) git status(git add(projeto))
- [x] você deseja verificar mudanças feitas no seu projeto.

- [x] você começa uma nova funcionalidade no seu projeto sem estragar o que já foi feito. -> git branch para criar uma nova funcionalidade, (dou git status para ver se estou na nova branch, entao touch para criar a nova funcionalidade,)
- [x] você adiciona as novas funcionalidades ao seu projeto em produção. -> git merge para uni-las, no meu caso foi git merge feature/cart
- [x] você quer deletar a branch da nova funcionalidade, depois quer aplicar em seu projeto -> deletar a branch da nova funcionalidade -> git branch -D <Nome da branch>

- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
- `git commit` // inicia um ponto na linha do tempo
- `git log ` // visualiza todos os pontos na linha do tempo / commit
- `git status` // imforma o estado das alteraçoes do nosso projeto
- `git show` // apresenta determinado ponto na história
- `git merge` // adicona novas funcionalidades ao projeto em produção
- `git branch -D` // deleta a branch