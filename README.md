~~~go
package main

type DeltaLimit struct {
	Name     string `json:"Name"`
	Location string `json:"Location"`
	Skills   string `json:"Skills"`
	Age      int    `json:"Age"`
}

func main() {
	var ME DeltaLimit
	ME.Name = "DeltaLimit"
	ME.Age = 15
	ME.Skills = "GoLang, MySQL, SQLite, MongoDB, Redis, Lua, Java, Kotlin"
	ME.Location = "Asia/Shanghai"
}

~~~

<script src="https://gist.github.com/DeltaLimit/54d9e2a926782ce29123a2ce86835ee8.js"></script>
