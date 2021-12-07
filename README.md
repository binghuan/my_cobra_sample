# my_cobra_sample

## What is cobra
Cobra is both a library for creating powerful modern CLI applications as well as a program to generate applications and command files.  
<https://github.com/spf13/cobra>
## How to add CLI using Cobra
1. Create a folder for project
```shell
mkdir mycobra;
```

2. Init cobra 
```shell
cd mycobra; 
go mod init mycobra;
cobra init --pkg-name mycobra;
go mod tidy
```

3. Add command 
```shell
cobra add hello;
```

4. Test command
```shell
go run main.go hello
```

Then, you can see the ouput.
```text
hello called
```

## File Structure
```text
.
├── LICENSE
├── cmd
│   ├── hello.go
│   └── root.go
├── go.mod
├── go.sum
└── main.go

1 directory, 6 files

```
