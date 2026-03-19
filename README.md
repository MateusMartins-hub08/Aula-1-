```mermaid
sequenceDiagram
    participant Usuario
    participant Sistema
    participant Banco

    Usuario->>Sistema: Fazer login
    Sistema->>Banco: Verificar credenciais
    Banco-->>Sistema: OK
    Sistema-->>Usuario: Login aprovado
```
