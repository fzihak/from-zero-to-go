# Go Basics - Hello World Explained

## Breaking Down My First Go Program

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

### Line-by-Line Breakdown

**`package main`**
- Every Go program needs a **package**
- `main` means this is the program that can run (executable)
- Think of it as telling Go "this is a complete program, not just a piece of one"

**`import "fmt"`**
- `import` brings in extra tools to use in my program
- `fmt` is a Go tool for **printing text** and **formatting data**
- Like borrowing tools from a toolbox when you need them

**`func main()`**
- `func` = **function**, a piece of code that does something
- `main()` is where Go **starts running** the program
- Every executable Go program must have a `main()` function

**Curly braces `{}`**
- Everything inside `{}` is part of the main function
- They **group the code together**
- Like putting related items in the same box

**`fmt.Println("Hello, World!")`**
- `fmt.Println` prints text to the screen
- `"Hello, World!"` is the text I want to show
- `Println` adds a **new line automatically** (unlike `Print`)

## How to Run

1. **Save** as `filename.go` (`.go` extension is required)
2. **Open terminal** in the same folder
3. **Run command**: 
   ```bash
   go run hello.go
   ```
   (Replace `hello.go` with your actual filename)

## Key Concepts to Remember

| Term | Simple Explanation | Example |
|------|-------------------|---------|
| **Function** | Small action or task | `main()` |
| **Package** | Folder with useful code | `fmt` |
| **String** | Text in quotes | `"Hello, World!"` |
| **Dot `.`** | Use something from a package | `fmt.Println` |
| **Curly braces `{}`** | Group code together | `{ code here }` |

## Mental Model
Think of Go programs like recipes:
- **Package** = The cookbook section (main dishes, desserts, etc.)
- **Import** = Getting ingredients from the pantry
- **Function** = Individual recipe steps
- **Curly braces** = Grouping related steps together
- **Running the program** = Following the recipe to make the dish

---

*Next up: Variables and data types! 🎯*