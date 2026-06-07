# Miniguia de Estudos com NotebookLM: Gestao Financeira Aplicada a Impressao 3D

## Contexto do Projeto

Este projeto foi desenvolvido como parte de um desafio pratico da DIO, com o objetivo de explorar o uso da Inteligencia Artificial como ferramenta de aprendizagem ativa.

O tema escolhido para o caderno tematico no NotebookLM foi:

**Gestao financeira basica aplicada a impressao 3D: custos, precificacao, fluxo de caixa e controle de desperdicios.**

A escolha do tema conecta conceitos introdutorios de educacao financeira com uma aplicacao pratica em impressao 3D, especialmente para quem utiliza impressoras como a **Anycubic Kobra S1 Combo** em estudos, pequenos servicos, prototipagem ou possivel geracao de renda.

A ideia central foi usar o NotebookLM para organizar fontes confiaveis, elaborar perguntas estrategicas, testar prompts e consolidar um miniguia de estudo que ajude iniciantes a entender como controlar custos, definir precos e reduzir perdas em projetos de impressao 3D.

## Objetivos de Estudo

Os principais objetivos deste caderno foram:

- Compreender conceitos basicos de controle financeiro, fluxo de caixa e planejamento.
- Entender a diferenca entre receita, custo, despesa, lucro e margem.
- Aprender como a precificacao influencia a sustentabilidade de um pequeno projeto ou negocio.
- Relacionar falhas de impressao 3D com desperdicio financeiro, retrabalho e perda de produtividade.
- Criar perguntas estrategicas para estudar o tema com apoio de IA.
- Registrar variacoes de prompts, respostas obtidas e dificuldades encontradas durante o processo.
- Consolidar um miniguia com resumos, glossario e prompts reutilizaveis para revisoes futuras.

## Curadoria de Fontes

Foram selecionadas fontes abertas em texto e PDF, priorizando materiais introdutorios, confiaveis e aplicaveis ao contexto do projeto.

