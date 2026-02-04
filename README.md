# Agent Skills

SuperDoc's official collection of skills for AI coding agents. Skills are packaged instructions that extend agent capabilities for document editing applications.

Skills follow the [Agent Skills](https://agentskills.io/) format.

## Available Skills

### superdoc-react

React integration guidelines for SuperDoc - the document editing library. Contains patterns for component usage, lifecycle management, and common use cases.

**Use when:**
- Adding SuperDoc to a React or Next.js application
- Implementing document editing features
- Working with DOCX files in React
- Setting up collaboration features

**Topics covered:**
- Installation and setup
- Component props and ref API
- Document mode switching
- File upload patterns
- SSR/Next.js integration
- Collaboration setup
- TypeScript usage

### superdoc-core

Core SuperDoc usage guidelines for vanilla JavaScript applications. Contains initialization patterns, configuration options, and API reference.

**Use when:**
- Adding SuperDoc to a vanilla JS application
- Integrating with Vue, Svelte, or other frameworks
- Understanding SuperDoc's core API
- Configuring advanced features

**Topics covered:**
- Installation and initialization
- Configuration options
- Event callbacks
- Export and import
- Collaboration modules
- AI integration

## Installation

```bash
npx skills add superdoc-dev/agent-skills
```

Or install specific skills:

```bash
npx skills add superdoc-dev/agent-skills/superdoc-react
npx skills add superdoc-dev/agent-skills/superdoc-core
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

**Examples:**
```
Add a document editor to my React app
```
```
Help me set up SuperDoc with collaboration
```
```
Create a DOCX viewer component
```

## Skill Structure

Each skill contains:
- `SKILL.md` - Instructions for the agent

## Links

- [SuperDoc Documentation](https://docs.superdoc.dev)
- [SuperDoc GitHub](https://github.com/superdoc-dev/superdoc)
- [npm: superdoc](https://www.npmjs.com/package/superdoc)
- [npm: @superdoc-dev/react](https://www.npmjs.com/package/@superdoc-dev/react)

## License

MIT
