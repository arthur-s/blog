---
title: "Животный мир Кораллового рифа"
date: "2025-02-04"
image: "coral_reef.jpg"
summary: "Поговорим немного о животном мире?"
---

Hello my friends!

today I want to talk about code examples:

```python
print("This line will be printed.")
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
```

```go
type Point struct {
    x int
    y int
}

func (p *Point) next_row() {
    p.x += 1
}

func main() {
    p := Point{0, 0}
    f := p.next_row

    for i := 0; i < 2; i++ {
        fmt.Println(p)
        f()
    }
    fmt.Println(p)
}
```

Thanks!