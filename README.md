# Guia de Estudos Python com NotebookLM

> Um caderno temático desenvolvido como parte do desafio da DIO, utilizando o **NotebookLM** como ferramenta de aprendizagem ativa para organizar conteúdos, aprofundar conhecimentos e consolidar um material de revisão sobre Python.

---

# Sobre o projeto

Este projeto tem como objetivo documentar minha experiência utilizando o **NotebookLM** para estudar Python, explorando desde os conceitos fundamentais da linguagem até bibliotecas amplamente utilizadas em análise e visualização de dados.

Ao longo do processo, utilizei diferentes fontes de estudo, realizei perguntas estratégicas para a IA, refinei prompts e organizei o conhecimento adquirido em um guia de revisão.

Além de atender aos requisitos do desafio da DIO, este repositório serve como um material de consulta para estudos futuros e como parte do meu portfólio no GitHub.

---

# Objetivos

Os principais objetivos deste projeto foram:

- Aprender os fundamentos da linguagem Python;
- Desenvolver habilidades em análise de dados utilizando Python;
- Explorar bibliotecas como Pandas, Matplotlib e Seaborn;
- Utilizar o NotebookLM como ferramenta de aprendizagem ativa;
- Criar um material organizado para futuras revisões.

---

# Ferramentas Utilizadas

| Ferramenta | Finalidade |
|------------|------------|
| NotebookLM | Organização dos materiais e estudo assistido por IA |
| GitHub | Versionamento e documentação do projeto |
| Markdown | Escrita e organização do README |
| Python | Linguagem estudada |

---

# Fontes Utilizadas

As principais fontes utilizadas durante os estudos foram:

1. **Python 3.14 Documentation**
   https://docs.python.org/3/

2. **Pandas Documentation**
   https://pandas.pydata.org/docs/

3. **Kaggle Learn**
   https://www.kaggle.com/learn

4. **Análise de Dados com Python: Guia Completo para Iniciantes**
   Hashtag Treinamentos

5. **Curso em Vídeo — Python**
   https://www.cursoemvideo.com/

### Materiais complementares consultados

Durante os estudos também foram consultados materiais impressos e livros técnicos, utilizados apenas como referência bibliográfica:

- *Entendendo Algoritmos: Um Guia Ilustrado para Programadores e Outros Curiosos* — Aditya Bhargava
- *Python for Data Analysis* — Wes McKinney

---

# Engenharia de Prompts

Durante os estudos, utilizei diferentes estratégias de prompts para explorar os conteúdos presentes nas fontes adicionadas ao NotebookLM.

## Exemplos de prompts utilizados

### Conceitos básicos

> Explique o que são variáveis em Python utilizando exemplos simples.

---

### Estruturas de repetição

> Qual a diferença entre os comandos `for` e `while`? Em quais situações cada um deve ser utilizado?

---

### Estruturas de dados

> Compare listas, tuplas e dicionários mostrando vantagens e desvantagens.

---

### Pandas

> Explique o funcionamento de um DataFrame e apresente exemplos práticos.

---

### Visualização de dados

> Qual a diferença entre Matplotlib e Seaborn?

---

### Exercícios

> Crie cinco exercícios sobre listas e funções sem mostrar as respostas.

---

# Cicatrizes (Troubleshooting)

Durante a utilização do NotebookLM foram observadas algumas dificuldades que ajudaram a melhorar a qualidade dos resultados.

| Problema encontrado | Solução adotada |
|--------------------|-----------------|
| Perguntas muito genéricas geravam respostas muito amplas | Passei a formular perguntas específicas e contextualizadas |
| Respostas muito extensas | Solicitei resumos em tópicos |
| Conceitos muito técnicos | Pedi explicações voltadas para iniciantes |
| Alguns assuntos ficaram superficiais | Solicitei exemplos práticos e exercícios |

### Aprendizado

Percebi que a qualidade das respostas depende diretamente da qualidade dos prompts elaborados. Perguntas objetivas e bem contextualizadas produziram respostas mais úteis e organizadas.

---

# Miniguia de Estudos

## Python

Python é uma linguagem de programação de alto nível, conhecida pela simplicidade de sua sintaxe e ampla aplicação em desenvolvimento web, automação, ciência de dados, inteligência artificial e análise de dados.

---

## Variáveis

São utilizadas para armazenar informações durante a execução do programa.

```python
nome = "Pedro"
idade = 22
```

---

## Tipos de dados

- int
- float
- str
- bool
- list
- tuple
- dict

---

## Estruturas condicionais

Permitem executar diferentes ações dependendo de uma condição.

```python
if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

---

## Estruturas de repetição

### For

```python
for numero in range(5):
    print(numero)
```

### While

```python
contador = 0

while contador < 5:
    contador += 1
```

---

## Funções

Permitem reutilizar blocos de código.

```python
def soma(a, b):
    return a + b
```

---

## Listas

Coleção ordenada e mutável.

```python
nomes = ["Ana", "Carlos", "Pedro"]
```

---

## Dicionários

Estrutura baseada em chave e valor.

```python
aluno = {
    "nome": "Pedro",
    "idade": 22
}
```

---

## Pandas

Biblioteca utilizada para manipulação e análise de dados.

Principais recursos:

- DataFrame
- Series
- Leitura de arquivos CSV
- Limpeza de dados
- Estatísticas

---

## Matplotlib

Biblioteca utilizada para construção de gráficos.

Exemplos:

- gráfico de linhas
- gráfico de barras
- gráfico de dispersão
- histogramas

---

## Seaborn

Biblioteca construída sobre o Matplotlib, oferecendo gráficos estatísticos com visual mais elaborado e menor quantidade de código.

---

# Glossário

| Conceito | Definição |
|-----------|-----------|
| Variável | Espaço utilizado para armazenar valores |
| Lista | Coleção ordenada e mutável |
| Tupla | Coleção ordenada e imutável |
| Dicionário | Estrutura composta por chave e valor |
| Função | Bloco reutilizável de código |
| Loop | Estrutura de repetição |
| DataFrame | Estrutura tabular utilizada pelo Pandas |
| Pandas | Biblioteca para análise de dados |
| Matplotlib | Biblioteca para criação de gráficos |
| Seaborn | Biblioteca para visualização estatística |

---

# Prompts reutilizáveis

Os seguintes prompts podem ser reutilizados para futuras revisões:

- Explique este conceito como se eu fosse iniciante.
- Compare dois conceitos em formato de tabela.
- Crie exemplos práticos utilizando Python.
- Gere cinco exercícios sem apresentar as respostas.
- Explique os erros mais comuns relacionados a este assunto.
- Resuma este conteúdo em tópicos.
- Crie um mapa mental textual sobre este tema.
- Monte um roteiro de estudos para revisar este conteúdo.

---

# Conclusão

A utilização do NotebookLM demonstrou ser uma estratégia eficiente para organizar conteúdos, esclarecer dúvidas e consolidar conhecimentos utilizando Inteligência Artificial como ferramenta de aprendizagem.

Além de aprofundar meus conhecimentos em Python, este projeto contribuiu para desenvolver habilidades relacionadas à curadoria de fontes, documentação técnica, engenharia de prompts e organização do conhecimento, competências importantes para estudos e para o mercado de tecnologia.

---

# Autor

**Pedro Jordan**

Projeto desenvolvido como parte do desafio de aprendizagem da **DIO (Digital Innovation One)** utilizando o **NotebookLM** como ferramenta de apoio aos estudos.
