# Countdown

Plugin criado com o intuito de instanciar um contador em escala regressiva a partir de uma data fornecida. O mesmo foi criado usando os conceitos de classe, então pode ser importado como um modulo, direto no escopo do projeto atraves da tag script e afins.  

# Exemplos de Uso
```javascript
import Countdown from './countdown.js';
const daysToXmas = new Countdown('24 December 2018 23:59:59 GMT-0300');

//Return
Countdown {futureDate: "24 December 2018 23:59:59 GMT-0300"}
    futureDate: "24 December 2018 23:59:59 GMT-0300"
    days: 2
    hours: 55
    minutes: 3321
    result: Object
    days: 2
    hours: 7
    minutes: 36
    seconds: 19
    __proto__: Object
    seconds: 199293
    _currentDate: Sat Dec 22 2018 17:38:26 GMT-0200 (Horário de Verão de Brasília)
    _futureDate: Tue Dec 25 2018 00:59:59 GMT-0200 (Horário de Verão de Brasília)
```