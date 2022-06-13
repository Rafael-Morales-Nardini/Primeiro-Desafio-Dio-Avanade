tab - auto-complete

sha1 - conjunto de 40 caracteres encriptados para um arquivo

git init - cria uma pasta .git e inicia um repositório no git dentro da pasta

git add - trackeia o arquivo

git status - diz o status do arquivo

git commit -m “mensagem aqui” cria um commit

git remote add origin (Link do github) - Linka os seus commits com o projeto no github

git push origin master - Envia para o Github

git pull origin master - Recebe do github, utilizado em problemas de merge

Untracked - Arquivo que ainda não passou pelo git add

tracked (Se divide em 3 classes)

Unmodified - Ainda não sofreu modificação

Modified - Um arquivo Unmodified que sofreu alteração, é percebido pela mudança de Sha1

Staged - Área especial que está aguardando para entrada em ação, surge quando se roda o git add em um arquivo modified

Quando um arquvio Unmodified é removido, ele se torna novamente untracked

Quando um arquivo do tipo Staged passa por um Commit, ele retorna ao estado de unmodified

blob - bloco básico de composição

tree - aponta blobs ou outras trees

commit - Unico, possui autor e se refere a árvore(s)