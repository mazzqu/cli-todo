## Todo CLI

For learning Golang purpose & neat line code.

### Build with

Golang(1.19)

## Getting Started

1. Making setup for go module in your local enviroment.

```sh
go mod init github.com/mazzqu/cli-todo
```

<br/>
or
<br/>

2.Clone this repository instead for a short hand.

```sh
git clone https://github.com/mazzqu/cli-todo.git
```

## Usage

How to run :

```sh
go run main.go -task "Task thats you want to add."
```

How to check list of data there :

```sh
go run main.go -list
```

how to change complete :

```sh
go run main.go -complete 1
```

How to test :

```sh
go test -v
```

<br/>
or

<br/>

```sh
go test -v -run functionName
```
