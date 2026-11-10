# Unraid templates by coderoftime

Unraid Community Applications templates for the apps at [coderoftime.dev](https://coderoftime.dev).

- `ca_profile.xml` is the repository overview shown in Community Applications.
- `templates/` holds one Docker template per app.
- `icons/` and `screenshots/` hold the images the templates show.

| App                                                 | Template                                           | Support                                                                         |
| --------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------- |
| [Cellarly](https://gitlab.com/coderoftime/cellarly) | [`templates/cellarly.xml`](templates/cellarly.xml) | [Unraid forum thread](https://forums.unraid.net/topic/201181-support-cellarly/) |

Cellarly is in beta, so its template runs the image tag `beta`, the newest release. Its container
runs as `99:100` (`nobody:users`), so its appdata folder is writable by default. Cellarly's README
says how to [install it on Unraid](https://gitlab.com/coderoftime/cellarly/-/blob/main/README.md#on-unraid)
and how to [upgrade](https://gitlab.com/coderoftime/cellarly/-/blob/main/README.md#upgrading), its
data and backups page how to
[roll back](https://gitlab.com/coderoftime/cellarly/-/blob/main/docs/backups.md#rolling-back), and
its [configuration reference](https://gitlab.com/coderoftime/cellarly/-/blob/main/docs/configuration.md)
describes every setting the template offers.

## License

The templates in this repository are free software under the
[GNU Affero General Public License v3.0](LICENSE), as Cellarly itself is.
