<p align="center">
  <img src="https://raw.githubusercontent.com/link-loom/.github/main/profile/assets/link-loom.svg" alt="Link Loom" width="300">
</p>

<p align="center">
  Open-source building blocks for software that runs in production: a runtime for Node.js services, the React kits for
  the apps around them, and a CLI that creates both with the standard already in place.
</p>

<p align="center">
  <a href="https://linkloom.io">linkloom.io</a> ·
  <a href="https://www.npmjs.com/org/link-loom">npm</a> ·
  <a href="https://github.com/link-loom/loom-cli">Link Loom CLI</a>
</p>

## Start here

```bash
npx @link-loom/cli
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/link-loom/.github/main/profile/assets/cli-home-dark.svg">
  <img src="https://raw.githubusercontent.com/link-loom/.github/main/profile/assets/cli-home-light.svg" alt="The Link Loom CLI: Loomi says hi and asks what you want to create" width="760">
</picture>

The CLI creates a landing page, a webapp (client or admin) or a backend service, and then every piece inside it (a
CRUD, a page, a section, a sidebar entry) with the same standard every time. Each flow shows its plan before writing
anything and ends with the equivalent command, so whatever a person does in the terminal, an agent can repeat.

## Meet Loomi

<p align="center">
  <img src="https://raw.githubusercontent.com/link-loom/.github/main/profile/assets/loomi.svg" alt="Loomi idle, working, done and stopped" width="760">
</p>

Loomi is the weaver who keeps you company in the CLI. It blinks while you choose, puts on a hard hat while your project
is woven, waves when it is done, and looks a little sad if you stop halfway, right before telling you how to clean up or
finish.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/link-loom/.github/main/profile/assets/cli-working-dark.svg">
  <img src="https://raw.githubusercontent.com/link-loom/.github/main/profile/assets/cli-working-light.svg" alt="Loomi at work with a hard hat while the dependencies install, with the progress beside it" width="760">
</picture>

## Built for agents

The CLI is made for AI agents first, with a real terminal UI for people:

- **One JSON document** on stdout with `--json`, stable exit codes and `--dry-run` plans.
- **An MCP server**: `npx @link-loom/cli mcp` offers the same commands as tools, and generated webapps and landing pages
  connect it in `.mcp.json`.
- **Progress** of long runs as JSON lines on stderr, and as `notifications/progress` over MCP.
- **`AGENTS.md` and skills** in every project, plus a quality gate (`npx link-loom check`) that says what to fix.

## Projects

| Repository | Package | What it is |
| --- | --- | --- |
| [loom-cli](https://github.com/link-loom/loom-cli) | `@link-loom/cli` | Creates landing pages, webapps and services, and every piece inside them |
| [loom-sdk](https://github.com/link-loom/loom-sdk) | `@link-loom/sdk` | The runtime for Node.js services: lifecycle, dependency injection, adapters and workers |
| [loom-svc-js](https://github.com/link-loom/loom-svc-js) |  | The service template on the SDK |
| [link-loom-react-shell](https://github.com/link-loom/link-loom-react-shell) | `@link-loom/react-shell` | The frame of every Link Loom webapp: header, sidebar, menus, sign-in screens, language and theme |
| [link-loom-react-sdk](https://github.com/link-loom/link-loom-react-sdk) | `@link-loom/react-sdk` | React components, Omnisearch, page meta and the record and list kit |
| [link-loom-cloud-sdk](https://github.com/link-loom/link-loom-cloud-sdk) | `@link-loom/cloud-sdk` | Link Loom Cloud for React: App Engine apps, the launchpad, platforms, support center and billing |
| [agent-skills](https://github.com/link-loom/agent-skills) |  | Agent skills for Link Loom frontends and backends |

## Contributing

Issues and pull requests are welcome in each repository. Its README says how to run it, and its license file says how
you can use it.
