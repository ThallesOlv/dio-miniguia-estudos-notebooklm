# 🔁 Prompts Reutilizáveis

> Conjunto de prompts testados no NotebookLM para revisão futura do tema. Substitua `[tema]` pelo conceito desejado (ex: "cidadania financeira", "inadimplência", "mercado de valores mobiliários").

---

## 1. Resumo estruturado

```text
Resuma o conceito de [tema] apresentado nas fontes, em até 150 palavras,
organizando em: definição, pilares/elementos principais, e um exemplo
prático citado no material. Indique de qual fonte cada informação vem.
```

**Uso recomendado:** primeira leitura de cada fonte, para gerar os resumos estruturados (`/miniguia/resumos.md`).

---

## 2. Comparação entre fontes

```text
Compare como as fontes do Banco Central e da Febraban tratam o tema
[tema]. Aponte convergências, divergências e uma conclusão sobre o que
isso significa para um banco de varejo.
```

**Uso recomendado:** construção do mapa de conexões (`/miniguia/mapa-conexoes.md`).

---

## 3. Extração de glossário

```text
Liste 10 termos técnicos usados nas fontes relacionados a [tema], com
definição de uma frase cada, citando a fonte de origem de cada termo.
```

**Uso recomendado:** montagem do glossário (`/miniguia/glossario.md`).

---

## 4. Aplicação prática/negócio

```text
Com base nas fontes, sugira 3 formas como um banco poderia usar esses
conceitos para criar um indicador gerencial ou uma ação de educação
financeira voltada ao cliente.
```

**Uso recomendado:** conectar o tema ao contexto profissional/bancário — útil para discussões e apresentação do projeto.

---

## 5. Verificação crítica

```text
Aponte se há alguma limitação, viés ou lacuna de dados mencionada
explicitamente nas fontes sobre [tema]. Cite a fonte.
```

**Uso recomendado:** reflexão crítica (`/miniguia/reflexao-critica.md`).

---

## 6. Variações de teste (para comparar comportamento da IA)

```text
Variação objetiva:
Explique [tema] de forma direta e curta.

Variação crítica:
Aponte falhas, contradições ou pontos fracos na forma como [tema] é
tratado nas fontes.

Variação comparativa:
Compare como a Fonte X e a Fonte Y tratam [tema], destacando diferenças
de enfoque.
```

**Uso recomendado:** exercício de "testar variações de prompts" pedido pelo desafio — registrar como a resposta muda conforme a formulação.

---

## 📌 Como revisar o tema no futuro (fluxo rápido)

1. Abra o notebook no NotebookLM.
2. Rode o prompt de **resumo estruturado** para relembrar os conceitos principais.
3. Rode o prompt de **glossário** se precisar revisar termos técnicos.
4. Use o prompt de **aplicação prática** para pensar em como usar o conceito no trabalho.
5. Sempre confira a fonte citada pela IA antes de considerar a informação definitiva.
