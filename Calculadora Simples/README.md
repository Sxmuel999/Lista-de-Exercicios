#Calculadora Simples

Atividade com o intuito de criar uma Calculadora Simples, que Soma, Subtrai, Divide e Multiplica

## Desenvolvimento

Desafio feito pela Lista de Atividades - Valete 03

- [X] Soma
- [X] Subtração
- [X] Divisão
- [X] Multiplica

### Código: Função de cada botão de sinal

```
        private void btnResultado_Click(object sender, EventArgs e)
        {
            switch (OperacaoSelecionada)
            {
                case Operacao.Adicao:
                    Resultado = Valor + Convert.ToDecimal (txtResultado.Text);
                    break;
                case Operacao.Subtracao:
                    Resultado = Valor - Convert.ToDecimal(txtResultado.Text);
                    break;
                case Operacao.Multiplicacao:
                    Resultado = Valor * Convert.ToDecimal(txtResultado.Text);
                    break;
                ; case Operacao.Divisao:
                    Resultado = Valor / Convert.ToDecimal(txtResultado.Text);
                    break;
            }
            txtResultado.Text = Convert.ToString(Resultado);
```
