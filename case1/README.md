# Automation Analitics for Criptocurrency Account Tributation in Brazil

---

1. Collect all instructions
2. Make a run
3. Docs it

---
## First piece

```
o arquivo binance csv é o arquivo bruto retirado da binance, o foxbit-Evair são dados semi tratados pelo cliente e enviado para mim, como se ele tivesse pego o csv da corretora e extraído estas informações para eu analisar, no caso deste cliente o CSV não corresponde as suas operações , pois este foi arquivo que encontrei para dar de exemplo, e o ultimo arquivo planilha calculo foxbit vitoria foi onde eu peguei os dados da foxbit-evair e calculei o saldo final dele, ganhos de capital e total de vendas de cada mês
```
===
```
os parâmetros que eu preciso prestar atenção são o seguinte:
IN1888: A IN1888 é uma obrigação acessória, sendo assim o declarante não pagará nada apenas apresentará informações ao fisco, a IN1888 é declara no ECAC o portal eletrônico da receita federal, e é possível fazer uma declaração manual ou importada, mas os arquivos tem que estra no formato aceito pela receita
```
[in1888](data/in1888.rar)


```
o arquivo anterior é referente ao formato aceito pela receitafederal a declaração da IN1888 é mensal, devo declarar os meses cuja a movimentação é maior do que 30mil
este foi o primeiro tópico IN1888
GCAP:

O gcap seria a declaração de ganhos de capital, todas as vendas de cripto moeda que o cliente efetua eu preciso verificar o preço de médio do ativo em sua carteira e calcular o ganho de capital, desde que o montante total de vendas no mês seja maior que 35k, sendo menor os ganhos serão isentos, esta declaração é mensal
BENS E DIREITOS:
A parte de bens e direitos é simples, ele é preenchido dentro do programa de imposto de renda, basta apurar o saldo final de cada criptomoeda em 31-12  e o seu valor, eu devo declarar todas as criptos com saldo igual ou maior a 5k
com relação ao projeto de contabilidade é basicamente isso, eu devo fazer um arquivo com todos os dados de um cliente para a gente poder testar, esse ai se não me engano o csv não é dele, caso você ja tenha compreendido
```
