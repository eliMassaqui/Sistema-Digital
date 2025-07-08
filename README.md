# ⚙️ Portas Lógicas Fundamentais

As **portas lógicas** são os blocos construtivos da eletrônica digital. Elas processam sinais **binários (0 e 1)** para realizar operações fundamentais em **circuitos digitais**, **processadores**, e **sistemas embarcados**.

---

## 🔢 Tipos de Portas Lógicas

### 1. ⬛ Porta **AND** (E)

* **Símbolo:** `·` ou `∧`
* **Operação:** Retorna 1 somente se **todas as entradas forem 1**.
* **Equação:** `A · B · C` (com 3 entradas)
* **Tabela Verdade (3 Entradas):**

  | A | B | C | A · B · C |
  | - | - | - | --------- |
  | 0 | 0 | 0 | 0         |
  | 0 | 0 | 1 | 0         |
  | 0 | 1 | 0 | 0         |
  | 0 | 1 | 1 | 0         |
  | 1 | 0 | 0 | 0         |
  | 1 | 0 | 1 | 0         |
  | 1 | 1 | 0 | 0         |
  | 1 | 1 | 1 | 1         |

### 💡 Circuito Lógico (3 entradas):

```
A ─┬──────┐
   │      │
B ─┤ AND  ├───── Saída (A · B · C)
   │      │
C ─┘──────┘
```

---

### 2. 🟥 Porta **OR** (OU)

* **Símbolo:** `+` ou `∨`
* **Operação:** Retorna 1 se **pelo menos uma entrada for 1**.
* **Equação:** `A + B + C`
* **Tabela Verdade (3 Entradas):**

  | A | B | C | A + B + C |
  | - | - | - | --------- |
  | 0 | 0 | 0 | 0         |
  | 0 | 0 | 1 | 1         |
  | 0 | 1 | 0 | 1         |
  | 0 | 1 | 1 | 1         |
  | 1 | 0 | 0 | 1         |
  | 1 | 0 | 1 | 1         |
  | 1 | 1 | 0 | 1         |
  | 1 | 1 | 1 | 1         |

### 💡 Circuito Lógico (3 entradas):

```
A ─┬──────┐
   │      │
B ─┤ OR   ├────── Saída (A + B + C)
   │      │
C ─┘──────┘
```

---

### 3. 🟩 Porta **XOR** (OU Exclusivo)

* **Símbolo:** `⊕`
* **Operação:** Retorna 1 se **número ímpar de entradas for 1**.
* **Equação:** `A ⊕ B ⊕ C`
* **Tabela Verdade (3 Entradas):**

  | A | B | C | A ⊕ B ⊕ C |
  | - | - | - | --------- |
  | 0 | 0 | 0 | 0         |
  | 0 | 0 | 1 | 1         |
  | 0 | 1 | 0 | 1         |
  | 0 | 1 | 1 | 0         |
  | 1 | 0 | 0 | 1         |
  | 1 | 0 | 1 | 0         |
  | 1 | 1 | 0 | 0         |
  | 1 | 1 | 1 | 1         |

### 💡 Circuito Lógico (3 entradas):

```
A ─┬────┐
   │    │
B ─┤ XOR├─┐
   │    │ │
   └────┘ │ XOR──── Saída (A ⊕ B ⊕ C)
          │
C ────────┘
```

---

## 🧠 Mapeamento Mental: Porta vs. Porta Inversa

| Porta Básica | Porta Invertida | Relação           |
| ------------ | --------------- | ----------------- |
| AND          | NAND            | `NAND = ¬(A · B)` |
| OR           | NOR             | `NOR = ¬(A + B)`  |
| XOR          | XNOR            | `XNOR = ¬(A ⊕ B)` |
| NOT          | —               | Auto-inversora    |

### 💡 Dicas de Memorização

* O **N** nas portas **NAND, NOR, XNOR** significa **“NOT”**.
* **XNOR** é o inverso lógico da **XOR**.
* **NOT** é usada sozinha para inverter qualquer valor lógico.

---

## 🛠️ Prática Recomendada

### 📌 Ferramentas de Simulação:

* 🔗 [Logisim](http://www.cburch.com/logisim/)
* 🔗 [Tinkercad Circuits](https://www.tinkercad.com/)

### 💻 Programação de Portas Lógicas:

* **Python:** usando operadores lógicos (`and`, `or`, `not`)
* **C/C++:** com operadores binários (`&`, `|`, `!`)
* **VHDL / Verilog:** em projetos de FPGA

---

## 🧮 Próximo Nível: Redução Lógica

Utilize **Mapas de Karnaugh** para:

* Eliminar redundâncias
* Otimizar circuitos
* Reduzir número de portas

> Minimizar lógica digital = desempenho + economia

---

## 📁 Autor

**Elísio Massaki Luamba**
📘 Nº de Estudante: 61313
🏛️ Universidade Metodista de Angola
