# Conversor de Temperaturas

Tarefa que consistia em desenvolver um Conversor de Temperaturas de Celsius para Fahrenheit.

## Desenvolvimento

- [X] Conversor de Temperaturas Desenvolvido

-  [X] Converter de Celsius para Fahrenheit
  
-  [ ] Converter de Fahrenheit para Celsius

### Código Principal do Conversor: 
```
        private void btnConverter_Click(object sender, EventArgs e)
        {
            int TCel,TFah;

            TCel = int.Parse(textBox1.Text);
            TFah = (((TCel * 9 ) / 5) + 32);

            label5.Text = TFah.ToString();
        }
``
