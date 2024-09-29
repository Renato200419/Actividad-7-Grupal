---
name: Must allow multiple counters
about: Template para la historia de usuario que permite gestionar múltiples contadores
  dentro del servicio, facilitando el seguimiento de diferentes métricas de forma
  simultánea
title: ''
labels: ''
assignees: ''

---

**As a** User,  
**I need** the ability to have multiple counters,  
**So that** I can keep track of several counts at once.

### Details and Assumptions
* El servicio debe permitir agregar y visualizar múltiples contadores.
* Los contadores deben identificarse por nombres únicos para evitar confusión.

### Acceptance Criteria
```gherkin
Given [the user has access to the service]  
When [the user creates a new counter]  
Then [the counter should appear in the list of available counters]
```
