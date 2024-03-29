# Design 🧩

### Big Picture 🎨
The project consists of
- `UI`
- Authorization server
- Main server

with the following logic:  
`UI -> Auth server -> Main server -> External service`  
where main server is responsible for calling other services.

### Detailed View 🔩