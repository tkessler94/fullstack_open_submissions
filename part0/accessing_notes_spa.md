```mermaid
    sequenceDiagram
    participant User as User
    participant Browser as Browser
    participant Server as Server

    User->>+Browser: Access SPA URL
    Browser->>+Server: HTTP GET request for SPA
    Server-->>-Browser: Respond with HTML, CSS, JavaScript
    Browser->>Browser: Render initial page content
    Browser->>-User: Display loaded SPA

```