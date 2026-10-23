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

The repository's original software is offered under any one of the MIT,
Apache-2.0, or GPL-3.0-or-later licenses; see [`LICENSE`](LICENSE). The SPDX
expression is `MIT OR Apache-2.0 OR GPL-3.0-or-later`, meaning users may choose
one of those licenses.

The author's VBL 2.6 text is retained in
[`VBL-2.6-ARCHIVE.md`](VBL-2.6-ARCHIVE.md) as a historical statement, not as an
additional condition on the software. Its referenced registers remain available
at [`REGISTER-NEIMENOVANIH.jsonl`](REGISTER-NEIMENOVANIH.jsonl),
[`REGISTER-PADCEV.jsonl`](REGISTER-PADCEV.jsonl), and
[`canon/DOVOLJENJA.md`](canon/DOVOLJENJA.md); they do not alter the software
license. Third-party dependencies and design assets may have separate terms.

## Available Scripts

Run the backend server with json-server.

```bash
npx json-server db.json
```