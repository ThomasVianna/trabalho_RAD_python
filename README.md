Aqui está uma sugestão de como organizar o **README.md** do seu repositório no GitHub para deixar o trabalho claro e bem estruturado:

---

# 📊 Trabalho de Folha de Pagamento (Programação Estruturada)

## 👥 Informações Gerais
- Trabalho em grupo de até **3 integrantes**  
- Cadastro de pelo menos **5 funcionários**  
- Utilizar somente **programação estruturada**  
- Apresentação nas aulas dos dias **18 e 25 de março**  
- Cada grupo é livre para escolher a abordagem  

---

## 🧾 Folha de Pagamento

### 1. Salário Bruto
- Valor total recebido pelo colaborador.

### 2. Desconto do INSS  
**Tabela de Contribuição INSS 2026 (Empregado CLT, Doméstico e Avulso):**
- Até R$ 1.621,00 → **7,5%**  
- De R$ 1.621,01 até R$ 2.902,84 → **9%**  
- De R$ 2.902,85 até R$ 4.354,27 → **12%**  
- De R$ 4.354,28 até R$ 8.475,55 (Teto) → **14%**  
- Qualquer valor acima do teto → **R$ 1.186,57 fixo**

**Fórmula:**  
\[
\text{Desconto INSS} = \text{Salário Bruto} \times \text{Alíquota INSS}
\]

---

### 3. Cálculo do Imposto de Renda (IRRF)  
**Tabela IRRF (a partir de 01/05/2025):**

| Base de Cálculo Mensal (R$) | Alíquota (%) | Parcela a Deduzir (R$) |
|-----------------------------|--------------|-------------------------|
| Até 2.428,80                | Isento       | 0,00                   |
| 2.428,81 – 2.826,65         | 7,5%         | 182,16                 |
| 2.826,66 – 3.751,05         | 15%          | 394,16                 |
| 3.751,06 – 4.664,68         | 22,5%        | 675,49                 |
| Acima de 4.664,68           | 27,5%        | 908,73                 |

**Fórmulas:**  
\[
\text{Base de Cálculo IRPF} = \text{Salário Bruto} - \text{Desconto INSS}
\]  
\[
\text{Desconto IRPF} = (\text{Base de Cálculo} \times \text{Alíquota IRPF}) - \text{Parcela a Deduzir}
\]

---

### 4. Vale Transporte
\[
\text{Vale Transporte} = 6\% \times \text{Salário Bruto}
\]

---

### 5. Salário Líquido
\[
\text{Salário Líquido} = \text{Salário Bruto} - \text{Desconto INSS} - \text{Desconto IRPF} - \text{Vale Transporte}
\]

---

## 📌 Entregáveis
- Código em **programação estruturada** (sem orientação a objetos).  
- Cadastro de **mínimo 5 funcionários**.  
- Cálculo automático da folha de pagamento com base nas tabelas acima.  
- Apresentação prática nas datas definidas.  

---

Quer que eu monte também um **exemplo de código em pseudocódigo ou Python estruturado** para ilustrar como ficaria o cálculo dentro do README? Isso deixaria o repositório ainda mais didático.
