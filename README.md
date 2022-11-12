# go_quiz

## Get the Beginners CLI development tutorial <a href="https://siddhesh-dev.co/getting-started-with-clis-using-golang">here</a>

This is a simple CLI quiz game built usinh Golang and Cobra-CLI.

Command 1:
```
go_quiz
```
Output :
```
A Simple Quiz game CLI using Golang.
```
Command 2:
```
go_quiz -h
```
Output :
```
A Simple Quiz game CLI using Golang.

Usage:
  go_quiz [flags]
  go_quiz [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  help        Help about any command
  start       Starting a new Quiz

Flags:
  -h, --help     help for go_quiz
  -t, --toggle   Help message for toggle

Use "go_quiz [command] --help" for more information about a command.
```
# To start the Quiz :
```
go_quiz start
```
Output :
```
5+5 :
```

start entering the responses :)

if any of the reponse is incorrect,
Output :
```
.
.
.
8+3 : 1 
Your Score is 3
```
And if all the entered responses are correct,
```
.
.
.
1+8 : 9
correct
Congrats!, you got all questions Correct
Your Score is 16
```
