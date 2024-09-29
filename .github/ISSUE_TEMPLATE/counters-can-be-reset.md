---
name: Counters can be reset
about: Template para la historia de usuario que permite a los administradores reiniciar
  el valor de los contadores a cero.
title: ''
labels: ''
assignees: ''

---

**As a** System Administrator,  
**I need** the ability to reset a counter,  
**So that** I can start counting from scratch if needed.

### Details and Assumptions
* El administrador debe poder reiniciar cualquier contador sin afectar a otros contadores.
* El reset debe ser registrado en los logs del sistema para auditoría.

### Acceptance Criteria
```gherkin
Given [a counter has been used]  
When [admin decides to reset it]  
Then [the count should return to zero]
```
