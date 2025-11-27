# OlaMundo2 — Activity for the course

## English

This directory contains a simple exercise for the Software Engineering course at Faculdade Estácio. The program in this folder is a minimal C program that prints the message "Olá, Mundo!".

Contents

- `OlaMundo2.c` — a simple C program that uses `printf` to print a greeting.
- `.gitignore` — ignores build artefacts and editor folders.
- `LICENSE` — MIT license for this project.

How it works

- The source includes the standard header `<stdio.h>`, defines `main()`, calls `printf("Olá, Mundo!\n");` to print the message and returns `0`.

Build and run (Windows — `cmd.exe`)

1. Open Command Prompt in this directory (where `OlaMundo2.c` is located).
2. Compile with `gcc` (MinGW or other toolchain):

```bat
gcc OlaMundo2.c -o OlaMundo2.exe
OlaMundo2.exe
```

Build and run (Linux / macOS)

```bash
gcc OlaMundo2.c -o OlaMundo2
./OlaMundo2
```

Notes

- If you don't have `gcc` on Windows, install MinGW-w64 or use WSL.

## Português (pt-BR)

Este diretório contém uma atividade simples da disciplina de Engenharia de Software da Faculdade Estácio. O programa presente aqui é um programa mínimo em C que imprime a mensagem "Olá, Mundo!".

Conteúdo

- `OlaMundo2.c` — programa em C que utiliza `printf` para imprimir uma saudação.
- `.gitignore` — evita versionar artefatos de compilação e pastas do editor.
- `LICENSE` — licença MIT para este projeto.

Como funciona

- O código inclui a biblioteca padrão `<stdio.h>`, define `main()`, chama `printf("Olá, Mundo!\n");` para imprimir a mensagem e retorna `0`.

Compilar e executar (Windows — `cmd.exe`)

1. Abra o Prompt de Comando nesta pasta (onde está `OlaMundo2.c`).
2. Compile com `gcc` (MinGW ou outra toolchain):

```bat
gcc OlaMundo2.c -o OlaMundo2.exe
OlaMundo2.exe
```

Compilar e executar (Linux / macOS)

```bash
gcc OlaMundo2.c -o OlaMundo2
./OlaMundo2
```

Observações

- Caso não possua `gcc` no Windows, instale MinGW-w64 ou use o WSL.

Licença

- O código está disponível sob a licença MIT — veja o arquivo `LICENSE` neste diretório.
