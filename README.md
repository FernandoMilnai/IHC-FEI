# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado **Mapeamento de trajetos e fluxo de pessoas com base em dados processados de rastreamento multicâmera** sob orientação do Professor **Ricardo de Carvalho Destro** e desenvolvido pelos seguintes alunos:

- Fernando Milani Venerando
- Lucas Rezende Simões

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

<img width="1024" height="574" alt="image" src="https://blog.dsacademy.com.br/wp-content/uploads/2022/02/Qual-a-Diferenca-Entre-Analista-de-Dados-e-Cientista-de-Dados.jpeg" />

---

## Persona primária 2:
- **Nome**: Erasmo Carlos, 32 anos  
- **Profissão**: Engenheiro Civil  
Erasmo trabalha na Secretaria Municipal de Infraestrutura de São Paulo e está envolvido em projetos de mobilidade urbana. Tem a missão de propor a expansão da malha metroviária com base em dados técnicos e sociais.  
Ele utiliza o software para embasar decisões com evidências, analisando horários de pico, fluxo de passageiros e regiões mais movimentadas. Tem experiência com leitura de mapas técnicos, geoprocessamento e espera agilidade no acesso às informações.

<img width="1024" height="574" alt="image" src="https://media.istockphoto.com/id/1428349031/pt/foto/handsome-engineer.jpg?s=612x612&w=is&k=20&c=6fwjIEzOAPNddRvj7pVPpMhunMgR2iniC_LLrOmFEfA=" />

---

## Persona primária 3:
- **Nome**: Fiuk Carlos, 43 anos  
- **Profissão**: Policial Civil – Setor de Pessoas Desaparecidas  
Fiuk é investigador da polícia civil há mais de 15 anos e atua especificamente em casos de desaparecimento. Muitas vezes precisa analisar rapidamente o último paradeiro de uma pessoa com base em imagens e dados de movimentação.  
Com acesso restrito à interface policial do sistema, ele busca registros de entrada e saída nas estações, comparações com imagens de câmeras e possíveis padrões de deslocamento. Valoriza rapidez, clareza e segurança da informação.

<img width="1024" height="574" alt="image" src="https://media.istockphoto.com/id/1347645338/pt/foto/police-detective-on-a-dark-background-a-policeman-at-work-tough-cop-fake-badge.jpg?s=1024x1024&w=is&k=20&c=Y754vE4HhhrIxgMAUpWOvDr-NOc6LsEyemcOILHsZ3I=" />

---

## Persona secundária:
- **Nome**: Carlos Alberto de Nóbrega Carlos, 20 anos  
- **Profissão**: Estudante de Ciência da Computação  
Carlos é aluno de uma universidade federal e está em seu segundo ano do curso. Participa de um projeto de iniciação científica que estuda algoritmos preditivos aplicados à mobilidade urbana.  
Ele vê no sistema uma fonte rica de dados para testar seus modelos, criar visualizações e entender padrões reais. Está aprendendo a lidar com grandes volumes de dados, APIs e conceitos de ciência de dados aplicada ao setor público.

<img width="1024" height="574" alt="image" src="https://media.gettyimages.com/id/1182479258/pt/foto/an-african-american-university-student-studying-in-the-library-stock-photo.jpg?s=612x612&w=gi&k=20&c=4a36lnsy5t-M2Uro3UwgqlTEzNuSIjGoRrN_NPIOryU=" />



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
- Pessoa primária: Roberto Carlos.
- Encontra-se num escritório convecional, normalmente se encontra com colegas de trabalho e diariamente utiliza o computador para trabalhar.
- Normalmente sons de teclados e ocasionalmente conversas entre colegas de trabalho e ocasionalmente tutoriais de SQL no Youtube
- Ele analisa dados e estatísticas recebidas e fornecidas pelo sofware, podendo reportar dados de análise de interesse aos seus superiores em um relatório.
- Ele espera conseguir usar a aplicação sem travamentos e de forma intuitiva.
- Estresse com o tratamento de discrepâncias em dias muito movimentados.
- O produto auxilia-o em seu trabalho ao simplificar as estastísticas, organizando-as para que ele não precise fazer isso manualmente.


- Pessoa Secundária: Carlos Alberto de Nobrega Carlos
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


<!--
## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
 -->
 
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
