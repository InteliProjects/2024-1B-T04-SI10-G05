# Home page Wizard ON

Este projeto contém o código front-end para a landing page da Wizard ON. A página é projetada para fornecer informações sobre os cursos de inglês online da Wizard e capturar leads através de um formulário de contato.
A "Proposta B para Teste A/B" consiste na nova página refatorada de acordo com as modificações propostas pelo grupo, baseadas na página original. Este documento sintetiza o resultado de um processo colaborativo e incremental, integrando insights e feedbacks de várias etapas do desenvolvimento do projeto.

## Índice

- [Recursos](#recursos)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Configuração](#configuração)
- [Estrutura](#estrutura)
- [Conformidade Funcional](#conformidade-funcional)
    - [Preservação das Funcionalidades Originais](#preservação-das-funcionalidades-originais)
    - [Integridade Operacional](#integridade-operacional)
- [Adesão à Identidade da Marca](#adesão-à-identidade-da-marca)
    - [Consistência Visual e de Conteúdo](#consistência-visual-e-de-conteúdo)
    - [Elementos Estruturais e Estilísticos](#elementos-estruturais-e-estilísticos)
- [Documentação e Transparência](#documentação-e-transparência)
    - [Detalhamento das Modificações](#detalhamento-das-modificações)
    - [Evidências de Implementação](#evidências-de-implementação)
    - [Apoio no Processo de Homologação](#apoio-no-processo-de-homologação)

---

## Recursos

- Design responsivo para garantir usabilidade em vários dispositivos.
- Destaque dos principais benefícios do programa Wizard ON.
- Um formulário de contato para capturar informações de potenciais alunos.
- Um botão de call-to-action para engajamento imediato.

## Tecnologias Utilizadas

- HTML
- CSS (SCSS)
- PHP (para processamento no lado do servidor)
- JavaScript (para validação de formulários e interações)

## Estrutura

### Front-end (HTML/PHP)

A seção principal da página de captura é estruturada em duas partes principais: o banner e o formulário.

#### Seção do Banner

- Exibe o logotipo da Wizard ON.
- Inclui um título que captura a essência do programa.
- Lista os principais benefícios em um formato estruturado.

#### Seção do Formulário

- Contém um link para chamada telefônica para contato imediato.
- Inclui um formulário flutuante que coleta informações do usuário, como nome, e-mail e telefone.
- Um botão de envio para submissão do formulário.

### CSS

O CSS é organizado usando SCSS (Sass) para melhor modularidade e manutenção. Elementos-chave são estilizados para corresponder às especificações de design fornecidas na imagem.

#### Classes e IDs Principais

- `#banner`: Estiliza o plano de fundo e o layout do banner principal.
- `.floating-form`: Alinha o conteúdo do formulário verticalmente ao centro.
- `.logo-wizard-on`: Define a largura máxima para a imagem do logotipo.
- `.banner-list`: Estiliza a lista de benefícios na seção do banner.
- `#form`: Estiliza o layout e os elementos do formulário de contato.


## Conformidade Funcional Preservação das Funcionalidades Originais
Como é possível ver pelo próprio site de homologação, https://g5.intelli-wizard-on.mmserver.com.br/ , todas as alterações respeitaram as rotas do backend e de APIs, de forma a manter a integridade do site, conforme o que foi passado anteriormente. As maiores alterações foram somente na organização dos componentes, assim, acabamos por preservar as funcionalidades originais. Não houve proposta de alteração de funcionalidade da LP. 

- Foi feito uma bateria de testes de todos os botões e formulários da página, e todos funcionaram corretamente, sem erros. 
- **IMPORTANTE**: Testes de integridade operacional feitos antes do envio do site para o servidor de homologação

## Integridade Operacional
Nos certificamos de que todas as alterações feitas na página operassem de forma similar à página original, garantindo que as chamadas de rotas do backend e de APIs ocorressem de forma que o desempenho e o tempo de carregamento fossem extremamente parecidos, preservando a experiência do usuário.

- Um possível teste a se fazer é com o botão do whatsapp, que foi alterado para "Tenho dúvidas sobre o curso". É possível verificar que tanto na page alterada como na original, o tempo de resposta é o mesmo, e a funcionalidade do botão é a mesma, ou seja, o botão redireciona para o whatsapp da Wizard On.


## Adesão à Identidade da Marca Consistência Visual e de Conteúdo
Como visto em páginas anteriores, essencialmente nenhuma parte crítica da landing page foi alterada. Assim, mantivemos o respeito aos parâmetros de marca estabelecidos pelo parceiro. A única alteração significativa foi a realocação de conteúdo, que não afetou a identidade visual da marca, mas sim a organização dos elementos na página. 

## Elementos Estruturais e Estilísticos
Uma das alterações de maior impacto que afeta diretamente a estrutura da página foi a do banner à esquerda do formulário. O banner foi substituído por uma listagem de pontos sobre a proposta de valor da Wizard On, que anteriormente estava posicionada no final da landing page. O banner foi movido para logo abaixo da área do formulário.

Essa alteração na estrutura da página dá um enfoque muito maior aos pontos que a Wizard On deseja passar sobre sua proposta para o cliente, deixando a campanha do banner em segundo plano. Essa decisão segue a identidade da marca, uma vez que nada foi alterado em questão de design dos componentes, mas gera uma grande mudança estrutural que pode levar a conclusões importantes sobre qual deve ser o foco na LP: a campanha ou a proposta da empresa.

## Documentação e Transparência Detalhamento das Modificações

1.  Realocação de conteúdo-campanha
    - Reposicionamento da explicação sobre o curso no local da campanha promocional.
    - Justificativa: Muitos usuários não exploram a página completamente e perdem informações importantes sobre o curso. A landing page focada nos diferenciais do Wizard On fornece informações sobre o que torna o curso único, aumentando a percepção de valor.
    - Objetivo: Aumento da percepção de valor entre os visitantes, resultando em uma maior taxa de conversão.
    - Classificação:
        - Arquitetura de Informação: a realocação da explicação sobre o curso para a parte superior da landing page.
        - Design de Interface: a mudança de layout dos tópicos de três colunas para duas colunas, otimização do espaço da página, e aumento do tamanho da fonte de 12.8 para 16.
        - Redação Estratégica (UX Writing):
    - Hipóteses:
        - H0: Destacar os diferenciais do curso não aumentará a percepção de valor entre os visitantes.
        - H1: Destacar os diferenciais do curso aumentará a percepção de valor entre os visitantes.
    - Impacto Esperado:
        - Percepção de Valor: Aumento na percepção de valor do curso pelos visitantes.
        - Engajamento: Maior engajamento com a página e com as informações sobre o curso.
        - Conversão: Aumento na taxa de conversão.

2. Reescrita do título do formulário
    - Reescrita do título do formulário de “Aprenda inglês online com aulas ao vivo <3” para “Tenho interesse em me matricular”.
    - Justificativa: Houve confusão sobre o propósito do formulário.
    - Objetivo: Aumento da taxa de preenchimento do formulário.
    - Classificação:
        - Arquitetura de Informação: não houve alteração.
        - Design de Interface: remoção do marca-texto vermelho atrás da frase.
        - Redação Estratégica (UX Writing):
    - Hipóteses:
        - H0: Um título mais direto não aumentará a taxa de preenchimento do formulário.
        - H1: Um título mais direto aumentará a taxa de preenchimento do formulário.
    - Impacto Esperado:
        - Preenchimento de Formulário: Aumento na taxa de preenchimento do formulário de matrícula.
        - Engajamento: Maior engajamento dos visitantes com o formulário.
        - Conversão: Aumento na taxa de conversão.

3. Reescrita da descrição do botão do formulário
    - Reescrita da descrição do botão de formulário de “Aproveite!” para “Enviar”.
    - Justificativa: O CTA atual "Aproveite!" não comunica claramente a ação esperada.
    - Objetivo: Aumento da taxa de cliques no botão de envio.
    - Classificação:
        - Arquitetura de Informação: não houve alteração.
        - Design de Interface: mudança de texto de maiúsculas para minúsculas.
        - Redação Estratégica (UX Writing):
    - Hipóteses:
        - H0: Um CTA claro não aumentará a taxa de cliques no botão de envio.
        - H1: Um CTA claro aumentará a taxa de cliques no botão de envio.
    - Impacto Esperado:
        - Envio de Formulário: Aumento na taxa de envios de formulários de matrícula.
        - Conversão: Melhoria na taxa de conversão geral da página.
        - Experiência do Usuário: Melhoria na experiência do usuário.
        - Redução de Fricção: Redução de confusão em relação à ação que precisa ser tomada.

4. Reescrita da descrição do botão de Whatsapp
    - Reescrita da descrição do botão de Whatsapp de “Clique aqui e fale conosco” para “Tenho dúvidas sobre o curso”.
    - Justificativa: Houve confusão entre a funcionalidade do formulário e do WhatsApp.
    - Objetivo: Redução da confusão e diferenciação clara entre os canais de contato.
    - Classificação:
        - Arquitetura de Informação: não houve alteração.
        - Design de Interface: não houve alteração.
        - Redação Estratégica (UX Writing):
    - Hipóteses:
        - H0: Um CTA específico não reduzirá a confusão entre a funcionalidade do formulário e do Whatsapp.
        - H1: Um CTA específico reduzirá a confusão entre a funcionalidade do formulário e do Whatsapp.
    - Impacto Esperado:
        - Engajamento: Aumento no número de cliques no botão do WhatsApp.
        - Conversão: Maior número de conversas que resultam em matrículas.
        - Confiança: Aumento na confiança dos visitantes em relação ao curso.

## Evidências de Implementação
Aqui irei demonstrar, com evidências, as principais alterações que fizemos no código do projeto para que se adaptasse às nossas propostas de alteração, presentes no arquivo ["Preposição Teste A/B"]("https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/docs/sprint3/Preposicao%20Teste.md").

### Alterações no código

As nossa alterações consistiram na alteração e inclusão dos arquivos abaixo:
<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image-3.png"/>
Imagem 1 - Arquivos de código alterados (arquivo pessoal)

### Alterações em `assets`
As alterações na pasta de `assets` consistiram em algumas mudanças no CSS, adaptando-o às novas propostas. A identificação dos itens a serem alterados foi realizada por meio do uso de DevTools do Google para depuração e modificação no site da Wizard ON.
<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image-4.png"/>
Imagem 2 - DevTools do Google (arquivo pessoal)

### Alterações em `themes`
A pasta de `themes` era a principal, contendo o código da home page e componentes como o header e o footer. As maiores alterações foram feitas nessa parte, incluindo a adição da nova imagem do botão do WhatsApp. Também foram realizadas pequenas alterações no header, footer e em um modal. Abaixo estão as capturas de tela e os detalhes das modificações:
<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image-5.png"/>
Imagem 3 - Header (arquivo pessoal)

<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image-6.png"/>
Imagem 4 - Formulário (arquivo pessoal)

<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image-7.png"/>
Imagem 5 - Footer (arquivo pessoal)

### Alterações em `home.php`
As alterações feitas nesse arquivo foram as maiores e mais essenciais. A principal mudança foi a organização dos componentes e a introdução da nova campanha da Wizard ON. Uma grande alteração é que as informações nas setinhas, que dentro do código são chamadas de "rtb", foram transformadas em uma `div` para que fossem colocadas dentro do banner e ficassem ao lado do formulário. No próximo tópico será possível verificar algumas das alterações feitas no código.

### Alterações dentro do código:
- home.php
    - Muitas alterações foram feitas no código, por isso não iremos abrir de forma detalhada, mas sim mostrar as principais alterações feitas no código.
```php
<main id="homepage">
	<section id="banner">
	</section>

	<section id="propaganda">
	</section>

	<section id="promo">
	</section>

	<section id="wizmenew">
	</section>
	
	<section id="compromisso">
	</section>

	<section id="faq">
	</section>
</main>
```

- footer.php
```php
<a id="robbu-whatsapp-button" target="_blank" href="https://api.whatsapp.com/send?phone=5511994203008&amp;text=Quero%20saber%20mais%20informa%C3%A7%C3%B5es.">
	<img src="<?= asset("web", "images/botao-wpp.png") ?>"> </a>
```

- header.php
```php
    <a data-scroll href="#form" class="w-100 btn btn-red">EU QUERO!</a>
    <a data-scroll href="#form" class="d-none d-lg-block btn btn-red ">EU QUERO!</a>
```

- leadModal.php
```php
        APRENDA INGLÊS
        <span class="bg-red px-2 text-white d-inline-block"> ONDE VOCÊ ESTIVER! </span>
    </h2>
    <small>Preencha agora o formulário e entraremos em contato para mais informações.</small>

    <button class="btn btn-red text-white btn-lg cursor-pointer" id="submitFormCta" disabled="true" type="submit">
        EU QUERO!
    </button>

```

- _homepage.php
```css
	#propaganda {
		padding: 2rem 0;
		background: $blue url("../../../themes/web/images/background-banner.webp") no-repeat center center/cover;
		overflow: hidden;

		@media (max-width: 991px) {
			min-height: auto;
			background: $blue url(" ../../../themes/web/images/background-banner-mobile.webp") no-repeat top center;
		}

	#wizmenew {
		padding: 2rem 0 0;
		background-color: #f3f3f3;

		.text {
			color: #003057;
			text-align: start;
			padding-top: 3.5rem
				}
		.text b {
			margin-bottom: 1.2rem;
			margin-top: 1.2rem;
			font-size: 2rem;
			display: block;
			line-height: 2rem
		}
	}

	#compromisso {
		padding: 2rem 0;
		background-color: #ffffff;

		.my-3 {
			color: #003057;
			font-weight: 600;
			font-size: 22px
				}
		.mb-3 {
			color: #003057;
			font-weight: 600;
			font-size: 24px
		}
	}
```


Estas evidências mostram as mudanças implementadas, garantindo que todas as alterações foram bem documentadas e justificadas, conforme os critérios de avaliação estabelecidos. Essas mudanças foram cuidadosamente testadas para assegurar a preservação da funcionalidade original e a consistência com a identidade da marca, além de melhorar a experiência do usuário.

## Apoio no Processo de Homologação

Primeiramente, para que o processo de homologação seja feito de forma eficiente, é necessário que o cliente tenha acesso ao código fonte da página, para que possa ser feita a comparação entre a página original e a proposta de alteração. Por isso foi feito a entrega do código fonte da página para o servidor passado pelo cliente, utilizando a ferramenta FileZilla.

Para quaisquer questões ou dúvidas de como rodar o projeto, é sugerido que siga o passo a passo disponibilizado pelo próprio cliente, que vai desde a instalação de todas as dependências necessárias para rodar o projeto, até a execução do projeto em si no servidor de homologação.

Por fim, para que tenhamos um guia claro de como passar todas as alterações feitas para o deploy no servidor, é necessário, como dito anteriormente, ter o softwatere FileZilla instalado, pois assim é possível fazer a transferência de arquivos da raiz do computador para os arquivos do servidor. Veja as imagens abaixo para entender como é feito o processo de transferência de arquivos:

1. Execute o programa FileZilla instalado anteriormente.
2. Clique no ícone do Gerenciador de Sites.
<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image.png"/>

3. Na janela que se abrir, insira as informações correspondentes ao servidor de homologação.
<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image-1.png"/>

4. Assim que informar esses dados, no lado esquerdo, clique em Renomear, para
renomear o novo site e atribuir um nome amigável de fácil identificação.
5. Quanto tudo estiver corretamente configurado, clique em Conectar para salvar as
informações e estabelecer uma conexão com o servidor.
6. Assim que o FileZilla concluir a conexão, você verá do lado esquerdo da tela a árvore
de arquivos local e do lado direito a árvore de arquivos remota. Na árvore local,
navegue até a pasta da aplicação em seu computador. Você verá que a organização das
pastas é igual.
<img src="https://github.com/Inteli-College/2024-1B-T04-SI10-G05/blob/main/assets/proposta_b/image-2.png"/>

7. Para enviar os arquivos ao servidor, selecione os desejados na árvore local e arraste para a árvore remota. Aguarde a conclusão do envio dos arquivos. Se houver necessidade, você pode confirmar a operação de substituir os arquivos.
8. Acesse o domínio correspondente ao seu grupo para visualizar as atualizações publicadas.