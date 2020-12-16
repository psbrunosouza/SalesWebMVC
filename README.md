## Sistema de vendas com MVC 

Esse sistema foi desenvolvido como projeto final do curso C# completo + POO do professor Nélio Alves.
O objetivo era entender os fundamentos da criação de sistemas web com o padrão mvc.

Nesse sistema pude aprender algumas funcionalidades e características do razor, trabalhar com banco e migrations, 
trabalhar com serviços e entender mais sobre o padrão MVC.

### Tela departamentos
Nessa tela o usuário pode criar novos departamentos e visualizar todos os departamentos disponíveis.

### Tela de vendedores
Nessa tela o usuário pode cadastrar um novo vendedor, editar ou excluir. Cada vendedor pertence a um departamente, 
ou seja, está completamente relacionado aos departamentos que foram cadastrados no sistema.

### Tela de busca
Nesse sistema foi trabalhado duas formas de pesquisa:
1. Pesquisa simples
  Traz todo conteúdo de vendas cadastrado no aplicativo dentro de uma data especificada, e realiza o somatório total de vendas.
  
2. Pesquisa agrupada
  Traz todo conteúdo de vendas organizado por **departamento**, também realizando um somatório total, porém para cada departamento.
 
### Tratamento de erros
Foi realizado alguns tratamentos de erros simples, como durante a pesquisa informar ao usuário que não existem dados a serem pesquisados,
ao excluir um departamento inteiro, dispara um alerta informando ao usuário que aquele departamento possui vendedores, da mesma forma para 
as vendas que estão associadas a um vendedor especifico.
