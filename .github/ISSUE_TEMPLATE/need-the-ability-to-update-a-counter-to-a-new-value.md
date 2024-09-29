---
name: Need the ability to update a counter to a new value
about: Template para la historia de usuario que permite actualizar el valor de un
  contador existente.
title: ''
labels: ''
assignees: ''

---

**As a** User,  
**I need** the ability to update a counter to a new value,  
**So that** I can correct mistakes or update the count as needed.

### Details and Assumptions
* El servicio debe permitir modificar el valor actual del contador a cualquier nuevo valor especificado.
* El historial de cambios en el contador debe mantenerse para referencia futura.

### Acceptance Criteria
```gherkin
Given [a counter has an incorrect value]  
When [user updates the counter to a new value]  
Then [the counter reflects the updated value accurately]
```
