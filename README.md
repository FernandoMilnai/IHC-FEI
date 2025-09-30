# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado **Mapeamento de trajetos e fluxo de pessoas com base em dados processados de rastreamento multicâmera** sob orientação do Professor **Ricardo de Carvalho Destro** e desenvolvido pelos seguintes alunos:

- Fernando Milani Venerando RA:24.122.063-1
- Lucas Rezende Simões RA: 24.122.028-4

## Resumo
Um software capaz de apresentarum relatório contendo trajeto e fluxo dos indivíduos, processando dados obtidos por câmeras de segurança

## Introdução
Análise de dados de fluxo de indiíduos, focando no uso das dependências dos metrôs de São Paulo, mas podendo ser usado por outras instituições de transporte

- Problemas ou necessidades que o produto ou serviço resolve ou satisfaz:

A falta de ferramentas de análise de fluxo para gerenciamento e manutenções possíveis

- Liste as características e funcionalidades do seu produto ou serviço de forma detalhada.
1. Adicionar ou receber diretamente dados das câmeras de segurança da instituição correspondente
2. Processar os dados, mapeando rotas e fluxo
3. Lidar com possíveis discrepâncias dos dados previamente recebidos
4. Exibição de estatísticas e resultados dos dados obtidos

Futuramente seria implementado interfaces diferentes para determinados usos, como procura de indivíduos por aparência e uma focada em análise de estatísticas da instituição, focada para a área de engenharia civil.
1. Receber dados de aparência de indivíduos e perquisar rotas correspondentes
2. Exibir mais informações e gráficos (Picos de uso por hora, estações mais frequentadas, etc) 
 
- Liste as tecnologias e ferramentas computacionais que pretendem usar neste projeto (TCC).
1. Banco de dados/ SLQ
2. Python
3. HTML/ CSS/ JS

- Apresente o contexto de uso dessa aplicação. (“Usuários, tarefas, equipamentos (hardware, software e materiais) e o ambiente físico e social no qual um produto é usado.”)

Uso focado nas dependências do metrô de São Paulo, mas podendo ser usado por qualquer instituição que lide com grandes quantias de transporte ou fluxo de indivíduos em um ambiente vigiado. Pode ser acessado por funcionários qualificados para análise através de um computador da empresa.

## Publico Alvo

- Determine qual o grupo específico de pessoas ou organizações para as quais este produto ou serviço é direcionado.

Uso focado nas dependências do metrô de São Paulo, mas podendo ser usado por qualquer instituição que lide com grandes quantias de transporte ou fluxo de indivíduos em um ambiente vigiado.

- Descreva as caracteristicas demográficas, comportamentais, psicográficas ou geográficas deste público alvo que o torna mais propenso a se interessar pelo que está sendo oferecido neste projeto ou serviço.

Tais instituições podem encontrar dificuldades com tomada de decisões devido ao elevado número de pessoas sem rastreamento.

## Análise de concorrência
1. Identifique os principais concorrentes ou softwares mais utilizados pelo seu público-alvo.

Baseado em análises recentes, os nomes mais relevantes no mercado de dashboards e BI são Microsoft Power BI e Google Looker Studio

2. Colete informações sobre os concorrentes selecionados.

PoerBI integra ao ecossistema Microsoft como Excel e Teams, tem versões gratúitas e pagas. Google Looker é gratuito, com integração nativa aos produtos Google como Analytics, Ads, Sheets e Wikipédia, também tem versão Pro com controle mais estruturado e suporte corporativo

Power BI:
<img width="1024" height="574" alt="image" src="https://github.com/user-attachments/assets/3d4ca187-4705-4a71-9f55-7f48a48943fa" />


Google Analytics:
<img width="1024" height="574" alt="image" src="https://cdn.shopify.com/s/files/1/0070/7032/files/realtimeoverview.png?v=1746317946" />


3. Analise as características e funcionalidades dos concorrentes.

Marcantes pela variedade de funcionalidades, versátil para diferenes aplicações e possível integração com outras plataformas
   
4. Avalie a experiência do usuário (UX).

