# Commandments of Programming

1. Arrays are meant to be looped through.
1. Objects can be accessed with dot or bracket notation
1. Indices start at 0, this can cause "off-by-one" errors
1. Booleans love if-statements
1. Functions
1. Strings have a length property
1. DRY
1. Scope
1. OOP
1. HTTP

### Functions
```
// named function
function hookah () {

}

// anonymous function
var hookah = function() {

}

// returns
function getName () {
  return "Adrena"
}
var myName = getName()

// arguments/parameters & returns
function canDrinkAlcohol(age) {
  return age >= 21 // expression
}
canDrinkAlcohol(18) // false
canDrinkAlcohol(21) // true
canDrinkAlcohol(25) // true

```

### Booleans
```
var age = 18;
var canDrinkAlcohol = age >= 21;
if (canDrinkAlcohol) {
  //bottoms up!
}
else {
  //shirly temple
}

```


### Objects
```
var user = {
  name: 'Adrena'
};

user.name // Dot Notation
user.age // undefined
user.age = 25;
user.age; // 25

user.age = 25;


var tits = 'age';

user['name'] // "Adrena", Bracket Notation
user[tits] = 25;
```

### Loops
```
var names = ['Adrena', 'Jacob', 'Brian', 'Michael'];
names.forEach(function (name) {
  console.log(name); // First iteration, "Adrena"
});
console.log('Done');

for ( var i = 0; i < names.length; i++) {
  var name = names[i];
  console.log(name);
}

for(var i = 0; i < 4; i++) {
  console.log('Hi', i);
}

```
