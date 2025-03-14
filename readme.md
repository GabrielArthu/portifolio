Checkout de um commit específico:

Isso coloca o repositório no estado "detached HEAD".

Efeitos do estado "detached HEAD":

Você pode fazer alterações e commits, mas esses commits não estarão em nenhuma branch.
Se você mudar para outra branch, esses commits podem ser perdidos, a menos que você crie uma nova branch a partir do estado atual.
Criar uma nova branch a partir do estado "detached HEAD":

Isso cria uma nova branch e preserva os commits feitos enquanto o HEAD estava destacado.

Exemplo Prático
Verifique o histórico de commits:

Faça checkout de um commit específico:

Faça algumas alterações e commits:

Crie uma nova branch para salvar essas alterações:

Conclusão
O estado "detached HEAD" é útil para explorar o histórico do repositório ou fazer alterações temporárias. No entanto, é importante lembrar de criar uma nova branch se você quiser preservar essas alterações.

Texto adicionado para fazer o teste do detached mode, este conteudo está 1 commit atras da main, sera feito a criação de uma nova branch para que posteriormente este conteudo seja adicionado as branc principar ficando assim "up to date"
