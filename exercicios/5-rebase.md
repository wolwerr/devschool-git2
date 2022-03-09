# Rebase

Para mantermos o histórico de commits limpos, podemos efetuar operações de "Rebase" para evitar a criação de commits de merge e também para manipular os commits de nossa branch antes de enviarmos os commits para serem mergeados nas branchs públicas.

Os rebases são operações que devem ser realizadas somente em branchs locais e não utilizadas por outras pessoas do time, pois é uma operação que re-escreve o histórico de commits.

`git rebase nome_da_branch_ou_referencia` fará o rebase dos commits a mais a sua branch em relação à branch indicada

`git rebase nome_da_branch_ou_referencia --interactive` permite manipularmos o que será feito com cada commit.
