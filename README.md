# Portas Lógicas Fundamentais

As portas lógicas são os blocos básicos da eletrônica digital. Elas operam com **sinais binários** (0 e 1) e realizam operações **lógicas fundamentais** em circuitos digitais.

---

## 🔢 Tipos de Portas Lógicas

### 1. Porta **AND**
- **Função:** Retorna 1 somente se **todas as entradas forem 1**.
- **Exemplos de entrada:**  
  `0010`, `0110`, `1010`, `1111`

### 2. Porta **OR**
- **Função:** Retorna 1 se **pelo menos uma** das entradas for 1.
- **Exemplos de entrada:**  
  `1001`, `0111`, `1011`, `1111`

### 3. Porta **NOT**
- **Função:** Inverte o valor da entrada.  
  `0 → 1`  
  `1 → 0`

### 4. Porta **NAND**
- **Função:** Inverso da AND.  
  Retorna 1 se **nem todas** as entradas forem 1.  
  `NAND = NOT(AND)`

### 5. Porta **NOR**
- **Função:** Inverso da OR.  
  Retorna 1 se **nenhuma** entrada for 1.  
  `NOR = NOT(OR)`

### 6. Porta **XOR**
- **Função:** Retorna 1 se as entradas forem **diferentes**.  
  `XOR = A ≠ B`

### 7. Porta **XNOR**
- **Função:** Retorna 1 se as entradas forem **iguais**.  
  `XNOR = NOT(XOR)`

---

## 🧠 Mapeamento Mental: Portas e Suas Contrárias

| Porta Básica | Porta Invertida | Relação |
|--------------|------------------|---------|
| AND          | NAND             | `NAND = NOT(AND)` |
| OR           | NOR              | `NOR = NOT(OR)` |
| XOR          | XNOR             | `XNOR = NOT(XOR)` |
| NOT          | —                | É auto-inversora |

### 💡 Dica para memorização:
- **NAND** e **NOR** têm um "N" de **"Not"** → são **inversas**.
- **XNOR** → "X de XOR" + "N de NOT".
- **NOT** é usada para inverter qualquer outra porta.

---

## 🧪 Exemplos Visuais

### AND
| A | B | A · B |
|---|---|-------|
| 0 | 0 |   0   |
| 0 | 1 |   0   |
| 1 | 0 |   0   |
| 1 | 1 |   1   |

### OR
| A | B | A + B |
|---|---|-------|
| 0 | 0 |   0   |
| 0 | 1 |   1   |
| 1 | 0 |   1   |
| 1 | 1 |   1   |

### NOT
| A | ¬A |
|---|----|
| 0 | 1  |
| 1 | 0  |

### XOR
| A | B | A ⊕ B |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   0    |

### XNOR
| A | B | A ⊙ B |
|---|---|--------|
| 0 | 0 |   1    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

---

## 🛠️ Recomendações de Estudo

- Usar simuladores como:
  - [Logisim](http://www.cburch.com/logisim/)
  - [Tinkercad Circuits](https://www.tinkercad.com/)
- Implementar portas lógicas em:
  - **Linguagem C**
  - **Python**
  - **VHDL**
- Criar mapas de Karnaugh simples para reduzir expressões.

---

## 📁 Autor

**Elísio Massaki Luamba**  
Nº de Estudante: 61313  
Universidade Metodista de Angola
