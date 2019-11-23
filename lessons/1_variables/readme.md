Variables are little memory helpers, they remember things for you

### declare a new variable like this:

`let VARIABLE_NAME;`

VARIABLE_NAME can be whatever you want, as long as the name isn't "reserved"

### initialize a new variable like this:

```javascript
let VARIABLE_NAME_2 = VALUE;
```
As before VARIABLE_NAME_2 can be whatever you want
VALUE can be anything you want as well, variables can hold many `types` of things

### assign a new value to a variable like this:

```javascript
VARIABLE_NAME = NEW_VALUE;
```

VARIABLE_NAME must be a variable you created earlier (with let or var, not with const)
NEW_VALUE can be anything you like, including something of a completely different type

**example**
```javascript
var myAge = 27;
// At this point myAge is 27
myAge = 28;
// At this point myAge is 28, the old value "27" is gone forever, overwritten by 28
```

## List of `types`

#### Integer: Whole Numbers

```javascript
let jeffery = 1;
let jimmy = 2;
let bobby = 3;
let ernest = 4+4;
let carl = 137213 * 389402834;
let bernard = -999;
```

#### Float: Fractional Numbers (bigger fractional numbers can sometimes be called doubles)

```javascript
let floatingJeffery = 1.2;
let floatingJimmy = 2.99;
let floatingBobby = 5/3;
let floatingErnest = 4+4.1;
let floatingCarl = 137213.1 * 389402834.5;
let floatingBernard = -999.1002;
```

#### String: Words/Sentences/Letters

```javascript
let name = 'jebroni';
let hometown = 'los angeles';
let favoriteFlower = 'orange roses, but sometimes daisies';
let age = '22 years old';
let firstLetter = 's';
let stringWithEscapedQuote = 'You can\'t avoid \'s forever';
let doubleQuotedString = "You don't have to use 's forever";
let backTickString = `You can use backticks to include variables in your string like so: '${firstLetter}'`;
```

#### Array: Lists

```javascript
let appleTypes = ['granny', 'honeycrisp', 'green', 'pink lady'];
let months = ['january', 'february', 'march', 'april', 'may', 'june', 'july', 'august', 'september', 'october', 'november', 'december'];
let days = ['monday', 'tuesday', 'wednesday', 'thursday', 'friday', 'saturday', 'sunday'];
```

#### Object: Key Value Storage (sometimes called dictionaries)

```javascript
let relationships = {
  brendan: 'thao',
  brad: 'angelina',
  brian: 'jessica',
};
let phones = {
  2085556666: 'stephen',
  4401233333: 'ryan',
  9923942441: 'ophelia',
};
let colorCodes = {
  red: 'ff0000',
  green: '00ff00',
  blue: '0000ff',
  white: 'ffffff',
  black: '000000',
};
```

#### Others
There are many many other "types" of things, including

Date
RegExp
Set

You can define your own "types" using classes
