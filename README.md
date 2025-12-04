# Trabalho-Aeds-e-Fes

# Hotel Descanso Garantido

Projeto para as disciplinas Fundamentos de Engenharia de Software e Algoritmos e Estruturas de Dados I.

## Integrantes
- Lucas Alves Rabelo
- João Paulo Fadul
- Victor Gabriel Soares

## Organização de pastas
- `src/` : código fonte (.c) e `include/` com .h
- `tests/` : testes com MUnit (coloque `munit.c` e `munit.h` em `tests/munit/`)
- `data/` : arquivos binários usados pelo sistema
- `docs/` : backlog, documentação das funções, casos de teste, relatório de execução
- `scripts/` : utilitário para gerar dados de exemplo
- `build/` : gerado pelo `make`

## Requisitos
- compilador C (gcc)
- make
- MUnit para testes (https://nemequ.github.io/munit/) — copie `munit.h` e `munit.c` para `tests/munit/`

## Como compilar e executar
1. Gere os dados de exemplo:
```bash
make data
