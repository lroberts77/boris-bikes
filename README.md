# Boris Bikes
### Technologies: Ruby, Rspec

## Index
* [Installation](#Install)
* [Rspec Tests](#Rspec)
* [Project Direction](#Project)
* [Usage](#Usage)

First challenge at Makers Academy, complete a project in Ruby that handles the functionality of Boris's Bikes
<!-- 
## Specification

### Requirements

* You should be able to interact with your code via a REPL like IRB or the JavaScript console.  (You don't need to implement a command line interface that takes input from STDIN.)
* Deposits, withdrawal.
* Account statement (date, amount, balance) printing.
* Data can be kept in memory (it doesn't need to be stored to a database or anything).

### Acceptance criteria

**Given** a client makes a deposit of 1000 on 10-01-2012  
**And** a deposit of 2000 on 13-01-2012  
**And** a withdrawal of 500 on 14-01-2012  
**When** she prints her bank statement  
**Then** she would see

```
date || credit || debit || balance
14/01/2012 || || 500.00 || 2500.00
13/01/2012 || 2000.00 || || 3000.00
10/01/2012 || 1000.00 || || 1000.00
```

## <a name="Project">Project Direction</a>
For this tech test i tried to use code simplicity to keep the code readable and concise. Whilst splitting the Accountstatement class form the Bankaccount class I learned about dependancy injection which made the task easier. Next on my list is to move the transaction handling and formatting into a different class.

## <a name="Install">Installation</a>
* To clone the repo
```shell
$ git clone https://github.com/lroberts77/Bank-account
$ cd bank-account
$ bundle
```


## <a name="Rspec">Rspec Tests</a>
```shell
$ cd bank-account
$ rspec
```


## <a name="Usage">Usage</a>
in the terminal
```ruby
$ ruby irb.rb
$ account = Bankaccount.new
$ account.deposit(100.99)
$ account.deposit(100)
$ account.withdraw(50.20)
$ account.withdraw(30.20)
$ account.outputstatement      
(this displays your current balance)
``` -->