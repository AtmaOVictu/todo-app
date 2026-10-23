# Todo App

A clean and responsive task-management application based on the [Todo App design from Figma Community](https://www.figma.com/community/file/1350344600031523800).

The application helps users organize daily tasks, track progress, and manage completed activities through a simple and intuitive interface.

## Features

- Create new tasks
- Mark tasks as completed
- Delete tasks
- View active and completed tasks
- Responsive layout for desktop and mobile devices

## Design

The user interface is based on the following Figma Community design:

[View the Todo App design in Figma](https://www.figma.com/community/file/1350344600031523800)

## Tech Stack

- React
- Vite
- CSS

## Getting Started

### Prerequisites

Install the following tools:

- [Node.js](https://nodejs.org/) version 18 or newer
- npm, yarn, or pnpm

### Installation

Clone the repository:

```bash
git clone https://github.com/rpritr/todo-app
cd todo-app
```

Install the dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL shown in the terminal, usually:

```text
http://localhost:5173
```

## Available Scripts

```bash
npm run dev
```

Starts the application in development mode.

```bash
npm run build
```

Creates an optimized production build.

```bash
npm run preview
```

Runs the production build locally.

```bash
npm run lint
```

Checks the source code for linting issues.

## License

This repository is licensed under VBL 2.6; read [`LICENSE`](LICENSE) before
using, copying, or distributing the work. The license requires copies to carry
the unmodified license and contributor register. Its named-fall and permission
records are [`REGISTER-PADCEV.jsonl`](REGISTER-PADCEV.jsonl) and
[`canon/DOVOLJENJA.md`](canon/DOVOLJENJA.md). The current contributor register
is [`REGISTER-NEIMENOVANIH.jsonl`](REGISTER-NEIMENOVANIH.jsonl).

VBL 2.6 is a custom license and is not an SPDX-approved open-source license.
The `package.json` license field points to the local text; it does not express
an OSI-approved SPDX identifier. Third-party dependencies and design assets
may have separate terms.

## Available Scripts

Run the backend server with json-server.

```bash
npx json-server db.json
```