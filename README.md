# Portas Lógicas Fundamentais

As portas lógicas são blocos fundamentais da eletrônica digital. Elas realizam operações lógicas com sinais binários (0 e 1).

---

## 🔢 Tipos de Portas Lógicas

### 1. Porta **AND**
- **Função:** Retorna 1 se **todas** as entradas forem 1.
- **Exemplo de entradas:** `0010`, `0110`, `1010`, `1111`

### 2. Porta **OR**
- **Função:** Retorna 1 se **pelo menos uma** entrada for 1.
- **Exemplo de entradas:** `1001`, `0111`, `1011`, `1111`

### 3. Porta **NOT**
- **Função:** Inverte o valor da entrada.
- **Exemplos:**
  - `0 → 1`
  - `1 → 0`

### 4. Porta **NAND**
- **Função:** Inverso da AND.
- **Exemplo:** `1101`, `1011`, `1111`, `0111`

### 5. Porta **NOR**
- **Função:** Inverso da OR.
- **Exemplo:** `0000`, `1000`, `0100`, `0000`

### 6. Porta **XOR**
- **Função:** Retorna 1 se as entradas forem **diferentes**.
- **Exemplo:** `1010`, `0101`, `1100`, `0011`

### 7. Porta **XNOR**
- **Função:** Retorna 1 se as entradas forem **iguais**.
- **Exemplo:** `1001`, `0110`, `0011`, `1100`

---

## 🧮 Símbolos Lógicos

| Porta | Símbolo | Expressão |
|-------|---------|-----------|
| AND   | ![AND](https://upload.wikimedia.org/wikipedia/commons/0/0c/AND_ANSI_Labelled.svg) | `X = A · B` |
| OR    | ![OR](https://upload.wikimedia.org/wikipedia/commons/d/d5/OR_ANSI_Labelled.svg) | `C = A + B` |
| NOT   | ![NOT](https://upload.wikimedia.org/wikipedia/commons/4/4c/NOT_ANSI_Labelled.svg) | `Y = ¬A` |
| NAND  | ![NAND](https://upload.wikimedia.org/wikipedia/commons/b/b2/NAND_ANSI_Labelled.svg) | `X = ¬(A · B)` |
| NOR   | ![NOR](https://upload.wikimedia.org/wikipedia/commons/e/e6/NOR_ANSI_Labelled.svg) | `Q = ¬(A + B)` |
| XOR   | ![XOR](https://upload.wikimedia.org/wikipedia/commons/9/99/XOR_ANSI_Labelled.svg) | `X = A ⊕ B` |
| XNOR  | ![XNOR](https://upload.wikimedia.org/wikipedia/commons/7/7a/XNOR_ANSI_Labelled.svg) | `X = ¬(A ⊕ B)` |

> As imagens acima são links diretos de símbolos ANSI da Wikipedia.

---

## 💡 Dicas para Prática

- ✅ Simule as portas usando ferramentas como [Logisim](http://www.cburch.com/logisim/) ou Proteus.
- ✅ Implemente em linguagens como **C**, **Python**, ou **VHDL**.
- ✅ Crie a **tabela-verdade** de cada porta para reforçar a lógica binária.

---

## 📁 Autor
Elísio Massaki Luamba  
Nº de estudante: 61313  
Universidade Metodista de Angola
