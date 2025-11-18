# OS.js

Minimal OS.js implementation - a web desktop environment built on the [OS.js](https://github.com/os-js) framework.

## Features

- Full desktop environment with windows, panels, and dialogs
- Virtual file system (VFS)
- Authentication system
- Settings management
- Notifications
- GUI components

## Quick Start

```bash
npm install
npm run build
npm run serve
```

Visit http://localhost:8000 to access the desktop.

## Development

```bash
npm run watch
```

Watches for file changes and rebuilds automatically.

## Structure

```
src/
├── client/          # Frontend application
│   ├── index.js     # Client entry point with service providers
│   ├── index.html   # HTML template
│   └── index.scss   # Global styles
└── server/          # Backend server
    ├── index.js     # Server entry point with service providers
    └── config.js    # Server configuration
```

## Technology Stack

- **Framework**: OS.js v3
- **UI**: Hyperapp
- **Build**: Webpack 5
- **Server**: Node.js with Express
- **Database**: Session storage via connect-loki

## License

MIT