As principais críticas ao PowerBI são referentes à falta de responsividade automática de atualização dos gráficos e dificuldade de cancelar planos. Mas muito elogiado pela versatilidade de uso.
<img width="945" height="403" alt="image" src="https://github.com/user-attachments/assets/1e41c3b6-6e2c-41f9-a06a-5f399660b9b9" />

As principais críticas ao  Google Analytics é pelas utilidades limitadas comparado ao PowerBI e lógica mais complexa. Mas elogiado pela fácil integração com outros sistemas Google e acesso gratuito à nuvem.
<img width="816" height="777" alt="image" src="https://github.com/user-attachments/assets/45d2c31e-4cde-419c-9235-d0779495cefa" />

  
5. Examine os preços e modelos de negócio.

O Power BI tem uma versão gratuita e versões Pro por R$93,50/mês e Premium R$160,30/mês, e Google Analytics é gratuito.

6. Pesquisa de satisfação do cliente e opiniões.

Power BI, Tableau e Looker Studio são amplamente elogiados por usabilidade e visual moderno


7. Identifique padrões e tendências no mercado.

Tanto o Power BI quanto o Google Analytics têm acompanhado uma forte tendência de **automação na análise de dados**, **visualização interativa** e **integração com múltiplas fontes**. O mercado mostra uma preferência crescente por soluções que:

- Permitirem **monitoramento em tempo real**
- Apresentem **gráficos intuitivos** com foco na **tomada de decisão rápida**
- Se integrem com **plataformas corporativas** (Microsoft 365, Google Workspace, etc)
- Suportem **análise preditiva** e **reconhecimento de padrões**, como sazonalidades de fluxo, horários de pico e variações de comportamento de usuários.

Os usuários valorizam ferramentas com **experiência amigável**, **baixo tempo de resposta** e **mobilidade**, como dashboards acessíveis via web e mobile.


8. Elabore relatórios e sumarize os resultados.


9. Extraia pontos positivos e faça recomendações.

### Pontos positivos identificados:

- **Power BI**
  - Alta integração com sistemas corporativos
  - Visualizações ricas e personalizáveis
  - Análises preditivas com suporte de IA
  - Capacidade de combinar diversas fontes de dados.

- **Google Analytics**
  - Forte integração com o ecossistema Google
  - Ideal para rastreamento de comportamento em ambientes web
  - Relatórios em tempo real e eventos personalizados
  - Gratuito e acessível para todos os níveis de usuários.
 
 ### Pontos negativos identificados:
- **Power BI**
  - Falta de responsividade automática
  - Dificuldade em lidar com contas pagas

- **Google Analytics**
  - Uso não muito intuitivo, tornando
  - Sem muita variedade de gráficos

### Recomendações:

- **Utilizar Power BI para análises internas e operacionais** (como fluxo físico nas estações, comportamento por faixa horária).
- **Utilizar Google Analytics para compreender o comportamento dos usuários na aplicação web**, identificando quais funcionalidades são mais acessadas.
- **Integrar ambas as ferramentas** quando possível, para uma visão mais completa (online + offline).
- Criar **dashboards personalizados para diferentes personas** (analistas, engenheiros, segurança pública), focando nas informações mais relevantes para cada função.
- Garantir que os relatórios estejam alinhados com a LGPD, mantendo privacidade e segurança dos dados pessoais.


### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?

## Persona primária 1:
- **Nome**: Roberto Carlos, 25 anos  
- **Profissão**: Analista de Dados  
Roberto Carlos se formou em Ciência da Computação em uma universidade pública de São Paulo e rapidamente se destacou no estágio na CPTM, sendo contratado como analista.  
Ele trabalha com análise de dados operacionais, utilizando informações vindas das câmeras para otimizar o funcionamento das estações. É curioso, autodidata, e sempre busca formas de automatizar relatórios e criar insights com dados reais.

<img width="936" height="908" alt="image" src="https://github.com/user-attachments/assets/8ff8027b-74d1-46b8-9438-cfed5dd6840e" />

---

