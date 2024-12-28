# Day3LearnSmartContract
This what i learn in day three

## What i learn ?
in this section is no code i just wanna relearn what i code in day 1 and 2 because alot a syntax data types that i dont really understood

## uint and int

i learn bout **uint** and **int** how it works and use for what
so in simple ways **uint** is integer that can only store a positive number, and for **int** is integer that can handle both ways.
and why people using **uint** rather than **int** it's because **uint** is have no overflows or underflows issues because the size is fixed even the positive number exceeds its maximum limit It will simply wrap around and become incorrect and also cant be underflows because the number always be positive.
For example: with uint8, trying to store 255 + 1 would result in 0

## functions

So the function is to make the contract we create have the capabilities needed for the contract we have created.

## this symbol = and this _

yeah this symbol = is just asign value to the variable  
and this symbol _  underscore is used to avoid naming conflicts between variables and parameters.  
**explain**  
_SimpleStorageIndex: This variable name starts with an underscore, which means it's treated as a local or internal parameter.

## new keyword on arrays
new keyword is used for create brand new contract inclued function,variable,own storage and added to array like my code in day two 

**explanation :**

```SimpleStorage newSimpleStorageContract = new SimpleStorage();```


**SimpleStorage** is just type of variable which refers to the contract imported at my code in day two.  
**newSimpleStorageContract** is the variable that gonna hold the value of the intance contract after we deploy it so when we call the function it gonna create brand new contract.  
**new SimpleStorage();** this new keyword use for create new intance, When this is executed, Solidity deploys a new SimpleStorage contract to the blockchain and returns the address of that deployed contract.





