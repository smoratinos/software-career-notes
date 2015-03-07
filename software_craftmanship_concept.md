# Concept


## Sécurité

## Disponibilité et Fiabilité

L'intégration est le 1er risque. Tous les appels externes peuvent nuire au système.

### Circuit Breaker

### Use Timeouts
Thread pools vs. connection pooling

### Let it Crash / Supervisors

Laisser l'erreur se produire et la gérer avec des superviseurs par exemple.
"Retry Strategie"

### Crash Early

Valider les entrées le plus tôt possible.
Ex : validation d'un fichier de configuration
Ex : vérifier la disponibilité des ressources avant d'exécuter une tâche coûteuse.

### Use Decoupling Middleware

### Handshaking

### Test Harness

### Bulkheads

### Steady State (clean up resources)

### Throttling

## Evolutivité

SOA