## Persona primária 2:
- **Nome**: Erasmo Carlos, 32 anos  
- **Profissão**: Engenheiro Civil  
Erasmo trabalha na Secretaria Municipal de Infraestrutura de São Paulo e está envolvido em projetos de mobilidade urbana. Tem a missão de propor a expansão da malha metroviária com base em dados técnicos e sociais.  
Ele utiliza o software para embasar decisões com evidências, analisando horários de pico, fluxo de passageiros e regiões mais movimentadas. Tem experiência com leitura de mapas técnicos, geoprocessamento e espera agilidade no acesso às informações.
<img width="935" height="911" alt="image" src="https://github.com/user-attachments/assets/7abbe888-bc42-4227-80c5-187561c47933" />

---

## Persona primária 3:
- **Nome**: Fiuk Carlos, 43 anos  
- **Profissão**: Policial Civil – Setor de Pessoas Desaparecidas  
Fiuk é investigador da polícia civil há mais de 15 anos e atua especificamente em casos de desaparecimento. Muitas vezes precisa analisar rapidamente o último paradeiro de uma pessoa com base em imagens e dados de movimentação.  
Com acesso restrito à interface policial do sistema, ele busca registros de entrada e saída nas estações, comparações com imagens de câmeras e possíveis padrões de deslocamento. Valoriza rapidez, clareza e segurança da informação.

<img width="939" height="909" alt="image" src="https://github.com/user-attachments/assets/c0dbfda6-f0a9-404f-9f17-73a889db9686" />

---

## Persona secundária:
- **Nome**: Carlos Alberto de Nóbrega Carlos, 20 anos  
- **Profissão**: Estudante de Ciência da Computação  
Carlos é aluno de uma universidade federal e está em seu segundo ano do curso. Participa de um projeto de iniciação científica que estuda algoritmos preditivos aplicados à mobilidade urbana.  
Ele vê no sistema uma fonte rica de dados para testar seus modelos, criar visualizações e entender padrões reais. Está aprendendo a lidar com grandes volumes de dados, APIs e conceitos de ciência de dados aplicada ao setor público.

<img width="933" height="915" alt="image" src="https://github.com/user-attachments/assets/98ab1eba-e3b6-4b5f-8ccd-c488242b8ded" />


### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou poduto.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou poduto?
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?

### Mapa de empatia:
Pessoa primária: Roberto Carlos.
- Encontra-se num escritório convecional, normalmente se encontra com colegas de trabalho e diariamente utiliza o computador para trabalhar.
- Normalmente sons de teclados e ocasionalmente conversas entre colegas de trabalho e ocasionalmente tutoriais de SQL no Youtube
- Ele analisa dados e estatísticas recebidas e fornecidas pelo sofware, podendo reportar dados de análise de interesse aos seus superiores em um relatório.
- Ele espera conseguir usar a aplicação sem travamentos e de forma intuitiva.
- Estresse com o tratamento de discrepâncias em dias muito movimentados.
- O produto auxilia-o em seu trabalho ao simplificar as estastísticas, organizando-as para que ele não precise fazer isso manualmente.


Pessoa Secundária: Carlos Alberto de Nobrega Carlos
- Encontra-se em um laboratório da faculdade, normalmente vê colegas e professores da faculdade, utiliza diariamente um computador para trabalhar em seu projeto.
- Conversas de alunos e professores e notificações de seu orientador.
- Ele adquiri a base de dados para testar em seu projeto, gerando ocasionalmente dados aleatórios.
- Ele espera conseguir dados diferentes e realistas do produto.
- Discrepâncias e casos mal adaptados para a situação dele.
- Dados gerados de forma rápida intuitiva, e acessível.

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
   - Um ambiente de escritório convencional.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
   - LGPD
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
   - Cumprimento dos requisitos recomendados para a execução do programa.
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?
  - Durante o uso do software na jornada de trabalho comum do analista, é acessado por seu PC, e além de verificar possiveis discrepanceas nos dados, pode receber e responder por informações solicitadas por seus superiores

## Jornada do usuário

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?


