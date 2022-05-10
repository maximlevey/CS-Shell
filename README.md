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

## Redirects

