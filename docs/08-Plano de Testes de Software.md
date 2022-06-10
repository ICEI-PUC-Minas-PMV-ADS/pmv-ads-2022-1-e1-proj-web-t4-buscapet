# Plano de Testes de Software

### CASOS DE TESTES SUCESSO: 
<ol>

    |CASO DE TESTE| CT-01 – | Validação Tela Cadastro de Usuário e Login
    |--------------|------------------------|
    |REQUISITOS ASSOCIADOS	|RF-001|
    |                                                   |
    |OBJETIVO DO TESTE	| Cadastrar usuário e realizar Login|
    |      | 1) Acessar a aplicação | 
    |PASSOS| 2) Clicar em "Criar Conta"|
    |      | 3) Usuário terá acesso ao local onde irá realizar seu cadastro| 
    |CRITÉRIO DE ÊXITO| Após o cadastro realizado,o usuário poderá efetuar login clicando em "Entrar" |

 
    |CASO DE TESTE |CT-02 – | Cadastro de animais
    |--------------|-------------------------------------|
    |REQUISITOS ASSOCIADOS	|RF-002 | 
    |OBJETIVO DO TESTE|Realizar cadastro de animais na tela Cadastrar Pet|
    |      	|1) Acessar a aplicação	|
    |       |2)	Clicar em "Entrar" e efetuar o login do usuário|
    |       |3)	Será redirecionado para a tela Home|
    |       |4)	Na tela Home clicar em "Cadastrar Pet"|
    |PASSOS |5)	Na tela Cadastrar Pet preencher todas as informações obrigatórias|
    |       |6)	Em seguida clicar em "Cadastrar Pet"|
    |   CRITÉRIO DE ÊXITO  |Após o cadastro realizado do pet o usuário será 
    |                      |capaz de vizualiza-lo na tela Home |
    |	                   |Usuário será capaz de editar e vizualizar cadastro |
    |                 	   |Caso necessário será capaz de deletar cadastro |
 
 
    |CASO DE TESTE| CT-03 – | Lista de aniamis cadastrados
    |--------------|------------------------|
    |REQUISITOS ASSOCIADOS	|RF-003|
    |                                                   |
    |OBJETIVO DO TESTE	| Vizualizar lista de animais cadastrados |
    |      | 1) Acessar a aplicação| 
    |PASSOS| 2) Efetuar login| 
    |      | 3) Será redirecionado para a tela Home onde será 
    |           possivel vizualizar a lista de animais cadastrados.| 
    |CRITÉRIO DE ÊXITO| Conseguir vizualizar a lista de todos os 
    animais cadastrados com suas devidas informações importantes. |
 

    | CASO DE TESTE| CT-04 – | Visualização detalhada de um caso
    |--------------|------------------------|
    |REQUISITOS ASSOCIADOS	|RF-007|
    |                                                   |
    |OBJETIVO DO TESTE	| Vizualizar/Consultar um caso cadastrado |
    |      | 1) Acessar a aplicação |
    |PASSOS| 2) Efetuar login|
    |      | 3) Será redirecionado para a tela Home |
    |      | 4) Na tela Home clicar em "Consultar" no animal que deseja vizualizar cadastro|
    |      | 5) Será redirecionado para a tela onde será vizualizado 
            o cadastro selecionado.|
    |CRITÉRIO DE ÊXITO| Conseguir vizualizar o cadastro de animal escolhido |
 
    | CASO DE TESTE| CT-05 – | Remover caso
    |--------------|------------------------|
    |REQUISITOS ASSOCIADOS	|RF-010|
    |                                                   |
    |OBJETIVO DO TESTE	| Deletar um caso cadastrado |
    |      | 1) Acessar a aplicação |
    |PASSOS| 2) Efetuar login|
    |      | 3) Será redirecionado para a tela Home|
    |      | 4) Na tela Home clicar em "Deletar" no animal que deseja remover |      | 5) Será exibido uma mensagem "Pet Deletado com Sucesso" |
    |CRITÉRIO DE ÊXITO| Conseguir deletar um caso cadastrado |


    | CASO DE TESTE| CT-05 – | Editar caso
    |--------------|------------------------|
    |REQUISITOS ASSOCIADOS	|RF-000|
    |                                                   |
    |OBJETIVO DO TESTE	| Atualizar um caso cadastrado |
    |      | 1) Acessar a aplicação |
    |PASSOS| 2) Efetuar login|
    |      | 3) Será redirecionado para a tela Home|
    |      | 4) Na tela Home clicar em "Editar" no animal que desej atualizar 
    |      | 5) Será redirecionado para a tela onde poderá 
                editar o pet selecionado  |
    |      | 6) Após as alterações clicar em "Atualizar Pet"
    |CRITÉRIO DE ÊXITO| Conseguir editar um caso cadastrado |

<ol>
 
## CASOS DE TESTE INSUCESSO: CT-01 (RF-001)
<ol>
 
    |CASO DE TESTE |	CT-01 – ERRO EM LOGIN | 
    |-------------|-----------------------|
    |REQUISITOS ASSOCIADOS	|RF-001|
    |OBJETIVO DO TESTE|Confirmar validação do cadastro de usuário para 
    |                  efetuar login|
    |                 |1) Acessar a aplicação|
    |Passos           |2) Clicar em "Entrar"|
    |                 |3) Preencher Email e Senha|
    |                 |4) Clicar em "Entrar"|
    |Critérios de Êxito	|Para efetuar login é necessário que usuário esteja 
    cadastrado, caso não será emitido uma mensagem de alertada informando  "Usuário não encontrado!"|


    |CASO DE TESTE |	CT-01 – ERRO CADASTRAR ANIMAL | 
    |-------------|-----------------------|
    |REQUISITOS ASSOCIADOS	|RF-002|
    |OBJETIVO DO TESTE|Confirmar validação do cadastro de animal|
    |                 |1) Acessar a aplicação|
    |Passos           |2) Efetuar login|
    |                 |3) Será redirecionado para tela Home|
    |                 |4) Na tela Home clicar em "Cadastar Pet"|
    |                 |5) Será redirecionado para a tela 
                          de cadastro animal|
    |                 |6) Preencher formulário
    |Critérios de Êxito	|Para realizar o cadastro de animal deverá ser preenchido todo o formulário, caso não seja será emitido uma mensagem informado "Preencher todos os campos corretamente"|
 





  </ol>
 </ol>