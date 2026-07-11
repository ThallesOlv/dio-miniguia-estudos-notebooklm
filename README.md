# 📚 Caderno Temático de Educação Financeira — NotebookLM

> Projeto desenvolvido no **Bootcamp Bradesco** como parte da atividade de curadoria de fontes, uso estratégico de IA e organização do conhecimento aplicada a um tema financeiro introdutório.

---

## 📌 Descrição do Projeto

O desafio propõe a criação de um caderno temático no **NotebookLM**, reunindo de três a cinco fontes abertas em texto ou PDF sobre um assunto financeiro introdutório. A partir desse material, são definidos objetivos de estudo, elaboradas perguntas estratégicas e testadas variações de prompts, registrando as respostas e suas referências.

O resultado esperado é um **miniguia de estudo** com resumos estruturados, glossário de conceitos e um conjunto de prompts reutilizáveis que apoiem futuras revisões. A atividade enfatiza o uso da IA como ferramenta de aprendizagem ativa, aliando pensamento crítico, curadoria de fontes e organização do conhecimento.

---

## 🎯 Motivo da Escolha do Tema

**Tema escolhido:** *Educação Financeira e Cidadania Financeira — dos fundamentos pessoais à relação com o Sistema Financeiro Nacional (SFN).*

A escolha se justifica pela forte aderência ao contexto do bootcamp e do setor bancário:

- **Base conceitual dos produtos bancários de varejo** — orçamento, poupança, crédito e investimentos são o alicerce de qualquer produto oferecido por instituições financeiras como o Bradesco.
- **Relevância direta para o negócio** — cidadania financeira e inadimplência impactam risco de crédito, relacionamento com o cliente e indicadores gerenciais (tema próximo da minha própria atuação profissional com indicadores de risco e automação de processos).
- **Múltiplas perspectivas complementares** — o tema permite cruzar a visão regulatória (Banco Central) com a visão do setor bancário (Febraban) e do mercado de capitais (CVM), enriquecendo a curadoria de fontes e as perguntas estratégicas.
- **Caráter introdutório, mas com profundidade** — os conceitos são acessíveis para quem está começando, mas têm dados, indicadores e nuances suficientes para gerar discussões ricas com a IA.

---

## 🔗 Fontes Utilizadas

