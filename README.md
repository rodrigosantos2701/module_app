# module_app
# Webpack Module Federation Example

A basic Module Federation setup with one React application demonstrating micro-frontend architecture using Webpack 5 to be consumed as a external module.

## Technology Stack

- **Framework**: React 18
- **Architecture**: Module Federation
- **Bundler**: Webpack 5
- **Language**: JavaScript
- **Deployment**: Zephyr Cloud


## Getting Started

1. **Install dependencies**
   ```bash
   pnpm install
   ```

2. **Start development servers**
   ```bash
   pnpm start
   ```
   
   This starts both applications concurrently:
   - **mf-remote-app3** (Remote): http://localhost:3003
   
   Or start them individually:
   ```bash
   cd mf-remote-app3 && pnpm start  # External remote on port 3003
   ```

3. **Build for production**
   ```bash
   pnpm build
   ```

## Project Structure


- **`mf-remote-app3/`** - External repository with remote application that exposes components