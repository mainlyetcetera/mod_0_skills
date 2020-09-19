## Example of a Class in a Restaurant: Wine

**Attributes:**
  * wineName _(string)_
  * isRed _(boolean)_
  * isWhite _(boolean)_
  * category _(string)_
  * priceByGlass _(number)_
  * priceByBottle _(number)_
  * taste _(array of strings)_
  * bottlesInStock _(number)_
  * bottlesNeedInInventory _(number)_

**Methods:**
  * changeNeed: reset bottlesNeedInInventory to new number
  * stock: reset bottlesInStock number to equal bottlesNeedInInventory number
  * serveByBottle: decrement bottlesInStock by 1
  * describeTaste: print exclamation describing the taste
  * givePrice: describe the price by glass and bottle
  * changeColor: swap which value is true, isRed or isWhite
  * describeCategory: print formatted category string
