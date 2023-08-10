# Project Title

Creating My_token

## Description

1). Contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2). Contract will have a mapping of addresses to balances (address => uint)
3). Contract will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases 
    the balance of the address by that amount.
4). Contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the 
    mint functions. It will then deduct the value from the total supply and the address's balance.
5). Lastly,  the burn function has conditionals to make sure the balance of the account is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Installing

Here we are executing our code on Remix IDE. So, we don’t need any installation here.

### Executing program

* We first have to compile the code by ctrl+s.
* Then we have to go to deploy and run the transaction option.
* There we will get all the functions and variables which we have created.
* By passing the arguments in that we will able to get our output.
  

## Authors

Name:-   Vishnu Vishvas Sharma
Email:-  21BCS5240@cuchd.in


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
