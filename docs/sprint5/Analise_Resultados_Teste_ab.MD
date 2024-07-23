# Análise Final dos Resultados do Teste A/B
## Sumário
1. [Introdução](#1-introdução)
    1. [Propósito do Teste A/B](#11-propósito-do-teste-ab)
    2. [Metas do Teste](#12-metas-do-teste)
    3. [Estrutura do Teste](#13-estrutura-do-teste)
        1. [Reposicionamento da Explicação sobre o Curso](#131-reposicionamento-da-explicação-sobre-o-curso)
        2. [Reescrita do Título do Formulário](#132-reescrita-do-título-do-formulário)
        3. [Reescrita da Descrição do Botão do Formulário](#133-reescrita-da-descrição-do-botão-do-formulário)
        4. [Reescrita da Descrição do Botão de Whatsapp](#134-reescrita-da-descrição-do-botão-de-whatsapp)
        5. [Comparação das páginas](#135-comparação-das-páginas)
2. [Dados Acumulados](#2-dados-acumulados)
    1. [Dados Coletados, quantitativos](#21-dados-coletados-quantitativos)
        1. [Grupo 5](#grupo-5)
        2. [Página A](#página-a)
    2. [Dados Qualitativos](#22-dados-qualitativos)
    3. [Informações dos dados](#23-informações-dos-dados)
3. [Metodologia de Análise](#3-metodologia-de-análise)
    1. [Ferramentas Utilizadas](#31-ferramentas-utilizadas)
    2. [Técnicas Estatísticas](#32-técnicas-estatísticas)
    3. [Contribuição das Metodologias para os Insights](#33-contribuição-das-metodologias-para-os-insights)
    4. [Notebook](#34-notebook)
4. [Resultados e Observações](#4-resultados-e-observações)
    1. [Exploração de Tendências](#41-exploração-de-tendências)
    2. [Detecção de Anomalias](#42-detecção-de-anomalias)
    3. [Padrões Observados](#43-padrões-observados)
    4. [Vinculação aos Resultados Esperados](#44-vinculação-aos-resultados-esperados)
    5. [Confirmação ou Refutação das Hipóteses](#45-confirmação-ou-refutação-das-hipóteses)


## 1. Introdução

### 1.1 Propósito do Teste A/B
O teste A/B foi realizado para avaliar o impacto de diversas mudanças na landing page do Wizard On, visando melhorar a percepção de valor do curso e aumentar a taxa de conversão, mantendo a identidade visual da marca e agregando ao design existente da página. O teste foi dividido em cinco variações, dentre os 5 diferentes grupos, cada uma com uma mudança específica na arquitetura de informação, design de interface e redação estratégica. O objetivo era identificar quais mudanças resultariam em um aumento significativo na taxa de conversão e engajamento dos visitantes. Assim, abaixo iremos relembrar como foi essa variação para o nosso grupo.

### 1.2 Metas do Teste
- Aumento da percepção de valor entre os visitantes.
- Maior taxa de conversão.

### 1.3 Período do teste
A página experimental esteve no ar de 06 de junho de 2024 a 16 de junho de 2024. Os dados sobre a evolução do teste foram recebidos diariamente e foram extraídos pelo Looker.

### 1.4 Estrutura do Teste

#### 1.4.1 Reposicionamento da Explicação sobre o Curso
- **Justificativa:** Muitos usuários não exploram a página completamente e perdem informações importantes sobre o curso. A landing page focada nos diferenciais do Wizard On fornece informações sobre o que torna o curso único.
- **Objetivo:** Aumentar a percepção de valor entre os visitantes, resultando em uma maior taxa de conversão.
- **Classificação:**
  - Arquitetura de Informação: realocação da explicação sobre o curso para a parte superior da landing page.
  - Design de Interface: mudança de layout dos tópicos de três colunas para duas colunas, otimização do espaço da página, e aumento do tamanho da fonte de 12.8 para 16.
  - Redação Estratégica (UX Writing): Reescrita dos textos focando nos diferenciais do curso.
- **Hipóteses:**
  - H0: Destacar os diferenciais do curso não aumentará a percepção de valor entre os visitantes.
  - H1: Destacar os diferenciais do curso aumentará a percepção de valor entre os visitantes.
- **Impacto Esperado:**
  - Percepção de Valor: Aumento na percepção de valor do curso pelos visitantes.
  - Engajamento: Maior engajamento com a página e com as informações sobre o curso.
  - Conversão: Aumento na taxa de conversão.

#### 1.4.2 Reescrita do Título do Formulário
- **Justificativa:** Houve confusão sobre o propósito do formulário.
- **Objetivo:** Aumento da taxa de preenchimento do formulário.
- **Classificação:**
  - Arquitetura de Informação: não houve alteração.
  - Design de Interface: remoção do marca-texto vermelho atrás da frase.
  - Redação Estratégica (UX Writing): título reescrito para "Tenho interesse em me matricular".
- **Hipóteses:**
  - H0: Um título mais direto não aumentará a taxa de preenchimento do formulário.
  - H1: Um título mais direto aumentará a taxa de preenchimento do formulário.
- **Impacto Esperado:**
  - Preenchimento de Formulário: Aumento na taxa de preenchimento do formulário de matrícula.
  - Engajamento: Maior engajamento dos visitantes com o formulário.
  - Conversão: Aumento na taxa de conversão.

#### 1.4.3 Reescrita da Descrição do Botão do Formulário
- **Justificativa:** O CTA atual "Aproveite!" não comunica claramente a ação esperada.
- **Objetivo:** Aumento da taxa de cliques no botão de envio.
- **Classificação:**
  - Arquitetura de Informação: não houve alteração.
  - Design de Interface: mudança de texto de maiúsculas para minúsculas.
  - Redação Estratégica (UX Writing): descrição reescrita para "Enviar".
- **Hipóteses:**
  - H0: Um CTA claro não aumentará a taxa de cliques no botão de envio.
  - H1: Um CTA claro aumentará a taxa de cliques no botão de envio.
- **Impacto Esperado:**
  - Envio de Formulário: Aumento na taxa de envios de formulários de matrícula.
  - Conversão: Melhoria na taxa de conversão geral da página.
  - Experiência do Usuário: Melhoria na experiência do usuário.
  - Redução de Fricção: Redução de confusão em relação à ação que precisa ser tomada.

#### 1.4.4 Reescrita da Descrição do Botão de Whatsapp
- **Justificativa:** Houve confusão entre a funcionalidade do formulário e do WhatsApp.
- **Objetivo:** Redução da confusão e diferenciação clara entre os canais de contato.
- **Classificação:**
  - Arquitetura de Informação: não houve alteração.
  - Design de Interface: não houve alteração.
  - Redação Estratégica (UX Writing): descrição reescrita para "Tenho dúvidas sobre o curso".
- **Hipóteses:**
  - H0: Um CTA específico não reduzirá a confusão entre a funcionalidade do formulário e do WhatsApp.
  - H1: Um CTA específico reduzirá a confusão entre a funcionalidade do formulário e do WhatsApp.
- **Impacto Esperado:**
  - Engajamento: Aumento no número de cliques no botão do WhatsApp.
  - Conversão: Maior número de conversas que resultam em matrículas.
  - Confiança: Aumento na confiança dos visitantes em relação ao curso.

#### 1.4.5 Comparação das páginas

Imagem 3 - Página Teste A - arquitetura (arquivo pessoal)
![alt text](/assets/arquitetura0.png)

Imagem 4 - Página Teste B - arquitetura (arquivo pessoal)
![alt text](/assets/arquitetura1.png)

## 2. Dados Acumulados

### 2.1 Dados Coletados, quantitativos

#### Grupo 5
| Data  | FORMS | Sessões página | TAXA CONVERSÃO (leads forms X sessões) |
|-------|-------|----------------|----------------------------------------|
| Total | 17    | 534            | 3.2%                                   |

**Análise do Grupo 5:**
- **FORMS:** O total de 17 formulários preenchidos indica o número de leads gerados durante o período analisado.
- **Sessões página:** Com 534 sessões na página, esse valor representa o total de interações dos usuários com a landing page.
- **Taxa de conversão:** A taxa de conversão de 3.2% é obtida dividindo o número de formulários preenchidos pelo total de sessões na página, multiplicado por 100. Esta métrica é crucial para entender a eficácia da landing page em transformar visitas em leads. Embora a taxa de conversão de 3.2% esteja abaixo do desejado, ela oferece uma linha de base para melhorias futuras.

#### Página A
| Data  | FORMS | Sessões página | TAXA CONVERSÃO (leads forms X sessões) |
|-------|-------|----------------|----------------------------------------|
| Total | 470   | 13,476         | 3.5%                                   |

**Análise da Página A:**
- **FORMS:** Com 470 formulários preenchidos, Página A gerou um número significativamente maior de leads em comparação com o Grupo 5.
- **Sessões página:** O total de 13,476 sessões na página mostra um volume elevado de interações dos usuários com a landing page, sugerindo uma boa atração de tráfego.
- **Taxa de conversão:** A taxa de conversão de 3.5%, embora ligeiramente superior à do Grupo 5, mostra uma performance mais eficaz em converter visitas em leads. Este incremento, embora pequeno (0.3 pontos percentuais), pode representar uma melhoria significativa quando considerado em grande escala, sugerindo que as mudanças feitas na Página A foram eficazes.

### Comparação entre Grupo 5 e Página A
- **Total de Forms:** Página A teve um número de formulários preenchidos muito maior do que o Grupo 5, indicando uma melhor performance em engajamento de usuários.
- **Sessões página:** Página A atraiu muito mais sessões do que o Grupo 5, possivelmente devido a uma melhor estratégia de atração de tráfego.
- **Taxa de conversão:** A diferença de 0.3% na taxa de conversão entre os dois grupos pode parecer pequena, mas é significativa em um contexto de marketing digital. Página A mostrou uma ligeira vantagem em converter visitantes em leads, destacando a eficácia das mudanças implementadas na estrutura e conteúdo da página.

### 2.2 Dados Qualitativos

Realizamos uma análise qualitativa detalhada baseada nas observações de usuários reais em um ambiente controlado de observação. A análise qualitativa foi realizada para compreender melhor as interações e percepções dos usuários em relação às plataformas de cursos de inglês online. Dois usuários foram observados enquanto navegavam em diferentes sites de cursos de inglês, incluindo a landing page da Wizard On.

Os dados qualitativos fornecem insights valiosos sobre as motivações, frustrações e satisfações dos usuários durante suas experiências de navegação e interação. Estes dados complementam os resultados quantitativos, permitindo uma visão mais holística sobre como as mudanças na landing page impactam a percepção de valor do curso e a taxa de conversão. A análise qualitativa foca em aspectos como a facilidade de navegação, clareza das informações, eficácia dos call-to-actions (CTAs) e a experiência geral do usuário ao tentar se matricular no curso online da Wizard On.

[Para uma compreensão mais detalhada dos métodos utilizados e dos insights obtidos, consulte a parte da Análise Qualitativa nesse Documento](https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/docs/sprint1/Ana%CC%81lise%20preliminar.md).

### 2.3 Informações dos dados

Os dados obtidos nessa análise são de clientes reais na landing page da Wizard On, que tinham interesse em adquirir o curso online. A página B do nosso grupo tinha aproximadamente 3,96% da quantidade de dados do teste A, então os resultados podem ser influenciados pelo tamanha da base utilizada para a realização do teste.

## 3. Metodologia de Análise
Para a análise dos dados de engajamento das campanhas de promoção da WizardOn, utilizamos uma variedade de ferramentas e técnicas estatísticas que foram fundamentais para gerar insights valiosos e interpretar os resultados obtidos. A seguir, descrevemos essas ferramentas e metodologias em detalhes:

### 3.1 Ferramentas Utilizadas

- **Looker**: Plataforma da google utilizada para observar e exportar os dados, permitindo a visualização e facilitando a análise
- **Google Colab**: Plataforma usada para escrever e executar o código Python, facilitando a colaboração e a análise de dados em tempo real.
- **Pandas**: Biblioteca Python utilizada para manipulação e análise de dados, permitindo a importação, limpeza, transformação e visualização dos dados de engajamento.
- **NumPy**: Biblioteca Python usada para operações matemáticas e estatísticas eficientes, essencial para cálculos complexos e manipulação de arrays.
- **Matplotlib e Seaborn**: Bibliotecas Python utilizadas para visualização de dados, permitindo a criação de gráficos e plots que ajudam a entender padrões e tendências nos dados.

### 3.2. Técnicas Estatísticas

- **Filtragem e Seleção de Dados**: Utilizamos técnicas de filtragem e seleção de dados para isolar períodos específicos antes e durante as campanhas promocionais (Black Friday, Volta às Aulas, e Férias). Isso permitiu comparar diretamente os níveis de engajamento entre esses períodos.

- **Análise Descritiva**: Aplicamos técnicas de análise descritiva para calcular medidas estatísticas básicas, como média, mediana, desvio padrão e distribuição dos dados. Essa análise forneceu uma visão geral dos dados de engajamento e identificou possíveis outliers ou anomalias.

- **Teste t de Student**: Realizamos testes t de Student para comparar as médias de engajamento antes e durante as campanhas promocionais. Isso ajudou a determinar se as diferenças observadas eram estatisticamente significativas.

- **Simulação de Monte Carlo**: Implementamos simulações de Monte Carlo para modelar o impacto potencial das campanhas promocionais sobre o engajamento. Essa técnica nos permitiu avaliar a variabilidade e a incerteza dos resultados esperados, fornecendo uma estimativa robusta dos efeitos das campanhas.

### 3.3. Contribuição das Metodologias para os Insights

As ferramentas e técnicas estatísticas utilizadas desempenharam um papel crucial na interpretação dos resultados da análise de dados de engajamento:

- **Comparação de Períodos**: A filtragem e seleção de dados permitiram uma comparação clara entre os períodos pré e durante as campanhas, destacando as mudanças no engajamento.

- **Significância Estatística**: Os testes t de Student ajudaram a confirmar se as mudanças observadas eram significativas, fornecendo uma base sólida para afirmar que as campanhas tiveram um impacto real no engajamento.

- **Visualização de Dados**: As bibliotecas de visualização (Matplotlib e Seaborn) facilitaram a interpretação dos dados ao apresentar os resultados de maneira visualmente intuitiva, tornando mais fácil identificar padrões e tendências.

- **Simulação de Impacto**: A simulação de Monte Carlo permitiu modelar diferentes cenários e entender a variabilidade nos resultados, ajudando a prever o impacto potencial das campanhas futuras e a tomar decisões baseadas em dados.

Em resumo, o uso combinado dessas ferramentas e técnicas estatísticas proporcionou uma análise abrangente e detalhada dos dados de engajamento, permitindo a geração de insights valiosos e a tomada de decisões informadas sobre as campanhas promocionais da WizardOn.

### 3.4. Notebook
- Essas técnicas podem ser encontradas no notebook da [análise preliminar](https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/docs/sprint4/analise_preliminar.ipynb)

## 4. Resultados e Observações

Neste tópicos, nós fizemos a integração de outros dois tópicos, sendo eles: Descobertas Principais e Apresentação visual dos dados, de forma a facilitar a compreensão dos resultados obtidos, validando as descobertas que fizemos e trazendo uma visão mais clara dos dados.

Bom, para começar, temos que entender que o grupo de visitantes da página B ser significativamente menor em comparação com a página A, com 534 visitantes e 17 formulários preenchidos representando a intenção de matrícula, em contraste com os 13.476 visitantes e 470 formulários da página A, a diferença de 0.3% na taxa de conversão sugere que o teste é válido. Os resultados, portanto, não são considerados "absurdos" e podem ser considerados com seriedade para análise.

O teste A/B revelou que, embora a página B, com seu enfoque na promoção para estimular a matrícula com desconto, tenha apresentado uma taxa de conversão maior, isso pode requerer reconsideração futura. Após o fim da promoção, houve uma queda de 0.3% na conversão. Isso sugere que, apesar da promoção ser eficaz, o foco principal do usuário ainda é o produto. Portanto, a estratégia de abordagem para despertar o interesse do visitante pode ser revista.

Aqui iremos fazer uma avaliação das tendências, anomalias e padrões observados nos dados do teste A/B, com o objetivo de identificar insights valiosos e entender como esses dados se relacionam com as expectativas iniciais do teste.	

| Página               | Sessões | Conversões | Taxa de Conversão (%) |
|----------------------|---------|------------|-----------------------|
| Página A - Controle  | 13476   | 470        | 3.49                  |
| Teste B - Grupo 1    | 888     | 45         | 5.07                  |
| Teste B - Grupo 2    | 600     | 30         | 5.00                  |
| Teste B - Grupo 3    | 867     | 32         | 3.69                  |
| Teste B - Grupo 4    | 611     | 31         | 5.07                  |
| Teste B - Grupo 5    | 534     | 17         | 3.18                  |

Comparação com Expectativas
As expectativas iniciais do teste eram de que as páginas de teste teriam uma taxa de conversão maior que a página de controle. Observamos que a maioria dos grupos de teste (Grupo 1, Grupo 2 e Grupo 4) superou a taxa de conversão da página de controle, enquanto os Grupos 3 e 5 não conseguiram alcançar a mesma eficiência.

Implicações das Tendências
Os resultados indicam que as modificações implementadas pelos Grupos 1, 2 e 4 tiveram um impacto positivo nas conversões. No entanto, o Grupo 5, que é o foco principal, não alcançou o desempenho esperado. Isso sugere que as mudanças implementadas pelo Grupo 5 não foram tão eficazes em melhorar a percepção de valor ou direcionar os visitantes a concluir a conversão.

![](/assets/output.png)

Uma anomalia identificada é que o Grupo 5 teve uma taxa de conversão significativamente menor em comparação com os outros grupos de teste.

Causas Potenciais das Anomalias
Possíveis razões para a baixa taxa de conversão do Grupo 5 podem incluir:
- Implementação inadequada das mudanças sugeridas, já que percebemos um padrão de distinção entre os valores de quantidade de sessões entre os grupos.
- A proposta de valor destacada não ressoou com os visitantes.
- Problemas de usabilidade ou clareza na landing page.
- Impacto das Anomalias nos Resultados
- A baixa taxa de conversão do Grupo 5 impacta negativamente a validação das hipóteses formuladas. Isso sugere que as mudanças não aumentaram a percepção de valor entre os visitantes nem direcionaram melhor os leads, contrariando as hipóteses H1.

#### Análise de Tendências
- **Grupo 1**: A taxa de conversão apresentou picos nos dias 10/jun e 15/jun. Houve uma tendência geral de aumento até o dia 10/jun, seguido de flutuações.
- **Grupo 2**: A taxa de conversão apresentou um pico significativo em 14/jun, indicando uma possível anomalia ou evento especial que aumentou a conversão nesse dia.
- **Grupo 3**: Houve um aumento significativo na taxa de conversão em 10/jun e 16/jun, com uma queda notável em 15/jun.
- **Grupo 4**: Observamos um pico em 13/jun e 14/jun, indicando possíveis ações que aumentaram a conversão nesses dias.
- **Grupo 5**: A taxa de conversão foi mais baixa, com picos menores e uma tendência de queda.
- **Página A**: A taxa de conversão foi relativamente estável, com um aumento notável em 14/jun.

#### Padrões
- A maioria dos grupos apresentou flutuações em torno de datas similares, sugerindo que eventos externos ou campanhas podem ter influenciado os resultados de todos os grupos simultaneamente.

### Conclusão
Os dados indicam que alguns dias apresentaram picos anômalos que merecem investigação adicional. Além disso, a tendência geral mostra que a conversão pode ser influenciada por fatores externos, possivelmente campanhas ou mudanças na estratégia de marketing.

Os resultados do teste A/B fornecem insights valiosos sobre o impacto das mudanças implementadas nas páginas de teste. Embora a maioria dos grupos tenha superado a taxa de conversão da página de controle, o Grupo 5 não alcançou o desempenho esperado. Isso sugere que as mudanças implementadas pelo Grupo 5 não foram tão eficazes em melhorar a percepção de valor ou direcionar os visitantes a concluir a conversão.