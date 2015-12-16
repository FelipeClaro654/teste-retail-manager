# Teste Retail Manager
Uma aplicação simples para testar as habilidades com Ruby on Rails.

##### Procedimento
Fazer um fork do projeto, e ao finalizar fazer um pull request para o repositório original.

##### Prazo de entrega
2 dias a partir do recebimento do teste por email. Faça um pull request, mesmo que não tenha finalizado tudo 100%, gostariamos de analisar o seu código de qualquer forma.

##### Descrição da tarefa:
Um cliente precisa de uma aplicação para controle de estoque dos seus produtos. Ele pode ter um mesmo produto em diferentes tamanhos e cores.

Por exemplo, ele pode ter no estoque:
- 5 peças da Camiseta X, na cor preta, tamanho P
- 2 peças da Camiseta X, na cor preta, tamanho M
- 3 peças da Camiseta X, na cor preta, tamanho G
- 7 peças da Camiseta X, na cor azul, tamanho M
- 1 peça da Camiseta Y, na cor braca, tamanho M

Etc...

##### O que você irá fazer:
Precisamos uma tela onde seja possível cadastrar um produto com nome e descrição, e relacionar novas cores, tamanhos e quantidade utilizando Nested Forms.

Cor e tamanho não precisa ter CRUD, apenas crie os modelos e popule com alguns dados de teste para serem relacionados ao produto (Pode ser um arquivo de seed).

##### Requisitos
- Escrever testes utilizando RSpec ou MiniTest. (Nosso projeto atual usa RSpec)
- Não utilizar o scaffold. Mostre sua habilidade em criar views, controllers, models, sem usar scaffold.
- Organização e legibilidade do código
- Se utilizar gems, listar quais gems foram utilizadas, e para qual finalidade

##### Bônus
- Usar bootstrap para formatar as páginas de cadastro
- Utilizar SimpleForm
- Publicar no heroku e nos enviar o link
