# Conclusões e Recomendações de Negócio

## 1. Introdução
Este documento tem como objetivo sintetizar os principais resultados do teste A/B realizado, fornecendo uma análise final e orientações estratégicas para a empresa. Baseado nos dados coletados durante o teste, destacamos as descobertas críticas e suas implicações para o negócio. As recomendações aqui apresentadas visam otimizar a performance do negócio e direcionar futuras estratégias de forma objetiva e baseada em dados.


## 2. Apresentação dos Dados 
Durante o teste A/B, coletamos dados quantitativos e qualitativos essenciais para nossas análises.

**Dados quantitativos:**
- **Event Name:** Identificação do evento teste A/B.
- **Active Users (Usuários Ativos):** Número de usuários únicos ativos em um período específico, coletado por meio de cookies e identificadores de usuário.
- **Inteli_ab_test:** Identificação das páginas de teste B.
- **Sessions:** Número de sessões na página em determinado período de tempo.

**Descrições Qualitativas:**
- Feedback dos usuários coletado por meio de questionários e observações diretas, focando na clareza das informações e usabilidade.

## 3. Ferramentas e Metodologias Utilizadas para a Análise dos Dados
As ferramentas que foram utilizadas, tornando as análises estatísticas, a visualização dos dados e o embasamento dos dados coletados foram as seguintes:

- **Python:** Utilizado para cálculos estatísticos e simulação de cenários.
- **Bibliotecas Python:** scipy.stats para o teste t, numpy e pandas para manipulação de dados.
- **Looker:** Ferramenta de visualização de dados e criação de relatórios interativos.

Dentre as metodologias que serviram como base para o processo de análise, podem ser citadas três que foram chave para o embasamento do projeto:


### 3.1 Teste de Hipóteses Estatísticas
Realizamos testes de hipóteses estatísticas para determinar a significância das mudanças, aceitando ou rejeitando hipóteses com base no p-valor. Utilizamos essa metodologia para validar se as alterações na landing page causaram um impacto estatisticamente significativo nas métricas de taxa de conversão e número de sessões.

### 3.2 Teste Multivariado
Aplicamos o teste multivariado para comparar as novas versões da landing page, identificando qual apresentou melhor desempenho. Esse método nos permitiu testar múltiplas variáveis simultaneamente para entender o impacto combinado das mudanças, auxiliando na identificação da versão da landing page com melhor performance.


## 4. Relação entre Hipóteses das Mudanças na Landing Page
A análise dos testes A/B realizados nas landing pages revelou insights importantes sobre como diferentes alterações podem impactar as taxas de conversão. Enquanto os grupos 1 e 4 alcançaram uma taxa de conversão de 4.4%, os grupos 2 e 3 obtiveram 3.9% e 3.2%, respectivamente, e o nosso grupo, o 5,  atingiu 1.7%. 


Esses resultados destacam a importância da simplificação da página, da clareza da proposta de valor e da redução de distrações visuais. Para entender melhor como as hipóteses de cada grupo influenciaram as taxas de conversão, analisamos especificamente as mudanças propostas nas landing pages e como elas correlacionam com as taxas de conversão obtidas.

### 4.1 Grupo 1
#### Resultados:
- Sessões: 903
- Conversões: 40
- Taxa de Conversão: 4.4%
- Proporção B: 7.3%
#### Hipóteses e Mudanças:
- **Alterar a mensagem de confirmação de envio do formulário:** Melhor experiência do usuário.
- **Diminuir o tamanho do botão do WhatsApp e remover o CTA "Clique Aqui e Fale Conosco":** Redução de distrações.
Simplificar o conteúdo da página: Foco nos benefícios principais do curso.
#### Análise:
- **Mensagem de Confirmação:** A mudança na mensagem de confirmação visava assegurar ao usuário que sua ação foi bem-sucedida, proporcionando uma experiência positiva e possivelmente incentivando futuras interações.
- **Redução de Distrações:** Ao diminuir o tamanho do botão do WhatsApp e remover o CTA, a página se tornou menos poluída, permitindo que os visitantes tivessem o foco voltado mais no formulário de inscrição.
- **Simplificação do Conteúdo:** Ao focar nos benefícios principais do curso, a página se tornou mais direta e menos confusa, facilitando a tomada de decisão pelos visitantes.
- **Resultado:** A combinação dessas mudanças resultou em uma taxa de conversão de  4.4%, demonstrando que a clareza e a usabilidade são cruciais para a conversão.

