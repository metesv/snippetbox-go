# snippetbox-go
This repo is my personal work on Alex Edwards book named Let's Go!

Here is my notes from book:

Go modules:
It is a canonical name or identifier for your project.
You can pick any string as you want the important thing is uniqueness.
The command is turn project directory into a module -> go mod init <param>
It will create go.mod file
Turning project directory a module has few advantages: Managing third-party dependencies, avoid supply-chain attacks, reproducible builds...

Running app command: 
go run .

Web application terminology:
We can establish a web server in Go natively and listen requests. There is no need external third-party server like Nginx.
Router -> servemux
