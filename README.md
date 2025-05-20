# fr4ncisco7-CRUD-de-Alunos-com-HTML-JSON-e-MVC

1-View:Nesse projeto o view está sendo responsável em exibir as informações e responsável por captar as alterações que estão acontecendo, porque é nele que está o arquivo com o código html.

controller: Nesse projeto o controller ele está gerencindo as rotas dos alunos, cursos e professores. Ele é responsável por possuir as requisições http de alterar, criar , remover e atualizar e a URL, o endereço para onde ir.

Model: Nesse projeto o modelo está pegando a informação do controller e está fazendo as operações no banco de dados, ele execulta a sql.

Eles se completam, o view está tendo o contato com os usuários. Ele avisa ao controller quando o usuário quer fazer alguma alteração, o controller pega essa requisição do cliente e leva para o model. Lá o model faz as operações com o banco de dados. Assim, fazendo o caminho inverso agora, o model passa os dados para o controller,o controller para para o view e o view passa para o usuário.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2-Como ocorre o envio e o recebimento de dados no formato JSON neste projeto?
Cite uma rota que responde em JSON e explique seu funcionamento.

2-O Json é como uma forma padronizada de escrever objetos javascript como texte. Logo, isso é muito importante porque esses arquivos são mais leves e muito mais facil do computador ler, o que facilita a troca de dados entre diversos sistemas.

Exemplo é o  [  res.json(alunos); ] que envia uma resposta em formato JSON para o cliente 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3- Porque são um formato básico e muito funcional formulários coletam os dados e as tabelas exibem esses dados.

esse tipo de estrutura ainda é útil em projetos back-end com Node.js porque HTML básico facilita a comunicação entre front-end e back-end. O Node.js envia páginas HTML para o navegador, que usam formulários para receber dados.