### Jornada Roberto Carlos:
1. Na sua jornada de trabalho comum como analista de dados pela CPTM, ele comaça abrindo o software em seu PC no escritório
2. Nas primeiras horas de trabalho, monitorava possiveis discrepancias dos dados recebidos do Banco de Dados da instituição
3. Recebeu solicitações via e-mail de seu superior pedindo um arquivo .CVS contendo apenas informações da estação da Liberdade entre 08:00 e 12:00 do dia 20/05/2025
4. Selecionou a estação "Liberdade" no combobox de estações, definiu horário inicial e final no input de hora e definiu o dia no input de data.
5. Clicou em "Pesquisar" o terminal do programa exibiu o resultado desejado
6. Roberto clicou no botão de "Exportar", salvando o arquivo em sua área de trabalho
7. Enviou o arquivo solicitado ao seu superior
8. Voltou a monitorar discrepancias, até que recebeu o mais novo relatório do software sobre individuos com falhas de detecção no trajeto
9. Abriu o relaório exibindo os trajetos num grafo e corrigiu as falhas possíveis.
10. Reportou o relatório e suas correções ao grupo de TI para melhorias de detecção de dados futuros
11. Fim do expediente.
12. Fechou o software.
 
### Jornada Erasmo Carlos:
1. Erasmo foi contratado pela prefeitura de SP para planejar uma reforma em conexões do metrô de São Paulo e a construção de uma nova linha metroviária
2. ⁠Lhe foi concedido acesso ao software para melhor análise de estatística reais obtidas pela instituição
3. ⁠Abrindo o software e logando com o acesso que lhe foi dado, pode visualizar gráficos e estatísticas sobre estações e horários na qual ocorrem maior fluxo de instituição
4. ⁠Assim auxiliando-o no planejamento da construção de uma nova linha e sabendo quais estações não seriam prejudicadas ao serem interditadas por alguns dias para a reforma
5. Após finalizar o planejamento, informou a prefeitura. Perdendo seu acesso ao software
 
### Jornada Fiuk Carlos:
1. Fiuk trabalha no setor investigativo  da polícia. E no seu último caso, foi encarregado de encontrar Ayrton Senna, um jovem desaparecido há 2 dias. A última informação que se tem sobre ele, é que foi visto entrando no metro de São Paulo com uma camiseta amarela
2. ⁠Fiuk solicitou à instituição do Metro uma procura por essas características.
3. ⁠Um analista (Roberto Carlos) recebeu essa solicitação e usou o software para buscar registros com estas características fornecidas por Fiuk na solicitação.
4. ⁠No informativo de busca por aparência selecionou, gênero: masculino, roupa: vermelha, Idade: 15-25. Selecionou “Pesquisar” e o resultado foi exibido no terminal. Ayrton foi avistado no dia 20/08/2025 as 13:42 entrando na praça da Sé, e saindo as 15:09 saindo na Liberdade, mostrando todo seu trajeto num grafo e imagens de suas aparições.
5. ⁠Clicando no botão “Exportar” todas as informações fornecidas foram salvas num arquivo, no qual Roberto Carlos enviou para Fiuk Carlos
6. ⁠Agora com as informações, Fiuk pode prosseguir com sua busca pelo jovem Ayrton

<!--
## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
 -->

## Cenário de Análise/Problema

Cenário Roberto Carlos:
- Cenário
  - Roberto Carlos, 25 anos, analista de dados da CPTM, precisa analisar grandes quantidades de informações coletadas pelas câmeras das estações. No entanto, o sistema que ele utiliza para acessar esses dados é pouco intuitivo: os relatórios são gerados em formatos confusos, com informações desorganizadas e difíceis de cruzar. Isso faz com que Roberto perca muito tempo reorganizando planilhas manualmente, além de correr o risco de cometer erros durante a análise. Essa limitação o frustra, já que ele gosta de automatizar processos e gerar insights mais rápidos e assertivos.
- Refinamento
  - 1: Quanto tempo ele gasta organizando os relatórios manualmente?
  - 2: Esse retrabalho impacta prazos ou a qualidade das análises que entrega?
  - 3: O sistema atual tem suporte para integração com outras ferramentas que ele domina?
  - 4: Como ele se sente em relação à diferença entre o potencial que poderia alcançar e as limitações do sistema?
  - 5: Quem fornece as informações para ele?
  - 6: Em que situações o cenário ocorre?
  - 7: Por que ele precisa alcançar o objetivo?
  - 8: De quais conhecimentos ele precisa para realizar este objetivo?
  - 9: Quais informações são usadas para concluir o objetivo?
  - 10: Quais dispositivos e recursos são necessários para concluir o objetivo?
