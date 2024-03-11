# Lista de Exercícios

## Lista de Exercícios - Valete 03

### Objetivo
Lista Desenvolvida para ver o nível de cada Aluno

- [X] Finalizar o Conversor de Temperaturas
   - [X] Converter para Fahrenheit
   - [ ] Converter para Kelvin
- [X] Finalizar a Calculadora Simples
- [X] Finalizar a Calculadora IMC
- [X] Finalizar o Cronômetro
- [ ] Finalizar a Calculadora de Hipoteca

### Códigos importantes a serem ressaltados:

`O Código de Conversor de Temperaturas`

O Conversor de Temperaturas foi o meu projeto principal dessa lista, que eu tinha que apresentar e falar como ele funcionava.

<details>
   
```
        private void btnConverter_Click(object sender, EventArgs e)
        {
            int TCel,TFah;

            TCel = int.Parse(textBox1.Text);
            TFah = (((TCel * 9 ) / 5) + 32);

            label5.Text = TFah.ToString();
        }

        private void button2_Click(object sender, EventArgs e)
        {
            this.Close();
        }
```
</details>
