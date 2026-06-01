# Caderno Temático no NotebookLM: Introdução aos Investimentos

## Contexto e Objetivos

Este projeto prático visa explorar o uso da Inteligência Artificial como uma ferramenta de aprendizagem ativa, aplicando pensamento crítico, curadoria de fontes e organização do conhecimento para criar um Caderno Temático no NotebookLM. Como estudante de tecnologia, escolhi o assunto **"Introdução aos Investimentos"** para demonstrar a capacidade de sintetizar informações complexas e estruturar um material de estudo abrangente e acessível.

Os objetivos de estudo com este material são:

* **Compreender os conceitos fundamentais de investimentos:** Adquirir uma base sólida sobre o que são investimentos, seus tipos, riscos e retornos.
* **Identificar e analisar diferentes modalidades de investimento:** Explorar as características de investimentos como Tesouro Direto, fundos de investimento e outros ativos de renda fixa e variável.
* **Desenvolver habilidades de curadoria de conteúdo:** Selecionar e avaliar fontes de informação confiáveis e relevantes para o tema.
* **Aprimorar a engenharia de prompts para IA:** Elaborar perguntas estratégicas e otimizar prompts para extrair informações precisas e úteis de modelos de linguagem, documentando o processo e as "cicatrizes" (dificuldades e soluções).
* **Organizar o conhecimento de forma estruturada:** Criar resumos, glossários e prompts reutilizáveis que facilitem a revisão e o aprendizado contínuo.
* **Demonstrar maturidade técnica na estruturação de um repositório GitHub:** Organizar o projeto de forma clara e profissional, contemplando todas as etapas do desenvolvimento.

## Curadoria de Fontes

A seguir, são listadas as fontes abertas em texto ou PDF que foram selecionadas para o upload no NotebookLM e que servirão como base para a construção do Caderno Temático. Estas fontes foram escolhidas por sua relevância, autoridade e acessibilidade para o público iniciante em investimentos:

1. **Livros CVM - Publicações Educacionais** \[1]

   * **Descrição:** Série de publicações educacionais desenvolvidas ou apoiadas pela CVM, com foco em temas relevantes do mercado de capitais, apresentados em linguagem acessível.
   * **Link:** https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm
2. **Guia do Investidor - Tesouro Direto** \[2]

   * **Descrição:** Material informativo sobre o Tesouro Direto, programa que permite a qualquer pessoa física investir em títulos públicos federais pela internet, com foco em previsibilidade e segurança.
   * **Link:** https://repositorio.enap.gov.br/bitstream/1/6248/1/Guia\_Investidor%20TD.pdf
3. **Princípios de Investimento - Material de Estudos CPA-10 (ANBIMA)** \[3]

   * **Descrição:** Capítulo do material de estudos da certificação CPA-10 da ANBIMA, que aborda os princípios fundamentais de investimento, incluindo fatores de análise, rentabilidade, liquidez e riscos.
   * **Link:** https://www.anbima.com.br/data/files/74/40/1D/33/466A4810EA926748882BA2A8/CPA-10-Cap4.pdf

# Miniguia de Estudo: Introdução aos Investimentos

Este miniguia de estudo consolida os principais aprendizados sobre a introdução aos investimentos, com base nas fontes curadas. Ele é composto por resumos estruturados, um glossário de termos essenciais e um conjunto de prompts reutilizáveis para auxiliar em futuras revisões.

## Resumos Estruturados

### 1\. Conceitos Fundamentais de Investimento

Investimento é a aplicação de recursos (dinheiro) com a expectativa de obter um retorno futuro, seja na forma de juros, dividendos ou valorização do ativo. Diferente da poupança, que apenas guarda o dinheiro, o investimento busca multiplicá-lo. Os principais fatores a serem considerados em qualquer investimento são a **rentabilidade**, a **liquidez** e o **risco** \[3].

* **Rentabilidade:** Refere-se ao ganho obtido com o investimento. Pode ser prefixada (conhecida no momento da aplicação) ou pós-fixada (atrelada a um índice, como Selic ou IPCA) \[2].
* **Liquidez:** É a facilidade e rapidez com que um investimento pode ser convertido em dinheiro sem perdas significativas. Investimentos de alta liquidez são importantes para reservas de emergência \[2] \[3].
* **Risco:** A possibilidade de o retorno real do investimento ser diferente do esperado, incluindo a chance de perda do capital. Existem diversos tipos de risco, como risco de mercado, risco de crédito e risco de liquidez \[3].

### 2\. Tesouro Direto

O Tesouro Direto é um programa do Tesouro Nacional que permite a pessoas físicas investir em títulos públicos federais pela internet, com foco em previsibilidade e segurança \[2]. É considerado um investimento de renda fixa, onde a regra de rentabilidade e os pagamentos de juros são conhecidos no momento da aplicação. É acessível a pequenos investidores, com aplicações a partir de aproximadamente trinta reais \[2].

