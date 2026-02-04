# Analise de Dados - Tips Dataset

Analise exploratoria do dataset **Tips** (Seaborn), comparando diferentes bibliotecas de visualizacao em Python.

## Objetivo

Explorar a distribuicao de transacoes por dia da semana usando tres abordagens diferentes de visualizacao, demonstrando as diferencas entre cada biblioteca.

## Dataset

O dataset `tips` contem **244 registros** de transacoes em um restaurante com as colunas:
- `total_bill` — valor total da conta
- `tip` — gorjeta
- `sex`, `smoker` — dados demograficos
- `day`, `time` — dia e periodo
- `size` — tamanho do grupo

## Visualizacoes

Tres abordagens para o mesmo grafico de barras (transacoes por dia):

1. **Pandas** — `.plot(kind='bar')` — rapido e direto
2. **Seaborn** — `countplot()` — estatistico e elegante
3. **Matplotlib** — `pyplot` — controle total sobre o grafico

## Resultado

| Dia | Transacoes |
|-----|-----------|
| Quinta | 62 |
| Sexta | 19 |
| Sabado | 87 |
| Domingo | 76 |

Sabado e o dia com maior volume de transacoes, seguido por domingo.

## Tecnologias

- Python 3
- Pandas
- Seaborn
- Matplotlib
