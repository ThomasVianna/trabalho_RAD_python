# Trabalho RAD em Python  
## Folha de Pagamento  

- **Salário Bruto:** 2.500,00  

- **Cálculo do INSS: ver tabela**  
  - Fórmula: `desconto_inss = salário_bruto × alíquota_inss`  

- **Cálculo do IRPF:**  
  - Base de cálculo: `base_irpf = salário_bruto - desconto_inss`  
  - Aplicar alíquota conforme tabela vigente: `desconto_irpf = base_irpf × alíquota_irpf`  

- **Salário Líquido:**  
  - Fórmula: `salário_liquido = salário_bruto - desconto_inss - desconto_irpf`  
