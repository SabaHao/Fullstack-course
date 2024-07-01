```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POSThttps://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: Note created
    deactivate server
```