### 4.2 Grupo 2
#### Resultados:
- Sessões: 613
- Conversões: 24
- Taxa de Conversão: 3.9%
 Proporção B: 5.0%
#### Hipóteses e Mudanças:
- **Clareza sobre a WizardOn e seus diferenciais:** Maior entendimento do serviço.
- **Ajuste do botão do WhatsApp para melhorar a visualização do formulário:** Menos distração visual.
#### Análise:
- **Clarificação dos Diferenciais:** Esclarecer o que é a WizardOn e seus diferenciais ajudou a alinhar as expectativas dos visitantes, tornando mais fácil para eles entenderem o valor do serviço.
- **Ajuste Visual do WhatsApp:** Melhorar a visualização do formulário, ajustando o botão do WhatsApp, reduziu distrações e facilitou a interação com o formulário.
#### Resultado: 
Essa abordagem resultou em uma taxa de conversão de  3.9%, quase equivalente ao Grupo 1, indicando que a clareza das informações também é um fator chave para a conversão.

### 4.3 Grupo 3
#### Resultados:
- Sessões: 920
- Conversões: 29
- Taxa de Conversão: 3.2%
- Proporção B: 7.4%
#### Hipóteses e Mudanças:
- **Formulário ao lado das informações do curso:** Acesso imediato a informações relevantes.
- **Destaque na campanha na primeira página:** Maior visibilidade.
#### Análise:
- **Formulário ao Lado das Informações:** A ideia era fornecer aos visitantes todas as informações necessárias de forma rápida e acessível. No entanto, isso pode ter sobrecarregado os visitantes com informações excessivas.
- **Destaque na Campanha:** Dar destaque à campanha na primeira página visava aumentar a visibilidade e o interesse, mas pode não ter sido suficientemente persuasivo.
#### Resultado: 
A taxa de conversão de 3.2% sugere que as informações adicionais e o destaque na campanha não foram tão eficazes quanto o esperado. A complexidade e a possível sobrecarga de informações podem ter desmotivado os visitantes.

### 4.4 Grupo 4
#### Resultados:
- Sessões: 623
- Conversões: 26
- Taxa de Conversão: 4.2%
- Proporção B: 5.0%
#### Hipóteses e Mudanças:
- **Simplificação da página e melhoria da usabilidade:** Página menos poluída e com melhor usabilidade.
- **Substituição do botão do regulamento por FAQ, remoção de CTA do WhatsApp, e ajuste no call to action do botão "Aproveite":** Redução de distrações e foco na ação desejada.
#### Análise:
- **Simplificação e Usabilidade:** Ao tornar a página menos poluída e mais fácil de navegar, os visitantes puderam focar melhor no formulário de inscrição.
- **Substituição por FAQ:** A substituição do botão do regulamento por uma FAQ ajudou a responder possíveis dúvidas sem distrair os visitantes da ação principal.
- **Remoção de Distrações:** A remoção do CTA do WhatsApp e o ajuste do call to action para "Aproveitar promoção" simplificaram a interface e reduziram distrações.
#### Resultado: 
Com uma taxa de conversão de 4.2%, as mudanças no Grupo 4 mostram que a simplificação e a clareza são fundamentais para aumentar a conversão.

### 4.5 Grupo 5 
#### Resultados:
- Sessões: 540
- Conversões: 9
- Taxa de Conversão: 1.7%
- Proporção B: 4.4%
#### Hipóteses e Mudanças:
- **Destacar os diferenciais do curso:** Maior percepção de valor.
- **Título mais direto e orientado à ação:** Claridade e direção.
- **CTAs claros e específicos:** Redução de confusão entre formulário e WhatsApp.
#### Análise:
- **Destacar os diferenciais do curso:** Esta alteração, apesar de provavelmente ter trazido um ganho na questão percepção de valor por parte do usuário, pode ter poluído de certa forma a seção principal da interface. Uma possibilidade é que um foco um pouco maior em alterações nas mensagens apresentadas neste ponto ou até mesmo em geral na simplificação e na remoção de distrações poderia reduzir essa complexidade, atraindo mais conversões.
- **Título mais direto e orientado à ação:** Esta foi uma alteração pontual que garantiu maior claridade e direção para o usuário da landing page e, como foi objetiva, não chega a levantar a possibilidade de ter afetado a taxa de conversão final.
- **CTAs claros e específicos:** Esta foi uma alteração objetiva, assim como a do título, para garantir a redução da confusão entre formulário e WhatsApp. Apesar disso, é possível que o resultado desta alteração tenha sido ofuscado por uma falta de rastreabilidade das conversões no WhatsApp.

