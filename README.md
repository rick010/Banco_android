1- Na class ContasActivity fiz o método observe que quando altera, o adapter atualiza as contas

2- Na classe ContaViewHolder no método bindTo fiz a chamada do addListener que altera a imagem conforme o saldo da conta.

3- chamei o startActivity e setei a variavel i do Intent criado para enviar o usuário para a tela EditarContaActivity

4- Na classe AdicionarContaActivity fiz a validações para que o usuário não consiga fazer operações com os dados inválidos

5- Na classe ContaDAO criei os métodos de atualizar, remover e o de busca pelo CPF, Nome e Número da conta.

6- Na classe ContaRepository complementei os metodos de inserir, atualizar, remover, buscarPeloNome, buscarPeloCPF e buscarPeloNumero para responder adequadamente para 
as classes que chamam ContaRepository.

7-Na classe ContaViewModel, criei os métodos para atualizar e remover contas no banco de dados, criei também o método de buscarPeloNumero para retornar a conta buscadada pelo número.

8- Na classe EditarContaActivity criei a função que pega os dados daa conta  e oque o usuário digitou,e atualiza ou remove do banco de dados.

9-Na classe EditarContaActivity criei a funcionalidade de validar as informações digitadas antes de atualizar a Conta no banco de dados e Implementei também o código que usa ContaViewModel para armazenar o objeto  atualizado no banco de dados

10-Na classe EditarContaActivity criei a  funcionabilidade para validar os campos que não haver espaços em branco na hora de salvar no banco, criei a funcionabilidade para a remover o objeto do banco pela ContaViewModel.

11- Na classe BancoViewModel criei os métodos para realizar as operações de transferir creditar e debitar e os métodos de buscar por nome do cliente e pelo cpf.

12- Nas classes DebitarActivity, CreditarActivity, e TransferirActivity foi implementado funcionalidades para validações e chamar os métodos na classe BancoViewModel

13-Na classe PesquisarActivity, criei o método  que faz busca no banco de dados de acordo com o tipo de busca escolhido pelo usuário.

14-Na classe PesquisarActivity criei as funcionalidades para chamar os métodos de busca a partir da opção escolhida pelo usuário, utilizando também o método de RecyclerView para renderizar na mesma tela usando o adapter e o método observer para atualizar quando houver uma nova pesquisa.

15- Na classe MainActivity criei método observer que atualiza o saldo total do Banco se tiver alguma alteração..