**Tipos de Títulos do Tesouro Direto:**

|Tipo de Título|Característica Principal|Indicação|Observações|
|-|-|-|-|
|**Tesouro Prefixado**|Taxa de juros fixa, conhecida na aplicação.|Objetivos de médio e longo prazo.|O investidor sabe exatamente o valor a receber no vencimento.|
|**Tesouro Selic**|Rentabilidade atrelada à Taxa Selic.|Reserva de emergência, curto prazo.|Preço do título aumenta diariamente conforme a Selic.|
|**Tesouro IPCA+**|Rentabilidade atrelada ao IPCA (inflação) + taxa fixa.|Proteção contra inflação, longo prazo.|Rentabilidade real garantida acima da inflação.|

**Custos e Impostos:**

* **Taxa de Custódia (B3):** 0,25% ao ano sobre o valor aplicado \[2].
* **Taxa de Administração (Instituição Financeira):** Pode variar de 0% a 2% ao ano \[2].
* **Imposto de Renda (IR):** Alíquota regressiva sobre os rendimentos, conforme o prazo do investimento (de 22,5% para até 180 dias a 15% para mais de 720 dias) \[2].
* **IOF (Imposto sobre Operações Financeiras):** Incide apenas para resgates com menos de 30 dias \[2].

### 3\. Fatores de Análise de Investimentos (CPA-10 ANBIMA)

Ao analisar um investimento, é crucial considerar diversos fatores que impactam seu desempenho e adequação ao perfil do investidor. A ANBIMA, em seu material CPA-10, destaca a importância de entender a rentabilidade, liquidez e risco, além de outros riscos específicos \[3].

* **Risco de Mercado:** Variações nos preços dos ativos devido a fatores macroeconômicos, políticos ou setoriais \[3].
* **Risco de Crédito:** Possibilidade de o emissor do título (governo, empresa, banco) não honrar seus compromissos de pagamento \[3].
* **Risco de Liquidez:** Dificuldade em vender um ativo rapidamente sem que haja perda significativa de valor \[3].

## Glossário de Conceitos Essenciais

* **Ativo:** Bem ou direito que possui valor econômico e pode gerar benefícios futuros.
* **CVM (Comissão de Valores Mobiliários):** Autarquia federal que fiscaliza, normatiza, disciplina e desenvolve o mercado de valores mobiliários no Brasil \[1].
* **IPCA (Índice Nacional de Preços ao Consumidor Amplo):** Índice oficial de inflação do Brasil, medido pelo IBGE.
* **Liquidez:** Capacidade de um investimento ser convertido em dinheiro rapidamente, sem perda substancial de valor.
* **Renda Fixa:** Modalidade de investimento onde a forma de cálculo da remuneração é definida no momento da aplicação, oferecendo maior previsibilidade \[2].
* **Renda Variável:** Modalidade de investimento onde não é possível prever o retorno no momento da aplicação, pois ele varia conforme as condições de mercado (ex: ações).
* **Rentabilidade:** O retorno ou lucro gerado por um investimento em um determinado período.
* **Risco:** A incerteza sobre os retornos futuros de um investimento, incluindo a possibilidade de perdas.
* **Selic (Sistema Especial de Liquidação e de Custódia):** Taxa básica de juros da economia brasileira, definida pelo Banco Central.
* **Tesouro Direto:** Programa do Tesouro Nacional que permite a pessoas físicas investir em títulos públicos federais \[2].
* **Títulos Públicos:** Dívidas emitidas pelo governo para financiar suas atividades, consideradas de baixo risco de crédito.

## Conjunto de Prompts Reutilizáveis

Estes prompts são projetados para serem utilizados com modelos de linguagem (como o NotebookLM) para aprofundar o estudo e revisar os conceitos de investimentos. Eles foram elaborados para serem claros, diretos e focados na extração de informações específicas.

1. **Prompt para Resumo de Conceitos:**

&#x20;   `"Explique de forma concisa os conceitos de \\\[CONCEITO\\\_1], \\\[CONCEITO\\\_2] e \\\[CONCEITO\\\_3] no contexto de investimentos, destacando suas inter-relações e importância para o investidor iniciante. Utilize as fontes fornecidas para embasar a resposta."`

*Exemplo:* "Explique de forma concisa os conceitos de rentabilidade, liquidez e risco no contexto de investimentos, destacando suas inter-relações e importância para o investidor iniciante. Utilize as fontes fornecidas para embasar a resposta."

2. **Prompt para Comparação de Títulos (Tesouro Direto):**

   &#x20;   ```
