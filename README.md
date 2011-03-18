## godo

Shell script which allows running Go "scripts" like "godo script.go" in the style of "ruby script.rb" or "python script.py".

### Installation

Place the file anywhere in your $PATH and you're good to go.

### Usage

Either

	godo script.go
	godo script1.go script2.go
	godo *.go
	godo script1.go script2.go -- arg1 arg2 arg3

Or

	chmod +x script.go
	./script.go
	./script.go -- arg1 arg2 arg3
	
	# assuming `script.go` begins with "#!/usr/bin/env godo"

### Credits

Inspiration came from gorun and goscript, but they're both written in Go, this is written in portable .sh and is simpler.
