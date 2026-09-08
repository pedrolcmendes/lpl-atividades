# Atividade - Aula 00

[← Voltar ao índice](../README.md)

Primeira atividade prática da disciplina. A linguagem sorteada foi **Python**.

## Enunciado

1. Executar um programa "Olá, mundo!" em um compilador on-line;
2. Alterar o programa para receber um número e exibir sua tabuada;
3. Pesquisar uma vaga real, uma faixa salarial e os paradigmas da linguagem;
4. Publicar a atividade no GitHub.

## Arquivos

```text
aula-00/
├── README.md
└── src/
    ├── ola_mundo.py
    └── tabuada.py
```

## Execução

É necessário ter Python 3 instalado:

```bash
python aula-00/src/ola_mundo.py
python aula-00/src/tabuada.py
```

Também é possível colar o código no [OneCompiler](https://onecompiler.com/python).
No programa da tabuada, a entrada deve ser informada na área **STDIN**.

## 1. Olá, mundo!

```python
print("Olá, mundo!")
```

Python permite executar essa instrução diretamente, sem exigir uma classe ou
uma função `main`.

## 2. Tabuada

```python
numero = int(input("Digite um número inteiro: "))

print(f"\nTabuada do {numero}:")

for multiplicador in range(1, 11):
    print(f"{numero} x {multiplicador} = {numero * multiplicador}")
```

O programa lê um inteiro e usa um laço `for` para realizar as multiplicações de
1 a 10. O limite final de `range(1, 11)` não é incluído, por isso a última
iteração usa o número 10.

## 3. Pesquisa

### Vaga real

| Campo | Informação |
|---|---|
| Cargo | Back-end Developer (Python) |
| Empresa | Halliburton |
| Local | Rio de Janeiro/RJ, remoto no Brasil |
| Publicação | 15 de agosto de 2026 |
| Consulta | 7 de setembro de 2026 |
| Link | [Página oficial da vaga](https://jobs.halliburton.com/job/Rio-de-Janeiro-Brazil-Remote-Back-end-Developer-%28Python%29-RJ-291941/1401269800/) |

A vaga pede experiência com Python para criar APIs REST, microsserviços e
aplicações orientadas a dados. Também cita FastAPI, Flask ou Django,
PostgreSQL, Redis, MongoDB, Kafka ou RabbitMQ, Docker e Kubernetes.

### Faixa salarial

A vaga não informa remuneração. Como referência de mercado para profissionais
Python no Brasil em 2026, foram encontradas as seguintes faixas mensais CLT:

| Nível | Faixa aproximada |
|---|---:|
| Júnior | R$ 3.000 a R$ 6.000 |
| Pleno | R$ 6.000 a R$ 10.000 |
| Sênior | R$ 10.000 a R$ 16.000 |

Os valores variam conforme região, experiência, especialização e regime de
contratação. A fonte foi atualizada em agosto de 2026.

### Paradigmas do Python

Python é uma linguagem **multiparadigma**:

| Paradigma | Exemplos na linguagem |
|---|---|
| Imperativo/procedural | atribuições, decisões, laços e funções |
| Orientado a objetos | classes, objetos, herança e polimorfismo |
| Funcional | funções de primeira classe, `lambda`, `map`, `filter` e compreensões |

A tabuada desta atividade segue principalmente o paradigma imperativo: o
programa descreve, passo a passo, a leitura da entrada e a repetição das
multiplicações.

## Referências

- [Halliburton - Back-end Developer (Python)](https://jobs.halliburton.com/job/Rio-de-Janeiro-Brazil-Remote-Back-end-Developer-%28Python%29-RJ-291941/1401269800/)
- [Faixas salariais Python no Brasil em 2026](https://python.dev.br/carreira/salarios-python-brasil/)
- [Python.org - visão geral da linguagem](https://www.python.org/doc/essays/blurb/)
- [Python Docs - programação funcional](https://docs.python.org/3/howto/functional.html)

> Vagas podem ser removidas após o encerramento do processo seletivo.