- Refinamento do cenário
  - Roberto Carlos, 25 anos, analista de dados na CPTM, dedica parte significativa do seu tempo a analisar informações provenientes das câmeras de monitoramento das estações[9], a fim de cobrir sua cota diária[7]. O sistema atual, porém, gera constantemente[6] relatórios fragmentados, em formatos pouco flexíveis e sem integração com outras ferramentas de análise[3]. Por isso, Roberto precisa exportar manualmente os arquivos fornecidos por seu chefe[5], reorganizá-los em planilhas em seu computador[10] e só então conseguir aplicar suas técnicas de análise e automação[8]. Esse retrabalho consome em média 2 a 3 horas do seu expediente diário[1], reduzindo o tempo disponível para gerar insights estratégicos[2]. Roberto se sente limitado, pois sabe que poderia entregar resultados mais inovadores se tivesse acesso a dados organizados e a uma interface mais eficiente[4].

Cenário Erasmo Carlos:
- Cenário
  - Erasmo Carlos, 32 anos, Engenheiro civil da Secretaria Municipal de São Paulo e está trabalhando principalmente em projetos de mobilidade urbana, envolvendo as instalações públicas da cidade de São Paulo. Entre estes projetos, Erasmo se encontra com a missão de propor a expansão da malha metroviária, e para isso, ele precisa de dados técnicos e sociais como fluxo de passageiros, horários de pico e regiões de maior movimento. Apesar de atualmente conseguir tais dados, Erasmo se encontra estressado por precisar gastar de 3 a 4 horas apenas para realizar tais pesquisas, visto que existem poucas ferramentas capazes de auxiliá-lo na coleta de dados.
- Refinamento
  - 1: Em que situações o cenário ocorre?
  - 2: Por que ele precisa alcançar este objetivo?
  - 3: Quais informações são usadas para concluir o objetivo?
  - 4: Como ele se sente em relação à diferença entre o potencial que poderia alcançar e as limitações do sistema?
  - 5: Quanto tempo ele gasta realizando as pesquisas manualmente?
  - 6: Que pressões existem para o alcance do objetivo?
  - 7: Como ele alcança o objetivo atualmente?
  - 8: Qual é a função do dele?
  - 9: Quem depende do alcance do objetivo?
  - 10: Quem fornece as informações necessárias para alcançar o objetivo
- Refinamento do cenário
  - Erasmo Carlos, 32 anos, Engenheiro civil da Secretaria Municipal de São Paulo[8][9] e está trabalhando principalmente em projetos de mobilidade urbana, envolvendo as instalações públicas da cidade de São Paulo[1]. Entre estes projetos, Erasmo se encontra com a missão de propor a expansão da malha metroviária[2] até o próximo mês[6], e para isso, ele precisa de dados técnicos e sociais como fluxo de passageiros, horários de pico e regiões de maior movimento[3]. Apesar de atualmente conseguir tais dados por relatórios de passagem das catracas e câmeras de segurança das vias metroviárias[7][10], Erasmo se encontra estressado[4] por precisar gastar de 3 a 4 horas apenas para realizar tais pesquisas[5], visto que existem poucas ferramentas capazes de auxiliá-lo na coleta de dados.
 
## Análise de tarefas

### Funcionalidades:
- Criação de grafo do ambiente
- Pesquisa de dados
- Análise de discrepâncias
- Conexão com base de dados


### HTAs:
Criação de grafo do ambiente

Descrição: Permite ao usuário importar ou criar o mapa de câmeras onde o programa realizrá as análises.

