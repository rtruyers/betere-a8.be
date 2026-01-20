# bet ere-a8.be

Static Hugo website (theme: PaperMod) for the *Actiecomité “Een Betere A8”* in Essenbeek (Halle, BE).

This site publishes news, updates and background information about the planned A8 project in Halle: the highway is expected to go into a tunnel, while access patterns around the neighbourhood may change significantly. The committee aims to keep residents informed (including less-publicized updates), and to act as a bridge between citizens, the project actors, and the local government of Halle. Together, we try to ensure practical neighbourhood concerns and details are not overlooked during planning and construction.

## Tech

- **Static site generator:** Hugo (Extended)
- **Theme:** PaperMod (included as a submodule under `themes/PaperMod/`)
- **Config:** `hugo.yml`
- **Content:** `content/`
- **Static assets:** `static/`
- **Generated output:** `public/` (created by Hugo)

## Local development

### Prerequisites

- Hugo **Extended** (recommended: match the version used in CI)
- Git (for theme submodule)

## Writing content

- Blog posts live in `content/posts/`.
- Images can be placed in `static/` or alongside content (depending on your preferred Hugo setup).
- Tags/categories are used to group posts (e.g. “Nieuws”, “Verslagen”).

## Contributing

Contributions are welcome (typos, improvements, new posts/updates).

- Prefer small PRs with a clear description.
- Keep the tone factual and cite sources where possible.

## Theme license

PaperMod is a third-party theme with its own license. See `themes/PaperMod/LICENSE` and `themes/PaperMod/README.md` for details.
