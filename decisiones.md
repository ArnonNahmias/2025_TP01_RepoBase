# Decisiones del TP01
## Configuración de identidad
Para este trabajo práctico configuré mi identidad de Git de la siguiente forma:
```bash
git config --global user.name "ArnonNahmias"
git config --global user.email "2222270@ucc.edu.ar"
git config --global init.defaultBranch main




## Estrategia de desarrollo

Usamos una **rama nueva** (`feature/nueva-funcionalidad`) para no trabajar directo en `main` y así mantenerlo siempre estable.  
Hicimos **commits atómicos** para que cada cambio sea pequeño, claro y fácil de revisar o revertir si hace falta.
