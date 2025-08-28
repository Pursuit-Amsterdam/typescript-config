# @pursuit-amsterdam/typescript-config

TypeScript configuration package for Pursuit Amsterdam projects.

## Installation

```bash
npm install --save-dev @pursuit-amsterdam/typescript-config typescript
```

## Usage

### For Next.js projects

```json
{
  "extends": "@pursuit-amsterdam/typescript-config/next.json"
}
```

### For React projects

```json
{
  "extends": "@pursuit-amsterdam/typescript-config/react.json"
}
```

### For Node.js projects

```json
{
  "extends": "@pursuit-amsterdam/typescript-config/node.json"
}
```

### For general TypeScript projects

```json
{
  "extends": "@pursuit-amsterdam/typescript-config/base.json"
}
```

## Configurations

- **base.json**: Strict TypeScript configuration for any project
- **react.json**: Extends base + React-specific settings
- **next.json**: Extends React + Next.js-specific settings (path mapping, etc.)
- **node.json**: Extends base + Node.js-specific settings

## Features

- Strict type checking enabled
- Modern ES features
- Consistent casing enforcement
- Optimized for development experience
- Path mapping support (Next.js config)

## License

MIT