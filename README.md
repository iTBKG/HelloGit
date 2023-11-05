Primeira vez que eu crio um README, que loucura.

git init -> Inicializa um repositório Git vazio
git add -> Deixa um arquivo pronto para tomar um "pull" (ser empurrado)
git status -> Mostra quais arquivos estão prontos para tomarem o pull
git commit -m "primeiro comite" -> Lança o arquivo que estava pronto para ser empurrado. É enviado pro GitHub
git branch -M main -> renomeia o nome da branch de "master" para "main"
git push -u origin main -> Empurra os arquivos locais para o github, nosso repositório remoto

1. Primeiro precisamos criar a pasta
2. Abrir ela com o gitbash
3. Dar git init para iniciar um repositório na máquina
4. Criar algum arquivo, como um README.md por exemplo, ou qualquer outro arquivo
5. Dar o git add *nome do arquivo*
6. Dar o git status para ver se o arquivo esta preparado para o commit
7. Dar o git branch -M main para mudar o nome da branch, de *master* para *main*
8. Dar o git commit -m *Descrição do commit*
9. Dar o git remote add origin *https://github.com/iTBKG/nome-do-repositorio*
10. Dar o git push -u origin main

Posso dar git add . - para adicionar todos arquivos que foram alterados
Depois não preciso mais dar git push -u origin main, posso mandar apenas git push origin main


Alteração (teste)