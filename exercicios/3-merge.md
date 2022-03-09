# Merges

A criação e merge de branchs é um processo natural do git, vamos praticar fazer o merge de branchs criadas no exercício anterior.

`git merge nome_da_branch` mergeia a branch indicada na branch atual

# Conflitos

É normal que arquivos tenham divergências conflitantes ao se fazer o merge entre uma ou mais branch. Nesses casos, devemos resolver os conflitos e então realizar um `merge commit` com a versão final dos arquivos após a resolução dos conflitos.

Um merge commit é um commit normal, porém, ele vai ter dois ou mais commits pais, indicando que é um commit originado de uma operação de merge.