| # | Fonte | Instituição | Link |
|---|-------|--------------|------|
| 1 | Página institucional de Educação | CVM | [Acessar página](https://www.gov.br/cvm/pt-br/assuntos/educacao) |
| 2 | Guia de Boas Práticas de Educação Financeira no Setor Bancário Brasileiro | Febraban | [Acessar PDF](https://cmsarquivos.febraban.org.br/Arquivos/documentos/PDF/febraban-guia%20de%20boas%20pr%C3%A1ticas-v7-web.pdf) |
| 3 | Caderno de Educação Financeira — Gestão de Finanças Pessoais | Banco Central do Brasil (BCB) | [Acessar PDF](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf) |
| 4 | Série Cidadania Financeira Estudos sobre Educação, Proteção e Inclusão | Banco Central do Brasil (BCB) | [Acessar PDF](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/serie_cidadania/serie_cidadania_5_financeira_pesquisa.pdf) |
| 5 | Livro TOP: Mercado de Valores Mobiliários Brasileiro (5ª ed.) | CVM | [Acessar PDF](https://www.gov.br/investidor/pt-br/educacional/publicacoes-educacionais/livros-cvm/cvm-livro_top_valores_mobiliarios_br_5ed.pdf/@@display-file/file) |


> ⚠️ **Nota:** o link 2 pode falhar ao ser importado por URL diretamente no NotebookLM (comum em domínios governamentais). Recomenda-se baixar o PDF e fazer upload manual do arquivo.

---

## 🎓 Objetivos de Estudo

1. Compreender os pilares da **cidadania financeira** (inclusão, educação, proteção e participação) segundo o Banco Central.
2. Entender como os **conceitos de finanças pessoais** (orçamento, poupança, planejamento) se conectam a produtos bancários de varejo (crédito, conta, investimentos).
3. Identificar como o **setor bancário** traduz esses conceitos em ações práticas junto ao cliente, incluindo a relação com **inadimplência**.
4. Conhecer o papel da **CVM** na educação sobre mercado de capitais e investimentos, como complemento ao crédito e à poupança.
5. Construir um **glossário técnico** e um conjunto de **prompts reutilizáveis** para revisão futura do tema.

---

## ❓ Perguntas Estratégicas

**Conceituais**
- O que é cidadania financeira e quais são seus quatro pilares segundo o BC?
- Qual a diferença entre inclusão financeira, educação financeira e proteção do consumidor financeiro?

**Conectivas (cruzando fontes)**
- Como os dados de inadimplência do guia da Febraban se relacionam com o nível de educação financeira relatado pelo Banco Central?
- Como o planejamento financeiro pessoal se conecta com os produtos de investimento descritos no livro da CVM?
- Quais ações do guia da Febraban decorrem da parceria entre Febraban e Banco Central?

**Aplicadas ao negócio bancário**
- Que tipo de indicador um banco poderia construir a partir dos conceitos de saúde financeira mencionados nas fontes?
- Como a jornada do cliente bancário poderia incorporar educação financeira, segundo as boas práticas do setor?

**Críticas**
- As fontes divergem em algum ponto sobre o papel do banco na educação financeira do cliente?
- Que limitações ou lacunas aparecem nos dados de inclusão financeira apresentados?

---

## 🔁 Prompts Reutilizáveis

```text
[Resumo estruturado]
Resuma o conceito de [tema] apresentado nas fontes, em até 150 palavras,
organizando em: definição, pilares/elementos principais, e um exemplo
prático citado no material. Indique de qual fonte cada informação vem.

[Comparação entre fontes]
Compare como as fontes do Banco Central e da Febraban tratam o tema
[tema]. Aponte convergências, divergências e uma conclusão sobre o que
isso significa para um banco de varejo.

[Extração de glossário]
Liste 10 termos técnicos usados nas fontes relacionados a [tema], com
definição de uma frase cada, citando a fonte de origem de cada termo.

[Aplicação prática/negócio]
Com base nas fontes, sugira 3 formas como um banco poderia usar esses
conceitos para criar um indicador gerencial ou uma ação de educação
financeira voltada ao cliente.

[Verificação crítica]
Aponte se há alguma limitação, viés ou lacuna de dados mencionada
explicitamente nas fontes sobre [tema]. Cite a fonte.
```

---

## 🗂️ Estrutura do Repositório

```
├── README.md                  # Este arquivo
├── /fontes                    # PDFs das fontes utilizadas (ou links, se não versionados)
├── /miniguia
│   ├── resumos.md              # Resumos estruturados por fonte
│   ├── glossario.md            # Glossário de termos técnicos
│   ├── mapa-conexoes.md        # Conexões entre conceitos das fontes
│   └── reflexao-critica.md     # Respostas às perguntas críticas
├── /prompts
│   └── prompts-reutilizaveis.md
└── /evidencias
    └── capturas-notebooklm/     # Prints das interações no NotebookLM (opcional)
```

---

## 📝 Miniguia de Estudo (Resultado Final)

O miniguia produzido a partir das interações com o NotebookLM está disponível em [`/miniguia`](./miniguia), contendo:

- **Resumos estruturados** de cada fonte, com referência de origem.
- **Glossário** de termos técnicos (ex: cidadania financeira, letramento financeiro, inadimplência, ativo problemático).
- **Mapa de conexões** entre os conceitos das 5 fontes.
- **Reflexão crítica** sobre limitações e lacunas identificadas nas fontes.

---

## 🛠️ Ferramentas Utilizadas

- **NotebookLM** (Google) — curadoria de fontes, chat de perguntas e geração de resumos.
- **Markdown** — documentação e registro do miniguia.
- Fontes oficiais: **Banco Central do Brasil, Febraban e CVM**.

---

## 👤 Autor

**Thallao** — Bootcamp Bradesco, 2026
Contexto profissional: dados, automação e indicadores gerenciais.

---

## 📄 Licença

Este projeto tem fins educacionais, desenvolvido como entrega de atividade do Bootcamp Bradesco. As fontes citadas pertencem às respectivas instituições (BCB, Febraban, CVM) e são de acesso público e gratuito.
