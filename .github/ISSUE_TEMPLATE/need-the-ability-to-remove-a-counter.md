---
name: Need the ability to remove a counter
about: Template para la historia de usuario que permite eliminar contadores cuando
  ya no sean necesarios.
title: ''
labels: ''
assignees: ''

---

**As a** User,  
**I need** the ability to remove a counter,  
**So that** I can delete unnecessary counters and keep my list organized.

### Details and Assumptions
* Los contadores eliminados deben ser removidos permanentemente del servicio.
* La eliminación debe ser irreversible y confirmada por el usuario.

### Acceptance Criteria
```gherkin
Given [a counter is no longer needed]  
When [user removes the counter]  
Then [the counter is deleted and no longer appears in the list]
```
