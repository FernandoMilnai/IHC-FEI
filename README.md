# Projeto de Interface Humano-Computador

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interface Humano-Computador (CC8122) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

Este projeto se baseia no Trabalho de Conclusão de Curso (TCC) entitulado **Mapeamento de trajetos e fluxo de pessoas com base em dados processados de rastreamento multicâmera** sob orientação do Professor **Ricardo de Carvalho Destro** e desenvolvido pelos seguintes alunos:

- Fernando Milani Venerando
- Lucas Rezende Simões

## Resumo
Apresente uma breve descrição da sua aplicação ou produto.

Um software capaz de apresentarum relatório contendo trajeto e fluxo dos indivíduos, processando dados obtidos por câmeras de segurança

## Introdução
 
- Apresente o propósito do produto ou serviço e quais são os principais benefícios que ele oferece aos usuários.]

Análise de dados de fluxo de indiíduos, focando no uso das dependências dos metrôs de São Paulo, mas podendo ser usado por outras instituições de transporte

- Identifique os problemas ou necessidades que o produto ou serviço resolve ou satisfaz.

A falta de ferramentas de análise de fluxo para gerenciamento e manutenções possíveis

- Liste as características e funcionalidades do seu produto ou serviço de forma detalhada.
1. Adicionar ou receber diretamente dados das câmeras de segurança da instituição correspondente
2. Processar os dados, mapeando rotas e fluxo
3. Lidar com possíveis discrepâncias dos dados previamente recebidos
4. Exibição de estatísticas e resultados dos dados obtidos
 
- Liste as tecnologias e ferramentas computacionais que pretendem usar neste projeto (TCC).
1. Banco de dados
2. Python

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

3. Analise as características e funcionalidades dos concorrentes.

Marcantes pela variedade de funcionalidades, versátil para diferenes aplicações e possível integração com outras plataformas
   
4. Avalie a experiência do usuário (UX).

ok
  
5. Examine os preços e modelos de negócio.

O Power BI tem uma versão gratuita e versãoes Pro por R$93,50/mês e Premium R$160,30/mês

6. Pesquisa de satisfação do cliente e opiniões.

Power BI, Tableau e Looker Studio são amplamente elogiados por usabilidade e visual moderno


7. Identifique padrões e tendências no mercado.



11. Elabore relatórios e sumarize os resultados.
12. Extraia pontos positivos e faça recomendações.

Dashboards

### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?

  - Persona primaira ...
  - Persona secundária ...
  - Outras personas ...

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

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?

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
