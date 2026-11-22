# My First MCP

This project is a Model Context Protocol (MCP) implementation.

## Project Overview

This repository contains a basic MCP server/client structure using the `@modelcontextprotocol/sdk`. It includes a service layer for handling business logic and a testing suite to ensure reliability.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v24.14.0 or higher)
- [pnpm](https://pnpm.io/)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd my-first-mcp
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

## Development

### Running the Project

To start the project in development mode with hot reloading and inspection:
```bash
pnpm dev
```

### Running Tests

To run the test suite:
```bash
pnpm test
```

To run the test suite with watch mode and inspection:
```bash
pnpm test:dev
```

### MCP Inspection

To inspect the MCP server using the official inspector:
```bash
pnpm mcp:inspect
```

## Project Structure

- `src/`: Contains the main source code.
  - `index.ts`: Entry point of the application.
  - `mcp.ts`: Core MCP logic.
  - `service.ts`: Business logic services.
- `tests/`: Contains the test suite.
  - `helpers.ts`: Test utility functions.
  - `mcp.test.ts`: Tests for the MCP logic.

## License

This project is licensed under the ISC License.
