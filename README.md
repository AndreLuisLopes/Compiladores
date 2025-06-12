
# Analisador Léxico e Sintático de Expressões Matemáticas

Este projeto implementa um analisador léxico e sintático simples para expressões matemáticas, utilizando Python. Ele é capaz de identificar e classificar tokens como operadores, números inteiros, números decimais e parênteses, além de aplicar regras gramaticais para validar e derivar a estrutura da expressão.

## 🚀 Funcionalidades

- **Análise léxica**: identifica e classifica os elementos (tokens) da expressão.
- **Análise sintática**: aplica uma gramática recursiva para verificar se a expressão é válida e gera as derivações.
- **Suporte a números inteiros e decimais**
- **Reconhecimento de operadores básicos**: `+`, `-`, `*`, `/`
- **Tratamento de expressões com parênteses**

## 📚 Exemplo de uso

Ao executar o programa, será solicitado que o usuário digite uma expressão matemática:

```bash
Digite a expressão matemática: (2 + 3.5) * 4
```

A saída será composta por:

1. A expressão original
2. A tabela de tokens com seus respectivos códigos
3. As derivações gramaticais com base na análise sintática

## 🧠 Gramática utilizada

A gramática utilizada segue a seguinte forma:

```
E → I O E | I  
I → N  
N → D | D.D | ( E )  
D → [0-9]+
O → + | - | * | /
```

## 🛠️ Tecnologias

- Python 3
- Biblioteca `re` para expressões regulares

## 📁 Estrutura do projeto

```
analisador/
│
├── analisador.py        # Código principal com análise léxica e sintática
└── README.md            # Este arquivo
```

## 👨‍💻 Autores

- [Paulo Henrique](https://github.com/paulohique)  
- [André Luís](https://github.com/AndreLuisLopes)  
- [Matheus Bomtempo](https://github.com/MatheusBomtempo)

## 📄 Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).
