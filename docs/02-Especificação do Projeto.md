# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
>
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
> Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` | PARA ... `MOTIVO/VALOR`               |
| -------------------- | ---------------------------------- | ------------------------------------- |
| Usuário do sistema   | Registrar casos de avistamento de  | Ajudar com a localização para resgate |
|                      | animais na rua                     | ou encontrar animais que se perderam  |
| Administrador        | Marcar localização do aminal para  | Permitir que usuarios visualizem caso |
|                      | divulgação na rede de seguidores   | proximos a sua localidade             |
|                      | proximos                           |                                       |

### Maria Alves

QUERO/PRECISO...

Deseja receber mais postagens das páginas que segue no facebook
Saber de casos de pessoas que possam estar precisando de sua ajuda

PARA ...

Algoritmo priorizar postagens de seus amigos, quando lembra de entrar no grupo muitos posts já estão velhos
Porque não tem contato direto com a vizinhança, então não consegui saber se algum caso próximo está acontecendo

### Ana da Silva

QUERO/PRECISO...

Fazer notificações sobre a busca de seu animal perdido
Ter um local específico para notificar a perda de seu animal de estimação

PARA ...

Não acredita que espalhar panfletos ajudou, hoje em dia as pessoas vivem com a atenção nas redes sociais
Não tinha a nenhum lugar específico para recorrer e ter ajuda

### Sandra Maia

QUERO/PRECISO...

Poder ajudar mais casos de animais nas ruas do seu bairro
Mais visibilidade à situação crítica
Ao caminhar encontra vários animais, mas não sabe onde recorrer uma vez que as ongs estão lotadas

PARA ...

Ter dados sobre a situação
Não vê que a população tem noção real da situação de fato, o que prejudica atuação e interesse público
Não consegui dados sobre a situação do abandono de animais e população de animais abandonados de sua cidade.

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID     | Descrição do Requisito                                                                                                | Prioridade |
| ------ | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| RF-001 | O site deve apresentar na página principal um menu para cadastro e login de usuários.                                 | ALTA       |
| RF-002 | O site deve permitir ao usuário a opção de cadastro de animais em situação de rua.                                    | ALTA       |
| RF-003 | O site deve apresentar uma lista de todos os animais cadastrados (feed).                                              | ALTA       |
| RF-004 | O site deve oferecer a funcionalidade de filtro/pesquisa para permitir ao usuário localizar animais pela proximidade. | ALTA       |
| RF-005 | O site deve permitir a visualização detalhada de um caso.                                                             | ALTA       |
| RF-006 | O site deve permitir a atualização de cadastro de usuário.                                                            | MÉDIA      |
| RF-007 | O site deve permitir visualizar todas as postagens feitas pelo usuário.                                               | BAIXA      |
| RF-008 | O site deve permitir visualizar o usuário.                                                                            | BAIXA      |
| RF-009 | O site deve permitir visualizar dados de contato entre os usuários.                                                   | MÉDIA      |
| RF-010 | O site deve permitir remover postagens.                                                                               | MÉDIA      |
| RF-010 | O site deve permitir curtir postagens.                                                                                | BAIXA      |

### Requisitos não Funcionais

| ID      | Descrição do Requisito                                                                  | Prioridade |
| ------- | --------------------------------------------------------------------------------------- | ---------- |
| RNF-001 | O site deve ser publicado em um ambiente acessível publicamente na internet.            | ALTA       |
| RNF-002 | O site deverá ser responsivo permitindo a visualização em um celular de forma adequada. | ALTA       |
| RNF-003 | O site deve ter bom nível de contraste entre os elementos da tela em conformidade.      | MÉDIA      |
| RNF-004 | O site deve ser compatível com os principais navegadores do mercado.                    | ALTA       |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

| ID  | Restrição                                             |
| --- | ----------------------------------------------------- |
| 01  | O projeto deverá ser entregue até o final do semestre |
| 02  | Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
>
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
