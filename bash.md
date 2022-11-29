# Bash
[My Notes](./README.md)


## Introduction
---
Open your terminal 

    1) nano nameofscript.sh
    2) shebang = #!/bin/bash
    3) chmod +x nameofscript.sh
    4) bash nameofscript.sh or ./nameofscript



>in text editor begin with the shebang : #!/bin/bash
-type your text with echo "blabla" and your arguments with "$"

the argument can be a command,for examples : 

- name=$1
- compliment=$2
- user=$(whoami)
- date=$(date)
- whereami=$(pwd)


    >echo "good morning $name"
    - sleep 1
  
    >echo "you're looking good $name"
    - sleep 1

    >echo "you have the best $compliment I'v ever seen $name"
    - sleep 2
        
    >echo "you are currently logged in as $user and your are in the dire$
            $whereami. also today is $date"
---
       
## Variables
---

                    VAR=X 

for exemple:
  - PRICE_PER_APPLE=5
  - MyFirstLetters=ABC
  - greeting='Hello world!'

Variable : on peut créer une variable en lui assignant une valeur.
cette valeur peut contenir un nombre, un caractère ou une ligne de caractères.
Il faudra utiliser le "=" sans espaces ni avant ni après le signe.
N.B: une combinaison de lettres sera séparé par "_"


## If, Then, Else
---
### If
A basic if statement effectively says, if a particular test is true, then perform a given set of actions. If it is not true then don't perform those actions. If follows the format below:

            if [ <some test> ]
            then
            <commands>
            fi

### Then 

Anything between then and fi (if backwards) will be executed only if the test (between the square brackets) is true.

### Else

Sometimes we want to perform a certain set of actions if a statement is true, and another set of actions if it is false. We can accommodate this with the else mechanism.

            if [ <some test> ]
            then
            <commands>
            else
            <other commands>
            fi


### If Elif Else 

Sometimes we may have a series of conditions that may lead to different paths.

            if [ <some test> ]
            then
            <commands>
            elif [ <some test> ] 
            then
            <different commands>
            else
            <other commands>
            fi


For example it may be the case that if you are 18 or over you may go to the party. If you aren't but you have a letter from your parents you may go but must be back before midnight. Otherwise you cannot go.

## Input and Output
---

## Control Flow
---
- ### While and Until 4m
- ### The Classic For Statement 6m
- ### The C-Style For Statement 6m
- ### Break and Continue 5m
- ### The Case Statement 8m
- ### && and || 8m
## Variables 2
---

### Arrays

Syntax	        Result

- arr=()	    Create an empty array
- arr=(1 2 3)	Initialize array
- ${arr[2]}	    Retrieve third element
- ${arr[@]}	    Retrieve all elements
- ${!arr[@]}	Retrieve array indices
- ${#arr[@]}	Calculate array size
- arr[0]=3	    Overwrite 1st element
- arr+=(4)	    Append value(s)
- str=$(ls)	    Save ls output as a string
- arr=( $(ls) )	Save ls output as an array of files
- ${arr[@]:s:n}	Retrieve n elements starting at index s
## Handling Script Parameters
---
## Shell Functions
---
## Fun with Strings
---
## Many Ways to Run Your Script
---


    