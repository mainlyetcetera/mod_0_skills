## Instance of Employee: Roger (front-of-house employee)

*Attributes:*
  * isFrontOfHouse: true
  * isBackOfHouse: false
  * hourlyRate: 10.02
  * outfit: ['black shirt,' 'black pants', 'black shoes']
  * lengthEmployedInMonths: 5

*Methods:*
  * `movesBackOfHouse():`
```javascript
isFrontOfHouse: false;
isBackOfHouse: true;
```

  * `movesFrontOfHouse():`
```javascript
isFrontOfHouse: true;
isBackOfHouse: false;
```

  * `increasePay():`
```javascript
console.log(`Congratulations! You got a pay raise! Your pay now is ${hourlyRate + .5}!`); // 10.52
```

  * `describeOutfit():`
```javascript
console.log(`As a reminder, please arrive at work properly dressed in:
${outfit[0]}
${outfit[1]}
${outfit[2]}

Thank you!`);
```
  * `workOneMonth():`
```javascript
lengthEmployedInMonths += 1;
console.log(`Woah! You've been here ${lengthEmployedInMonths}! Great job!`);
```
