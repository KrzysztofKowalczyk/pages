
# Markdown based github pages using different md renderer

Todo:
- [x] Render using tui.editor
- [ ] Support for mermaid in fences
- [ ] Solve lack of .hljs on pre (lack of style background from highlight.js themes for code :/)
- [ ] Customize or pick better theme

A **simple** md *file*

A list
- a
- b
- c

[link to nowhere](nowhere)


Java code
```java
public static void hello() {
    System.out.println("world");
}
```

shell code
```sh
echo "hello world"
```


A graph
```mermaid
graph TD
A[Christmas] -->|Get money| B(Go shopping)
B --> C{Let me think}
C -->|One| D[Laptop]
C -->|Two| E[iPhone]
C -->|Three| F[fa:fa-car Car]
```

Sequence diagram
```mermaid
sequenceDiagram
participant Alice
participant Bob
Alice->John: Hello John, how are you?
loop Healthcheck
    John->John: Fight against hypochondria
end
Note right of John: Rational thoughts <br/>prevail...
John-->Alice: Great!
John->Bob: How about you?
Bob-->John: Jolly good!
```