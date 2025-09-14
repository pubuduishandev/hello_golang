# Go Learning Examples

A collection of hands-on Go (Golang) example programs covering core concepts, standard libraries, and advanced topics. This README guides you to **set up Go** on your PC and **run the example files**.

## **1. Install Go on Your PC**

### Windows
1. Download the installer from [Go Downloads](https://golang.org/dl/).
2. Run the `.msi` installer and follow the wizard.
3. Verify installation:

```bash
go version
```

You should see something like:

```
go version go1.25.1 windows/amd64
```

### macOS
1. Download the `.pkg` installer from [Go Downloads](https://golang.org/dl/).
2. Open the installer and follow instructions.
3. Verify installation:

```bash
go version
```

### Linux
1. Download the tar file from [Go Downloads](https://golang.org/dl/).
2. Extract to `/usr/local`:

```bash
sudo tar -C /usr/local -xzf go1.xx.linux-amd64.tar.gz
```

3. Add Go to PATH:

```bash
export PATH=$PATH:/usr/local/go/bin
```

4. Verify installation:

```bash
go version
```

## **2. Clone This Repository**

```bash
git clone https://github.com/yourusername/go-learning-examples.git
cd go-learning-examples
```

## **3. Folder Structure**
Each folder contains examples grouped by topic:

```
go-learning-examples/
│
├── basics/          # Hello World, Variables, Constants, Loops, If/Else
├── functions/       # Functions, Multiple Return Values, Closures, Recursion
├── concurrency/     # Goroutines, Channels, Worker Pools
├── structs/         # Structs, Methods, Interfaces
├── stdlib/          # JSON, HTTP, Time, File operations
└── README.md
```

## **4. Running Examples**
1. Open a terminal in the example folder.
2. Run any `.go` file with `go run`:

```bash
go run hello_world.go
```

Output:

```
Hello, Go!
```

3. For modules (if required):

```bash
go mod init example_name   # Only once per project/folder
go run filename.go
```

## **5. Naming Conventions**
* Use **lowercase letters** and underscores for filenames: `text_templates.go`
* Do **not** use hyphens `-` in filenames.

## **6. Learning Resources**
* [Official Go Documentation](https://golang.org/doc/)
* [Go by Example](https://gobyexample.com/)

## **7. Contributing**
* Add new examples in the appropriate folder.
* Follow Go conventions and add comments explaining your code.
* Submit a pull request with a description of your changes.

---

This README is **universal**, so anyone can:
1. Set up Go on Windows/macOS/Linux
2. Navigate folders
3. Run any example file
4. Learn Go step by step