# Unraid templates by coderoftime

Unraid Community Applications templates for the apps at [coderoftime.dev](https://coderoftime.dev).

- `ca_profile.xml` is the repository overview shown in Community Applications.
- `templates/` holds one Docker template per app.

| App                                                 | Template                                           |
| --------------------------------------------------- | -------------------------------------------------- |
| [Cellarly](https://gitlab.com/coderoftime/cellarly) | [`templates/cellarly.xml`](templates/cellarly.xml) |

Cellarly's container runs as `99:100` (`nobody:users`), so its appdata folder is writable by default.
