```mermaid
classDiagram
    class c1["general"]
    class c2["especial"]
    c1 <|-- c2: tipo
    c1 *-- componente:  {{title}}
```
[ayuda](https://mermaid.js.org/syntax/classDiagram.html)

| Type  | Description   | Comentario |
| ----- | ------------- | ---------- |
| <\|-- | Inheritance   |            |
| `*--` | Composition   |            |
| `o--` | Aggregation   |            |
| `-->` | Association   |            |
| `--`  | Link (Solid)  |            |
| `..>` | Dependency    |            |
| ..\|> | Realization   |            |
| `..`  | Link (Dashed) |            |
