# 📚 Sistema de Gerenciamento de Livraria

Sistema de gerenciamento de livraria desenvolvido em **C** como projeto da disciplina de **Algoritmos e Estruturas de Dados I**.

O projeto utiliza **listas ligadas**, **Quicksort**, **busca binária**, **manipulação de arquivos** e **modularização do código**.

## ⚙️ Funcionalidades

* 🔐 **Sistema de Login**

  * Usuário e senha pré-definidos.
  * Usuário: `admin`
  * Senha: `1234`

* 📧 **Validação de E-mail**

  * Verificação da presença de `@`.
  * Limite de 80 caracteres.
  * Verificação de e-mails duplicados durante a sessão.

* 📖 **Gerenciamento de Livros**

  * Cadastrar livros.
  * Listar livros cadastrados.
  * Editar informações.
  * Excluir livros.

* 💾 **Persistência de Dados**

  * Os dados dos livros são armazenados em `livros.txt`.
  * O arquivo é carregado automaticamente ao iniciar o programa.

* 🔎 **Algoritmos**

  * **Quicksort:** utilizado para ordenar temporariamente os livros por ID.
  * **Busca Binária:** utilizada para localizar livros após a ordenação.

* 🛒 **Operações de Compra**

  * Listar livros com preço abaixo de R$ 50.
  * Listar livros disponíveis em estoque.
  * Comprar livros.
  * Atualizar estoque automaticamente.
  * Calcular o total da compra.
  * Visualizar compras realizadas.
  * Cancelar compras.

## 🗂️ Estrutura do Projeto

```text
livraria-c/
├── main.c
├── livraria.c
├── livraria.h
├── livros.txt
├── README.md
└── .gitignore
```

### Arquivos principais

* `main.c` — ponto de entrada do programa.
* `livraria.c` — implementação das funções do sistema.
* `livraria.h` — declarações e estruturas utilizadas pelo projeto.
* `livros.txt` — arquivo utilizado para persistência dos dados.

## 🔧 Tecnologias e Conceitos

* Linguagem C
* GCC
* Listas ligadas
* Quicksort
* Busca binária
* Manipulação de arquivos
* Modularização (`.c` e `.h`)
* CRUD

## ▶️ Como Compilar

Com o **GCC** instalado, abra o terminal dentro da pasta do projeto e execute:

```bash
gcc main.c livraria.c -o livraria.exe
```

Depois, execute:

```bash
livraria.exe
```

No Linux:

```bash
./livraria
```

## 🎓 Contexto Acadêmico

Projeto desenvolvido para a disciplina de **Algoritmos e Estruturas de Dados I**.
