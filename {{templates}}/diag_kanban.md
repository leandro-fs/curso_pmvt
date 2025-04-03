
```mermaid
---
config:
  kanban:
    ticketBaseUrl: 'https://127.0.0.1/#TICKET#'
---
kanban
  pilap[Pila Producto]
  listo[Listo para sprint]
  pilas[Pila Sprint]
  asignado[Progresando]
  completo
	  tarjeta1[historia completa]@{ticket: tktID, assigned: [[NombreApellido1]]}	
  validado
```
[ayuda](https://mermaid.js.org/syntax/kanban.html)

```
  pilap[Pila Producto]
  refinado[Listo para sprint]
  pilas[Pila Sprint]
  asignado[Progresando]
  espera[Esperando]
  completo
```


```
Backlog
Ready
Coding
Testing
Approval
Blocked
Deploy
```
