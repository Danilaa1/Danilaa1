<br />

```go
type Engineer struct {
    Name     string
    Location string
    Stack    []string
    Focus    []string
    Building []string
}

var daniel = Engineer{
    Name:     "Daniel White",
    Location: "Derby, UK",

    Stack: []string{
        "Go",
        "TypeScript",
        "Node.js",
        "PostgreSQL",
        "Docker",
        "Kubernetes",
    },

    Focus: []string{
        "Distributed Systems",
        "Developer Tooling",
        "Backend Architecture",
        "Performance Engineering",
    },

    Building: []string{
        "Cloudy Inspector",
        "Multi-Repo AI CLI",
        "System Design Projects",
    },
}
