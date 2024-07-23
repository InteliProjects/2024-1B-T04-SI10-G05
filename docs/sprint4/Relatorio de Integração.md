# Apresentação do artefato

Este relatório tem como objetivo detalhar a implementação do teste A/B no contexto do problema proposto, focando na melhoria de métricas específicas. A implementação inclui a coleta de resultados para medir as métricas e definir o cumprimento dos objetivos.

## Objetivo

O objetivo da implementação do teste A/B é implementar uma versão B que visa melhorar as métricas específicas dentro do contexto do problema, garantindo que a implementação seja feita sem erros. As métricas alvo foram escolhidas com base em sua relevância para os objetivos do parceiro e a capacidade de impactar positivamente a performance geral do sistema. A proposta B foi desenvolvida para abordar áreas onde a versão atual (versão A) apresenta oportunidades de otimização, seja em termos de usabilidade, engajamento ou conversão.

Com isso, como dito anteriormente, esse documento demonstrará os passos que foram seguidos para fazer uma implementação bem-sucedida do teste A/B.

## Como atingir o objetivo

Para atingir o objetivo de implementar a versão B sem erros e melhorar as métricas, a seguinte abordagem foi adotada:
- **Planejamento Detalhado**: Cada etapa da implementação foi planejada para evitar erros. Isso incluiu a definição clara dos requisitos, a elaboração de um cronograma detalhado e a alocação de recursos adequados.
- **Desenvolvimento**: A versão B foi desenvolvida seguindo rigorosos padrões de codificação e práticas de controle de qualidade, mantendo a identificação visual da Wizard. Revisões de código foram realizadas para garantir que nenhuma falha passasse despercebida.
- **Teste de Integração Contínua**: Em conjunto com os outros grupos, foram criadas diferentes propostas para obter feedback mais preciso e robusto, buscando identificar as melhores práticas na interface da tela e como podem ser ainda melhores.
- **Integração com o Ambiente de Homologação**: Realizamos a integração com o ambiente de homologação da Pearson para que as alterações realizadas na proposta B fossem usadas na landing page, permitindo a coleta de dados reais.

## Processo de Implementação

Após seguir todo o processo apresentado na documentação técnica fornecida pela Pearson, fizemos as alterações necessárias na landing page de acordo com a proposta descrita na [Preposição do Teste A/B](https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/docs/sprint3/Preposicao%20Teste.md). Para detalhes técnicos específicos sobre as alterações, consulte a [Proposta B](https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/docs/sprint3/Proposta%20B.md)..

O processo de implementação do teste A/B consistiu principalmente em seguir os passos da documentação técnica fornecida pela Pearson, focando na integração com o ambiente de homologação. Por motivos de segurança, não podemos compartilhar essas instruções.

Em resumo, fizemos as alterações locais e subimos para o ambiente de homologação da Pearson usando uma ferramenta chamada FileZilla <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/FileZilla_logo.svg/1200px-FileZilla_logo.svg.png" alt="FileZilla logo" width="20" height="20">, que é um software de transferência de arquivos. A Pearson então fez a integração com o ambiente de homologação e a landing page foi atualizada com a nossa proposta B. Para garantir que a proposta B estava funcionando corretamente, fizemos testes na landing page e verificamos se as alterações estavam de acordo com a nossa proposta.

Além disso, por usarmos essa ferramenta de conexão de servidor, questões como controle de versão e planos de rollback são facilmente gerenciáveis, já que a ferramenta permite fazer upload de versões anteriores da landing page caso algo dê errado e seja necessário voltar para uma versão anterior.

Para a conexão com o ambiente deles, utilizamos as configurações fornecidas pela Pearson para fazer a conexão com o ambiente de homologação via FileZilla. Com isso, conseguimos transferir os arquivos da nossa proposta B para a landing page com sucesso.

Infelizmente, não conseguimos integrar a proposta B com o ambiente de produção da Pearson, pois não tivemos acesso a ele. No entanto, fomos informados de que essa integração foi realizada com sucesso pela equipe da Pearson.

## Dificuldades Encontradas 

Em relção às dificuldades encontradas no processo de implementação e integração do projeto, as principais foram:

- **Questões de segurança**: Enfrentamos enormes complicações em relação à segurança ao rodar os projetos e fazer a integração com o ambiente de homologação da Pearson. Os computadores utilizados pelo Inteli não permitiam a execução de certos comandos, dificultando o processo de integração. Isso fez com que apenas as pessoas que possuíam computadores pessoais pudessem realizar o desenvolvimento.
- **Documentação Técnica Limitada**: A documentação técnica fornecida pela Pearson era limitada, dificultando a compreensão de certos aspectos do processo de integração. Essa limitação exigiu uma comunicação constante com a Pearson para esclarecer dúvidas e garantir a implementação correta.
- **Complexidades do FileZilla**: O uso do FileZilla para a transferência de arquivos foi desafiador, pois exigiu a configuração de várias opções e uma compreensão detalhada de como a ferramenta funciona. Foi necessário um esforço considerável para garantir que a integração fosse realizada corretamente.
- **Baixo Número de Visitas**: Devido ao baixo número de visitas na página, ainda é cedo para afirmar que as mudanças foram realmente eficientes. Isso limitou nossa capacidade de coletar dados reais e avaliar o impacto das alterações.
- **Falta de Acesso ao Ambiente de Produção**: Não tivemos acesso ao ambiente de produção da Pearson, o que dificultou a integração da proposta B com o ambiente de produção. Isso limitou nossa capacidade de testar a proposta B em um ambiente real e coletar dados reais.

Essas dificuldades destacam a necessidade de uma documentação técnica mais completa, uma infraestrutura de segurança mais flexível e maior acesso aos ambientes de produção para facilitar futuras implementações. Além disso, é fundamental manter uma comunicação constante com todos os envolvidos para resolver qualquer problema que possa surgir durante o desenvolvimento e a integração.

## Resultados Obtidos

Para garantir uma coleta de dados precisa e contínua, utilizamos a ferramenta Looker para monitorar o desempenho da página criada pelo grupo. Através dessa ferramenta, conseguimos realizar comparações detalhadas entre as versões A e B, analisando métricas-chave como taxa de conversão, tempo de permanência na página e taxa de rejeição.

### Estratégias de Monitoramento Contínuo e Suporte Operacional Durante o Período do Teste

- **Monitoramento Contínuo**: Visando entender o impacto das alterações das variáveis nas métricas, como a taxa de conversão, realizamos o monitoramento contínuo e observação das métricas. Mesmo que os resultados atingidos sejam satisfatórios, é importante entender o que melhorou na página.
- **Suporte Operacional**: O suporte operacional em conjunto com a Pearson garante que nenhuma funcionalidade vital da página seja afetada, garantindo que tudo necessário para o bom funcionamento da landing page esteja funcionando.

As análises mostraram que a versão B trouxe melhorias em termos de taxa de conversão e tempo de permanência na página, indicando que as mudanças implementadas foram eficazes. No entanto, devido ao baixo número de visitas na página, ainda é cedo para afirmar que as mudanças foram realmente eficientes.

## Conclusão

A implementação do teste A/B foi concluída com sucesso, com a versão B trazendo melhorias significativas em termos de taxa de conversão e tempo de permanência na página. No entanto, devido ao baixo número de visitas na página, ainda é cedo para afirmar que as mudanças foram realmente eficientes. A continuidade do monitoramento e análise das métricas é essencial para garantir que as melhorias sejam sustentáveis e duradouras. Além disso, a colaboração contínua com a Pearson é fundamental para garantir que a implementação seja bem-sucedida e que as metas sejam alcançadas.