Apesar de ter hipóteses bem fundamentadas, a taxa de conversão mais baixa sugere que as mudanças não foram tão eficazes quanto o esperado. Possíveis razões incluem a complexidade ou confusão causada pelas mudanças ou a falta de rastreabilidade de conversões no WhatsApp. O reposicionamento das explicações pode não ter sido tão impactante quanto a simplificação direta e a remoção de distrações observadas nos outros grupos.

## 5. Comparação dos Grupos por Hipóteses e Mudanças

### 5.1 Grupo 1 vs Grupo 4:

**Mudanças Similares**:
Ambos os grupos focaram na simplificação da página e na melhoria da usabilidade, com a remoção de elementos distrativos e a redução da carga cognitiva.

Grupo 1: 
**Taxa de Conversão**: 5,1%
**Hipóteses**: 
Melhorar a mensagem de confirmação, diminuir o tamanho do botão do WhatsApp.

Grupo 4:
**Taxa de Conversão**: 5,1%
**Hipóteses**:
Substituir o botão do regulamento por FAQ, remover CTA do WhatsApp, ajustar call to action do botão "Aproveite".

**Análise**:
Ambos os grupos alcançaram uma taxa de conversão alta ao simplificar suas páginas e focar nas ações principais. 
O grupo 1 fez modificações disruptivas na landing page original adicionando o banner para CTA, modificando a imagem da campanha e realocando diversas informações na página, enquanto o grupo 4 apenas modificou os botões de ancoragem do header, diminuíram o botão do Whatsapp e fizeram pequenas mudanças nos textos de CTA.
Como os resultados foram semelhantes e ambos satisfatórios, é possível concluir que o ponto semelhante entre eles, a proposta de manter o formulário no topo da página junto a imagem de campanha, foi uma estratégia efetiva para o aumento da taxa de conversão.

### 5.2 Grupo 2 vs Grupo 3:

**Mudanças Similares**:
Ambos os grupos buscaram clarificar a mensagem sobre a WizardOn e seus diferenciais, além de melhorar a visibilidade e acessibilidade do formulário.

Grupo 2:
**Taxa de Conversão**: 5,0%
**Hipóteses**:
Ajuste do botão do WhatsApp para melhorar a visualização, clarificação dos diferenciais da WizardOn.

Grupo 3:
**Taxa de Conversão**: 3,7%
**Hipóteses**: Colocar o formulário ao lado das informações do curso, destacar a campanha na primeira página.

**Análise**:
O Grupo 2 obteve uma taxa de conversão ligeiramente superior, indicando que a melhoria na comunicação dos diferenciais e a usabilidade do formulário são mais impactantes do que simplesmente fornecer mais informações. 
Deixar a imagem da campanha próxima ao formulário ajuda na conversão, pois todos os grupos que resolveram deixar o formulário próximo aos atributos não chegaram a resultados tão satisfatórios quanto estes que optaram por esta outra opção.
É possível chegar a conclusão de que a remoção de distrações e a facilitação da navegação são estratégias eficazes.

### 5.3 Grupo 5 em relação aos demais

#### 5.3.1 Alterações realizadas

**Reposicionamento da Explicação sobre o Curso**

- **Objetivo:** Aumentar a percepção de valor entre os visitantes.
- **Hipótese:**  Destacar os diferenciais do curso aumentará a percepção de valor entre os visitantes.

**Reescrita do Título do Formulário**

- **Objetivo:** Aumento da taxa de preenchimento do formulário.
- **Hipóteses** Um título mais direto aumentará a taxa de preenchimento do formulário.

**Reescrita da Descrição do Botão do Formulário**

- **Objetivo:** Aumento da taxa de cliques no botão de envio.
- **Hipóteses** Um CTA claro aumentará a taxa de cliques no botão de envio.

**Reescrita da Descrição do Botão de Whatsapp**

- **Objetivo:** Redução da confusão e diferenciação clara entre os canais de contato.
- **Hipóteses** Um CTA específico reduzirá a confusão entre a funcionalidade do formulário e do WhatsApp.

#### 5.3.2 Observações