"Compare os títulos \[TÍTULO\_1] e \[TÍTULO\_2] do Tesouro Direto, abordando suas características de rentabilidade, indicação de perfil de investidor e cenários econômicos ideais para cada um. Inclua informações sobre os custos e impostos aplicáveis. Baseie-se nas informações do 'Guia do Investidor - Tesouro Direto'."

   &#x20;   ```

   \*Exemplo:\* "Compare os títulos Tesouro Selic e Tesouro IPCA+ do Tesouro Direto, abordando suas características de rentabilidade, indicação de perfil de investidor e cenários econômicos ideais para cada um. Inclua informações sobre os custos e impostos aplicáveis. Baseie-se nas informações do 'Guia do Investidor - Tesouro Direto'."

3. \*\*Prompt para Análise de Riscos:\*\*

3. **Prompt para Análise de Riscos:**

   &#x20;   ```
"Descreva os principais tipos de risco associados a investimentos, como \[TIPO\_RISCO\_1], \[TIPO\_RISCO\_2] e \[TIPO\_RISCO\_3]. Explique como cada um pode afetar o investidor e quais estratégias podem ser adotadas para mitigá-los, conforme o material 'Princípios de Investimento - CPA-10 (ANBIMA)'."

   &#x20;   ```

   \*Exemplo:\* "Descreva os principais tipos de risco associados a investimentos, como risco de mercado, risco de crédito e risco de liquidez. Explique como cada um pode afetar o investidor e quais estratégias podem ser adotadas para mitigá-los, conforme o material 'Princípios de Investimento - CPA-10 (ANBIMA)'."

4. \*\*Prompt para Definição de Termo Específico:\*\*

4. **Prompt para Definição de Termo Específico:**

   &#x20;   ```
"Qual a definição de \[TERMO\_ESPECÍFICO] no contexto do mercado financeiro e qual sua relevância para o investidor? Cite a fonte de onde a informação foi extraída."

   &#x20;   ```

   \*Exemplo:\* "Qual a definição de CVM no contexto do mercado financeiro e qual sua relevância para o investidor? Cite a fonte de onde a informação foi extraída."

# Engenharia de Prompts e "Cicatrizes"

Esta seção documenta o processo iterativo de elaboração e refinamento de prompts para interagir com modelos de linguagem (IA), com o objetivo de extrair informações precisas e úteis sobre Introdução aos Investimentos. Serão apresentados exemplos de prompts iniciais, as respostas obtidas, as dificuldades ("cicatrizes") e as estratégias de refinamento para alcançar resultados mais satisfatórios.

## Exemplo 1: Conceitos Fundamentais

### Prompt Inicial

```
"O que são investimentos?"
```

### Resposta da IA

> "Investimentos são a aplicação de capital com a expectativa de obter um retorno financeiro. Existem diversos tipos, como renda fixa e renda variável."

### Referências da IA

> Nenhuma referência específica fornecida, resposta genérica.

### Dificuldades/Observações ("Cicatrizes")

A resposta foi muito genérica e superficial, sem aprofundar nos conceitos essenciais como rentabilidade, liquidez e risco, que são cruciais para um iniciante. Não houve menção às fontes curadas, o que dificulta a verificação da informação.

### Prompt Refinado

```
"Explique de forma concisa os conceitos de rentabilidade, liquidez e risco no contexto de investimentos, destacando suas inter-relações e importância para o investidor iniciante. Utilize as fontes fornecidas para embasar a resposta, especialmente o 'Guia do Investidor - Tesouro Direto' e 'Princípios de Investimento - CPA-10 (ANBIMA)'."
```

### Resposta Otimizada da IA

> "No contexto de investimentos, \\\*\\\*rentabilidade\\\*\\\* refere-se ao ganho obtido, podendo ser prefixada ou pós-fixada \\\[2]. A \\\*\\\*liquidez\\\*\\\* é a facilidade de converter o investimento em dinheiro sem perdas, sendo vital para reservas de emergência \\\[2] \\\[3]. O \\\*\\\*risco\\\*\\\* é a possibilidade de o retorno real ser diferente do esperado, incluindo a perda de capital, e abrange tipos como risco de mercado, crédito e liquidez \\\[3]. Esses três conceitos estão interligados: geralmente, maior rentabilidade potencial está associada a maior risco e/ou menor liquidez. Para o investidor iniciante, compreender essa tríade é fundamental para tomar decisões alinhadas aos seus objetivos e perfil."

### Lições Aprendidas

Especificar os conceitos desejados, o contexto e as fontes de referência direciona a IA para uma resposta mais detalhada e embasada. A solicitação de inter-relações e importância para o público-alvo (investidor iniciante) ajuda a contextualizar a informação de forma mais útil.

## Exemplo 2: Comparação de Títulos do Tesouro Direto

