```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, {{date}}, 30d
    Another task     :after a1  , 20d
    section Another
    Task in sec      :{{date}}  , 12d
    another task     : 24d
```