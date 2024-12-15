# Clientes Inadimplentes 💳

Este repositório é um projeto pessoal com dados publicamente disponíveis. O objetivo é desenvolver um modelo que preveja se uma conta ficará dividenda no próximo mês, de acordo com dados demográficos e históricos.

## 📄 Informações importantes sobre as variáveis

- **LIMIT_BAL:** Valor do crédito fornecido (em novos dólares taiwaneses (NT)) inclusive o crédito do consumidor individual e familiar (complementar).
  
- **SEX:** Gênero (1 = masculino; 2 = feminino).
- **EDUCATION:** Instrução (1 = pós-graduação; 2 = universidade; 3 = ensino médio; 4 = outros).
- **MARRIAGE:** Estado civil (1 = casado; 2 = solteiro; 3 = outros).
- **AGE:** Idade (ano).
- **PAY_1 - PAY_6:** Registro de pagamentos passados. Pagamentos mensais passados, registrados de abril a setembro (PAY_6 = abril; PAY_1 = setembro), com escala: -2 = começou o mês sem valor a ser pago e crédito não utilizado; -1 = pagamento totalmente pago; 0 = pagamento mínimo feito mas saldo total não foi pago; 1 = atraso de um mês; 2 = atraso de dois meses; ...; 8 = atraso de oito meses; 9 = atraso de nove meses ou mais.
- **BILL_AMT1 - BILL_AMT6:** Valor da fatura (em novos dólares taiwaneses), a partir do mês de abril até setembro.
- **PAY_AMT1 - PAY_AMT6:** Valor de pagamentos anteriores (novos dólares taiwaneses), a partir do mês de abril até setembro.

_Projeto ainda em andamento..._
