# Пурия

На графике ступенчатые индикаторы - дневные, плавные - часовые.
Торговая операция проходит после закрытия предыдущей свечи. Напримерт, если условия входа выполняются 12 июля в 9:00, то вход будет 12 июля в 10:00.

## Условия

### Покупка

- ma5 выше ma75l и ma85l
- ma5 была ниже ma75l и ma85l 2 часа назад (ma5 ниже обеих на прошлой или позапрошлой свече)
- свеча закрылась выше ma75l и ma85l
- не было пересечений (вверх или вних) ma по крайней мере 8 часов
- macd > 0.00005
- стохастик растет (изменение stoch за последний час > 0.00001)
- на дневке ma5 выше ma75l и ma85l
- на дневке свеча закрылась выше ma75l и ma85l

## Бектесты

Период: июнь-август 2024.

Счет: $10000

Leverage: 10x

Size: в зависимости от доступных средств и риска

### EURUSD

#### Profit target

20 pips, ~$190-$200

#### Stop loss

Падение цены на 10%. Риск 10% от баланса.

#### [Chart](./charts/EURUSD_2024.html)

#### Stats

Equity Final [$] 10174.752021

Return [%] 1.74752

Buy & Hold Return [%] 2.176447

Max. Drawdown [%] -0.474778

Max. Drawdown Duration 0 days 06:00:00

Trades 1

Win Rate [%] 100.0

#### Trades

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }

</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>EntryTime UTC</th>
      <th>Duration</th>
      <th>Size</th>
      <th>EntryPrice</th>
      <th>ExitPrice</th>
      <th>PnL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2024-07-10 13:00:00</th>
      <td>0 days 19:00:00</td>
      <td>92376</td>
      <td>1.082638</td>
      <td>1.08453</td>
      <td>174.752021</td>
    </tr>
  </tbody>
</table>
</div>

### AUDUSD

#### Profit target

24 pips, ~$350-$380

#### Stop loss

Падение цены на 10%. Риск 10% от баланса.

#### [Chart](./charts/AUDUSD_2024.html)

#### Stats

Equity Final [$] 9971.157423

Return [%] -0.288426

Buy & Hold Return [%] 4.045034

Max. Drawdown [%] -10.356227

Max. Drawdown Duration 24 days 08:00:00

Trades 4

Win Rate [%] 75.0

#### Trades

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }

</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>EntryTime UTC</th>
      <th>Duration</th>
      <th>Size</th>
      <th>EntryPrice</th>
      <th>ExitPrice</th>
      <th>PnL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2024-07-02 14:00:00</th>
      <td>0 days 23:00:00</td>
      <td>150037</td>
      <td>0.666567</td>
      <td>0.668900</td>
      <td>350.088834</td>
    </tr>
    <tr>
      <th>2024-07-30 13:00:00</th>
      <td>0 days 12:00:00</td>
      <td>-158359</td>
      <td>0.653515</td>
      <td>0.651180</td>
      <td>369.711572</td>
    </tr>
    <tr>
      <th>2024-08-06 12:00:00</th>
      <td>0 days 13:00:00</td>
      <td>-165459</td>
      <td>0.647815</td>
      <td>0.654359</td>
      <td>-1082.695527</td>
    </tr>
    <tr>
      <th>2024-08-23 13:00:00</th>
      <td>0 days 01:00:00</td>
      <td>143204</td>
      <td>0.673027</td>
      <td>0.675360</td>
      <td>334.052544</td>
    </tr>
  </tbody>
</table>
</div>