As alterações feitas pelo grupo 5 e seus respectivos objetivos podem ser considerados próximos, dentre os demais grupos, daqueles planejados pelo grupo 3 e pelo grupo 2, uma vez que grande parte do foco das alterações foi o de clarificar as propostas da Wizard. Apesar disso, as mudanças podem ter ofuscado o formulário, que continuou como ponto central de atenção em outras soluções. 
Comparando as alterações do grupo 5 com o restante, considerando os resultados de cada, portanto, é possível concluir que a construção de uma landing page mais direta e simples poderia ter sido o melhor caminho na aplicação do teste A / B.


### 5.4 Limitações

**Proporção de Acessos**: 
Nossa página não atingiu uma taxa de conversão de 6%, como outras páginas que tiveram mais acessos. A menor quantidade de sessões pode ter influenciado a precisão dos resultados. 

**Duração do Teste**:
O teste rodou por um período de 11 dias, menos que um ciclo econômico completo, o que pode não ser suficiente para captar todas as variações sazonais e comportamentais dos usuários. Para resultados mais robustos, recomenda-se rodar os testes por 1 a 2 ciclos econômicos, possivelmente coincidentes com períodos de campanhas, para capturar flutuações naturais e comportamentos sazonais dos usuários.

**Variáveis Múltiplas e Confundidoras**: 
A presença de várias variáveis modificadas em cada grupo introduz a possibilidade de variáveis confundidoras, dificultando a identificação precisa do impacto de cada alteração. A complexidade de testar múltiplas variáveis simultaneamente requer um design experimental mais controlado e isso pode dificultar a identificação precisa de qual alteração teve o maior impacto na taxa de conversão.

**Falta de Rastreamento de Conversões no WhatsApp**:
Não foi possível medir com precisão as interações e conversões realizadas através do WhatsApp, o que pode ter impactado a avaliação completa da eficácia das mudanças.
Desproporção de Acessos às Páginas B: A distribuição das páginas B entre os grupos não foi uniforme, com a seguinte proporção:

Grupo 1: 
7,18%

Grupo 2:
4,78%

Grupo 3:
7,05%

Grupo 4:
4,91%

Grupo 5:
4,29%

Os 2% restantes não foram identificados com precisão e foram atribuídos a um grupo geral de teste A/B.

**Reload do Mesmo Usuário**:
O mesmo usuário, ao recarregar a página, não necessariamente era direcionado à mesma versão, introduzindo variabilidade nos resultados.

## 6 Observações Mais Relevantes

### 6.1.1 Tendências Identificadas

**Simplificação do Conteúdo**:
A remoção de informações excessivas e a ênfase nos benefícios principais aumentaram a taxa de conversão.

**Clareza nos CTAs**:
CTAs claros e específicos direcionaram melhor os usuários, resultando em maior taxa de cliques.

### 6.1.2 Anomalias Detectadas

**Rastreamento Incompleto no WhatsApp**:
A falta de rastreabilidade das conversões via WhatsApp limitou a análise completa dos dados.

**Desproporção de Acessos**:
A desproporção no número de acessos entre as versões pode ter influenciado os resultados.

### 6.1.3 Padrões Significativos

**Engajamento em Dispositivos Móveis**:
A usabilidade em dispositivos móveis mostrou-se crucial para o sucesso das campanhas.

### 6.2 Conclusões Gerais

Grupos 1 e 4, que focaram em simplificação e redução de distrações, obtiveram as maiores taxas de conversão (5,1%). Isso sugere que menos é mais quando se trata de páginas de inscrição, onde um layout limpo e focado pode facilitar a ação do usuário. 

É possível que a proposta B do grupo 5 tenha desviado a atenção do formulário, enquanto outros grupos que impediram que isso aconteça chegaram a maiores taxas de conversão.

Já o Grupo 2 obteve uma taxa de conversão de 5,0% ao melhorar a clareza sobre o que é a WizardOn e seus diferenciais reposicionando o botão do Whatsapp e dando maior destaque ao formulário.

O Grupo 3 tentou fornecer mais informações, mas a taxa de conversão de 3,7% sugere que muita informação pode sobrecarregar os visitantes, especialmente se não for apresentada de maneira atraente e persuasiva. E por fim nosso grupo, o 5, focando em destacar diferenciais e melhorar CTAs, teve a menor taxa de conversão (3,2%).

As alterações, embora lógicas, podem ter sido testadas por tempo insuficiente para mostrar resultados positivos. Além disso, o fluxo de visitantes foi significativamente menor na proposta B em comparação a A, portanto, um teste futuro com um fluxo maior poderia levar a conclusões mais sólidas.




