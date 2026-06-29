# Guía para contribuir a ManosAbiertasVenezuela

¡Gracias por querer aportar! Este documento explica cómo funciona la colaboración en este repositorio.

---

## Antes de empezar

1. Lee el [README](./README.md) para entender qué estamos construyendo y por qué.
2. Revisa los [issues abiertos](../../issues) para ver qué se está trabajando y evitar duplicar esfuerzo.
3. Si tienes una idea nueva o encontraste un bug, **abre un issue primero** antes de hacer código. Así coordinamos.

---

## Flujo de trabajo

```
1. Fork del repositorio
2. Crea una rama: git checkout -b feature/nombre-descriptivo
3. Haz tus cambios
4. Commit con mensaje claro: git commit -m "feat: descripción breve"
5. Push a tu fork: git push origin feature/nombre-descriptivo
6. Abre un Pull Request hacia la rama main de este repo
```

---

## Convención de commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/es/):

| Prefijo | Cuándo usarlo |
|---|---|
| `feat:` | Nueva funcionalidad |
| `fix:` | Corrección de bug |
| `docs:` | Cambios en documentación |
| `style:` | Cambios de formato (sin lógica) |
| `refactor:` | Refactorización sin cambio de funcionalidad |
| `test:` | Agregar o corregir tests |
| `chore:` | Tareas de mantenimiento |

---

## Etiquetas de issues

| Etiqueta | Significado |
|---|---|
| `good first issue` | Ideal para nuevos contribuidores |
| `help wanted` | Se necesita ayuda externa |
| `bug` | Algo no funciona como debería |
| `feature` | Nueva funcionalidad propuesta |
| `design` | Requiere trabajo de UX/UI |
| `volunteer` | Contribución no técnica |
| `org-partnership` | Propuesta de alianza con organización |
| `urgent` | Prioridad alta |

---

## Prioridades actuales (MVP)

Si no sabes por dónde empezar, estos son los issues más importantes ahora:

1. **Stack tecnológico definido:** FastAPI (Python) + React + Supabase + Railway + Vercel — configurar estructura inicial del proyecto
2. **Diseño de esquema de base de datos** — para los dos módulos (alojamiento y talento)
3. **Wireframes del flujo de usuario** — especialmente para usuarios con conectividad limitada
4. **Frontend básico** — formulario de registro para quien ofrece espacio

---

## Principios de diseño

Toda contribución debe respetar estos principios:

- **Accesibilidad ante todo:** la plataforma debe funcionar con conectividad lenta o inestable.
- **Sin barreras de entrada:** el registro debe ser posible sin cuenta, con pasos mínimos.
- **Privacidad:** los datos de contacto de los usuarios nunca se exponen públicamente de forma directa.
- **Bilingüe:** todo contenido de cara al usuario debe estar en español. El inglés es bienvenido como segunda lengua en la documentación técnica.

---

## Código de conducta

Este proyecto se rige por los principios de respeto, colaboración y propósito compartido. Cualquier conducta irrespetuosa resultará en la remoción del colaborador. Estamos aquí para ayudar a Venezuela — eso es lo que importa.

---

## ¿Preguntas?

Abre un issue con la etiqueta `question` o escríbenos directamente.
