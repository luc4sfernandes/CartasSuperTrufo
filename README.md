# 🃏 Desafio Super Trunfo: Países (Edição Educativa)

Bem-vindo ao repositório do projeto **Super Trunfo - Países**! Este não é apenas um jogo de cartas, mas uma jornada de aprendizado em lógica de programação utilizando a linguagem **C**. 

O objetivo é construir um sistema de cadastro e comparação de cartas que evolui em complexidade, partindo do básico até o uso de lógica booleana e tipos de dados avançados.

---

## 🚀 O que você vai aprender?

Este projeto está dividido em três marcos de conhecimento:

### 1. Nível Novato: Fundamentos de Entrada e Saída
Aqui o foco é dominar a interação básica com o computador.
* **Conceitos chave:** * `printf()`: Como exibir dados de forma organizada para o usuário.
    * `scanf()`: Como capturar o que o usuário digita e salvar na memória.
    * **Tipos de Variáveis:** Diferença entre `int` (números inteiros) e `float` (números com casas decimais).
* **Objetivo:** Cadastrar 2 cartas com atributos básicos (População, Área, PIB e Pontos Turísticos).

### 2. Nível Aventureiro: Operações Matemáticas
Nesta etapa, transformamos dados brutos em informações úteis.
* **Conceitos chave:** * **Expressões Aritméticas:** Realizar divisões para obter métricas.
    * **Fórmulas Aplicadas:**
        * `Densidade Populacional = População / Área`
        * `PIB per Capita = PIB / População`
* **O que muda:** O sistema agora faz cálculos automáticos antes de exibir os resultados.

### 3. Nível Mestre: Lógica, Tipos Grandes e Comparações
O nível final onde o jogo realmente acontece.
* **Conceitos chave:** * `unsigned long int`: Uso de modificadores para armazenar números gigantes (como a população de um país inteiro).
    * **Lógica de Comparação:** Uso de operadores relacionais (`>`, `<`) para decidir qual carta vence.
    * **O "Super Poder":** Um atributo calculado pela soma de todos os dados, onde a Densidade Populacional tem peso invertido (quanto menor, melhor).
* **Regra de Ouro:** No Super Trunfo, vence quem tem o maior valor, *exceto* na Densidade Populacional, onde o menor valor ganha!

---

## 🛠️ Atributos das Cartas

Ao codificar, certifique-se de usar os tipos de dados corretos para cada atributo:

| Atributo | Tipo de Dado (Sugerido) | Descrição |
| :--- | :--- | :--- |
| **População** | `unsigned long int` | Número total de habitantes. |
| **Área** | `float` | Área em km². |
| **PIB** | `float` | Produto Interno Bruto. |
| **Pontos Turísticos** | `int` | Quantidade de locais famosos. |
| **Densidade** | `float` | Habitantes por km². |
| **PIB per Capita** | `float` | Renda média por pessoa. |
| **Super Poder** | `float` | A soma de todas as forças da carta. |

---

## 🧠 Como Rodar e Testar

1.  Certifique-se de ter um compilador de C instalado (como o GCC).
2.  Compile o arquivo:
    ```bash
    gcc desafio_super_trunfo.c -o jogo
    ```
3.  Execute o programa:
    ```bash
    ./jogo
    ```

---

## 🎓 Dicas para Evolução
- **Refatoração:** Consegue fazer o código usando menos variáveis?
- **Interface:** Tente usar caracteres especiais para criar uma "moldura" de carta no terminal usando `printf`.
- **Validação:** O que acontece se o usuário digitar uma letra onde deveria ser um número? (Desafio extra!).

---
*Este projeto faz parte da trilha de aprendizado da MateCheck.*
