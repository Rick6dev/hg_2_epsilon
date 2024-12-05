| Hacks | Details            |
| ----- | ------------------ |
| H-1   | Hacks              |
| H-2   | Close Pull Request |
| H-3   | Code Review        |

<br/>

---

### WORKFLOW

```mermaid
sequenceDiagram
    participant feature
    participant develop
    participant main
    feature->>develop: envia feature/foo a la rama develop
    develop->>main: los features en develop a la rama main
```

---

PULL_REQUEST_TEMPLATE

# Tipo de usuario

- [ ] Alfa
- [ ] Bravo
- [ ] Charlie
- [ ] Delta
- [x] Echo

# Tecnología

- [x] HTML
- [x] Json
- [x] Archivo plano (.txt)
- [ ] Javascript
- [ ] Markdown / .md

# Seleccione el tipo de actividad

- [x] Feature
- [ ] Changes
- [ ] Hotfix
- [ ] Refactor
- [ ] Performance
- [ ] Testing
