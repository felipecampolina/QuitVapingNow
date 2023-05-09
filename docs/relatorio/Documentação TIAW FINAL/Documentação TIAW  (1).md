` `![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.001.png)


QuitVapingNow

Trabalho Interdisciplinar - Aplicações Web










Belo Horizonte, Abril/2022

Sumário

[**Introdução](#_owhllrhmu8jp)	**4****

[Problema](#_luc17f5ery5y)	4

[Objetivos](#_j79puan2atxc)	4

[Justificativa](#_2o0jlxqg3jf5)	5

[Público alvo](#_v1fnbd43y91t)	5

[**Especificação do Projeto](#_rc2xxy5m3gq6)	**5****

[Personas](#_h7ifxrfesw8)	6

[Histórias de usuários](#_m5ioeugl6jbp)	8

[Requisitos do Projeto](#_xdhzbuv656bo)	9

[Requisitos Funcionais](#_6lpb0aldjaef)	9

[Requisitos não funcionais](#_it0l9ob4pqqi)	9

[Restrições](#_kjb1stvepiha)	10

[**Metodologia](#_ac9qgq80i7ks)	**10****

[Relação de Ambientes de Trabalho](#_frf60gjkoy6e)	10

[Gestão de código fonte](#_2mo7zrv24um9)	11

[Processos do desenvolvimento do trabalho](#_5j1i8wtf4ol)	11

[**Projeto de Interface](#_crxcf6cj4p1b)	**13****

[Fluxo do Usuário](#_cxx8i4z0pm94)	13

[Wireframes](#_7oogomjspand)	14

[Tela - Login](#_lexr23rs0df)	15

[Tela - Página de registrar](#_9aed1r5jksu5)	15

[Tela - Questionário](#_i9ezwhy8r7i6)	16

[Tela - Inicial](#_56h116t82b72)	16

[Tela - Conquistas e desafios](#_ox2gjduf98ol)	17

[Tela - Videos e notícias](#_vi4okkvqg13f)	17

[Tela - Benefícios e Malefícios](#_b8y4h3q2col3)	18

[Tela - Perfil](#_qjpijtwc7shu)	18

[Tela - Sobre](#_vu9jrev95qg7)	19

[Tela - Buscar](#_m8bx2gemse3j)	19

[**Implementação da Solução](#_bdhqpjaxz761)	**20****

[Arquitetura da Solução](#_hkyhu4lf2swe)	20

[Diagrama de Componentes](#_i6ay8q8rs7n7)	20

[Hospedagem](#_xo3n84rz8b9x)	21

[Template do Site](#_ca7r68kiwym2)	21

[Tela Principal](#_9ys623y3vzx)	22

[Conquistas e desafios](#_ytidwnoddza1)	22

[Tela de Visualização de Vídeos e Notícias](#_py6d9msj8n6e)	23

[Perfil de usuário](#_wl4j60dow46g)	23

[Benefícios e Malefícios](#_lz0mavyhuond)	24

[Sobre](#_zfnltbfxa7pd)	24

[Funcionalidades do Sistema (Telas)](#_mr9dupx5f66g)	25

[Entrega Sprint 1 - Visualização dos vídeos e notícias (RF-01,  RF-02 e RF-03)](#_ubm4ghxw6rhz)	25

[Entrega Sprint 2 - Visualizar informações acerca do tempo em que o usuário realizou o uso de cigarros durante a sessão (RF-04)](#_xu0sx0k9wkli)	26

[Entrega Sprint 2 - Visualizar os desafios e conquistas do usuário (RF-05 e RF-06)](#_wqnzy3l4k47t)	27

[Entrega Sprint 3 - Visualizar a página de perfil do usuário (RF-07)](#_tb22okehqsdw)	27

[Entrega Sprint 1 - Cadastro de informações para o login (RF-08)](#_jhdth2gacp6x)	28

[**Avaliação da Solução](#_v2u3kx19npr)	**29****

[Plano de Testes de Software](#_rd0o79q7lltz)	29

[Registro de Testes de Software](#_khqg4p6zawjj)	36

[Plano de Testes de Usabilidade](#_5onfacccmosp)	37

[Registro de Testes de Usabilidade](#_7cxcibmcuefo)	37

[**Referências Bibliográficas](#_tcpsb469odty)	**39****


#






















1. # Introdução
O contexto contemporâneo é caracterizado pela velocidade e praticidade. É notório que, a cada dia que se passa, a sociedade vem se adaptando para inserir-se nesse ambiente, criando, modificando, destruindo e transformando o mundo e os objetos nele presente.

Um exemplo dessa ideia, é criação de dispositivos eletrônicos para fumar (DEF 'S), em uma tentativa de acelerar e aumentar a facilidade e a usabilidade do hábito do tabagismo. A ideia de um “cigarro elétrico” aparece pela primeira vez no ano de 1960, nos Estados Unidos, desenvolvido e patenteado em 1963, por Herbert Gilbert, como um possível substituto menos maléfico para os cigarros. Entretanto, no século XXI, esse dispositivo se transformou, muitas vezes, numa porta de entrada para o tabagismo, consequentemente, crescendo o número de pessoas viciadas em nicotina, provocando dermatite, doenças cardiovasculares, câncer e inúmeros outros malefícios à saúde.

Além disso, vale ressaltar o grande número de jovens e adolescentes que estão usufruindo desses aparelhos, sendo assim ainda mais prejudiciais, por causa do corpo humano em desenvolvimento. É possível perceber a “febre” que os cigarros eletrônicos viraram internacionalmente, visto que, diversos países e organizações sanitárias proibiram a venda e comercialização, em uma tentativa de frear essa onda e proteger a saúde dos cidadãos.

## Problema
Conforme exposto, muitos usuários acreditam que os cigarros eletrônicos são menos maléficos do que os cigarros convencionais, justificando a troca, dessa forma, sustentando o vício pela nicotina de uma maneira “mais saudável”. Todavia, para combater a dependência é necessário a busca de auxílio de profissionais de saúde, além da redução gradativa do hábito de fumar.
## Objetivos
O objetivo geral deste trabalho é a criação de uma plataforma que auxilia as pessoas que fumam cigarros eletrônicos a reduzirem este hábito, visando a interrupção por completa dessa prática, assim reduzindo a prevalência de fumantes e a consequente morbimortalidade relacionada ao consumo de derivados do tabaco.

Como objetivos específicos, podemos ressaltar:

- Fornecer funcionalidades que permitam acompanhar o uso, por meio de uma gamificação. 
- Fornecer funcionalidades que permitam  acompanhar a economia feita ao cessar tal hábito.
##
## Justificativa
Em estudo realizado pela Global Clinical Research Journal, é evidente que os cigarros eletrônicos foram introduzidos na sociedade como um substituto do cigarro tradicional, entretanto viraram, em muitos dos casos, uma porta de entrada para o tabagismo . Além disso, é notório  um grande número de jovens seduzidos pela modernidade e particularidades dos dispositivos, utilizando-os sem saber dos malefícios à saúde(DA SILVA et al ; 2021). Adicionalmente, existe uma grande parcela de pessoas que estão viciadas em DEF 'S, graças a presença de nicotina nos mesmos.

Portanto, o trabalho foi desenvolvido para reduzir a predominância de fumantes e a consequente morbimortalidade e danos à saúde relacionados ao consumo de cigarros eletrônicos.
## Público alvo
Embora todas as pessoas possam se beneficiar da plataforma para se informarem sobre dispositivos eletrônicos para fumar, considerados como o novo cigarro do século XXI, a plataforma especificamente visa auxiliar aqueles que pretendem parar de fumar.



Desta forma, estabeleceu-se como público-alvo desta solução as pessoas que procuram interromper o hábito do tabagismo, ressaltando os jovens, maioria dos usuários de DEF`S, além de familiares e amigos de usuários que estão preocupados com o uso excessivo. 
1. # Especificação do Projeto
Após o trabalho de imersão nos proporcionado, com foco em discutir e debater problemas atuais, decidimos os membros da equipe responsável por esse problema e seus pontos mais relevantes a serem tratados. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.
##
##
##
##
##
## Personas
Nas figuras a seguir, são apresentadas as personas levantadas durante o processo de entendimento do problema.



|![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.002.jpeg)|**Jorge Matheus Otoni**|
| :-: | :-: |
||<p>**Idade**: 46</p><p>**Ocupação**: empresário, abriu uma empresa de agenciador de talentos e hoje trabalha com diversos pequenos e médios artistas pelo Brasil.</p>|<p>Aplicativos:</p><p>- Instagram.</p><p>- TikTok.</p><p>- Twitter.</p><p>- Linkedin.</p>|
|<p>Motivações</p><p>- Se tornar o maior agente de talentos do Brasil.</p><p>- Juntar dinheiro suficiente para a educação de seus filhos.</p><p>- Manter uma condição de vida alta para seus filhos.</p><p></p>|<p>Frustrações</p><p>- Não consegui parar de fumar.</p><p>- Dificuldade de realizar exercícios físicos.</p><p>- É julgado sempre que o assunto é tabagismo.</p><p>- Teme o risco de obter doenças pulmonares.</p>|<p>Hobbies, História</p><p>- Viajar com a família. </p><p>- Ir ao clube com os amigos.</p><p>- Frequentar sua casa de campo aos finais de semana.</p>|






|<p></p><p>![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.003.jpeg)</p>|**Gabriel Souza**|
| :-: | :-: |
||<p>**Idade**: 18</p><p>**Ocupação**: Estudante Universitário de engenharia da computação. Frequenta faculdade particular.</p>|<p>Aplicativos:</p><p>- TikTok</p><p>- Instagram</p><p>- Twitter</p><p>- WhatsApp</p>|
|<p>Motivações</p><p>- Se formar na faculdade.</p><p>- Construir uma família.</p><p>- Adquirir sua independência financeira.</p><p></p>|<p>Frustrações</p><p>- Já teve problemas de saúde relacionados ao seu vício.</p><p>- Não conseguir controlar a ansiedade.</p><p>- Dificuldade de controlar o vício em cigarros.</p><p>- Medo de sentir-se excluído como consequência de seu vício.</p>|<p>Hobbies, História.</p><p>- Ler livros.</p><p>- Sair com amigos.</p><p>- Andar de skate.</p>|


|![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.004.jpeg)|**Pietra Silva**|
| :-: | :-: |
||<p>**Idade**: 14</p><p>**Ocupação**: Estudante do ensino Médio . Frequenta escola estadual.</p>|<p>Aplicativos:</p><p>- Tiktok.</p><p>- Instagram.</p><p>- Pinterest.</p><p>- Twitter.</p><p>- WhatsApp.</p>|
|<p>Motivações</p><p>- Ser uma jogadora de futebol. </p><p>- Ter uma boa relação familiar.</p><p>- Se tornar uma influenciadora digital de sucesso.</p>|<p>Frustrações</p><p>- Seu irmão de 16 anos já é fumante.</p><p>- Seu pai morreu devido a problemas com cigarro.</p><p>- Ser rejeitada por diversos times de futebol.</p>|<p>Hobbies, História</p><p>- Jogar bola. </p><p>- Sair com os amigos.</p><p>- Jogar videogame.</p>|



## Histórias de usuários
As seguintes histórias de usuários foram registradas a partir da compreensão do dia a dia das personas identificadas para o projeto.


|**Eu como …  [PERSONA]**|**… quero/desejo … <br>[O QUE]**|<p>**… para ....**</p><p>**[POR QUE]**</p>|
| :-: | :-: | :-: |
|Jorge Matheus Otoni|Parar com o uso dos cigarros em geral.|Devido ao conhecimento de que cigarros eletrônicos são tão prejudiciais à saúde quanto os cigarros convencionais.|
|Jorge Matheus Otoni|Construir uma melhor relação familiar.|medo tornar-se uma pessoa excluída por sua própria família.|
|Jorge Matheus Otoni|Parar de mentir para as pessoas quando o assunto é cigarros.|não consegue admitir seu vício à seus amigos e familiares, prejudicando cada vez mais o processo de ajuda ao seu problema.|
|Pietra Silva|Deixar sua mãe feliz e despreocupada.|a mãe de Pietra vive preocupada com o vício de seu irmão, devido a grande quantidade de tempo que ele pratica o uso de cigarros.|
|Pietra Silva|Ajudar seu irmão a parar de fumar.|Possui um irmão viciado em cigarros a muito tempo e passando por situações complicadas como consequência desse ato.|
|Pietra Silva|Um futuro próspero para seu irmão.|Sabe das consequência do vício, uma vez que seu pai veio a falecer por causa disso..|
|Gabriel Souza|<p>Parar de utilizar cigarros convencionais. </p><p></p><p></p>|sente-se incomodado com o cheiro da fumaça.|
|<p>Gabriel Souza</p><p></p>|Um Incentivo e uma ajuda para parar de fumar.|Teme por sua saúde pulmonar.|

## Requisitos do Projeto
Por meio das obrigatoriedades que descrevem as possíveis interações entre os usuários, o escopo funcional do projeto é definido. Além disso, os requisitos não funcionais evidenciam os aspectos que o sistema deverá apresentar de maneira geral. A seguir, são apresentados estes requisitos.
### Requisitos Funcionais
A seguir está a tabela que aborda os requisitos do projeto, por meio da identificação da prioridade em que esses devem ser entregues.


|**ID**|**Descrição**|**Prioridade**|
| :-: | :-: | :-: |
|RF-01|O site deve apresentar um sistema de identificação dos usuários.|Média|
|RF-02|O site deve apresentar um sistema de acompanhamento do uso do usuário(página usuário) em gráficos e cards.|Alta|
|RF-03|O site deve acompanhar os benefícios financeiros de não usar cigarros/DEF 's.|Média|
|RF-04|O site deve oferecer um menu mobile.|Média|
|RF-06|O site deve possuir um sistema de recompensas, desafios e conquistas, a fim de incentivar o fim do hábito de fumar|Média|
|RF-07|O site deve possuir um questionário para identificar o perfil e vício do usuário. |Média|
|RF-08|O site deve ter uma página com os malefícios do cigarro eletrônico.|Baixa|
|RF-09|O site deve ter uma página vídeos e sobre o tabagismo.|Baixa|

### Requisitos não funcionais
Os requisitos não funcionais que o projeto deverá atender são apresentados na tabela abaixo.


|**ID**|**Descrição**|**Prioridade**|
| :-: | :-: | :-: |
|RNF-01|O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku); |Alta|
|RNF-02|O site deverá ser responsivo permitindo a visualização em um celular de forma adequada.|Alta|
|RNF-03|O site deve ter bom nível de contraste entre os elementos da tela em conformidade.|Média|
|RNF-04|O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge).|Alta|
|RNF-05|O site deve ter uma estética boa, a fim de atrair usuários.|Alta|
|RNF -06|O site deve ser uma experiência divertida para os usuários.|Média|


### Restrições
Questões responsáveis pela limitação da execução do projeto e que se configuram como obrigações evidentes para o desenvolvimento do projeto em questão, são apresentadas na tabela a seguir.


|**ID**|**Descrição**|
| :-: | :-: |
|RE-01|O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 03/07/2022.|
|RE-02|O aplicativo deve se restringir às tecnologias básicas da Web no Frontend.|
|RE-03|A equipe não pode subcontratar o desenvolvimento do trabalho.|
|RE-04|Falta de recursos financeiros para aprimorar recompensas.|
# Metodologia
A metodologia exerce a função de contemplar as definições de ferramentas utilizadas pela equipe. Nesse caso, ela é responsável tanto pela manutenção dos códigos e demais artefatos quanto pela organização do time na execução das tarefas do projeto.

## Relação de Ambientes de Trabalho
Os artefatos do projeto são desenvolvidos a partir de diferentes plataformas. Na tabela a seguir, é apresentada pelos ambientes com seus respectivos objetivos.


|**Ambiente**|**Plataforma**|**Link de Acesso**|
| :-: | :-: | :-: |
|Repositório de código fonte|GitHub|<https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-uso-excessivo-de-cigarros-eletronicos>|
|Design Thinking|Miro|<https://docs.google.com/folder/d/1xE9t6zD78VnVkeOSgDfss33QWe85ogqYpx9x-tuG24> |
|Projeto de Interface e  Wireframes|MarvelApp|[https://marvelapp.com/4hd6091](https://marvelapp.com/prototype/175iab59)  |
|Gerenciamento de tarefas|Trello|<https://trello.com/b/BoOabyw9/tiaw-uso-excessivo-de-cigarros-eletronicos>  |

## Gestão de código fonte
Na figura a seguir, é apresentado um processo que tem como base o **Git Feature Branch Workflow.** Esse, é utilizado pelo grupo para gestão do código fonte do software desenvolvido pela equipe. De tal maneira, todas as manutenções do código são realizadas em branches separadas. No site, "[5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)", é encontrada uma explicação rápida sobre este processo.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.005.png)

Figura X - Fluxo de controle do código fonte no repositório git

## Processos do desenvolvimento do trabalho
A equipe utiliza metodologias ágeis, tendo escolhido o Scrum como base para definição do processo de desenvolvimento.

A equipe está organizada da seguinte maneira:

- Scrum Master: Rommel Carneiro .
- Product Owner: Rafael Lana Mascarenhas Diegues.
- Equipe de Desenvolvimento
  - Felipe Campolina Soares de Paula (Desenvolvedor Back End)
  - Pedro Gustavo de Castro Markiewicz (Desenvolvedor Back End)
  - Arthur Sgarbi Andrade (Desenvolvedor Back End)
  - Arthur de Sá Camargo(Desenvolvedor Back End)

Para organização e distribuição das tarefas do projeto, a equipe está utilizando o Trello estruturado com as seguintes listas: 

- **Recursos**: A lista de recursos demonstra uma visualização de tarefas usuais, utilizando configurações padronizadas que devem ser seguidas pelo usuário.  A ideia é utilizar a mesma interface para ajudar na dinâmica da criação de novos cartões. 
- **Backlog**: Recebe as informações a serem desenvolvidas e representa o Product Backlog. Todas as interferências realizadas no projeto também devem ser representadas nessa lista.
- **A fazer**: Esta lista representa o Sprint Backlog. Esse é o atual sprint que está sendo desenvolvido pelo grupo.
- **Fazendo**: Quando uma tarefa for iniciada, movê-la para esse tópico.
- **Teste**: Visão final sobre o projeto, checagem de funcionamento. Quando o projeto estiver quase finalizado, realiza-se um teste final para verificar o funcionamento dos recursos. 
- **Feito**: Esse tópico apresenta as tarefas que passaram pelo processo de testes e estão prontos para serem entregues para a utilização dos usuários. Não há mais modificações ou observações a serem realizadas. 


O quadro kanban do grupo no Trello está disponível através da URL <https://trello.com/b/BoOabyw9/tiaw-uso-excessivo-de-cigarros-eletronicos> e é apresentado, no estado atual, na Figura X. A definição desta estrutura se baseou na proposta feita por Littlefield (2016).

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.006.png)

Figura X - Tela do Trello utilizada pelo grupo

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.007.png)


As tarefas foram divididas e etiquetadas nas seguintes categorias: 

- Documentação
- Desenvolvimento 
- Infraestrutura
- Testes
- Gerência de Projetos.

#
1. # Projeto de Interface

Diante das preocupações para a montagem da interface no sistema, é concedida uma maior ênfase em questões como agilidade, acessibilidade e usabilidade. Para que ocorra um funcionamento em desktops e dispositivos móveis, o projeto tem uma identidade visual padronizada em todas as telas.
## Fluxo do Usuário
São evidenciadas as interações dos usuários pelas telas do sistema no diagrama apresentado pela Figura X. Na seção de Wireframes a seguir, é detalhada cada uma das telas desse fluxo.  Para visualizar o wireframe interativo, acesse o [ambiente Marvel App do projeto](https://marvelapp.com/prototype/175iab59/screen/86225823).


![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.008.png)

` `Figura X - Fluxo de telas do usuário

## Wireframes
De acordo com o fluxo de telas apresentado no item anterior, as telas do sistema são detalhadas no item a seguir. Além disso, apresentam uma estrutura comum que é apresentada na figura X. Nessa estrutura existem 3 grandes blocos descritos a seguir. São eles:

- **Cabeçalho -** local onde são dispostos elementos fixos de identidade (logo) e navegação principal do site (menu da aplicação);
- **Conteúdo -** apresenta o conteúdo da tela em questão;
- **Rodapé** - apresenta os elementos de navegação secundária, geralmente associados aos elementos do bloco de conteúdo.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.009.png)

Figura X - Estrutura padrão do site
###








### Tela - Login
A “Tela-Login” é onde o usuário da entrada no site. Nela, ele precisa fazer o login com seu email e senha. Em caso de ainda não possuir uma conta, ele pode, por meio do botão "registre-se", criar uma conta no site. Em caso de esquecer a senha, o usuário pode tentar recuperá-la clicando em “esqueceu a senha”.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.010.png)

Figura X - Página de login

### Tela - Página de registrar
Na “Tela - página de registrar” o usuário é capaz de criar uma conta para ele no site. Para isso, é necessário inserir um email, uma senha, e confirmar a senha. Em caso de já possuir uma conta, o usuário pode optar pela opção “clique aqui” onde ele vai direto para a página de login no site.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.011.png)

Figura X - Página de registar
### Tela - Questionário
Na “Tela-Questionário”, após o usuário se registrar no site, ele será direcionado a essa página na qual ele responderá algumas perguntas com o intuito de caracterizar sua personalidade e relação com os DEF´S. 

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.012.png)

Figura X - Tela - Questionário
### Tela - Inicial
A “Tela- Inicial” é o lugar onde o usuário terá acesso às principais funcionalidades do site. A partir dela, ele pode acessar a página de conquistas e desafios, vídeos e notícias, experiências dos usuários, benefícios e malefícios e causa, prevenção e tratamento.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.013.png)

Figura X - Tela inicial - Home
### Tela - Conquistas e desafios
A “Tela- Conquistas e desafios”, possui duas partes, a de desafios e a de conquistas. Na primeira, o usuário é motivado por meio de desafios a serem cumpridos. Na segunda, fica representado suas conquistas referentes aos objetivos cumpridos.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.014.png)

Figura X - Tela de Conquistas e desafios
### Tela - Videos e notícias 
A  “Tela- Vídeos e Notícias” é onde ficam armazenadas as notícias e vídeos relacionados ao tema do site, combate aos DEF´S.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.015.png)

Figura X - Tela - Vídeos e notícias 
### Tela - Benefícios e Malefícios  
Na “Tela- Benefícios e Malefícios” são apresentados os malefícios de fumar e os benefícios de parar de fumar.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.016.png)

Figura X -  Benéficos e Malefícios
### Tela - Perfil
Na “Tela- Perfil” é apresentado um resumo sobre o perfil do usuário, mostrando suas principais características. Nela, estão presentes suas informações, pessoas com quem interagiu e suas conquistas no combate ao uso de DEF´S. 

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.017.png)

Figura X -  Perfil
### Tela - Sobre
Na “Tela- Sobre” é apresentado um resumo a respeito do grupo criador do site. Nela, estão presentes os principais objetivos do grupo, de onde eles vieram, suas parcerias e quem são.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.018.png)

Figura X -  Sobre
### Tela - Buscar
A tela "busca" foi feita com a finalidade de que o usuário ache todos os conteúdos de forma mais simples e compacta na plataforma.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.019.png)

Figura X - Buscar
# Implementação da Solução
Nesta seção são apresentados os detalhes técnicos da solução criada pela equipe, tratando da Arquitetura da Solução, as estruturas de dados e as telas já implementadas.

## Arquitetura da Solução

### Diagrama de Componentes
Os componentes que fazem parte da solução são apresentados na Figura abaixo:


![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.020.png)


A solução implementada conta com os seguintes módulos:

- **Navegador** - Interface padrão do sistema 
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que são necessárias para implementar as funcionalidades do sistema.
  - **Local Storage** - armazenamento presente no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
    - **Canais** - seções de informações para pessoas que utilizam cigarros eletrônicos.
    - **Preferidas** - lista de notícias e vídeos mantidas no acesso do usuário.
    - **Login** - cadastro de informações do usuário.
- **News API** - plataforma que permite o acesso às notícias exibidas no site.
- **YoutubedataAPI** - plataforma que permite o acesso dos vídeos exibidos no site.
- **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 
### Hospedagem
O site utiliza a plataforma do Netlify como ambiente de hospedagem do site do projeto. O site é mantido no ambiente da URL: <https://quitvapingnow.netlify.app/>

A publicação do site no Netlify é feita por meio de uma submissão do projeto (push) via git para o repositório remoto que se encontra no endereço: 

[https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-uso-excessivo-de-cigarros-eletronicos](https://git.heroku.com/link_exemplo.git)
## Template do Site
O padrão de layout a ser utilizado pelo site tem correspondência ao projeto de Interface elaborado anteriormente, conforme Figura 1.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.009.png)

Figura  - Template do site

O template criado é composto pelos seguintes layouts: 

- Tela principal
- Conquistas e desafios
- Tela de visualização de vídeos e notícias
- Perfil de usuário
- Benefícios e malefícios
- Sobre

A responsividade segue o padrão do Bootstrap.


### Tela Principal
Tela que contabiliza o tempo, cigarros evitados e dinheiro economizado.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.021.png)

###
### Conquistas e desafios
Este layout é utilizado para exibição das conquistas e desafios dos usuários do site .

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.022.png)

###

### Tela de Visualização de Vídeos e Notícias
Local onde são exibidas as noticias e vídeos sobre o assunto pesquisado pelo usuário.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.023.png)


### Perfil de usuário
Local onde é exibido o perfil de cada um dos usuários, permitindo uma alteração .

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.024.png)
















### Benefícios e Malefícios
Tela que abrange todas as informações sobre o uso do cigarro eletrônico.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.025.png)
### Sobre
Tela que abrange todas as informações e objetivos do grupo de desenvolvedores do site.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.026.png)













## Funcionalidades do Sistema (Telas)
Nesta seção são apresentadas as telas desenvolvidas para cada uma das funcionalidades do sistema. O respectivo endereço (URL) e outras orientações de acesso são apresentadas na sequência.

###
### Entrega Sprint 1 - Visualização dos vídeos e notícias (RF-01,  RF-02 e RF-03)
Alunos responsável: Felipe Campolina

Link do código: [githubvideosenoticias](https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-uso-excessivo-de-cigarros-eletronicos/tree/master/codigo/Sobre_VideosNoticias)

A tela principal do sistema apresenta os vídeos e notícias de destaque nas principais páginas. As notícias e os vídeos são adquiridos de duas API diferentes, News API e Youtube data API . Um exemplo da tela é apresentado na figura abaixo.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.023.png)



###

### Entrega Sprint 2 - Visualizar informações acerca do tempo em que o usuário realizou o uso de cigarros durante a sessão (RF-04)
Alunos responsável: Felipe Campolina

Link do código: [githubhome](https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-uso-excessivo-de-cigarros-eletronicos/tree/master/codigo/Home_Conquistas) 

Funcionalidade para acompanhar o uso de cigarros do usuário, com intermédio de um formulário encontrado na mesma página, além de um sistema de recompensas e desafios, encontrado na página de “Conquistas e Desafios”.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.023.png)



###
###
###



###
### Entrega Sprint 2 - Visualizar os desafios e conquistas do usuário (RF-05 e RF-06)
Alunos responsável: Felipe Campolina

Link do código: [githubconquista](https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-uso-excessivo-de-cigarros-eletronicos/tree/master/codigo/Home_Conquistas)

Após completados os desafios, o sistema deve atualizar os pontos do usuário, e atingindo os pontos suficientes, será permitido a compra da medalha selecionada.
# ![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.027.png)

### Entrega Sprint 3 - Visualizar a página de perfil do usuário (RF-07)
Alunos responsável: Arthur Sgarbi Andrade

Link do código: [githubperfil](https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-uso-excessivo-de-cigarros-eletronicos/blob/master/codigo/Perfil/index.html)

Criado para especificar e salvar as informações do usuário, de forma que da próxima vez em que o usuário for utilizar o site, as informações permaneçam salvas.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.028.png)

### Entrega Sprint 1 - Cadastro de informações para o login (RF-08)
Alunos responsável: Arthur de Sá

Link do código: [githublogin](https://github.com/ICEI-PUC-Minas-PMGCC-TI/tiaw-pmg-cc-m-20221-uso-excessivo-de-cigarros-eletronicos/tree/master/codigo/P%C3%A1gina%20login)

Criado para cadastrar e salvar as informações dos usuários que irão utilizar o site para que seja possível realizar o login na próxima visita ao site.

![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.029.png)

#
#
#

#
# ![](Aspose.Words.998177d1-240d-44ff-80ad-4f3afa1f547a.030.png)














#
# Avaliação da Solução
O processo de realização dos testes da solução desenvolvida está documentado na seção que se segue e traz os planos de testes de software e de usabilidade, na sequência, o registro dos testes realizados.
## Plano de Testes de Software
Requisitos para realização do teste:

- Site publicado na Internet
- Navegador da Internet - Chrome, Firefox ou Edge
- Conectividade de Internet para acesso às plataformas (APIs)


Os testes funcionais a serem realizados no aplicativo são descritos a seguir.



|**Caso de Teste**|**CT-01 - Visualizar vídeos e notícias principais**|
| :-: | :- |
|**Requisitos Associados**|<p>RF-01 - O site deve apresentar na página principal vídeos e notícias e orientações obtidas por meio de notícias da Internet (API)</p><p>RF-02 - O site deve apresentar, para cada vídeo e notícia, uma imagem correspondente ao assunto apresentado (*thumbnail*)</p>|
|**Objetivo do Teste**|Verificar se a carga de notícias está acontecendo corretamente|
|**Passos**|<p>1) Acessar o Navegador</p><p>2) Informar o endereço do Site</p><p>3) Visualizar a página principal</p><p>4) Verificar o processo de carga </p>|
|**Critérios de Êxito**|<p>- Deve haver uma requisição AJAX no painel NETWORK das ferramentas do Desenvolvedor (recurso do Navegador).</p><p>- As notícias e os vídeos devem ser exibidos de forma simples e clara no site, sendo necessárias pelo menos 1 notícia e 1 vídeo sendo apresentados.</p><p>- As notícias devem trazer imagens visíveis associadas ao assunto da notícia. Os vídeos devem apresentar a tumbnail presente no youtube</p><p>- Teste realizado no VSCODE, devido ao um erro de conexão entre a NewsAPi e o servidor do netfily.</p>|


















|**Caso de Teste**|**CT-02 - Visualizar detalhes das notícias e dos vídeos**|
| :-: | :- |
|**Requisitos Associados**|RF-03 - O site deve permitir ao usuário visualizar o texto completo da notícia e reproduzir o vídeo completo com todos os detalhes da publicação.|
|**Objetivo do Teste**|Verificar se as notícias e vídeos estão funcionais na página de vídeos e notícias.|
|**Passos**|<p>1) Acessar o Navegador</p><p>2) Informar o endereço do Site</p><p>3) Visualizar a página principal</p><p>4) Clicar em uma notícia</p>|
|**Critérios de Êxito**|- A página deve apresentar o título e a imagem da notícia, no caso do vídeo, apenas a tumbnail, imagem de destaque, data, autor e o texto completo.|

















|**Caso de Teste**|**CT-03 - Visualizar informações acerca do tempo em que o usuário realizou o uso de cigarros durante a sessão.**|
| :-: | :- |
|**Requisitos Associados**|RF-04 - O site deve permitir ao usuário visualizar os minutos, horas, dias, meses e anos que não faz uso de cigarros. Assim como o uso de cigarros evitados durante a sessão e o dinheiro economizado.|
|**Objetivo do Teste**|Verificar se a página principal (home) está funcionando corretamente.|
|**Passos**|<p>1) Acessar o Navegador</p><p>2) Informar o endereço do Site</p><p>3) Visualizar a página principal</p><p>4) Verificar o funcionamento dos timers, e dos dados presentes.</p>|
|**Critérios de Êxito**|- A página deve apresentar o cronômetro funcionando corretamente, os dados devem ser atualizados à medida que o cronômetro contabiliza o tempo e o sistema de cálculo do dinheiro economizado deve agir de forma correta de acordo com o número de cigarros evitados.|















|**Caso de Teste**|**CT-04 - Visualizar os desafios e conquistas do usuário.**|
| :-: | :- |
|**Requisitos Associados**|<p>RF-05 - O site deve permitir ao usuário visualizar quais os desafios que devem ser completados.</p><p>RF-06 - O site deve disponibilizar ao usuário a compra das medalhas (conquistas) de acordo com os pontos realizados pelos desafios cumpridos.</p>|
|**Objetivo do Teste**|Verificar se a página de conquistas e desafios está funcionando corretamente.|
|**Passos**|<p>1) Acessar o Navegador</p><p>2) Informar o endereço do Site</p><p>3) Visualizar a página de conquistas e desafios</p><p>4) Verificar o funcionamento das marcações dos desafios e da compra das medalhas</p>|
|**Critérios de Êxito**|<p>- A página deve apresentar os desafios de forma visível.</p><p>- A página deve permitir a compra das medalhas de acordo com os desafios completados.</p><p>- Deve ser funcional a soma dos pontos de acordo com os desafios marcados.</p>|





##
##












|**Caso de Teste**|**CT-05 - Visualizar a página de perfil do usuário**|
| :-: | :- |
|**Requisitos Associados**|<p>RF-07 - O site deve permitir ao usuário visualizar o perfil do usuário com todos os seus dados.</p><p></p>|
|**Objetivo do Teste**|Verificar se os dados do usuários estão sendo salvos de forma correta.|
|**Passos**|<p>1) Acessar o Navegador</p><p>2) Informar o endereço do Site</p><p>3) Visualizar a página de perfil.</p><p>4) Verificar o funcionamento das informações salvas.</p>|
|**Critérios de Êxito**|<p>- A página deve apresentar os dados como: id, login, senha, nome e e-mail do usuário.</p><p>- A página deve salvar os dados do usuário.</p>|









|**Caso de Teste**|**CT-06 - Cadastro de informações para o login**|
| :-: | :- |
|**Requisitos Associados**|<p>RF-08 - O site deve permitir ao usuário que cadastre suas informações.</p><p></p>|
|**Objetivo do Teste**|Salvar os dados dos usuários para permitir que o login seja realizado.|
|**Passos**|<p>1) Acessar o Navegador</p><p>2) Informar o endereço do Site</p><p>3) Visualizar a página de login.</p><p>4) Verificar se as informações foram salvas.</p>|
|**Critérios de Êxito**|<p>- A página deve salvar os dados que o usuário forneceu.</p><p>- A página deve realizar o login com os dados do usuário.</p><p></p>|





##
## Registro de Testes de Software
Os resultados obtidos nos testes de software realizados são descritos na Tabela a seguir.



|**Visualizar vídeos e notícias principais**|Site apresenta vídeos e notícias com API. (Funcionamento ok)|
| :-: | :- |
|**Visualizar detalhes das notícias e dos vídeos**|<p>Textos das notícias e vídeos completos dentro da página. (Funcionamento ok)</p><p></p>|
|**Visualizar informações acerca do tempo em que o usuário realizou o uso de cigarros durante a sessão.**|Usuários conseguem visualizar e salvar todos os dados da página inicial. (Funcionamento ok)|
|**Visualizar os desafios e conquistas do usuário**|Usuários conseguem visualizar os desafios e marcar os pontos necessários para comprar as conquistas. (Funcionamento ok)|
|**Visualizar a página de perfil do usuário**|<p>Usuários conseguem visualizar o perfil de usuário com todos os dados salvos. (Funcionamento ok)</p><p></p>|
|**Cadastro de informações para o login**|Usuários conseguem cadastrar suas informações para login na próxima visita ao site. (Funcionamento ok)|
## Plano de Testes de Usabilidade

O planejamento dos testes de usabilidade a serem realizados com usuários são descritos na Tabela a seguir.


|<p></p><p>**Funcionamento do cadastro de login**</p>|O usuário deve conseguir cadastrar seus dados da maneira mais intuitiva possível.|
| :-: | :- |
|<p></p><p>**Cronômetro funcionando da maneira correta**</p>|O cronômetro deve contabilizar corretamente os anos, meses, dias, horas, minutos e segundos  e deve ser visível ao usuário.|
|<p></p><p>**Formulário funcionando corretamente** </p>|O formulário deve salvar as informações que o usuário forneceu, de forma que ele funcione juntamente com o cronômetro e os dados da página principal. |
|<p></p><p>**Vídeos e notícias devem apresentar corretamente os conteúdos com ajuda da API**</p>|A aba vídeos e notícias deve apresentar corretamente todos os dados do conteúdo exposto, são eles: foto, texto e vídeo completo. |
|<p></p><p>**O perfil do usuário deve apresentar todas as informações cedidas pelo usuário no cadastro do login**</p>|Devem permanecer salvas as informações do usuário na aba de perfil, juntamente com seu “id”.|



## Registro de Testes de Usabilidade

Os resultados obtidos nos testes de usabilidade realizados são descritos na Tabela a seguir.




|<p></p><p>**Números de pessoas que testaram o site**</p>|Três pessoas.|
| :-: | :- |
|<p></p><p>**Detalhamento dos testes**</p>|De acordo com as pessoas que utilizaram, o site se manteve funcional e trabalhando da maneira esperada.|
|<p></p><p>**Problemas encontrados**</p>|<p>- Em alguns momentos, foram identificados erros de carregamentos nas páginas.</p><p>- O problema foi identificado e resolvido pela equipe.</p>|

#
#
#
#
#
#
#
#
#
#
#




# Referências Bibliográficas
- Littlefield, A. **Guia da metodologia ágil e scrum para iniciantes**. 2016. Disponível em: <https://blog.trello.com/br/scrum-metodologia-agil>. Acessado em 15/04/2022.
- DA SILVA MACHADO BARRADAS, A.; OLIVEIRA SOARES, T.; BRANCO MARINHO, A.; SOUSA DOS SANTOS, R. G.; IZIDIA ARAÚJO DA SILVA, L. **Os riscos do uso do cigarro eletrônico entre os jovens** . Global Clinical Research Journal, [S. l.], v. 1, n. 1, p. e8, 2021. DOI: 10.5935/2763-8847.20210008. Disponível em: https://www.globalclinicalresearchj.com/index.php/globclinres/article/view/15. Acesso em: 16 abr. 2022.
- Knorst, Marli Maria et al. **The electronic cigarette: the new cigarette of the 21st century?**\* \* Study carried out under the auspices of the Graduate Program in Pulmonology, Federal University of Rio Grande do Sul, and at the Porto Alegre Hospital de Clínicas, Porto Alegre, Brazil . Jornal Brasileiro de Pneumologia [online]. 2014, v. 40, n. 5 [Acessado 16 Abril 2022] , pp. 564-572. Disponível em: <https://doi.org/10.1590/S1806-37132014000500013>. ISSN 1806-3756. https://doi.org/10.1590/S1806-37132014000500013.

