# Curso TMW Git & GitHub 2025


Iniciando o curso para trabalhar com versionamento  de código e repositórios remotos com GitHub.



Além disso, vamos também trabalhar com GitFlow ao final do Curso e Visual Studio Code.

Testando se mudanças aqui ocasionarão conflitos. (HOUVE CONFLITO)
----

Ainda aprendendo, mas há duvidas.

- Learnwlv

## Fluxo de Trabalho Git Local

1. Git Checkout -b <nova-branch>
2. Cria ou Atualiza arquivos
3. Git Status
4. Git add .
5. Git Status
6. Git commit -m "Mensagem"
7. Git checkout main
9. Git merge nova-branch

## Fluxo de trabalho GitHub <> Local (Projeto propio ou da Empresa)

1. Git clone <endereço_projeto>
2. Git Checkout -b <nova-branch>
3. Alterações arquivos
4. Git Status
5. git add arquivos
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
8. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)
1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add arquivos
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>

