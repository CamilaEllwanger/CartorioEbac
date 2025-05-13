# 🗃️ Cartório da EBAC

Este é um sistema simples em linguagem C que simula as funcionalidades de um cartório digital. Ele permite registrar, consultar e deletar usuários com base em seu CPF, salvando os dados em arquivos `.txt`.

## 📌 Funcionalidades

- **Registrar usuário**: salva CPF, nome, sobrenome e cargo em um arquivo com o nome do CPF.
- **Consultar usuário**: busca um arquivo pelo CPF e mostra os dados cadastrados.
- **Deletar usuário**: remove o arquivo com base no CPF fornecido.
- **Menu interativo**: navegação fácil entre as opções do sistema.

## 🛠️ Bibliotecas utilizadas

```c
#include <stdio.h>     // Entrada e saída de dados
#include <stdlib.h>    // Alocação de memória, system("pause"), etc.
#include <locale.h>    // Suporte para acentuação
#include <string.h>    // Manipulação de strings
