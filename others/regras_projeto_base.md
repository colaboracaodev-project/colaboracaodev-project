# Calculadora de Rescisão Trabalhista v1.0

## Regras para o Projeto Base

### criar HTML
O html deverá conter os campos abaixo:
- salario atual;
    - recebe o salário atual.

- dias trabalhados no mês;
    - recebe os dias trabalhados no mês da rescisão.

- meses trabalhados no ano;
    - recebe os meses trabalhados no ano da rescisão.

- tempo total trabalhado e meses;
    - recebe o tempo total trabalhado na empresa em meses;

- botão calcular;

- tag para exibir o resultado do JavaScript;

### criar CSS
Estilizar o HTML e acordo com sua criatividade;

### criar função calculaSaldoSalario
- recebe como parâmetro o salário e os dias trabalhados no mês da rescisão;
- fórmula: (salário /30) * dias trabalhados no mês da rescisão; 
- retorno: saldo Salario;

### criar função calculaDecimoTerceiroProporcional
- recebe como parâmetro o salário e os meses trabalhados no ano da rescisão;
- fórmula: (salário / 12) * meses trabalhados no ano da rescisão;
- retorno: decimo Terceiro;

### criar função calculaFeriasVencidas
- recebe como parâmetro o salário;
- fórmula: salário + (1 terço do salário);
- retorno: ferias Vencidas

### criar função calculaFeriasProporcionais
- recebe como parâmetro o valor das férias vencidas e meses trabalhados no ano da rescisão;
- fórmula: (ferias Vencidas / 12) * meses trabalhados no ano da rescisão; 
- retorno: ferias Proporcionais

### criar função calculaAvisoPrevioIndenizado
- recebe como parâmetro o salário;
- fórmula: salário + 3 dias de salário;
- retorno: aviso PrevioIndenizado

### criar função calculaMultaRescisoria
- recebe como parâmetro o salário e o tempo total trabalhado na empresa em meses;
- fórmula:
        deposito Mensal FGTS = 8% do salário;
        total Contribuicao FGTS = deposito Mensal FGTS * tempo total trabalhado na empresa em meses;
        multa Rescisória = 40 % do total Contribuicao FGTS;
- retorno: multa Rescisoria

### criar função calculaTotal
- recebe como parâmetro o retorno de todas as funções calcula;
- fórmula: somar o retorno das funções saldoSalario , feriasVencidas , feriasProporcionais , decimoTerceiroProporcional , avisoPrevioIdenizado , multaRescisoria;
- retorno: retornar o resultado da soma

   