# Shell Scripting Cheat Sheet

## Command-line interpreter 
`#!/bin/bash`

## Redirects

### Create or Overwrite to Path
`>`

```shell
date > /Users/Admin/Desktop/date.txt
```

### Create or Append to Path 
`>>`

```shell
date >> /Users/Admin/Desktop/date.txt
```

## Variables

### Manually set a Variable
`Variable="Value"`

```shell
myName="Maxim"
```

### Command Substitution
`Variable=$(command)`

```shell
dateAndTime=$(date)
```
### Recall a Variable
`Variable=$(command)`

```shell
myName="Maxim"
dateAndTime=$(date)

  echo "Hello $myName, today is $dateAndTime"
```

## If Statements

### Open an if Statement
`if`

### Text Expressions
Value is Equal `if [[ "Value" == "Value" ]]`

```shell
if [[ "$myName" == "Maxim" ]]
```

Value is Not Equal `if [[ "Value" != "Value" ]]`

```shell
if [[ "$myName" != "Greg" ]]
```

File Exists at Path `if [[ -f /Path/ ]]`

```shell
if [[ -f /Users/Admin/Desktop/date.txt ]]
```

Directory Exists at Path `if [[ -d /Path/ ]]`

```shell
if [[ -d /Users/Admin/Desktop ]]
```