### Prompt Inicial

```
"Quais são os títulos do Tesouro Direto?"
```

### Resposta da IA

> "Os títulos do Tesouro Direto são Tesouro Prefixado, Tesouro Selic e Tesouro IPCA+."

### Referências da IA

> Nenhuma referência específica fornecida.

### Dificuldades/Observações ("Cicatrizes")

A resposta foi correta, mas muito breve. Não forneceu detalhes sobre as características de cada título, suas indicações ou os custos envolvidos, informações essenciais para a tomada de decisão do investidor.

### Prompt Refinado

```
"Compare os títulos Tesouro Selic e Tesouro IPCA+ do Tesouro Direto, abordando suas características de rentabilidade, indicação de perfil de investidor e cenários econômicos ideais para cada um. Inclua informações sobre os custos e impostos aplicáveis. Baseie-se nas informações do 'Guia do Investidor - Tesouro Direto'."
```

### Resposta Otimizada da IA

> "O \\\*\\\*Tesouro Selic\\\*\\\* possui rentabilidade atrelada à Taxa Selic, sendo ideal para quem busca liquidez e segurança, como a formação de reserva de emergência, e é indicado para cenários de alta ou estabilidade da Selic \\\[2]. Já o \\\*\\\*Tesouro IPCA+\\\*\\\* oferece rentabilidade atrelada ao IPCA (inflação) mais uma taxa fixa, sendo recomendado para proteção contra a inflação e objetivos de longo prazo \\\[2]. Ambos estão sujeitos à taxa de custódia da B3 (0,25% a.a.) e, opcionalmente, taxa de administração da instituição financeira. O Imposto de Renda incide de forma regressiva sobre os rendimentos, e o IOF apenas para resgates em menos de 30 dias \\\[2]."

### Lições Aprendidas

Solicitar uma comparação explícita entre elementos específicos e detalhar os aspectos a serem comparados (rentabilidade, indicação, cenários, custos) força a IA a fornecer uma análise mais aprofundada e estruturada, utilizando as fontes indicadas.

## Exemplo 3: Análise de Riscos

### Prompt Inicial

```
"Fale sobre os riscos de investir."
```

### Resposta da IA

> "Investir sempre envolve riscos, como perder dinheiro. É importante pesquisar antes de investir."

### Referências da IA

> Nenhuma referência específica fornecida.

### Dificuldades/Observações ("Cicatrizes")

A resposta é excessivamente simplista e não aborda os tipos específicos de riscos financeiros, nem como eles se manifestam ou podem ser gerenciados. A falta de detalhe é inaceitável para um guia de estudo.

### Prompt Refinado

```
"Descreva os principais tipos de risco associados a investimentos, como risco de mercado, risco de crédito e risco de liquidez. Explique como cada um pode afetar o investidor e quais estratégias podem ser adotadas para mitigá-los, conforme o material 'Princípios de Investimento - CPA-10 (ANBIMA)'."
```

### Resposta Otimizada da IA

> "Os principais riscos em investimentos incluem o \\\*\\\*risco de mercado\\\*\\\*, que se refere às variações nos preços dos ativos devido a fatores macroeconômicos ou setoriais; o \\\*\\\*risco de crédito\\\*\\\*, que é a possibilidade de o emissor do título não cumprir com suas obrigações de pagamento; e o \\\*\\\*risco de liquidez\\\*\\\*, que é a dificuldade de vender um ativo rapidamente sem perdas significativas \\\[3]. Para mitigar esses riscos, estratégias como a diversificação da carteira, a análise da solidez do emissor e a escolha de investimentos com liquidez adequada ao seu horizonte de tempo são cruciais \\\[3]."

### Lições Aprendidas

   Ao listar explicitamente os tipos de risco a serem abordados e solicitar a explicação de seus efeitos e estratégias de mitigação, a IA é capaz de fornecer uma análise mais completa e útil, baseada na fonte indicada. Isso transforma uma resposta vaga em um conteúdo educacional valioso.

\---

## Referências

\[1] Livros CVM - Publicações Educacionais. Disponível em: [https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm](https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm)
\[2] Guia do Investidor - Tesouro Direto. Disponível em: [https://repositorio.enap.gov.br/bitstream/1/6248/1/Guia\_Investidor%20TD.pdf](https://repositorio.enap.gov.br/bitstream/1/6248/1/Guia_Investidor%20TD.pdf)
\[3] Princípios de Investimento - Material de Estudos CPA-10 (ANBIMA). Disponível em: [https://www.anbima.com.br/data/files/74/40/1D/33/466A4810EA926748882BA2A8/CPA-10-Cap4.pdf](https://www.anbima.com.br/data/files/74/40/1D/33/466A4810EA926748882BA2A8/CPA-10-Cap4.pdf)

