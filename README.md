# Prototypes – Example Customer

Vaadin HTML prototypes for Example Customer, published at https://juuso-vaadin.github.io/prototypr-test/.

- **Add or change a prototype:** ask Claude Code in this repository, e.g. "Create a
  prototype of the order list with bulk actions, two variants". It follows
  [CLAUDE.md](CLAUDE.md) and checks its work in the viewer.
- **Publish:** merge to `main`. GitHub Actions deploys the site in a minute or two.
- **Preview locally:** `npm run serve` (Node 20+, nothing to install), then open
  http://localhost:8080/.
- **Comments:** turned off (`site.config.json` → `comments.backend`: `"none"`).

Theme: aura. Vaadin: 25.3.7. How this site was made from the
template: [docs/new-customer-site.md](docs/new-customer-site.md). Specification: [docs/SPEC.md](docs/SPEC.md).
