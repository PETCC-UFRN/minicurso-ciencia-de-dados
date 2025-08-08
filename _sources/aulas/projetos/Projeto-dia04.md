# Projeto - Dia 4: Testes e Hipóteses

## Validando Nossas Descobertas

Parabéns por chegarem ao Dia 4 do nosso projeto! Vocês já dominaram a limpeza de dados, a análise exploratória e a identificação de padrões através do clustering. Agora, é hora de levar suas análises para o próximo nível: a validação estatística. Neste dia, vamos focar em **Testes de Hipóteses**, uma ferramenta fundamental para confirmar se os padrões e diferenças que observamos em nossos dados são estatisticamente significativos ou apenas resultados do acaso.

No mundo da Ciência de Dados, é crucial não apenas encontrar insights, mas também provar sua robustez. Os testes de hipóteses nos permitem fazer inferências sobre a população a partir de uma amostra de dados, quantificando a probabilidade de nossas observações serem verdadeiras. No contexto das turmas da UFRN, isso significa que poderemos, por exemplo, confirmar se a diferença na capacidade de alunos entre turmas de graduação e pós-graduação é estatisticamente relevante, ou se a modalidade à distância realmente impacta o número de solicitações de matrícula.

---

## O Desafio do Dia 4: Testando Hipóteses nos Dados da UFRN

O objetivo deste dia é que vocês formulem hipóteses claras com base nas observações e insights dos dias anteriores (especialmente da Análise Exploratória e do Clustering) e as testem utilizando métodos estatísticos apropriados. Vocês precisarão escolher os testes corretos, interpretar os resultados (valores-p, intervalos de confiança) e tirar conclusões baseadas em evidências.

---

## Objetivos de Aprendizagem

Ao final deste dia, vocês deverão ser capazes de:

- **Formular Hipóteses Estatísticas**: Traduzir perguntas de pesquisa em hipóteses nula (H0) e alternativa (H1) de forma clara e testável.
- **Selecionar o Teste Estatístico Apropriado**: Escolher o teste estatístico correto com base no tipo de dados (numéricos, categóricos), no número de grupos a serem comparados e na natureza da pergunta (comparação de médias, proporções, associação).
- **Realizar Testes de Hipóteses em Python**: Implementar testes estatísticos comuns utilizando bibliotecas como `scipy.stats`.
- **Interpretar Resultados Estatísticos**: Compreender o significado de valores-p, estatísticas de teste e intervalos de confiança, e usá-los para aceitar ou rejeitar a hipótese nula.
- **Tirar Conclusões Baseadas em Evidências**: Formular conclusões claras e concisas a partir dos resultados dos testes, relacionando-as com as perguntas de pesquisa iniciais.
- **Documentar o Processo e as Conclusões**: Registrar todas as hipóteses, os testes realizados, os resultados e as conclusões no notebook, explicando o raciocínio por trás de cada etapa.

---

## Tarefas a Serem Realizadas no Notebook

Continuem o trabalho no notebook do Dia 3 ou criem um novo (`Dia_4_Testes_e_Hipoteses.ipynb`), importando os dados limpos e, se necessário, os resultados do clustering. Sigam os passos abaixo:

### 1. Revisão e Formulação de Hipóteses

- **Revisem os Insights**: Voltem aos insights e padrões que vocês identificaram nos Dias 2 e 3. Escolham pelo menos **três observações** que vocês gostariam de validar estatisticamente.
- **Formulem Hipóteses**: Para cada observação escolhida, formulem uma hipótese nula (H0) e uma hipótese alternativa (H1). Por exemplo:

  **Observação**: Parece que turmas de graduação têm maior capacidade de alunos do que turmas de pós-graduação.

  - H0: Não há diferença significativa na capacidade média de alunos entre turmas de graduação e pós-graduação.
  - H1: Há uma diferença significativa na capacidade média de alunos entre turmas de graduação e pós-graduação.

### 2. Tentativa de implementação:

- Tente implementar…

---

## Entrega

O notebook atualizado deve ser entregue até as **12:00 do dia 08/08** no email: **petcc@dimap.ufrn.br**. Ele deve conter:

- As três (ou mais) hipóteses nula e alternativa claramente formuladas.
- A tentativa de implementação do código para ao menos **um teste estatístico**.
- A possível interpretação dos resultados de cada teste (estatística de teste, valor-p, decisão).
- Código **limpo, organizado e bem comentado**.

---

Este dia é fundamental para transformar suas observações em conhecimento validado. Boa sorte e que seus testes sejam significativos!

**Até amanhã!**
