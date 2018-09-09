Verkefni 2
1. Búðu til object með upplýsingar um þig; nafn, heimasími og gsm. Prentaðu út með
console.log() síðara símanúmerið (0.5%)
```javascript
  var eg = {
    name: "Helgi Tuan",
    heimasimi: 5861355,
    gsmsimi: 7722236
  };
  console.log(eg.gsmsimi)

2. Prentaðu út með console.log() Nonni. (0.5%)
  let family = {
  "parents":
  {
  "fathers": [{"name":"Jakob"},{"name":"Nonni"}],
  "mothers":[{"name":"Rakel"},{"name":"Sara"}]
  }
   };

 console.log(family.parents.fathers[1])
```
3. Leystu lið 8 í Objects á Udacity https://classroom.udacity.com/courses/ud803 (1%)
```javascript
  var breakfast = {
    name: "The Lumberjack",
    price: 9.95,
    ingredients: ['eggs','sausage','toast','hashbrowns','pancakes']
  };
```
4. Leystu lið 9 í Objects á Udacity https://classroom.udacity.com/courses/ud803(1%)
```javascript
var savingsAccount = {
  balance: 1000,
  interestRatePercent: 1,
  deposit: function addMoney(amount) {
      if (amount > 0) {
          savingsAccount.balance += amount;
      }
  },
  withdraw: function removeMoney(amount) {
      var verifyBalance = savingsAccount.balance - amount;
      if (amount > 0 && verifyBalance >= 0) {
          savingsAccount.balance -= amount;
      }
  },
  // your code goes here
  printAccountSummary: function(){
      return "Welcome!\nYour balance is currently $" + savingsAccount.balance + " and your interest rate is " + savingsAccount.interestRatePercent + "%."
  }
};

console.log(savingsAccount.printAccountSummary());
```

5. Leystu lið 12 í Objects á Udacity https://classroom.udacity.com/courses/ud803(1%)
```javascript
  var donuts = [
    { type: "Jelly", cost: 1.22 },
    { type: "Chocolate", cost: 2.45 },
    { type: "Cider", cost: 1.59 },
    { type: "Boston Cream", cost: 5.99 }
  ];

  // your code goes here
  donuts.forEach(function(a) {
    return console.log(a.type + " donuts cost $" + a.cost + " each")
  });
```
6. Búðu til og notaðu smið (e. function constructor) til að búa til tvær mismunandi pizzur
(objects). Pizzan þarf að hafa; verð, stærð (large, medium, size) og álegg (ostur, skinka,
pepperoni, ananas). Dæmi: Stór Magherita (ostur, oregano) kr. 2195. (1%)
```javascript
function Pizza(size,alegg,alegg1){
  this.size = size
  this.alegg = alegg
  this.alegg1 = alegg1
}

var Pizza1 ={size: "Stór", alegg:"skinka" , alegg1:"ananas"}
var Pizza2 ={size: "Lítil", alegg:"pepperoni" , alegg1:"rjómaostur"}

console.log(Pizza1.size +" Hawaii ("+ Pizza1.alegg , Pizza1.alegg1 + ") kr. 2295.")
console.log(Pizza2.size +" RjómaPepp ("+ Pizza2.alegg , Pizza2.alegg1 + ") kr. 1995.")
```
