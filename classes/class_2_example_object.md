## Example of an instance of Wine: Penfolds Max's Cabernet Sauvignon

**Attributes:**
wineName: 'Penfolds Max's Cabernet Sauvignon'
isRed: true
isWhite: false
category: 'cabernet sauvignon'
priceByGlass: 7.5
priceByBottle: 29
taste: ['fruit intensity', 'ripe tannins']
bottlesInStock: 3
bottlesNeedInInventory: 15

**Methods:**
stock:
```javascript
bottlesInStock = 15;
```
serveByBottle:
```javascript
bottlesInStock = 14;
```
describeTaste:
```javascript
console.log(`The exquisite taste of ${wineName} is full of ${taste[0]} and ${taste[1]}!`);
```
givePrice:
```javascript
console.log(`The price of ${wineName} is ${priceByGlass} by the glass and ${priceByBottle} by the bottle.`);
```
changeColor
```javascript
isRed = false;
isWhite = true;
```

category
```javascript
console.log(`The type of wine is ${category}.`);
```
