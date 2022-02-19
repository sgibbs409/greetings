# greetings
A random Go module

### To publish package

#### Set version tag

- `git commit -m "Commit msg for version 1.0.1"`

- `git tag v1.0.1`

- `git push origin v1.0.1`

- `git push`

#### Signal Go pkg manager of new module to publish

- `GOPROXY=proxy.golang.org go list -m github.com/sgibbs409/greetings@v1.0.1`


### To use

#### File Imports

	import ( 
	...
	"github.com/sgibbs409/greetings"
	)

### In package dir

- `go get github.com/sgibbs409/greetings`

	
