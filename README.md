<div align="center">
  <img src="./assets/banner.svg" width="100%" />
</div>

<br />

```go
package main

type Engineer struct {
    Name        string
    Location    string
    Role        string
    Focus       []string
    Stack       []string
    Architecture []string
    CurrentBuilds []string
}

func NewEngineer() Engineer {
    return Engineer{
        Name:     "Daniel White",
        Location: "Derby, UK",
        Role:     "Software Engineer",
        Focus: []string{
            "Backend Systems",
            "Distributed Systems",
            "Developer Tooling",
            "Performance Engineering",
            "System Design",
        },
        Stack: []string{
            "Go",
            "TypeScript",
            "Node.js",
            "React",
            "Next.js",
            "PostgreSQL",
            "Docker",
            "Kubernetes",
        },
        Architecture: []string{
            "HTTP Internals",
            "Concurrency",
            "Caching",
            "Queues",
            "Profiling",
            "Observability",
        },
        CurrentBuilds: []string{
            "Cloudy Inspector",
            "Multi-Repo AI CLI",
            "Go Tooling Projects",
        },
    }
}
