## Ventajas de git worktree

Frente a cambiar de rama:
- Permite trabajar en varias ramas a la vez sin hacer checkout constante.

Frente a clonar repositorios:
- Es más ligero (no duplica todo el repo).
- Comparte el mismo historial.

---

## Situaciones reales

1. Trabajar en una feature mientras revisas un bug en otra rama.
2. Revisar un pull request sin cambiar tu entorno actual.
3. Probar un hotfix sin tocar tu rama principal.

---

## Buenas prácticas

- Usar nombres claros: wt-feature-a, wt-bugfix-123.
- Mantener los worktrees organizados fuera del repo principal.
- Eliminar worktrees que ya no se usen.
- Evitar tener demasiados activos al mismo tiempo.
