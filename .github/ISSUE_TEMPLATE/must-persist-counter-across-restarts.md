---
name: Must persist counter across restarts
about: Template para la historia de usuario que asegura que los contadores persistan
  su estado incluso después de un reinicio del servicio.
title: ''
labels: ''
assignees: ''

---

**As a** Service Provider,  
**I need** the service to persist the last known count,  
**So that** users don't lose track of their counts after a restart.

### Details and Assumptions
* El servicio debe almacenar el valor actual de cada contador de forma persistente.
* En caso de un reinicio, los valores deben restaurarse automáticamente al último estado conocido.

### Acceptance Criteria
```gherkin
Given [the service is restarted]  
When [user checks their counter]  
Then [the count is the same as before the restart]
```
