# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Perfil de Usuário** - neste campo os interessados inserem seus dados cadastrais que permitem adotar ou informar um pet em situação de rua.
     - **Cadastrar Pet** - nesta seção é feito o cadastro dos animais encontrados em situação de rua. 
     - **Adotar Pet** - são ofertados animais em diversas situações de vunerabilidade.
     
 - **Hospedagem** - a aplicação ficará hospedada no FireBase.


A imagem a seguir demonstra fluxograma que um usuário terá que seguir para cadastrar-se, cadastrar um pet ou adotar um pet. Assim que o usuário entra na plataforma, ele é apresentado à tela inicial
(Tela 1) onde é apresentado uma lista de animais encontrados recentemente.

Caso ele demonstre interesse por algum dos animais listados ele deverá seguir para (Tela 2) onde é feito cadastro com seus dados pessoais. 
Na (Tela 3) o usuário poderá cadastrar um pet avistado por ele, informando características básicas do animal bem como sua última localização conhecida.

Na (Tela 4) o usuário poderá alterar seus dados cadastrais facilitando a indentificação no momento de uma nova adoção.

## Hospedagem

Para esse projeto utilizamos a ferramenta do firebase que faz parte da GCP ( Google Cloud Plataform), ela torna simples a adoção do processo de deploy por todos os integrantes do time, também é possível com ela de maneira facilitada, monitorar e controlar versões dos artefatos entregues em produção. 