![HTA Func 1](https://github.com/user-attachments/assets/d3ae1505-47ac-492d-9ed0-06f48b5367dc)

Pesquisa de dados

Descrição: Permite ao usuário filtrar os resultados do programa por meio de botões ou querries de SQL

![HTA Func 2](https://github.com/user-attachments/assets/217d335a-d2b7-495a-856c-c02341367b56)


Análise de discrepâncias

Descrição: Apresenta ao usuário um relatório com as discrepâncias detectadas para que este as resolva.

![HTA Func 3](https://github.com/user-attachments/assets/039b4ea0-ec3d-4650-aa0a-d6b64b102522)


Conexão com base de dados

Descrição: Permite ao usuário importar e exportar uma base de dados via arquivo ou conectar o programa a um banco de dados externo.

![HTA Func 4](https://github.com/user-attachments/assets/235e537e-5957-4cda-b878-3d0bf1ab91cf)

### GOMS

Criação de grafo do ambiente
- GOAL 0: Gerar um grafo direcionado.
  - METHOD 0.A: Criar grafo a partir de arquivo
  - (SEL. RULE: Existência de um arquivo contendo os dados do grafo a ser gerado)
    - OP 0.A.1: Selecionar opção de abrir arquivo
    - OP 0.A.2: Selecionar arquivo
  - METHOD 0.B: Criar grafo a partir do usuário
  - (SEL. RULE: Preferência do usuário)
    - OP 0.B.1: Selecionar opção de criar novo mapa
    - METHOD 0.B.2: Adicionar vértice
      - OP 0.B.2.A: Pressionar o botão esquerdo do mouse na área vazia do editor
    - METHOD 0.B.3: Remover vértice
      - OP 0.B.3.A: Pressionar o botão esquerdo do mouse em um vérice já criado
    - METHOD 0.B.4: Conectar vértices
      - OP 0.B.4.A: Pressionar o botão direito do mouse em um vérice já criado
      - OP 0.B.4.B: Pressionar o botão esquerdo do mouse em um vérice diferente do anterior
    - METHOD 0.B.5: Definir vértice de entrada
      - OP 0.B.5.A: Pressionar o botão do meio do mouse em um vérice já criado
       
Pesquisa de dados
- GOAL 0: Encontrar uma série de dados desejada pelo usuário
- (SEL. RULE: Banco de dados já carregado)
  - METHOD 0.A: Buscar dados por SQL
  - (SEL. RULE: Preferência do usuário)
    - OP 0.A.1: Digitar código SQL na caixa de texto
    - OP 0.A.2: Clicar no botão de buscar logo abaixo da caixa de texto
  - METHOD 0.B: Buscar dados por botões
  - (SEL. RULE: Praticidade)
    - METHOD 0.B.1: Buscar por hash
    - (SEL. RULE: Preferência)
      - OP 0.B.1.A: Inserir o id da hash na caixa de texto correspondente
      - OP 0.B.1.B: Selecionar o botão correspondente para buscar
    - METHOD 0.B.2: Buscar por câmera
    - (SEL. RULE: Preferência)
      - OP 0.B.2.A: Inserir o id da câmera na caixa de texto correnspondente
      - OP 0.B.2.B: Selecionar o botão correspondente para buscar
    - METHOD 0.B.3: Buscar por tempo
    - (SEL. RULE: Preferência)
      - OP 0.B.3.A: Inserir os valores do período de tempo desejado na caixa de texto correspondente
      - OP 0.B.3.B: Selecionar o botão correspondente para buscar
    - METHOD 0.B.4: Buscar por linha
    - (SEL. RULE: Preferência)
      - OP 0.B.4.A: Inserir o id da linha na caixa de texto correspondente
      - OP 0.B.4.B: Selecionar o botão correspondente para buscar

Análise de discrepâncias
- GOAL 0: Corrigir discrepâncias identificadas
- (SEL. RULE: Banco de dados já carregado)
  - GOAL 1: Identificar discrepâncias corrigíveis
  - (SEL. RULE: Usuário com relatório de discrepâncias)
    - METHOD 1.A: Identificar aparecimento inconsistente
      - OP 1.A.1: O usuário seleciona a hash que apareceu em uma câmera inválida
      - OP 1.A.2: O usuário seleciona esta hash em uma câmera válida
      - OP 1.A.3: O usuário seleciona as câmeras percorridas por aquela hash no grafo
      - OP 1.A.4: O usuário confirma as mudanças em um menu pop-up
    - METHOD 1.B: Relatar impossibilidade
      - OP 1.B.1: O usuário seleciona a hash
      - OP 1.B.2: O usuário seleciona a opção de hash irrastreável em um menu pop-up
      - OP 1.A.1: O usuário confirma a mudança no menu pop-up
   - GOAL 2: Corrigir discrepâncias
   - (SET. RULE: Discrepâncias já selecionadas)
     - 

## Prototipação
 
## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->
