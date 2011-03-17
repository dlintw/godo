## godo

Shell script which allows running Go "scripts" like "godo script.go" in the style of "ruby script.rb" or "python script.py".

### Installation

Place the file anywhere in your $PATH and you're good to go.

### Usage

Either

	godo script.go

Or

	chmod +x script.go
	./script.go
	
	# assuming `script.go` begins with "#!/usr/bin/env godo"

### Credits

Inspiration came from gorun and goscript, but they're both written in Go, this is written in portable .sh and is simpler.