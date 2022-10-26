~~~go
package main

var DeltaLimit struct {
  Name string
  Location string
  Skills string
  Age int
}

func main() {
  DeltaLimit := &DeltaLimit {
    Name:     "DeltaLimit",
    Location: "Asia/Shanghai",
    Skills:   "GoLang, MySQL, MongoDB, Java, Kotlin, Lua",
    Age:      15
  }
  
  fmt.Println(DeltaLimit)
}
~~~