| Fonte | Tipo | Uso no Projeto |
|---|---|---|
| [Sebrae - Controle financeiro para pequenas empresas](https://sebrae.com.br/sites/PortalSebrae/ufs/es/Biblioteca-Digital/Finan%C3%A7as/controle-financeiros-para-pequenas-empresas%2C6287029a85ce5910VgnVCM1000001b00320aRCRD) | Texto/Ebook | Base para controles financeiros, organizacao de entradas e saidas e gestao simples. |
| [Sebrae - Fluxo de Caixa](https://sebrae.com.br/Sebrae/Portal%20Sebrae/Anexos/0_fluxo-de-caixa.pdf) | PDF | Referencia para entender fluxo de caixa, saldo do periodo e acompanhamento financeiro. |
| [Sebrae - A importancia da determinacao do preco de venda](https://sebrae.com.br/Sebrae/Portal%20Sebrae/UFs/MG/Imagens/Infogra%CC%81fico%20-%20A%20Importa%CC%82ncia%20da%20determinac%CC%A7a%CC%83o%20do%20prec%CC%A7o%20de%20venda%20%2802%29.pdf) | PDF | Base para estudo de precificacao, custos, despesas e margem. |
| [Banco Central - Caderno de Educacao Financeira](https://www.bcb.gov.br/pre/pef/port/caderno_cidadania_financeira.pdf) | PDF | Apoio conceitual sobre planejamento financeiro, orcamento e tomada de decisao. |
| [Acelera3D - Guia de erros de impressao 3D](https://acelera3d.com/erros-3d/) | Texto | Fonte tecnica para relacionar falhas de impressao com retrabalho, desperdicio e custos. |

## Engenharia de Prompts e Cicatrizes

Durante o uso do NotebookLM, foram testadas perguntas estrategicas e variacoes de prompts para obter respostas mais uteis, aplicaveis e bem referenciadas.

### Prompt 1

```text
Explique os principais controles financeiros que uma pessoa iniciante precisa acompanhar em um pequeno projeto de impressao 3D.
```

**Resultado esperado:** uma explicacao simples sobre entradas, saidas, custos, despesas e lucro.

**Resposta obtida:** o NotebookLM destacou a importancia de registrar receitas e despesas, controlar o fluxo de caixa e separar gastos pessoais dos gastos da atividade.

**Referencia principal:** materiais do Sebrae sobre controle financeiro e fluxo de caixa.

**Cicatriz / dificuldade:** a primeira resposta ficou muito generica e pouco conectada a impressao 3D.

**Ajuste feito no prompt:**

```text
Explique os principais controles financeiros para um pequeno projeto de impressao 3D, considerando filamento, energia, manutencao, falhas de impressao, tempo de maquina e preco de venda.
```

**Melhoria percebida:** a resposta passou a conectar melhor os conceitos financeiros com a realidade da impressao 3D.

---

### Prompt 2

```text
Quais custos devem ser considerados para precificar uma peca impressa em 3D?
```

**Resultado esperado:** lista de custos diretos e indiretos.

**Resposta obtida:** foram citados custos com material, energia, tempo, manutencao e margem desejada.

**Referencia principal:** material do Sebrae sobre preco de venda e fonte tecnica sobre erros de impressao 3D.

**Cicatriz / dificuldade:** a IA inicialmente nao diferenciou bem custo variavel, custo fixo e despesa.

**Ajuste feito no prompt:**

```text
Classifique os custos de uma peca impressa em 3D em custos variaveis, custos fixos e despesas, explicando como cada grupo afeta a formacao do preco de venda.
```

**Melhoria percebida:** a resposta ficou mais organizada e mais facil de transformar em planilha ou dashboard.

---

### Prompt 3

```text
Como as falhas de impressao 3D impactam o resultado financeiro de um projeto?
```

**Resultado esperado:** conexao entre problemas tecnicos e perdas financeiras.

**Resposta obtida:** o NotebookLM relacionou erros como falta de aderencia, deformacoes, entupimentos e retrabalho com desperdicio de filamento, tempo de maquina e energia.

**Referencia principal:** Acelera3D, combinada com conceitos de custo e controle financeiro do Sebrae.

**Cicatriz / dificuldade:** a IA trouxe muitos exemplos tecnicos, mas inicialmente faltou traduzir isso em impacto financeiro.

**Ajuste feito no prompt:**

```text
Transforme os principais erros de impressao 3D em exemplos de impacto financeiro, mostrando como cada erro pode gerar desperdicio, retrabalho ou reducao do lucro.
```

**Melhoria percebida:** a resposta ficou mais pratica e conectada ao objetivo do projeto.

---

### Prompt 4

```text
Crie um checklist financeiro antes de aceitar uma encomenda de impressao 3D.
```

**Resultado esperado:** lista pratica para tomada de decisao.

**Resposta obtida:** a IA sugeriu verificar custo do material, tempo estimado, risco de erro, prazo, margem e preco final.

**Referencia principal:** Sebrae sobre controle financeiro e preco de venda.

**Cicatriz / dificuldade:** a primeira versao parecia uma lista comum de tarefas, sem orientar decisao.

**Ajuste feito no prompt:**

```text
Crie um checklist financeiro de decisao para saber se vale a pena aceitar uma encomenda de impressao 3D, incluindo criterios de custo, tempo, risco de falha, preco minimo e margem.
```

**Melhoria percebida:** o checklist ficou mais util para avaliar se uma encomenda e viavel.

## Miniguia de Estudo

### 1. Controle financeiro

O controle financeiro e o registro organizado de tudo o que entra e sai de dinheiro. Em um pequeno projeto de impressao 3D, isso inclui valores recebidos por pecas vendidas, gastos com filamento, energia eletrica, manutencao, bicos, mesa, cola, embalagem, transporte e outros custos.

Sem controle financeiro, a pessoa pode acreditar que esta tendo lucro apenas porque recebeu dinheiro, mas sem perceber que os custos consumiram grande parte do resultado.

### 2. Fluxo de caixa

O fluxo de caixa permite acompanhar entradas e saidas em determinado periodo. Ele ajuda a responder perguntas como:

- Quanto entrou no mes?
- Quanto foi gasto?
- Qual foi o saldo final?
- O projeto esta gerando lucro ou prejuizo?
- Existem gastos recorrentes que precisam ser reduzidos?

Na impressao 3D, o fluxo de caixa pode ser organizado por dia, semana ou mes, registrando cada servico realizado e cada despesa relacionada.

### 3. Precificacao

Precificar uma peca impressa em 3D nao significa apenas somar o valor do filamento. O preco deve considerar:

- Material utilizado.
- Energia eletrica.
- Tempo de impressao.
- Tempo de preparacao e acabamento.
- Risco de falha.
- Manutencao da impressora.
- Desgaste de pecas.
- Embalagem.
- Impostos ou taxas, se houver.
- Margem de lucro.

Uma precificacao mal feita pode gerar vendas com prejuizo, mesmo quando ha movimento financeiro.

### 4. Custos fixos, custos variaveis e despesas

Custos variaveis mudam conforme a producao. Na impressao 3D, exemplos incluem filamento, energia e embalagem.

Custos fixos existem mesmo que nenhuma peca seja vendida. Exemplos: assinatura de software, aluguel de espaco, internet ou depreciacao da impressora.

Despesas sao gastos de apoio, como transporte, divulgacao, ferramentas, organizacao e manutencao administrativa.

Separar esses grupos ajuda a entender o preco minimo necessario para nao ter prejuizo.

### 5. Falhas de impressao e desperdicio

Erros de impressao impactam diretamente o resultado financeiro. Uma peca perdida nao consome apenas filamento. Ela tambem consome energia, tempo de maquina, tempo de preparacao e pode atrasar entregas.

Problemas como falta de aderencia, warping, entupimento, stringing, deslocamento de camada ou ma calibragem aumentam o custo real da producao. Por isso, melhorar a calibragem e reduzir erros tambem e uma decisao financeira.

### 6. Tomada de decisao

Antes de aceitar uma encomenda, e importante avaliar se o preco cobre todos os custos e ainda gera margem. Um projeto pode parecer simples, mas se tiver alto risco de falha, acabamento demorado ou consumo elevado de material, talvez precise de preco maior.

A IA pode ajudar a organizar essas analises, mas o usuario precisa conferir as fontes, validar os calculos e aplicar pensamento critico.

## Glossario

**Receita:** valor recebido por vendas ou servicos.

**Custo:** gasto diretamente ligado a producao de uma peca ou servico.

**Despesa:** gasto necessario para manter a atividade, mas que nao esta diretamente ligado a uma peca especifica.

**Lucro:** resultado positivo apos subtrair custos e despesas da receita.

**Prejuizo:** resultado negativo quando os custos e despesas superam a receita.

**Fluxo de caixa:** controle das entradas e saidas de dinheiro em um periodo.

**Precificacao:** processo de definir o preco de venda de um produto ou servico.

**Custo variavel:** custo que aumenta ou diminui conforme a quantidade produzida.

**Custo fixo:** custo que permanece mesmo sem producao.

**Margem de lucro:** percentual ou valor que sobra apos cobrir custos e despesas.

**Margem de contribuicao:** valor que sobra da venda apos custos variaveis, ajudando a pagar custos fixos e gerar lucro.

**Retrabalho:** necessidade de refazer uma peca ou corrigir falhas.

**Desperdicio:** perda de material, tempo, energia ou recursos.

**Viabilidade:** analise para entender se um projeto vale a pena financeiramente.

## Prompts Reutilizaveis

```text
Explique de forma simples os principais conceitos financeiros deste caderno, usando exemplos de impressao 3D.
```

```text
Liste os custos fixos, custos variaveis e despesas de um pequeno projeto de impressao 3D.
```

```text
Crie um modelo simples de fluxo de caixa mensal para uma pessoa que vende pecas impressas em 3D.
```

```text
Explique como calcular o preco minimo de uma peca impressa em 3D considerando material, energia, tempo, falhas e margem.
```

```text
Transforme os principais erros de impressao 3D em exemplos de impacto financeiro.
```

```text
Crie um checklist para avaliar se vale a pena aceitar uma encomenda de impressao 3D.
```

```text
Gere 10 perguntas de revisao sobre controle financeiro, fluxo de caixa e precificacao aplicados a impressao 3D.
```

```text
Resuma as fontes deste caderno em topicos objetivos para estudo rapido.
```

```text
Crie uma tabela com conceito, definicao simples e exemplo pratico em impressao 3D.
```

```text
Aponte quais informacoes financeiras eu deveria registrar em uma planilha ou dashboard para acompanhar meu projeto de impressao 3D.
```

## Aprendizados do Projeto

Este desafio mostrou que o NotebookLM pode ser usado como uma ferramenta de estudo ativo, nao apenas como um gerador de respostas. Ao trabalhar com fontes selecionadas, perguntas estrategicas e variacoes de prompts, foi possivel transformar materiais introdutorios em um guia pratico e aplicavel.

O principal aprendizado foi que a qualidade da resposta da IA depende da qualidade das fontes, da clareza da pergunta e da capacidade de revisar criticamente o resultado.

No contexto da impressao 3D, o estudo tambem mostrou que conhecimento tecnico e financeiro precisam caminhar juntos. Melhorar calibragem, reduzir falhas e controlar custos sao partes do mesmo processo de profissionalizacao.

## Como Este Projeto Pode Evoluir

Este caderno pode ser expandido futuramente com:

- Uma planilha de calculo de custos de impressao 3D.
- Um dashboard em Power BI para acompanhar receitas, despesas e margem.
- Comparacao entre diferentes tipos de filamento.
- Analise de viabilidade para venda de pecas personalizadas.
- Guia pratico de precificacao para iniciantes.
- Integracao com o projeto de conhecimento sobre Anycubic Kobra S1 Combo.

## Descricao para Entrega na DIO

Projeto desenvolvido com NotebookLM para criar um miniguia de estudos sobre gestao financeira basica aplicada a impressao 3D. O trabalho reuniu fontes abertas sobre controle financeiro, fluxo de caixa, precificacao, planejamento financeiro e erros de impressao 3D. A partir dessas fontes, foram definidos objetivos de estudo, perguntas estrategicas, variacoes de prompts, registros de dificuldades e um guia final com resumos, glossario e prompts reutilizaveis.

O projeto conecta educacao financeira introdutoria com uma aplicacao pratica em impressao 3D, demonstrando o uso da IA como ferramenta de aprendizagem ativa, organizacao do conhecimento e apoio a tomada de decisao.
